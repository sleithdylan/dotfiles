# dotfiles

## Github SSH Key Setup

1. Generate public and private keys

```sh
ssh-keygen -t rsa -C "sleithdylan@gmail.com"
```

2. Open .ssh folder in terminal from user directory

```sh
C:\Users\Name\.ssh
```

3. List all files

```sh
ls -al
```

There will be **two** files:

- id_rsa (Private Key)
- id_rsa.pub (Public Key)

4. Open "id_rsa.pub" in a text editor and copy everything in the file.

5. Open GitHub and add a SSH key and your done!

## Hide MINGW64 in terminal

1.  Go to `C:\Program Files\Git\etc\profile.d\` folder

2.  Find and open `git-prompt.sh` file in your text editor

3.  Comment out line `16` and `17`

4.  Restart terminal and you're done!
