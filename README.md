# Kubernetes setup with Ansible

This project can be used to setup a kubernetes cluster with any number of nodes on remote servers.

**_Note: Do not use on existing production servers._**

## Quick start
* Add the remote server Ip addresses to hosts file.
* Enter the ssh user details to hosts file.
* A ssh key exists in the files folder, use your own keys or create a new pair and use them at your servers.
* 
  

## Run 
 
```
ansible-playbook deploy.yml
```

## Clean

If anything goes wrong and you need to reset everything done before,  run the following command:

```bash
ansible-playbook reset.yml
```
  