# FCS-Pi-Ansible
Ansible Playbooks for FCS-Pi System

[Wiki Entry](https://wiki.fiel.solutions/doku.php?id=fcs-pi)

```
  sudo apt install git ansible
  
  cd ~
  git clone https://github.com/Fiel-Computer-Solutions/FCS-Pi-Ansible.git
  cd FCS-Pi-Ansible
  
  cp config.yml.ex config.yml
  nano config.yml

  sudo ansible-playbook --ask-vault-pass fcs-pi.yml
```
