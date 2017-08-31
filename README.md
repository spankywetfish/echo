# echo
For controlling local devices with the Amazon Echo.

Instructions for installation and usage [available on Instructables here](http://www.instructables.com/id/Hacking-the-Amazon-Echo/)

Brought to you by [FabricateIO](http://fabricate.io)

### Updated by spankywetfish

Integration of code to allow control of TP-Link SmartPlugs based on the work of [softScheck](https://github.com/softScheck/tplink-smartplug)
          
Added logging to syslog.

## Quick Start

1. Create a [Python Virtual Environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
2. git clone *this_repo*
3. cd *this_repo*
4. pip install -r requirements.txt
5. Modify smarthome.py with device DNS names
4. python smarthome.py
6. Tell Echo, "discover my devices"
7. Use Echo's "turn off device" and "device on" to see True/False script output

