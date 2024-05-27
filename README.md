# Lcd4Linux Configs

## Install this configuration

```
sudo install -m 0600 lcd4linux.conf /etc/lcd4linux.conf
sudo install -m 0644 lcd4linux.service /etc/systemd/system/lcd4linux.service
sudo systemctl daemon-reload
sudo systemctl enable --now lcd4linux
```