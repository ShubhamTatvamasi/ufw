# ufw

enable ufw:
```bash
sudo ufw enable
```

check status:
```bash
sudo ufw status
sudo ufw status verbose
```

allow ssh connection:
```bash
sudo ufw allow ssh
```

reset ufw:
```bash
sudo ufw reset
```

reload firewall:
```bash
sudo ufw reload
```

denay everything from IP:
```bash
sudo ufw deny from 10.10.10.216
```

allow everything on port 80,443:
```bash
sudo ufw allow proto tcp from any to any port 80,443
```

allow anything on port 3306 from spcfic IP:
```bash
sudo ufw allow from 15.15.15.15 to any port 3306
```

deny everything on port 25:
```bash
sudo ufw deny out 25
```

denay on specfic interface:
```bash
sudo ufw deny in on eth0 from 10.10.10.216
```


