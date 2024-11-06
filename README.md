### For custom.ipxe

This is a example for custom ipxe refer to https://github.com/netbootxyz/netboot.xyz/tree/master

Because there is a issue in the live CD kernel in Ubuntu 22.04.2, it could not get gateway.
Need design gateway and netmask in kernel parameter at boot, format as below:

*ip=<client-ip>:<server-ip>:<gw-ip>:<netmask>:<hostname>:<device>:<autoconf>*

And this is only working in Ubuntu 22.04.2.

More customized items refer to https://netboot.xyz/docs/.

`=======================================================================`
