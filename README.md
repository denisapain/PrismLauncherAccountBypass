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

### Manual Way
Download [this file](https://raw.githubusercontent.com/denisapain/PrismLauncherAccountBypass/main/accounts.json) and put it into the correct directory (listed below)



**Windows: %appdata%/PrismLauncher/**

**macOS: ~/Library/Application Support/PrismLauncher/**

` in macos, show the path bar by pressing the Option key to show it momentarily. copy the directory from the macos section  and paste it, then put the accounts.json file in that directory, or you know, use the command above `

**Linux: ~/.local/share/PrismLauncher/**

**Linux (flatpak): ~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/**
