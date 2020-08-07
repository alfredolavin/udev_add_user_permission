# udev_add_user_permission
Simple script for allowing normal users to access USB devices easily. Ideal for embedded development with cheap pirated programmers without ussing sudo every time.

You only need to know the device vendor and device id's.
- *Generaly you connect the device and check dmesg's command tail. It would look something like this:*
[29997.790839] usb 1-10: new full-speed USB device number 12 using xhci_hcd
[29997.939719] usb 1-10: New USB device found, idVendor=1a86, idProduct=5512, bcdDevice= 3.04
[29997.939720] usb 1-10: New USB device strings: Mfr=0, Product=0, SerialNumber=0

 - *Did you found Wally there? Let's highlite it for you:*
[29997.790839] usb 1-10: new full-speed USB device number 12 using xhci_hcd
[29997.939719] usb 1-10: New USB device found, **idVendor=1a86, idProduct=5512**, bcdDevice= 3.04
[29997.939720] usb 1-10: New USB device strings: Mfr=0, Product=0, SerialNumber=0

How to install and use:
