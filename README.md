# Skyport
```                                       skyport panel

PANEL INSTALL:
```
sudo su
```

```
bash <(curl -s https://raw.githubusercontent.com/Omar9282jwee/skyport/refs/heads/main/panel)
```

WINGS/NODE INSTALL:
```
sudo su
```
```
bash <(curl -s https://raw.githubusercontent.com/Omar9282jwee/skyport/refs/heads/main/wings)
```
```
cd skyportd


- paste your node configure

```
pm2 start .
```
### panel relaunch
```
pm2 start index
```
```
pm2 start skyportd
```
