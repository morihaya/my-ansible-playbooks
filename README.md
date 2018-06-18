# This is my ansible playbooks

## Setup commands

```
sudo apt update && sudo apt upgrade

sudo apt install curl
sudo curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
sudo python get-pip.py

sudo pip install --upgrade pip
sudo pip install ansible

sudo ssh-keygen

sudo su -
cat ~/.ssh/id_rsa.pub >> /root/.ssh/authorized_keys
exit

sudo mkdir /etc/ansible
cd /etc/ansible

sudo apt install git
sudo git clone https://github.com/morihaya/my-ansible-playbooks.git
```
