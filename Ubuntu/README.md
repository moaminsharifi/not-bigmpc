# My linux config:

![My favorite config](https://github.com/bigmpc/bigmpc/raw/main/Ubuntu/My%20favorite%20config.png)

In here I want to talk about which app and config I use in ubuntu base linux on main system (laptop and pc)
---
### My hardwares:
- **Laptop: Dell xps 13 - i7 10510 - 16ram - 512 ssd nvme**
- **Pc: Custombuild - I5 8400 - 32 ram - 512 ssd nmve**

## Which distributions I use?
- laptop Ubuntu 18.04 installed by dell
- PC Kubuntu 20.04 

## List of Main Packges:
- Packge Manager
  - [Snapp](https://snapcraft.io/) - `sudo apt install snapd`
- Programing
  - IDE
    - VSCODE - [configs](https://gist.github.com/bigmpc/e8615de2963724ee83c096bfe8646124) - `sudo apt install code`

      1- Install [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) and login to github
      
      2 - Add gits id `e8615de2963724ee83c096bfe8646124`
      
      3- enjoy it!
    - jupyter - configs - `pip3 install jupyter`
    - IntelJ IDE - configs
    
  - ENV
     - [php 7.4](https://github.com/bigmpc/bigmpc/blob/main/Ubuntu/programing/php.md)
     - [python 3.8.x](https://github.com/bigmpc/bigmpc/blob/main/Ubuntu/programing/python.md)
     - [nodejs 14.x](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04)
     - [docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
     - rust nightly
     
 
- Multi Media
  - Recoring Video
    - ffmpeg
    - obs-stduio
    ```bash 
    sudo apt install ffmpeg
    sudo add-apt-repository ppa:obsproject/obs-studio
    sudo apt install obs-studio
    ```
   
  - Edit Video
    - [KDENLIVE video editor](https://kdenlive.org/en/)
  - PDF Reader
    - [Foxit Reader](https://linuxhint.com/install_foxit_reader_ubuntu/)
    
  - Image Editing
    - gimp - `sudo snap install gimp`
    - [photopea](https://www.photopea.com/)
  
- Internet:
  - Browser:
    - Firefox
    - Chormium - `sudo apt install chromium-browser`
    - PostMan - `sudo snap install postman`
  - **aria2 download manager** - `sudo apt install -y aria2`
  - VPN - Change IP
    - [tor](https://molaei.org/tor-ubuntu/)
    - nordvpn
    ```bash 
    wget https://github.com/bigmpc/nordvpn/raw/main/nordvpn_3.8.5_amd64.deb
    sudo apt --fix-broken install ./nordvpn_3.8.5_amd64.deb
    ```


- ENV and Linux Custom config
  
 

## list of fonts:
 - [Fira Code](https://github.com/tonsky/FiraCode)
 - [Vazir](https://rastikerdar.github.io/vazir-font/)
 - [Vazir Code](https://rastikerdar.github.io/vazir-code-font/)
