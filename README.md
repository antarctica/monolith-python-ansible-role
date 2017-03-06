# Monolith Python Ansible Role

System setup for a Python Monolith instance.

# Description

Prototype role for use in creating Python Monolith instances, within with Python applications can be deployed.

This role is meant to creating local instances (using Vagrant) from which verification scripts/playbooks can be created 
to test remote instances provisioned by, for example, BAS ICT.

Components this role installs, are what is expected on all Python Monolith instances and consists of:

* Python (and related modules)
* Nginx (with the default config removed, and permission for members of the ‘deployers’ group to create configs)
* A ‘webapps-deploy’ user, and ‘deployers’ group
* A common directory structure

# Requirements

None.

# Role Variables

None.

# Dependencies

None.

# Example Usage

...

# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - antarctica.monolith-python

# Testing

Use the included Vagrant VM in `tests`.

# License

Copyright 2017 NERC BAS.

Unless stated otherwise, all code is licensed under the MIT license.
