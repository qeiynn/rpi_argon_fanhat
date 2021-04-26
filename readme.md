# Argon Fan Hat script
### Tested with raspios

## Instructions

1. Download and run the "argonfanhat.sh" from this repository to /etc/argon_fanhat.
```
sudo git clone https://github.com/qeiynn/rpi_argon.fan.hat
```
```
sudo bash argonfanhat.sh
```

2. Delete the downloaded directory (including the script)
```
sudo rm -r rpi_argon.fan.hat
```

3. Commands:

argonone-config: configure tha fan curve (standard curve is good though).
argonone-uninstall: uninstall the script


3. Button funtion:

While Pi is off: a short press turns it on.

While Pi is on: Long press initiates soft shutdown. Double Tap reboots.

made by Argon40
