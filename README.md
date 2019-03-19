#Ansible Playbook To Install LampStack and configure wordpress
Ansible Playbook To Install LampStack and configure wordpress
-----------
This playbook which will install a fully functional Apache , php , mysql in the a fresh server. This would also download and wordoress contents and configure the  in your document root. 

Configuration Requirements
------------

The role is mainly for Centos

You need to  edit the following for changes as you want.
   >Editting templates/vhost.j2 and  will change the document root as per your need. Currenly the document root will be as "/var/www/html"

Role Variables
--------------

You can edit the following variables from the /var/main.yml, according to your need.

****
>db_name: 
>root_pass:
>wordpress_user: 
>wordpress_pass: 
>domain: 
>wordpress_url:
>wordpress_dest: 
>wordpress_unarchive: 
>wordpress_checksum: 
****

Example Playbook
-------------
hosts: centos
  roles: rolename

Author Information
------------------
- Name:   Justine Mathew Zacharias
- Mail:   justinejmz@gmail.com
- Mob:    +91 8301862439
- Linkdln: https://www.linkedin.com/in/justine-mathew-zacharias-223560157/
