# ANSIBLE
Ansible stuff
# https://learn.redhat.com/t5/RH294-Red-Hat-Linux-Automation/How-to-get-ansible-module-info/td-p/38839

ansible-doc --list

ansible-navigator
# https://docs.redhat.com/en/documentation/red_hat_ansible_automation_platform/2.0-ea/html-single/ansible_navigator_creator_guide/index


ansible-navigator doc ansible.builtin.file


# https://stackoverflow.com/questions/75951759/what-ansible-command-to-list-or-verify-installed-modules-whether-built-in-or-a
https://devops.stackexchange.com/questions/18990/how-to-determine-the-color-of-a-shell-script-task-in-ansible

https://docs.ansible.com/ansible/latest/reference_appendices/config.html#ansible-nocolor
ANSIBLE_NOCOLOR=True ansible localhost -a "date"

https://serverfault.com/questions/956195/ansible-print-debug-msg-with-different-color

COLOR_OK
green

https://www.devopsworld.co.in/2022/02/ansible-output-color.html
https://www.devopsworld.co.in/2022/02/ansible-vault.html

ansible-vaule create test.yaml
New Vault password: (twice)

ansible-playbook test.yaml --ask-vault-password

ansible-vault encrypt test.yaml ; test.yaml exist
ansible-value decrypt test.yaml
