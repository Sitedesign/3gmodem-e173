# 3gmodem-e173
HUAWEI E173 start/stop script for Debian based systems.
## Getting started

### Requirements

* Huawei E173 3G modem
* coreutils package (stty)
* pppd package
* usb-modeswitch package

### Install
Copy 3gmodem-e173 file to /usr/local/bin and make it executable.
Edit the parameters in the script for your needs.

### Usage
Start modem and establish PPP connection:
```
3gmodem-e173 start
```

Disconnect and stop modem:
```
3gmodem-e173 stop
```

Get connection status:
```
3gmodem-e173 status
```

USB modeswitching:
```
3gmodem-e173 modeswitch
```

## License
Copyright (c) 2015 Krisztian CSANYI Licensed under the GPLv2 license.
