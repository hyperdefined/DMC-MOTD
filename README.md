# DMC-MOTD
MOTD system for DESTROYMC.NET. The plugin supports both Bungeecord and Bukkit servers. Simply drop the jar into your plugins folder.

### Default config
Use `/motdreload` to reload the config.
```yaml
# Type can be "random" or "fixed." Random will pick a MOTD from the list. Fixed will only show the fixed MOTD.
type: "random"
random-motd:
 - '&6random1'
 - '&6random2'
fixed-motd: "fixed test"

# Set a custom favicon here. This allows you to reload the icon without having to reload the proxy/server.
# Place the icon in the DMC-MOTD folder with the config.yml
use-custom-icon: false
custom-icon-filename: "icon.png"
```
