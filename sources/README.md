Official Debian Repos for Raspbian

Add Repos List to Raspbian:
sudo wget https://raw.githubusercontent.com/Killertamagotchi/RPi/master/sources/debian.list -O /etc/apt/sources.list.d/debian.list 

Add Repos Key to Raspbian
wget https://ftp-master.debian.org/keys/archive-key-10.asc -O - | sudo apt-key add -
wget https://ftp-master.debian.org/keys/archive-key-10-security.asc -O - | sudo apt-key add -
wget https://ftp-master.debian.org/keys/release-10.asc -O - | sudo apt-key add -
