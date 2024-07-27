![image](https://github.com/user-attachments/assets/83ca8b84-2ba3-42dc-9576-3f33fb3f0d24)

# sources.list
The Ubuntu sources.list

## Ubuntu 22.04
server for Bangladesh

```txt
deb http://bd.archive.ubuntu.com/ubuntu/ jammy main restricted
deb http://bd.archive.ubuntu.com/ubuntu/ jammy-updates main restricted
deb http://bd.archive.ubuntu.com/ubuntu/ jammy universe
deb http://bd.archive.ubuntu.com/ubuntu/ jammy-updates universe
deb http://bd.archive.ubuntu.com/ubuntu/ jammy multiverse
deb http://bd.archive.ubuntu.com/ubuntu/ jammy-updates multiverse
deb http://bd.archive.ubuntu.com/ubuntu/ jammy-backports main restricted universe multiverse
deb http://security.ubuntu.com/ubuntu jammy-security main restricted
deb http://security.ubuntu.com/ubuntu jammy-security universe
deb http://security.ubuntu.com/ubuntu jammy-security multiverse

```

step-1: open terminal.
step-2: update cache & upgrade source list
```sh
sudo apt update
sudo apt upgrade
```
step-3:
```sh
sudo nano /etc/apt/sources.list
```
Then upgrade your sources.list
