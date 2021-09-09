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

