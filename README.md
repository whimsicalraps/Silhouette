# Silhouette
Silhouette Eurorack Module Firmware

Here you'll find firmware updates for Silhouette.

Get the [Latest Firmware](https://github.com/whimsicalraps/Silhouette/releases/latest).

You can view & download historical versions by viewing [Releases](https://github.com/whimsicalraps/Silhouette/releases). Each version has notes on the changes made for the given release.

## How to Update

You'll need to access the left edge of the module, so either remove it slightly from the case, or remove the module to the left of Silhouette.
Keep your Eurorack case powered on throughout this process (you can turn off the power while attaching the USB cable to be extra safe).

### Download new firmware file

* Download the [Latest Firmware](https://github.com/whimsicalraps/Silhouette/releases/latest), or an older version if you need to downgrade.

The file has a `.uf2` extension.

* Open a file browser and locate this file (likely in your Downloads folder).

### Locate the USB port

On the lower of the 2 circuit boards, at the left edge, beneath the input jacks, you'll find a USB-C port.

* Connect this port to your computer with an appropriate cable.

### Enter the bootloader
Find the 2 buttons next to the USB port:

* Press them both at once (the module will turn off)
* Release the button nearest the top of the module
* Then release the button immediately next to the USB port

Silhouette will appear as a removable disk drive on your computer. It will be called "RPI-RP2" on windows.

### Upload the firmware

* Drag-and-drop the the firmware file (eg. `Silhouette_v111.uf2`) onto the removable disk drive that appeared.

The file will take a few seconds to copy, after which Silhouette will restart automaticaly.

Your firmware is now up to date!
