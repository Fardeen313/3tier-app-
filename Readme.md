Hi Alvin,

I have completed the migration of all the Basic SKU IPs to Standard SKU. Only three dynamic IPs are pending, as they cannot be migrated by simply disassociating them from the VMs. I also tried creating new Standard dynamic IPs via both CLI and portal, but it is not possible since Standard SKU only supports static allocation.

The only available option is to create Standard static IPs and attach them to the three VMs. Please let me know how you’d like to proceed.
