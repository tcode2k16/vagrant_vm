# Vagrant vm for CTF competitions

## What is this?

This is a ubuntu-based vagrant vm for CTF competitions with some helpful tools included.

## Installation

Download vagrant file

`❯ curl https://raw.githubusercontent.com/tcode2k16/vagrant_vm/master/ubuntu_ctf/Vagrantfile > Vagrantfile`

Run the installation process (*This will take around 1 hour if it is the first time you run this*)

`❯ vagrant up`

Access the vm

`> vagrant ssh`

Shutdown the vm

`> vagrant halt`

## Tools included

* x86 binary libs
* gdb with peda
* binwalk
* exiftool
* imagemagick
* socat
* unzip
* python2
* nodejs
* radare2
* pwntools
* ipython
* masscan
* featherduster

## Suggestions

Pull requests are welcomed.
