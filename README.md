# Boomer-Maggy

The purpose of this script is to electronically filter non alphanumeric characters from a Magnetometer data string before entering acquisition software. The garbled characters are introduced through a Boomer sub-bottom profiler that is being flown in tandem. 

# Usage 

Clone the repository on a Raspberry Pi
Assign portOut/portIn to usb ports on the Pi using SYMLINK rules with specified port path.  
Add start command upon boot in /etc/rc.local file. 
Connect incoming data stream to portIn
Connect outgoing data stream to portOut, attach null modem to usb-serial cabl
