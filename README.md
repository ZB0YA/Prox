to install open shell config by typeing
nano ~/.bashrc
in terminal then past code at the bottom 
to save type control+O and enter 
then to exit Control+X
then reboot to install or update 
proxmark3 software type prox update 
to connect to your proxmark3 
via TCP on port 5000 type prox tcp 
note requires UART TCP bridge 
V2.1 only prox USB connects via USB serial 
only works if only USB serial device 
prox flash updates firmware 
only works on proxmark3 easy and other generic pm3
note /storage/emulated/0/NFC_RFID_dump has to exist for termux version to work 
prox eml <File name.eml>
emulates a MF classic tag
from tag dump no need for manually inputing UID
