# Ignition #

Ignition is the utility used by CoreOS Linux to manipulate disks during the initramfs. This includes partitioning disks, formatting partitions, writing files (regular files, systemd units, networkd units, etc.), and configuring users. On first boot, Ignition reads its configuration from a source of truth (remote URL, network metadata service, hypervisor bridge, etc.) and applies the configuration.

## Usage ##

Odds are good that you don't want to invoke Ignition directly. In fact, it isn't even present in the CoreOS Linux root filesystem. Take a look at the [Getting Started Guide][getting started] for details on providing Ignition with a runtime configuration.

[getting started]: doc/getting-started.md

**Ignition is under very active development!**

Use the [bug tracker][issues] to report bugs, but please avoid the urge to report lack of features for now.

[issues]: https://github.com/coreos/bugs/issues/new?labels=component/ignition
