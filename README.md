# Linux Mink (WIP)

NixOS configuration files for Linux Mink. Check the
[documentation](https://h-banii.github.io/LinuxMink/)!

https://github.com/user-attachments/assets/8faacc68-b6c7-47a0-92ca-e75077e7fb54

## Outputs

```js
└─legacyPackages.system
  └─livecd
    ├─vm
    ├─isoImage
    └─isoVm
```

### Live CD (preview)

#### Virtual Machine

```console
$ export QEMU_OPTS='-m 4G -device virtio-vga-gl -display gtk,gl=on'
$ nix run github:h-banii/LinuxMink#livecd.vm
```

#### ISO Image

```sh
nix build github:h-banii/LinuxMink#livecd.isoImage
```

### Graphical Installer (WIP)

### NixOS Module

https://h-banii.github.io/LinuxMink/modules/nixos/

### Home Manager Module

https://h-banii.github.io/LinuxMink/modules/home-manager/

## MikanTheMink

- https://www.youtube.com/@MikanTheMink
- https://www.twitch.tv/mikanthemink
- https://www.twitter.com/MikanTheMink
