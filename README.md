# PrismLauncherAccountBypass
Short command to make a "default" offline account so you don't have to buy minecraft on [prismlauncher](https://prismlauncher.org) :D



### Windows:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > %appdata%/PrismLauncher/accounts.json
```
 
 
### macOS:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/Library/Application\ Support/PrismLauncher/accounts.json
```


### Linux:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.local/share/PrismLauncher/accounts.json
```


### Linux (Flatpak):
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/accounts.json
```
