# Best-TLP-config-for-AMD-Ryzen-4800H-in-ASUS-Vivobook-PRO-15-OLED
This repo contains the best tlp config for ASUS Vivobook Pro 15 OLED with AMD Ryzen 7 4800H.

Just install tlp and tlp-rdw
```
sudo dnf install tlp tlp-rdw
sudo systemctl enable tlp.service
sudo tlp start
sudo dnf remove tuned tuned-ppd #For Fedora Workstations
```
Then copy this file to /etc/
```
sudo cp /Downloads/tlp.conf /etc/
```
And Done!

This config increased my battery life to 11 hours.
