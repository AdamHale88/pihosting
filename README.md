# Why the F*** would you do this !

Well for starters..... because i can. 

Furthermore ,  for the project im delopying I don't really require a lot of hardware or software. I dont need to worry about high traffic , I'm not concerned with automated scaling. Simplicity is key. Why make something overly complicated right ?

I wanted to explore another side of Web Development by spinning up a server, gathering my own domain name, and delopying my portfolio to a small little chip right on my computer desk at home. 

## Project B.O.M.
	 - Raspberry Pi Zero W
	 - microSD card ( 32gb)
	 - Diet Pi OS 
	 - NGINX Web Server
	 - Git
	 - Node JS
	 - React
	 - GoDaddy Domain Name Service

## Downloading Operating System Image
- Direct Link To Image Download
	>#####  [Raspbery Pi 1 / Zero / Zero W Image ISO](https://dietpi.com/downloads/images/DietPi_RPi-ARMv6-Bullseye.7z)

## Mount The Image
 - Unzip the Image file and mount to the Micro SD card using 
	> [BalenaEtcher](https://www.balena.io/etcher/)
 
## Setup OS 

- The best way for you to setup your working OS on your Pi Zero/w
	>[Diet Pi Offical Start Guide ](https://dietpi.com/docs/getting_started/)
 **I encourage CLI only **
  ##### You can Select all the Dependencies below within the Dietpi-Software manager at install. 
		  - NGINX Server 
		  - Node JS / NPM
		  - Git 
	 ##### Optional 
		  - *Certbot (SSL) 
		  - *LetsEncrypt (SSL)

## Installing Dependencies With Package Manager
-  #### Installing NGINX
> `sudo apt install nginx`
- ####  Installing Git
> `sudo apt install git-all`
- #### Installing Node Js / Npm 
> `curl -fsSL https://deb.nodesource.com/setup_16.x | bash - &&\
apt-get install -y nodejs`
