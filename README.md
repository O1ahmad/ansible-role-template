<p><img src="https://code.benco.io/icon-collection/logos/ansible.svg" alt="ansible logo" title="ansible" align="left" height="60" /></p>
<p><img src="https://i.imgur.com/IBNz2CM.jpg" alt="0xO1 logo" title="0xO1" align="right" height="80" /></p>

Ansible Role :zero::one: {Role}
=========
[![Galaxy Role](*role-shield-link*)](--role-link--)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/0x0I/ansible-role-template?color=yellow)
[![Downloads](*downloads-shield-link*)](--role-link--)
[![Build Status](https://travis-ci.org/0x0I/ansible-role-template.svg?branch=master)](https://travis-ci.org/0x0I/ansible-role-template)
[![License: MIT](https://img.shields.io/badge/License-MIT-blueviolet.svg)](https://opensource.org/licenses/MIT)

**Table of Contents**
  - [Supported Platforms](#supported-platforms)
  - [Requirements](#requirements)
  - [Role Variables](#role-variables)
      - [Install](#install)
      - [Config](#config)
      - [Launch](#launch)
      - [Uninstall](#uninstall)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

...*description of role*...

##### Supported Platforms:
```
* Debian
* MacOS
* Redhat(CentOS/Fedora)
* Ubuntu
```

Requirements
------------

...*description of provisioning requirements*...

Role Variables
--------------
Variables are available and organized according to the following software & machine provisioning stages:
* _install_
* _config_
* _launch_
* _uninstall_

#### Install

...*description of installation related vars*...

#### Config

...*description of configuration related vars*...

#### Launch

...*description of service launch related vars*...

#### Uninstall

...*description of uninstallation related vars*...

Dependencies
------------

...*list dependencies*...

Example Playbook
----------------
default example:
```
- hosts: all
  roles:
  - role: 0x0I.<role>
```

License
-------

MIT

Author Information
------------------

This role was created in 2019 by O1.IO.
