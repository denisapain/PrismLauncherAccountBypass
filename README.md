# PrismLauncher Account Bypass
A simple bypass to use [PrismLauncher](https://prismlauncher.org) without a paid Minecraft account!

#### USING THIS WILL REMOVE ANY EXISTING ACCOUNTS ON PRIMSLAUNCHER


### Portable Version (AnyOS)
Download [this file](https://raw.githubusercontent.com/denisapain/PrismLauncherAccountBypass/main/accounts.json) and put it into your prismlauncher directory!


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
