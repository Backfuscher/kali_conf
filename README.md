# kali_conf
## How to
```
git clone https://github.com/Backfuscher/kali_conf/
cd kali_conf
echo 'Acquire::ForceIPv4 "true";' | sudo tee /etc/apt/apt.conf.d/99force-ipv4
sudo apt update
sudo apt install python3 python3-pip ansible-core
pip3 install ansible
ansible-playbook main.yml --become
```
