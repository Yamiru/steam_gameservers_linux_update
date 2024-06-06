# Steam gameservers linux Install and Update 

<img src="https://img.shields.io/badge/Build%20Status-passed-green.svg" alt="passed"> <img src="https://img.shields.io/badge/tested%20OS-Debian%20server%2011%20x64-blue.svg">

## Requirements
- linux based os /debian,../
- sudoers   (```aptitude install sudo```)
- 32bit libs (x86) and other libs...



Steam Dedicated Game Servers update
1. create user user1  (```sudo adduser --disabled-login user1```)
1. navigate to folder e.g opt (```cd opt ```)
1. create folder: (```mkdir server1```)
2. navigate to /opt/server1 (```cd server1 ```)
1. download steamcmd: (```wget https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz```)
2. extract (```tar xf steamcmd_linux.tar.gz```)
3. change permission to foler (```sudo chown user1:user1 -R /opt/server1```)
4. login user1: (```su user1```)
5. create file (```nano csgo_server_update.sh```) (ctrl+x) y and ENTER
6. (```chmod +x csgo_server_update.sh```)
7. run (```./csgo_server_update.sh```)

server downloaded/update to folder /opt/server1/game/

start server and play :D


+works with teklab linux gamepanel autoupdate
