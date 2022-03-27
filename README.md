# Arch-Automated-Installation
<p> Makes your brainless arch installation even more brainless :D </p>

## Requirements
```
x86_64 system
EFI compatile
Internet connection
```
## Usage
Follow the installation instructions from https://wiki.archlinux.org/title/Installation_guide and create a bootable usb drive. Disable secure boot and boot the drive.
From this state you can continue by cloning this repo and running the script, though it is recomended to complete the installation using ssh.
```
pacman -Sy && pacman -S git
git clone https://github.com/emin-skrijelj/arch-automated-installation
./arch-automated-installation/arch-install.sh
```
## Second Usage
You can download an automated arch installation as a .iso file <a href="https://mega.nz/file/iloDkQCb#n9zsLtwbjZFj8K5uIbXuOgjBIkoTf1eIdAP1J678DEk">HERE</a>
Just make an bootable usb drive with this .iso file and your auto installation arch linux as .iso file will be ready to go :D
(note: this .iso file is a bit outdated since it hasn't been updates since this summer, there are some chances you get some error through the installation while downloading some packages.)
