# dosthol
Setup proxmox to wake virtual machines with any WOL client by default.

- Install the daemon on proxmox as a systemd service, enable and start it.
- If you want to use with any WOL client set the config option of the daemon accordingly by removing the comment sign to make "start" the default.
- If you want to send other comments to the virtual machine (restart, shutdown), use the client script (with GUI) on any client.


Source/Credit: https://forum.proxmox.com/threads/update-wake-and-other-on-lan-for-vms-v0-3.26381/
