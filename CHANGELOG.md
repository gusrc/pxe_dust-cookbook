## 1.2.6:
* COOK-1502: pxe_dust has some if statements that could that could be reduced
* support multiple items in the run list from the data bag
* switch from eth0 to auto for pxelinux.cfg

## 1.2.4:
* take default run_lists when none-specified
* clean up installer when finished

## 1.2.3:
* added attribute for always pulling latest Chef installer

## 1.2.2:
* COOK-1369 Ubuntu 12.04 Precise Pangolin support

## 1.2.1:
* updated to use apt cookbook using apt-cacher-ng
* make local mirrors of the netboots
* added Debian support

## 1.2.0:

* COOK-999 uses the full stack intaller for bootstrapping nodes.

## 1.1.2:

* Fixes COOK-481, COOK-594