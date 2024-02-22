# Putty-Minecraft
Putty Minecraft TUT
In Putty Console

Commands:
yum list jdk*  // List of the  available Java packages
Example: sudo yum install jdk-20-headless.aarch64


Opening vm's firewall ports:

sudo firewall-cmd --permanent --zone=public --add-port=25565/tcp 
sudo firewall-cmd --permanent --zone=public --add-port=25565/udp
sudo firewall-cmd --reload

Intalls tmux

sudo yum install tmux
tmux new -As m // Creates a new tmux session
now

use FileZilla

Open ServerManager
New Server

Proticoll: SFTP - SSH File Transfer Protocol
Server: Public Ip Adresse and Port
Conncont Key
User opc
Key from Putty
Click on Connect

For PapaerMc as a Server Start u need the Startup Command
Help Link: https://docs.papermc.io/paper/getting-started
Download Newest Paper Verision change the filename to papar.jar

Run this command 
java -Xmx4G -Xms4G -jar paper.jar --nogui 

and your done 

join your server with the Public IP
