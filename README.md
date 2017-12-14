# kubernetes-cluster
Kubernetes on CoreOS cluster setup scripts

# Local development
CoreOS cluster setup for development using [coreos-vagrant](https://github.com/coreos/coreos-vagrant)

## Quick start

    bin/pull
    bin/cluster-setup
    bin/cluster-start
    bin/cluster-stop
    
    . bin/activate
    ansible-playbook -K hosts-local.yml
    ssh core@core-01

# Kubernetes setup

Ansible scripts based on [CoreOS + Kubernetes Step By Step](https://coreos.com/kubernetes/docs/1.6.1/getting-started.html)

## Quick start

    bin/pull
    bin/setup_packages
    . bin/activate
    ansible-playbook setup.yml