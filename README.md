Ansible Role: Ninja
=====================

[//]: <> (Comment)
[//]: <> (A brief description of the role goes here.)

Install [Ninja](https://ninja-build.org/) on Centos 7 from sources. May work on other systems.

***

Requirements
------------

[//]: <> (Any pre-requisites that may not be covered by Ansible itself 
or the role should be mentioned here. For instance, if the role uses the EC2 module, 
)

cmake3

Role Variables
--------------

[//]: <> (A description of the settable variables for this role should go here,
including any variables that are in defaults/main.yml, vars/main.yml, 
and any variables that can/should be set via parameters to the role. 
Any variables that are read from other roles and/or the global scope 
\(ie. hostvars, group vars, etc.\) should be mentioned here as well.
)

Available variables are listed below, along with default values (see [`defaults/main.yml`](defaults/main.yml)):

| Variable  |  	Default  | Comments  |
|---|---|---|
| `ninja_version`   | [1.10.1](https://ninja-build.org/) | Choose ninja version to install  |
                       
Dependencies             
------------       
      
[//]: <> (A list of other roles hosted on Galaxy should go here, 
plus any details in regards to parameters that may need to be set for other roles, 
or variables that are used from other roles.
)

No dependency

Example Playbook
----------------

[//]: <> (Including an example of how to use your role \(for instance, with variables passed in as parameters\) is always nice for users too:)

    - hosts: my_server
      roles:
        - role: korzeczl.ninja

License
-------

[//]: <> (Comment)

[MIT][link-license]

Author Information
------------------

[//]: <> (An optional section for the role authors to include contact information, 
or a website \(HTML is not allowed\).)

This role was created in 2020 by Laurent Korzeczek.

[link-license]: https://gitlab.com/ansible-roles-korzeczl/ninja/-/blob/master/LICENSE
[link-galaxy]: https://galaxy.ansible.com/korzeczl/ninja