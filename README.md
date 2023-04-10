# opencopter-flightcontroller
OpenCopter controller board firmware forked from ArduCopter v3.2.1 

# Build firmware


# Upload firmware
/Applications/MYAPP/ArduinoOpenCopter.app/Contents/Resources/Java/hardware/tools/avr/bin/avrdude -C/Applications/MYAPP/ArduinoOpenCopter.app/Contents/Resources/Java/hardware/tools/avr/etc/avrdude.conf -v -v -v -v -patmega2560 -cwiring -P/dev/cu.usbmodem1411 -b115200 -D -Uflash:w:/var/folders/sc/1bk22l5d7yxfyvm1r7yt0q300000gn/T/ArduCopter.build/ArduCopter.hex:i
