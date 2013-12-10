Laravel 4.0.x + Vagrant + Ansible
=======================

Laravel Vagrant Box using Ansible 

The site will be available from http://laravel.dev once complete.

#### Prerequisites

1. Install VirtualBox - https://www.virtualbox.org/wiki/Downloads
2. Install Vagrant - http://downloads.vagrantup.com/tags/v1.3.5
2. Install Ansible - `sudo pip install ansible` (if you don't have pip run `sudo easy_install pip`)

#### Setup

Run the following command from inside the repository.  It will take a few minutes, especially the first time you run, as it has to download the VM image.

	$ vagrant up

#### Hosts File Setup

Add the following to your `/etc/hosts` file:

	192.168.57.111  laravel.dev

#### SSH

You can ssh into the VM by running `vagrant ssh` from inside the repo root.

You can also SSH in using the following:

* **Host:** laravel.dev
* **Username:** vagrant
* **Password:** vagrant

#### MySQL Access

*Note: This will most likely change, as you really shouldn't use the DB as root.*

* **Username:** root
* **Password:** root
