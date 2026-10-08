# quake3server 
*Quake 3 Arena Dedicated Server*

*Managed with `systemctl`*
## Additional Information
Server can be configured in `/home/servers/quake3/start.bat`
| systemd Service Name | Server Files | Client Files | Port |
| -------------------- | ------------ | ------------ | ---- |
| `quake3server` | `/home/servers/quake3` | `/home/pt/Quake 3 Arena.zip` | 27960 |
## Client: How to Connect
1. Start the game
2. Press \` (backtick, next to `1`) to open console
3. Type `connect 192.168.0.117`
## How to Manage
Follow [this page](./ch01-01-02-systemd.md) and replace `<service name>` with `quake3server`