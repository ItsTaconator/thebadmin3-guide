# t5server
*Call of Duty: Black Ops 1 Plutonium Server*

*Managed with Docker*

## Additional Information
| Server Files | Port |
| ------------ | ---- |
| `/home/dockeruser/t5server/` | 28961 |

## How to Manage
```
sudo machinectl dockeruser@
cd ~/t5server
docker compose <verb>
```
Replace `<verb>` with (remember to get rid of `<>`):
- Start server (`-d` is optional and just makes it run in the background):
    
    ```
    up -d
    ```
- Close server:

    ```
    down
    ```
- Access server console (while server is running) [to detach afterwards, press `Ctrl+p`, then `Ctrl+q`]:

    ```
    attach t5server
    ```

## More Information About Docker Compose
Follow [this page](./ch01-01-03-docker-compose.md) and replace folder path with `/home/dockeruser/t5server`