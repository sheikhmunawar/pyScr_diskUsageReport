Linux - Python, PIP and Virtual Environment Installation
```
dnf list installed
dnf search python
dnf install python311
alternatives --config python
python --version
sudo apt-get install python3-pip
sudo apt install python3-virtualenv
sudo apt install python3-venv (kali)
```

github add ssh-key
```
ssh-keygen -t ed25519 -C sheikhmunawar@gmail.com
ssh-keygen -t rsa -b 4096 -C "sheikhmunawar@gmail.com"
ls ~/.ssh
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519_github
cat ~/.ssh/id_ed25519_github.pub
```