# Nebraska Ops - Domain Controllers

Domain controllers are Microsoft Active Directory servers that host our authentication, part of our DNS, and other access control services. The offial domain is going to be lab.nebraskaops.net.

## Playbooks

Playbooks in this repository are located at the /domain-controllers folder.

### add-dc.yml

This playbook installs and creates an AD domain. Partial code was taken from [https://madlabber.wordpress.com/2019/09/08/creating-a-new-active-directory-forest-with-ansible/](https://madlabber.wordpress.com/2019/09/08/creating-a-new-active-directory-forest-with-ansible/).

### os-config.yml

This is the configuration of our domain controllers. A **TODO:** item is to talk about the tags and other playbook controls.
