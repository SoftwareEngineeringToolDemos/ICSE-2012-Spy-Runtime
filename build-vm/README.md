## VM spinup for Spy@Runtime

## Please follow the below steps:

1. Install <a href="https://www.vagrantup.com/downloads.html">Vagrant</a> and <a href="https://www.virtualbox.org/wiki/Downloads">VirtualBox</a> on the host machine.
2. From the <a href="https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-Spy-Runtime/tree/master/build-vm">build-vm</a> directory, download <a href="https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-Spy-Runtime/blob/master/build-vm/Vagrantfile">Vagrantfile</a>.
3. In the command prompt(in Windows)/bash(in Linux) of host machine, cd into the directory containing the Vagrantfile and run "vagrant up"


## Note:

- The "vagrant up" takes about half an hour.
- The base box on which this VM is built is <a href=https://atlas.hashicorp.com/hashicorp/boxes/precise64>Ubuntu Server 12.04</a>
- VM Login details:  
      Username: vagrant  
      Password: vagrant

## Acknowledgement:

- The commands for installing Java 8 have been taken from <a href="https://github.com/aglover">Andrew Glover's<a> <a href="https://github.com/aglover/ubuntu-equip">github repository</a>.
- The tutorial for Vagrant has been taken from [Vagrant Tutorial](http://www.dev9.com/article/2014/9/dev-environments-with-vagrant) by Dustin Barnes (http://www.dev9.com/article/2014/9/dev-environments-with-vagrant) 
