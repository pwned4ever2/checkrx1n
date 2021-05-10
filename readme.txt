checkra1n for linux with odysseyra1n


Linux-based distribution for jailbreaking iOS devices w/ checkra1n.

Download Etcher and the ISO from releases.(https://github.com/asineth0/checkn1x)
Open the .iso you downloaded in Etcher.
Write it to your USB drive.
Reboot and enter your BIOS's boot menu.
Select the USB drive.

The CRSOURCE variable is the direct link to the build of checkra1n that will be used.
Add something to the VERSION variable if you want to redistribute your image, i.e. 1.0.6-foo.
# debian/ubuntu/mint/etc.
apt install curl ca-certificates tar gzip grub2-common grub-pc-bin grub-efi-amd64-bin

# archlinux
pacman -S --needed curl tar gzip grub mtools xorriso cpio xz

sudo ./build.sh
credit:
asineth0
@pwned4ever2