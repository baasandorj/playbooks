# This folder for storing ansible collections for the playbook examples

You need to create ansible.cfg and add following content into it.  

```Ansible
# https://www.jeffgeerling.com/blog/2020/ansible-best-practices-using-project-local-collections-and-roles
[defaults]

# Chick-Fil-A would like a word...
nocows = True

# Installs collections into [current dir]/module_utils/ansible_collections/namespace/collection_name
collections_paths = ./module_utils

# Installs roles into [current dir]/roles/namespace.rolename
roles_path = ./roles
```

You need to create requirements.yml file and add following content into it.

```YAML
collections:
  - name: ansible.utils
    version: 2.9.0
  
  - name: ansible.netcommon 
    version: 4.1.0

  - name: community.general
    version: 6.6.0

```

You need to run following command for installing the required collections into the folder

```Bash
ansible-galaxy collection install -r requirements.yml
```
