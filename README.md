# kali_conf
## How to
```
sudo echo 'Acquire::ForceIPv4 "true";' >> /etc/apt/apt.conf.d/99force-ipv4
sudo dpkg-reconfigure keyboard-configuration
sudo apt update
sudo apt upgrade -y
sudo apt install python3 python3-pip ansible-core
git clone https://github.com/Backfuscher/kali_conf/
cd kali_conf
ansible-playbook main.yml --become --ask-become
```
