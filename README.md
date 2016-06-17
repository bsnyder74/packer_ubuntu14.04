# Packer - Ubuntu 14.04 Server (VBox)  

## Requirements  
[Packer](https://packer.io)  
[Vagrant](https://vagrantup.com)  
[Virtual Box](https://virtualbox.org)  
[Ubuntu server 14.04.4](http://releases.ubuntu.com/14.04.4/ubuntu-14.04.4-server-amd64.iso) if using a local iso file, otherwise it will be downloaded.  
Build is verified with the MD5 hash for v.14.04.4.  
If you want to use a different version, you will need to change the hash validation.  

## Usage  
`$ packer build vbox-ubuntu14.04.json`  

## Note:  
Builder looks for image in iso/ directory, otherwise downloads from web.  
iso/ directory not included due to size.  

#### TODO:  
Add provisioners scripts.  
