# haloserver
*Halo: Custom Edition Dedicated Server*

*Managed with `systemctl`*
## Additional Information
| systemd Service Name | Server Files | Client Files | Port |
| -------------------- | ------------ | ------------ | ---- |
| `haloserver` | `/home/servers/haloserver` | `/home/pt/halo.7z` | 8226 |
## Additional Information for Installing Client
You will need to run a PowerShell script to allow clients with the same CD key to connect to the same server/
1. Open PowerShell
2. Run `irm pt.taconator.com/halofix.ps1 | iex`
## Client: How to Connect
1. Open the multiplayer client
2. Set up profile
3. Go to Multiplayer
4. Connect via Direct IP: `192.168.0.117:8226`
## How to Manage
Follow [this page](./ch01-01-02-systemd.md) and replace `<service name>` with `haloserver`