Vagrant
=============

Vagrant Configuration for Springbox.

This will install a fully functional Ubuntu image with AMP mapped to the directory of your choice including local hostnames, etc.
Currently has PHP 5.3 but can be customized for different uses. 

Based off of a template created at [PuPHPet](https://puphpet.com/).

# Requirements #

1. [Virtualbox](http://www.virtualbox.org) (Make sure to add Guest Additions)
2. [Vagrant](http://www.vagrantup.com/)
3. [Vagrant Hostnames Plugin](https://github.com/cogitatio/vagrant-hostsupdater)
4. [Vagrant Virtualbox Guest Additions Plugin](https://github.com/dotless-de/vagrant-vbguest)

# Usage #

1. Clone this repository
2. Install all requirements
3. Configure Vagrantfile to point to your project roots
4. Confiture manifests/default.pp with your Virtualhost and database info (you can have more than 1 of each)
5. Activate Vagrant `vagrant up` from Vagrant repo clone
6. ????
7. Profit
