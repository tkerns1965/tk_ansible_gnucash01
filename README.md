# tk_ansible_gnucash01

For use on bare Ubuntu 20.04.1 Desktop

1.  sudo apt-add-repository -y ppa:ansible/ansible
2.  sudo apt install -y ansible git python-pexpect
3.  git clone https://github.com/tkerns1965/tk_ansible_gnucash01.git
4.  cd tk_ansible_gnucash01/
5.  cp roles/gnucash01/vars/private.yml.sample roles/gnucash01/vars/private.yml
6.  nano roles/gnucash01/vars/private.yml
7.  ansible-playbook -K gnucash01.yml
