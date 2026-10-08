# Issues Managing Docker/Docker Service Isn't Running
The proper sequence of commands for managing Docker is as follows:
```
sudo machinectl dockeruser@
systemctl <verb> docker --user
```
Replace `<verb>` with one of these:
- `start`
- `stop`
- `status`
- `restart`
- `enable`
- `disable`