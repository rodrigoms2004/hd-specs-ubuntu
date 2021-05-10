## HD command specs


### Install it
```
sudo apt install smartmontools
```

### Running
```
sudo smartctl -i /dev/sda
smartctl 6.6 2016-05-31 r4324 [x86_64-linux-4.15.0-142-generic] (local build)
Copyright (C) 2002-16, Bruce Allen, Christian Franke, www.smartmontools.org

=== START OF INFORMATION SECTION ===
Model Family:     Seagate Laptop SSHD
Device Model:     ST1000LM014-1EJ164
Serial Number:    W7737W9X
LU WWN Device Id: 5 000c50 09cb66e10
Firmware Version: DEMG
User Capacity:    1.000.204.886.016 bytes [1,00 TB]
Sector Sizes:     512 bytes logical, 4096 bytes physical
Rotation Rate:    5400 rpm
Form Factor:      2.5 inches
Device is:        In smartctl database [for details use: -P show]
ATA Version is:   ACS-2, ACS-3 T13/2161-D revision 3b
SATA Version is:  SATA 3.1, 6.0 Gb/s (current: 6.0 Gb/s)
Local Time is:    Mon May 10 08:32:59 2021 -03
SMART support is: Available - device has SMART capability.
SMART support is: Enabled

```



### From

https://askubuntu.com/questions/466366/is-there-a-command-to-view-hard-drive-specs