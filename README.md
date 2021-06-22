# Rocky Linux Vagrant Box

This is a Rocky Linux Vagrant box for local development with Rocky Linux.  For more information about Rocky Linux please check out their website https://rockylinux.org

## Usage

__Note:__ The `Vagrantfile` is just an example and you should use `vagrant init` and then modify your `Vagrantfile` to use the `rockylinux` box after importing the box into Vagrant.


You need to import this box into vagrant to use it.

To do this run the following from the directory in which `rockylinux.box` is located:

```bash
vagrant box add rockylinux rockylinux.box
```
