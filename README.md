# SET_UP_SCRIPT

## To install vagrant
1. $ vagrant box add ubuntu/trusty64
2. $ vagrant init ubuntu/trusty64
3. $ vagrant plugin install vagrant-vbguest
4. $ vagrant up
## To install other needed things
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
$ sudo apt-get install emacs
$ sudo apt-get install libc6-dev-i386
## (optional for later)
$ git clone (repo url(s))
$ git config --global user.email "your email"
$ git config --global user.name "your name"
$ git config --global credential.helper store
## When exiting while in VM type "exit"
In CMD type "vagrant halt" or "sudo shutdown now" (not sure which is better)
In CMD type "exit"
## To start in CMD
$ vagrant up
$ vagrant ssh
