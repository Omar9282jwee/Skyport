# skyport panel

# modded version of codesanbox: Docker

# PANEL INSTALL:
```
sudo su
```
```
bash <(curl -s https://raw.githubusercontent.com/Omar9282jwee/skyport/refs/heads/main/panel)
```

# WINGS/NODE INSTALL:

```
sudo su
```
```
bash <(curl -s https://raw.githubusercontent.com/Omar9282jwee/skyport/refs/heads/main/wings)
```
```
cd skyportd
```

- paste your node configure
```
pm2 start .
```

# panel relaunch
```
pm2 start index
```
```
pm2 start skyportd
```

### ip-costom
```
wget https://github.com/playit-cloud/playit-agent/releases/download/v0.15.26/playit-linux-amd64
chmod +x playit-linux-amd64
./playit-linux-amd64
```
### for again start ->
```
./playit-linux-amd64
```
