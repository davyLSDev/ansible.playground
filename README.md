# This repo is a testground for Ansible ideas. #

## to run this script##

* ensure that there is a server named testing with an account that can be sshed into from the control computer, i.e. the one that you run this script on

* ansible-playbook -i inventory site.yml --ask-vault-pass

* a quick ping like so: ansible servers -i inventory -m ping --ask-vault-pass

## References ##
[ansible vault how to](https://therealmarv.com/ansible-vault-file-handling/)