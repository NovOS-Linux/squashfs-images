Minimal squashfs images to get you started (You need to install kernel & other base packages first)

Download in releases page

How to extract: run unsquashfs -f -d /media/location /media/location2/NovOS.sfs as root.

How to get pacman working: run pacman-key --init & pacman-key --populate then you can update & install packages

theres a rungui app, however, its disabled by default: to enable it, run chmod +x /usr/bin/rungui.

DEFAULT ROOT PASSWORD IS novos.

REQUIRED FOR SOME APPS & AUR TO WORK:
Create a user account:
its usually more secure to use a normal user account on chrooted.
useradd *username*
usermod -aG wheel *username*
mkhomedir_helper *username*
passwd *username*
su *username*
cd /home/*username*/

That's all for setup!
