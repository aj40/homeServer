# My Home Server
Just wanted to do a quick breakdown of my home server & document the set up and resources I used for it.

## Hardware

1. Dell Optiplex Micro i5-7050T, 32GB RAM, 256Gb SSD
2. Yottamaster 4-bay HDD Enclosure
3. 12TB Recertified Barracuda drive
4. 4TB External harddrive taken apart
5. LG bp50nb40 blu-ray drive

## Software
Now for the fun part...

### Resources
Here's some videos and guides that helped me:
- [Hardware Haven - Proxmox & TrueNAS Setup](https://www.youtube.com/watch?v=_sfddZHhOj4)
- [Mounting TrueNAS in an unpriveleged LXC container](https://forum.proxmox.com/threads/tutorial-unprivileged-lxcs-mount-cifs-shares.101795/)
- [Jellyfin Intel Hardware Acceleration on an LXC container](https://jellyfin.org/docs/general/administration/hardware-acceleration/intel)
- [Immich Hardware Acceleration](https://immich.app/docs/features/hardware-transcoding)
- [Hardware Haven - ARM in Proxmox](https://www.youtube.com/watch?v=wPWx6GISIhY)
- [Potentially useful scripts](https://community-scripts.github.io/ProxmoxVE/)

### ProxMox
Standard ProxMox install using [this link.](https://pve.proxmox.com/wiki/Installation)

### TrueNAS Scale
12Gb RAM, 32Gb Disk, 4 cores

### Jellyfin
4Gb RAM, 32Gb Disk, 4 cores

### Immich
Using [Dockge](https://tteck.github.io/Proxmox/#dockge-lxc) 6Gb RAM, 16Gb Disk, 4 cores

### Custom Firmware for the Disc Drive
Using [this guide.](https://forum.makemkv.com/forum/viewtopic.php?f=16&t=19634#:~:text=BP50NB40%20to%20%3E%20BP50NB40,%22%20after%20rawflash)



