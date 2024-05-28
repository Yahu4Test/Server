# Server
# Commands

Server Creating:

sudo apt update
sudo apt upgrade

sudo apt install openjdk-17-jdk

mkdir minecraft_server
cd minecraft_server

wget "enter_url_here"

Vanilla Minecraft server file: 
https://piston-data.mojang.com/v1/objects/84194a2f286ef7c14ed7ce0090dba59902951553/server.jar
(1.20.1),

Vanilla Minecraft server file:
https://piston-data.mojang.com/v1/objects/1b557e7b033b583cd9f66746b7a9ab1ec1673ced/server.jar
(1.16.5),

Vanilla Minecraft server file:
https://launcher.mojang.com/v1/objects/b58b2ceb36e01bcd8dbf49c8fb66c55a9f0676cd/server.jar
(1.8.9)

java -Xmx12288M -Xms12288M -jar server.jar nogui






Port Forwarding:


wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz

tar -xvzf ngrok-v3-stable-linux-amd64.tgz

./ngrok authtoken “yourtoken”

./ngrok tcp 25565
