# EOL
Abandoned, use `sudo ifconfig wlan0 hw ether <enter mac>` (which was deprecated in favour for iptool2 but idc)<br>

# Mac-Spoofer
Allows to change your MAC Adress on Windows 10 Computers even if your NIC doesn't support MAC changing

**How this works**
This Program emulates a virtual NIC on your Computer (vSwich) without having to create a full VM, so it doesn't occupy computing power.
The NIC then gets Bridged, so the Network you're trying to connect to connects directly to your virtual NIC (through the Real One but the Network can't notice it)
Then You can Easily Change the MAC of your Virtaul NIC, which shows up in `ncpa.cpl` as *hxr404_mac*

**Usage**
Start the File SETUP.bat and let the installation wizard do it's Job. (You can change the parameters afterwards by Pressing WIN + R and typing ncpa.cpl)
The Virtual NIC is ready! Now just start the file *mac.bat* and enter your new MAC!

**Info**
This requires some Hyper-V to work, it installs the dependencies automatically. The Program itself is just some kind of Setup Wizard, ist fully portable. It just installs and configures the virtual NIC *hxr404_mac*. The concept is similar to Microsoft Loopback Adapter, but better. Also it's the first tool with that functionallity.

**License**
<del>Like any other repos, please don't redistribute this, instead share the Link, as here are always the newset updates.</del>
Apache 2.0
