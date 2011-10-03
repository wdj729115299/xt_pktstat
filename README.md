xt_pktstat; an iptable module for high frequency packet accounting:

A loadable kernel module that keeps track of number of frames and bytes received per submillisecond time windows.
An iptables shared library to add/configure/remove rules
A /proc subdirectory to easily use statistics in user programs

The project consists of two directories:
- kernel: loadable kernel module, accounting code
- iptables: userland shared library to manage accounting rules

Compilation of kernel module
----------------------------


Compilation of userland shared library
--------------------------------------

