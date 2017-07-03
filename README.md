Java
=====
Ansible role to install and configure Java.

Requirements
------------
None

Role Variables
--------------
By default this role installs Java 1.8. Aditionaly, the variable ```oracle_jdk_url``` can be defined with the url to the jdk. The role will install only the url version.
```yaml
---
remove_java: false
java_version: "1.8.0"

```

Example Playbook
----------------
```yml
- hosts: servers
  roles:
     - ansible-java
```

License
-------
MIT

