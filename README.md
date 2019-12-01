# steam_gameservers_linux_update

<img src="https://img.shields.io/badge/Build%20Status-passed-green.svg" alt="passed"> <img src="https://img.shields.io/badge/tested%20OS-Debian%20server%2010.1%20x64-blue.svg">

##Requirements
- linux based os /debian,../
- sudoers   (```aptitude install sudo```)
- user user1  (```sudo adduser --disabled-login user1```)
- 32bit libs (x86) and other libs...



Steam Dedicated Game Servers update

1. create folder: mkdir server1
1. download steamcmd: wget https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz
2. tar xf steamcmd_linux.tar.gz
3. sudo chown user1:user1 -R /opt/server1
4. login user1: su user1
5. ./csgo_server_update.sh

server downloaded/update to folder /opt/server1/game/

start server and play :D
