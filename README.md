# This repo is a testground for Ansible ideas.#

## to run this script##

* ensure that there is a server named tennant with an account that can be sshed into from the control computer, i.e. the one that you run this script on

* ansible-playbook -i inventory site.yml --ask-vault-pass