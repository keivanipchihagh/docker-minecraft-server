# docker-minecraft-server
🚀 Host a Minecraft server on your own server using Docker

## Setting up
Things to change while deploying your own version of Minecraft Server:

### Extras Directory
- `whitelist.json`: provide list of username/UUID pairs of authorized players.
- `ops.json`: provide a list of username/UUID pairs of Administrators.
- `mods.txt`: pass a list of server-side mods to download on initialization.
- `icon.jpeg`: custom icon for your Minecraft server.

### Game Variables
Rename the `.env.template` to `.env` and change the variables to adjust your preferred world's characteristics. (Remember to fill the empty spots!)

## Further Steps
- [ ] Move Minecraft-Server behind DNS and CDN
- [ ] Move Minecraft RCON behind DNS
- [ ] Add Dynamic support for extras directory (HTTP SD)
- [ ] Add Prometheus monitoring
- [ ] Add authentication for server login