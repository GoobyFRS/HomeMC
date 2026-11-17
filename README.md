# Goobs HomeMC

Version Controlled Minecraft Server repo for home use.

### First Time Setup

Download and install the following dependencies:

- [Amazon Corretto 25](https://docs.aws.amazon.com/corretto/latest/corretto-25-ug/downloads-list.html)
- [Minecraft Server Download](https://www.minecraft.net/en-us/download/server)
- [Gooby_RCON](https://github.com/GoobyFRS/Gooby_RCON)

### Running the Server

```shell
cd /path/to/your/minecraft/server/directory
git clone https://github.com/GoobyFRS/HomeMC.git
cd HomeMC
sudo cp minecraft_server.service /etc/systemd/system/minecraft_server.service
sudo systemctl daemon-reload
sudo systemctl enable minecraft_server
sudo systemctl start minecraft_server
```
