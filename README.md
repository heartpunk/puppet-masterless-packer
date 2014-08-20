puppet-masterless-packer
========================


Builds images with puppet ready for masterless use, using Ubuntu 14.04.

Uses [packer](http://packer.io).


To build the images, run:


```shell
AWS_SECRET_KEY=your_secret_key AWS_ACCESS_KEY=your_access_key packer build default.json
```
