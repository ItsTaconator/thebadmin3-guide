# Managing `systemd` services
`systemd` services are managed with a tool called `systemctl`. This page will cover basic usage of `systemctl`. For more information, see [this DigitalOcean guide](https://www.digitalocean.com/community/tutorials/how-to-use-systemctl-to-manage-systemd-services-and-units) or [the `systemctl` man pages](https://man7.org/linux/man-pages/man1/systemctl.1.html).

> Remove to remove `<>` from service names
## Start
```
sudo systemctl start <service name>
```
## Stop
```
sudo systemctl stop <service name>
```
## Restart
```
sudo systemctl restart <service name>
```
## Start automatically on boot
```
sudo systemctl enable <service name>
```
## Stop service from starting on boot
```
sudo systemctl disable <service name>
```
## Start automatically on boot, and start service now
```
sudo systemctl enable --now <service name>
```