# Kubernetes-Cluster-Setup

This is the Kubernetes Cluster Configuration automation

ansible-playbook Kubernetes-Cluster-Setup.yml -i inventory


This supports Verbose output, use -v, -vv for verbose output

This is provided with tags to support the installation of only masternodes of Slave nodes

use the below to add only  minions 
ansible-playbook Kubernetes-Cluster-Setup.yml -i inventory --skip-tags=master

use the below to add only master nodes
ansible-playbook Kubernetes-Cluster-Setup.yml -i inventory --skip-tags=minions

