# Instructions

Tested on:
- Ubuntu Server 20.04
- Ansible 3.0.0, ansible-base 2.10.6

Run this playbook with the following command:

    ansible-playbook -i mastery-hosts -c local --limit frontend mastery.yaml