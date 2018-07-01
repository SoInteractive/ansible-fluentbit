Ansible Role: fluentbit
=======================
[![Build Status](https://travis-ci.org/SoInteractive/ansible-fluentbit.svg?branch=master)](https://travis-ci.org/SoInteractive/ansible-fluentbit) 
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT) 
[![Ansible Role](https://img.shields.io/badge/ansible%20role-SoInteractive.fluentbit-blue.svg)](https://galaxy.ansible.com/SoInteractive/fluentbit/) 
[![GitHub tag](https://img.shields.io/github/tag/sointeractive/ansible-fluentbit.svg)](https://github.com/SoInteractive/ansible-fluentbit/tags) 
[![Twitter URL](https://img.shields.io/twitter/follow/sointeractive.svg?style=social&label=Follow%20%40SoInteractive)](https://twitter.com/sointeractive)

# :warning: IMPORTANT NOTICE

THIS PROJECT IS ABANDONED. WE DO NOT ACCEPT ANY NEW ISSUES AND/OR PULL REQUESTS.


Examples
--------
Use it in a playbook as follows:
```yaml
- hosts: all
  become: true
  roles:
    - SoInteractive.fluentbit
  
```

Have a look at the [defaults/main.yml](defaults/main.yml) for role variables
that can be overridden.
