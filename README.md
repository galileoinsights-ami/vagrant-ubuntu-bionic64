# Vagrant Machine - Ubuntu Bionic with Git and Terraform

A vagrant Ubuntu 18.04 (bionic64) machine with Git and Terraform installed.

## Pre-Requisite

1. Install [Oracle Virtual Box](https://www.virtualbox.org/)
2. Install [Vagrant](https://www.vagrantup.com/docs/installation/)


## Bringing up the Machine

Execute the following within the vagrant directory

```
vagrant up
```

## Accessing the machine

Execute the following within the vagrant directory

```
vagrant ssh
```

## Destroying the machine

Execute the following within the vagrant directory

```
vagrant destroy
```

## Sharing files between the Vagrant VM and Host machines.

Anything that you have put in the vagrant directoy on the local machine is accessible under `/vagrant` directory in the vagrant VM.