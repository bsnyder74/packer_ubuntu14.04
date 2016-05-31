# Packer - Ubuntu 14.04 Server (VBox)  

## Requirements  
[Packer](https://packer.io)  
[Vagrant](https://vagrantup.com)  
[Virtual Box](https://virtualbox.org)  

## Usage  
`$ packer build vbox-ubuntu14.04.json`  

## Note:  
Currently have iso file copied locally into iso/ directory.  
Ubuntu preseed file pulls from web server.  

#### TODO:  
Add provisioners scripts.
Add preseed locally to repo.  
