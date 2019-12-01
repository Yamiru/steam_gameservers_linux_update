# steam_gameservers_linux_update

##Requirements
-linux based os /debian,../
-user e.g. user1
-32bit libs (x86)
-console/terminal

Steam Dedicated Game Servers update

1. create folder: mkdir server1
1. download steamcmd: wget https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz
2. tar xf steamcmd_linux.tar.gz
3. sudo chown user1:user1 -R /opt/server1
4. login user1: su user1
5. ./csgo_server_update.sh

server downloaded/update to folder /opt/server1/game/

start server and play :D
