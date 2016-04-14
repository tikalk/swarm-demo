# swarm-demo
  
A few lines of Ansible instantiating a Docker Swarm Cluster

## Prequisites 
- Vagrant 
- Virtualbox { this was tested only with Virtualbox }
- Ansible

##Usagee:

``` vagrant up ```
will result with 4 instances of ubutntu 14.04

``` ansible-playbook -i hosts swarm.yml ```
result a docker swarm cluster
