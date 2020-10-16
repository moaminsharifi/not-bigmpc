# how to install?
in here I want to describe How and With Which sequnce I Install and config my linux,
Main idea is do not break chain of installation so let's start it.


- Step Zero:
```bash
# install snap
sudo apt update
sudo apt upgrade -y

sudo apt --fix-broken install -y software-properties-common crul git vim chromium-browser snapd aria2 python3-pip ffmpeg
snap install postman code gimp
sudo add-apt-repository universe

# install kdenlive

sudo add-apt-repository ppa:kdenlive/kdenlive-stable

sudo apt install kdenlive

# install obs-studio
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt install obs-studio


# install php packges
cat programing/php.txt  | xargs sudo apt-get install


# install pip packges
pip3 install --upgrade pip
pip3 install -r programing/python.txt

```

install https://www.foxitsoftware.com/pdf-reader/
2. Programing
```bash
snap install postman code 
```

3. what'is left
    - install fonts
    - config ides
    - install FISH