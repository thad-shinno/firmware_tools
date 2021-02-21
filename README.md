# firmware_tools

### Usage
```
curl https://raw.githubusercontent.com/sadeli413/firmware_tools/main/firwmare_tools_installer.sh | bash
```

### Description
`firmware_tools_installer.sh` is just a simple no-brain script that installs a few firmware analysis tools. These tools are:
- https://github.com/attify/firmware-analysis-toolkit
- https://github.com/firmadyne/firmadyne
- https://github.com/devttys0/sasquatch
- https://github.com/ReFirmLabs/binwalk

### Dependencies
This script only works on GNU/Linux systems that are:
- Debian based
- Use GCC 10 by default (for Makefile)
- bash

### Example Vulnerable Firmware
- https://www.downloads.netgear.com/files/GDC/WNAP320/WNAP320%20Firmware%20Version%202.0.3.zip
