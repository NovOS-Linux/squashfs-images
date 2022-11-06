# squashfs-images
Minimal squashfs images to get you started (You need to install kernel &amp; other base packages first)

Download in releases page

How to extract:
run unsquashfs -f -d /media/location /media/location2/NovOS.sfs as root.

How to get pacman working:
run pacman-key --init & pacman-key --populate
then you can update & install packages

theres a rungui app, however, its disabled by default:
to enable it, run chmod +x /usr/bin/rungui.

That's all for setup!
