For building steps, generally follow the Pengwin building guide [here](https://github.com/WhitewaterFoundry/Pengwin/blob/master/BUILDING.md).

.diff:

To create the install.tar.gz go to the project: https://github.com/WhitewaterFoundry/fedora-remix-rootfs-build
create-targz.sh must be run on an existing Fedora Linux build instead of Debian.

Because the building process bind-mounts /dev within the newly created chroot, this must be run on a full Fedora install (bare metal or virtualisation, NOT a WSL install).
