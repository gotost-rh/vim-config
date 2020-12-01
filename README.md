# vim-config
Ansible Playbook to auto configure vim

Prerequisites:
- vim
- Ansible

This article was followed in creating this playbook.
https://www.redhat.com/sysadmin/ansible-configure-vim?sc_cid=7013a0000026EoiAAE

These plugins are installed as a result of running the playbook.
https://www.redhat.com/sysadmin/five-vim-plugins

Steps to run the playbook:
1. mkdir ~/files
2. cp vimrc ~/files
3. ansible-playbook -K vim-config.yaml
