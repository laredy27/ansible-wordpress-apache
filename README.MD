# Ansible apache-wordpress

An example of a multi machine three-tiered wordpress application provisioned with vagrant and orchestrated with ansible. 

## Improvements
- Synchronize wp-content/uploads folder between the webservers. At the moment assets uploaded from the wp admin dashboard are only available for the actively balanced webserver.

### Credits
A cloud guru ansible intro [course](https://learn.acloud.guru/course/intro-ansible/dashboard)