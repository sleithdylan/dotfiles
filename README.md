# dotfiles

## Github SSH Key Setup


1. Generate public and private keys
```sh
ssh-keygen -t rsa -C "sleithdylan@gmail.com"
```

2. Open .ssh folder in terminal from user directory
```sh
C:\Users\35389\.ssh
```

3. List all files
```sh
ls -al
```

There should be two files:
* id_rsa (Private Key)
* id_rsa.pub (Public Key)

4. Open "id-rsa.pub" in a text editor and copy everything in the file.

5. Open GitHub and add a SSH key and your done!