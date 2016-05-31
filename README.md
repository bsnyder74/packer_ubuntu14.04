# Packer - Ubuntu 14.04 Server (VBox)  

## Requirements  
[Packer](https://packer.io)  
[Vagrant](https://vagrantup.com)  
[Virtual Box](https://virtualbox.org)  

## Usage  
`$ packer build vbox-ubuntu14.04.json`  

## Note:  
Builder looks for image in iso/ directory, otherwise downloads from web.  
iso/ directory not included due to size.  

#### TODO:  
Add provisioners scripts.  
