# kali_conf
## How to
```
sudo echo 'Acquire::ForceIPv4 "true";' >> /etc/apt/apt.conf.d/99force-ipv4
sudo dpkg-reconfigure keyboard-configuration
sudo apt update
sudo apt upgrade -y
sudo apt install python2 python3 python3-pip wget golang-go trufflehog gpg apt-transport-https pipx rustc python2-dev build-essential yara gobuster seclists kali-desktop-i3 docker.io docker-compose bloodyad -y
sudo apt install python3 python3-pip ansible-core
git clone https://github.com/Backfuscher/kali_conf/
cd kali_conf
ansible-playbook main.yml --become --ask-become
```
