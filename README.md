# Why the F*** would you do this !

Well for starters..... because i can. 

Furthermore ,  for the project im delopying I don't really require a lot of hardware or software. I dont need to worry about high traffic , I'm not concerned with automated scaling. Simplicity is key. Why make something overly complicated right ?

I wanted to explore another side of Web Development by spinning up a server, gathering my own domain name, and delopying my portfolio to a small little chip right on my computer desk at home. 

I have utilized alot of Digital Oceans tutorials for sake of time savings and the fact the documentation is superb. 

So shout out to :
##### NGINX on Debian 
> - Kathleen Juell  ~ Author /  Developer and author at DigitalOcean.~
> - Erika Heidi  ~  Author /  Developer Advocate ~
##### Lets Encrypt on Debian
> - Alex Garnett ~ Author / Senior DevOps Technical Writer ~
# Project B.O.M.
- Raspberry Pi Zero W
- microSD card ( 32gb)
- Diet Pi OS 
- NGINX Web Server
- Git
- Node JS
- React
- GoDaddy Domain Name Service

# Downloading Operating System Image
- Direct Link To Image Download
	>#####  [Raspbery Pi 1 / Zero / Zero W Image ISO](https://dietpi.com/downloads/images/DietPi_RPi-ARMv6-Bullseye.7z)

# Mount The Image
 - Unzip the Image file and mount to the Micro SD card using 
	> [BalenaEtcher](https://www.balena.io/etcher/)
 
# Setup OS 

- The best way for you to setup your working OS on your Pi Zero/w
	>[Diet Pi Offical Start Guide ](https://dietpi.com/docs/getting_started/)
 **I encourage CLI only **
  ##### You can Select all the Dependencies below within the Dietpi-Software manager at install. 
	- NGINX Server 
   - Node JS / NPM
	- Git 
	
## Manual  Install with Package Manager 
-  #### Installing NGINX
		 sudo apt install nginx
- ####  Installing Git
		sudo apt install git-all
- #### Installing Node Js / Npm 
		curl -fsSL https://deb.nodesource.com/setup_16.x | bash - &&\apt-get install -y nodejs


# Setup NGINX Server
- [NGINX on Debian](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-debian-10)

# Fecth a Domain Name
> - [IONOS](https://www.ionos.com/?ac=OM.US.USo41K356157T7073a&itc=P1W59NNS-TH53Y8-&utm_source=google&utm_medium=cpc&utm_campaign=SBT-US-BRA-MIXX---IONOS---&utm_term=ionos&matchtype=e&utm_content=IONOS&gclid=Cj0KCQiAzeSdBhC4ARIsACj36uEA05RcNArlhugr-koIjf_eUxvH-xSx1jKbb1a4Q_GmypOGMyi_1CsaAv6MEALw_wcB&gclsrc=aw.ds)
> - [HostGator](https://www.hostgator.com/?clickid=R7i2wZykgxyNWceRwL37OzQZUkAw0gUhIX0xQU0&irgwc=1&affpat=1&mpid=3286733)
> - [Bluehost](https://www.bluehost.com/domains)
> - [DreamHost](https://www.dreamhost.com/domains/)
> - [InMotion Hosting](https://www.inmotionhosting.com/domains)
> - [MochaHost](https://www.mochahost.com/domains.php)
> - [GoDaddy](https://www.godaddy.com/offers/domains/buy-domain?isc=gofxsl01&cdtl=c_17562590529.g_137334205599.k_aud-1719111401251:kwd-88659201.a_605892592481.d_c.ctv_g&bnb=b&gclid=Cj0KCQiAzeSdBhC4ARIsACj36uFbPd0QWKrogt4BFlf4w82e1shae_SVBQa1v7tP71WGbAWHOtt9GGoaAk8cEALw_wcB)

# Adding SSL 
- [Lets Encrypt on Debian](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-debian-11)
