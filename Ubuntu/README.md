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
    - Great VIM
    
  - ENV
     - git
     - [php 7.4](https://github.com/bigmpc/bigmpc/blob/main/Ubuntu/programing/php.md)
        - [composer](https://getcomposer.org/download/)
        - [laravel installer](https://laravel.com/docs/8.x/#installing-laravel)
     - [python 3.8.x](https://github.com/bigmpc/bigmpc/blob/main/Ubuntu/programing/python.md)
     - [nodejs 14.x](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04)
     - [docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
     - rust nightly
     - mysql (5.7)
     
     
 
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


## Config ENV and Linux Custom config
```bash
#spotify ad blocker
127.0.0.1 media-match.com
127.0.0.1 adclick.g.doublecklick.net
127.0.0.1 www.googleadservices.com
127.0.0.1 open.spotify.com
127.0.0.1 pagead2.googlesyndication.com
127.0.0.1 desktop.spotify.com
127.0.0.1 googleads.g.doubleclick.net
127.0.0.1 pubads.g.doubleclick.net
127.0.0.1 audio2.spotify.com
127.0.0.1 www.omaze.com
127.0.0.1 omaze.com
127.0.0.1 bounceexchange.com



127.0.0.1 adclick.g.doublecklick.net
127.0.0.1 adeventtracker.spotify.com
127.0.0.1 ads-fa.spotify.com
127.0.0.1 analytics.spotify.com
127.0.0.1 audio2.spotify.com
127.0.0.1 b.scorecardresearch.com
127.0.0.1 bounceexchange.com
127.0.0.1 bs.serving-sys.com
127.0.0.1 content.bitsontherun.com
127.0.0.1 core.insightexpressai.com
127.0.0.1 crashdump.spotify.com
127.0.0.1 d2gi7ultltnc2u.cloudfront.net
127.0.0.1 d3rt1990lpmkn.cloudfront.net
127.0.0.1 desktop.spotify.com
127.0.0.1 doubleclick.net
127.0.0.1 ds.serving-sys.com
127.0.0.1 googleadservices.com
127.0.0.1 googleads.g.doubleclick.net
127.0.0.1 gtssl2-ocsp.geotrust.com
127.0.0.1 js.moatads.com
127.0.0.1 log.spotify.com
127.0.0.1 media-match.com
127.0.0.1 omaze.com
127.0.0.1 open.spotify.com
127.0.0.1 pagead46.l.doubleclick.net
127.0.0.1 pagead2.googlesyndication.com
127.0.0.1 partner.googleadservices.com
127.0.0.1 pubads.g.doubleclick.net
127.0.0.1 redirector.gvt1.com
127.0.0.1 s0.2mdn.net
127.0.0.1 securepubads.g.doubleclick.net
127.0.0.1 spclient.wg.spotify.com
127.0.0.1 tpc.googlesyndication.com
127.0.0.1 v.jwpcdn.com
127.0.0.1 video-ad-stats.googlesyndication.com
127.0.0.1 weblb-wg.gslb.spotify.com
127.0.0.1 www.googleadservices.com
127.0.0.1 www.googletagservices.com
# IntelJ (If use crack version)
0.0.0.0 account.jetbrains.com
0.0.0.0 www.jetbrains.com
0.0.0.0 account.jetbrains.com
1.2.3.4 account.jetbrains.com
1.2.3.4 www.jetbrains.com
1.2.3.4 www-weighted.jetbrains.com
```

## list of fonts:
 - [Fira Code](https://github.com/tonsky/FiraCode)
 - [Vazir](https://rastikerdar.github.io/vazir-font/)
 - [Vazir Code](https://rastikerdar.github.io/vazir-code-font/)
