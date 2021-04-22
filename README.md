Role Name: K8S_master_config
=========

A ansible role to do cofiguration for kubernetes masternode on AWS EC2 instance. 

Requirements
------------

Require a EC2 Instance
Because role uses EC2 module, system(control node) require require boto and boto3 package.
To install boto and boto3 package run command: pip3 install boto boto3  

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

\-\ hosts: servers<br>
    become: yes<br>
    remote_user: ec2-user<br>
    roles:<br>
    \-  role: "K8S_master_config"
  
License
-------

BSD

Author Information
------------------

My linkedIn profile:-<https://linkedin.com/in/niraj-kumar->

