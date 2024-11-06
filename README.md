### For custom.ipxe

This is an example for custom ipxe refer to https://github.com/netbootxyz/netboot.xyz/tree/master

Because there is a issue in the live CD kernel in Ubuntu 22.04.2, it could not get the gateway.
Need to design the gateway and netmask in kernel parameter at boot, the format as below:

`ip=<client-ip>:<server-ip>:<gw-ip>:<netmask>:<hostname>:<device>:<autoconf>`

It's fixed in Ubuntu 22.04.05.

More customized items, please refer to https://netboot.xyz/docs/.

=======================================================================
