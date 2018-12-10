Ansible Playbook to deploy Cisco Meeting Server stand alone node.

# How to use 
It needs CMS beforehand with the following settings:

- Access to SSH 
- Upload license

Then, modify hosts file to replace ip address of your CMS node.

```
cms1 ansible_host=<your cms node>
```

Run ansible-playbook command

```
ansible-playbook -i hosts playbook.yml
```
