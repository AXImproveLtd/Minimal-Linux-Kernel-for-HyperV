# Minimal-Linux-Kernel-for-HyperV
The config file allowing to build custom, minimalist linux kernel for use as a Gen2 guest os in AMD-based Hyper-V server.

It is enough to run Debian 9 with PHP, Nginx and MariaDB

# Included features:

-x64, SMP

-AMD cpu (Opteron) ONLY

-ACPI

-console, text mode only

-drivers for Hyper-V syntetic devices (disk, network, etc)

-EXT3+4

-IP4, iptables

-majority of other kernel services.


# Not included
-Intel cpu

-GUI

-IP6

-other architectures

-other disk drivers

-other network drivers

-other protocols

-other filesystems

-LVM, RAID

-NFS, SMB

-other partition types


# How to use

Use one of the .config files provided as starting point to build the kernel suitable for your use case.

