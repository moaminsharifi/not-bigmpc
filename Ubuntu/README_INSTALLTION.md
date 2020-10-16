# how to install?
in here I want to describe How and With Which sequnce I Install and config my linux,
Main idea is do not break chain of installation so let's start it.


- Step Zero:
```bash
# install snap
sudo apt update
sudo apt upgrade -y

sudo apt --fix-broken install -y software-properties-common curl git vim chromium-browser snapd aria2 python3-pip ffmpeg tor obfs4proxy privoxy torsocks mysql-server telegram-desktop unzip
sudo snap install postman
sudo snap install code -- classic
sudo snap install discord 
sudo snap install skype -- classic
sudo snap install vlc

sudo apt update
sudo add-apt-repository universe



# install php packges
sudo add-apt-repository ppa:ondrej/php

wget https://raw.githubusercontent.com/bigmpc/bigmpc/main/Ubuntu/programing/php7-4.txt
cat php7-4.txt  | xargs sudo apt-get install -y

# install composer 
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '795f976fe0ebd8b75f26a6dd68f78fd3453ce79f32ecb33e7fd087d39bfeb978342fb73ac986cd4f54edd0dc902601dc') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer


echo 'export PATH="$PATH:$HOME/.composer/vendor/bin"' >> ~/.bashrc
source ~/.bashrc

# install laravel installer
composer global require laravel/installer


# install pip packges
pip3 --version
pip3 install --upgrade pip
pip3 --version
wget https://raw.githubusercontent.com/bigmpc/bigmpc/main/Ubuntu/programing/python3-8.txt
pip3 install -r python3-8.txt


# install docker
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ${USER}
# install kdenlive

sudo add-apt-repository ppa:kdenlive/kdenlive-stable

sudo apt install -y kdenlive

# install obs-studio mpv gimp
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt install -y obs-studio mpv gimp


# install nordvpn 
wget https://github.com/bigmpc/nordvpn/raw/main/nordvpn_3.8.5_amd64.deb
sudo apt --fix-broken install ./nordvpn_3.8.5_amd64.deb


# install calibre
sudo -v && wget -nv -O- https://download.calibre-ebook.com/linux-installer.sh | sudo sh /dev/stdin


# install nordvpn ppa
wget -qnc https://repo.nordvpn.com/deb/nordvpn/debian/pool/main/nordvpn-release_1.0.0_all.deb
sudo dpkg -i nordvpn-release_1.0.0_all.deb
sudo apt update


# install superproductivity edge version
sudo snap install --channel=edge superproductivity


```

- Step One: config them:

- [https://docs.docker.com/engine/security/rootless/](https://docs.docker.com/engine/security/rootless/)
 - [https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-ubuntu-18-04](https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-ubuntu-18-04)
- setup telgram
- set up browsers
