# ecorepython
python ide touch development framework ml framework

19th Dec 8.07

Figuring out how to get code onto this
Code is 

1. pi ide server. server boots from pi server name "arm"
2. pc client. main development client = ide on pc runs on pc only will runn happily on celeron name "ace"
3. pi client for touch development /test .. the development name "fix"

pi clients are 
"buster"

Linux arm 5.10.103-v8+ #1529 SMP PREEMPT Tue Mar 8 12:26:46 GMT 2022 aarch64 GNU/Linux

= "legacy buster" .. iso. using

import ft5406
from ft5406 import Touchscreen, TS_PRESS, TS_RELEASE, TS_MOVE
 
 ^ raspberry pi official 7" touch screen

to enable that driver which is multi touch

'/usr/local/lib/python3.7/dist-packages/ft5406.py'

~ line 116 changed from

changed from TOUCHSCREEN_EVDEV_NAME = 'FT5406 memory based driver'
to TOUCHSCREEN_EVDEV_NAME = 'raspberrypi-ts'

that driver, works headless

/etc/rc.local on "fix" .. the pi client name

calls "/home/dan/x/t0" 

"/home/dan/x/t0"

is 

#!/bin/bash
t
t0

that script .. cycles through.  the python client will only reboot. fast reboot
to refresh. .. pi client boots .. currently independently am going to fix. so it boots off the server/independently

this is general configuration information. will write approach to system documentation. when i get th code up and uploading.
will test the installation from this (git)


