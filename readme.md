# Argon Fan Hat script (by Argon40)
### Tested with raspios

## Instructions

1. Download and run the "argonfanhat.sh" from this repository to /etc/argon_fanhat.
```
sudo git clone https://github.com/qeiynn/rpi_argon_fanhat
```
```
sudo bash rpi_argon_fanhat/argonfanhat.sh
```

2. Delete the downloaded directory (including the script)
```
sudo rm -r rpi_argon_fanhat
```

### Commands:

argonone-config: configure the fan curve (standard curve is good though).

argonone-uninstall: uninstall the script

### Button funtions:

While Pi is off: a short press turns it on.

While Pi is on: Long press initiates soft shutdown. Double Tap reboots.
