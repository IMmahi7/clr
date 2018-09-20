# README

## Ansible Basics

* [Get Started](https://www.ansible.com/resources/videos/quick-start-video)
* [How Ansible works](https://www.ansible.com/how-ansible-works)
* [Learn to write Playbooks](http://docs.ansible.com/ansible/latest/playbooks.html)

## Ansible KB

* [Ansible Documentation](http://docs.ansible.com/ansible/latest/index.html)
* [Ansible Modules](http://docs.ansible.com/ansible/latest/modules_by_category.html)
* [Ansible Vault](http://docs.ansible.com/ansible/latest/playbooks_vault.html)
* [Ansible Examples](https://github.com/ansible/ansible-examples)

## Mitro Directory Layout

```sh
    mro
    ├── ansible.cfg
    ├── playbooks
    │   └── mro_deployment.yml
    ├── README.md
    ├── roles
    │   ├── Apache_Installation
    │   │   └── tasks
    │   │       └── main.yml
    │   ├── App_Deployment
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   └── tasks
    │   │       ├── CarrierNotification.yml
    │   │       ├── CMTmitro.yml
    │   │       ├── EmitroWar.yml
    │   │       ├── main.yml
    │   │       └── Restapi.yml
    │   ├── DB_Deployment
    │   │   └── tasks
    │   │       ├── count_invalid_objects_after_inst.yml
    │   │       ├── count_invalid_objects_before_inst.yml
    │   │       ├── main.yml
    │   │       ├── mark_release_installed.yml
    │   │       ├── mitromgr_install.yml
    │   │       ├── oracle_install.yml
    │   │       └── prerequisite_check.yml
    │   ├── Java_Installation
    │   │   └── tasks
    │   │       └── main.yml
    │   ├── Jboss_Configuration
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   └── templates
    │   │       ├── clientresource.properties
    │   │       ├── config.properties
    │   │       ├── connection.properties
    │   │       ├── emitroresource.properties
    │   │       └── standalone.xml
    │   └── Jboss_Installation
    │       └── tasks
    │           └── main.yml
    └── vars
        ├── devops-access.yml
        ├── mro_all_public.yml
        ├── mro_am_confidential.yml
        ├── mro_prod_confidential.yml
        ├── mro_qa_confidential.yml
        └── mro_test_confidential.yml
```
