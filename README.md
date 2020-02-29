# armlinux-x86

Various ARM Linux images customized to include an x86 (i386) Linux chroot with Wine for running x86 Linux and Windows apps

---

### What is this?
This project is a collection of ARM Linux images for different SoC devices, precustomized to include an i386 Linux chroot powered by some qemu binaries  to run x86 Linux apps (and Windows ones too, with the help of Wine).

### How did you make this? Could I have the sources of what you modified?
I probably wouldn't be able to build these images without the help of the sources listed below:
* [How to run x86 on ARM by Novaspirit](https://www.novaspirit.com/2019/04/15/run-x86-arm/)
* [Kernel building - Raspberry Pi Documentation](https://www.raspberrypi.org/documentation/linux/kernel/building.md)
Those are basically all the things I did without any external modification or strange software added into the image, so I would basically consider these as the sources. Also, I did not include any proprietary software whatsoever, so you will only find software that was already on the image by default or free software added by me.

### Which devices do you support? Which have been tested to work?
Available images are for:
* Raspberry Pi 0, 1, 2, 3 (all revisions) with Wine support
* Raspberry Pi 4 - soon
* Nintendo Switch - soon
They have been tested to work on:
* Raspberry Pi 3 (by me)

### How well does it perform?
Depends pretty much on the device. On the PI3 performance seems to be comparable with a circa 300 MHz Pentium CPU.
Below you have some various benchmarks and tests.
(soon)

---

### Downloads
* Raspberry Pi 0-3 (currently being uploaded)

### Contacts
If you built an image for another device, you tested an image on one of your devices, did some benchmarks or just have general suggestions, feel free to contact me at this email address:
[octoandri04@protonmail.com](mailto:octoandri04@protonmail.com)