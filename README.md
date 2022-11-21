# iuwviap
Intel Unraid Windows10 VM Integrated Audio Passthrough

Guide I'm referencing: https://forums.serverbuilds.net/t/guide-remote-gaming-on-unraid/4248/9
  Solutions to try: 
    7 > 2: update the vm:
      machine: i440FX-4.2 or Q35-4.2 only if running into issues
      graphics rom bios: https://forums.serverbuilds.net/t/guide-remote-gaming-on-unraid/4248/7#:~:text=Prepare%20GPU%20BIOS%20for%20passthrough%20(click%20me)
      sound card: none
      other pci devices:  none checked 
    8 > 5: 
    https://forums.serverbuilds.net/t/guide-remote-gaming-on-unraid/4248/9#:~:text=Take%20note%20of%20the%20device%E2%80%99s%20bus%2C%20in%20this%20case%20it%E2%80%99s%20%E2%80%9C09%E2%80%9D.

(...)

VM Status:
Running 2nd most optimally w/ SATA SSDs mounted & shared