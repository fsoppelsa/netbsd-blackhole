netbsd-blackhole
================

Old NetBSD 3.x tcp incoming blackholing kernel patch.

Instead of answering with a REJECT, stay silent.

The kernel property is settable via `sysctl`:

	sysctl net.inet.tcp.blackhole=1
