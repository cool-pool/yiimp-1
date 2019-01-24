# yiimp
Install script for yiimp on Ubuntu 18.04
This script will install yimmp on your Ubuntu 18.04 system. 

Before running this script make sure you are on a fresh server and running as a user. Do not run this script under root!

This install script will get you 95% ready to go with yiimp. There are a few things you need to do after the main install is finished.

You must update the following files:

1. /var/web/serverconfig.php - update this file to include your public ip to access the admin panel. update with public keys from exchanges. update with other information specific to your server..
2. /etc/yiimp/keys.php - update with secrect keys from the exchanges. 

After you add the missing information to those files then run:
./main.sh
./loop2.sh
./block.sh

curl -Lo install.sh https://raw.githubusercontent.com/crombiecrunch/yiimp/master/install.sh 
bash install.sh

You will be prompted for email, FDQN, and time zone. You onkly get one shot to enter this information correctly!

If this helped you or you feel giving please donate BTC Donation: 3BH9aSXZSz4ivTTLe3knkA35xwzYynJpFQ


