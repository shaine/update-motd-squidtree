# update-motd-squidtree

Better MOTD scripts for Ubuntu

## Set up
  
  * Install toilet: `sudo apt-get install toilet`
  * Install elinks: `sudo apt-get install elinks`
  * Install lolcat: `sudo gem install lolcat`
  * Add fonts: `curl http://www.figlet.org/fonts/big.flf > big.flf; sudo mv big.flf /usr/share/figlet`
  * Install fortune: `sudo apt-get install fortune`
  * Install cowsay: `sudo apt-get install cowsay`
  * Pull down MOTD repo to /etc/update-motd-squidtree: `sudo git clone https://github.com/shaine/update-motd-squidtree.git /etc/update-motd-squidtree`
  * Swap the default MOTD for the custom setup: `sudo mv update-motd.d update-motd.d-old; sudo ln -s /usr/local/share/update-motd-squidtree update-motd.d`
