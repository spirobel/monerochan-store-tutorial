# monerochan-store-tutorial
How to sell stuff online in the most based way.
# Stuff you need to get

## Get a VPS

use this Link and you will get 100 USD in vps credit.
https://m.do.co/c/cdfc125af818
(i will get 25 USD for every 25 USD in credit. I will use it to create more based monero projects.)
https://m.do.co/c/cdfc125af818
[![DigitalOcean Referral Badge](https://web-platforms.sfo2.digitaloceanspaces.com/WWW/Badge%203.svg)](https://www.digitalocean.com/?refcode=cdfc125af818&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)

## Get a Domain

just take one in this list so you can just follow their tutorial on how to connect it with digitalocean. 
https://www.digitalocean.com/community/tutorials/how-to-point-to-digitalocean-nameservers-from-common-domain-registrars
 
## Get the Monero Gui-wallet.

its easy. Just download it here: https://www.getmonero.org/downloads/#gui

# Commands

there are some commands in the video. turn off your brain and copy them into the root console.

* to install the php-bcmath extension
``` bash
sudo apt install php-bcmath
service apache2 reload
```
[source](https://stackoverflow.com/questions/3400362/how-to-install-bcmath-module)

* to generate the ssl certs
``` bash
certbot --apache -d example.com -d www.example.com
```
[source](https://marketplace.digitalocean.com/apps/wordpress?#getting-started)


#step by step

steps with video timestamps

* 1:15 setup digitalocean project
* 1:47 one click wordpress install
* 2:41 domain configuration
* 4:35 root console: setup and create ssl cert
* 9:01 install WooCommerce
* 10:45 install monero payment gateway
* 11:40 root console: install php-bcmath
* 12:50 connect seller wallet to monero payment gateway
* 14:40 create a product
* 15:45 switch display currency
* 17:00 buyer buy flow
* 18:49 sellers side
