jws_common_criteria
==================================================

This role will handle common criteria certification.

Role Variables
--------------

Required:

- display_xpath_res_override: default value is 'False'
- display_directory_stats_override: default value is 'False'
- jws_owner_override: default value is 'tomcat'
- jws_group_override: default value is 'tomcat'

Example Playbooks
-----------------

'''
---
- hosts: all
  gather_facts: false
  roles:
    - role: common_criteria
'''