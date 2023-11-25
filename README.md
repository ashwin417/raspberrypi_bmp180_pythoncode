# raspberrypi_bmp180

### Installation of Raspbian OS
- Get RaspberryPi Imager from official site.
- Connect the Micro SD Card to your PC with the card reader and open the imager
- Select the raspberrypi model and OS according to your model.
- Edit the settings with hostname, user detals, Wireless LAN SSID and Password, along with enabling SSH authentication.
- Flash the OS into the SD Card.
- Insert the card into Raspberry Pi SD Card slot.

### SSH Authentication through terminal
- Power on the raspberrypi and connect your PC to same Wireless LAN you have given while flashing Raspbian OS.
- Open terminal(Powershell or cmd in MS Windows) in your PC.
- Type ```ssh usernname@hostname``` and click enter.
- It will be asking for some fingerprint authorization and give YES for it.
- You will get remote access to raspberry Pi machine.
- For GUI, you shall download and install VNC Viewer and configure it with your hostname and user details.
