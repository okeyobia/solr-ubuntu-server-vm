# Simple Apache Solr server

This project aims to make spinning up a simple local VM Apache Solr environment incredibly quick and easy.

This will install the following on a VM:

  - Java
  - Apache Solr

## Quick Start Guide

### 1 - Install dependencies (VirtualBox, Vagrant, Ansible)

  1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
  2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html).
  3. [Mac/Linux only] Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).


### 2 - Build the Virtual Machine

  1. Download this project and put it wherever you want.
  2. Open Terminal, cd to this directory (containing the `Vagrantfile` and this README file).
  3. Type in `vagrant up`, and let Vagrant do its magic.


### 3 - Configure your host machine to access the VM.

  1. [Edit your hosts file](http://docs.rackspace.com/support/how-to/modify-your-hosts-file/), adding the line `192.168.56.10  solr.test` so you can connect to the VM.
  2. Open your browser and access [http://solr.test:8983/solr/](http://solr.test:8983/solr).
