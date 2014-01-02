armhf-node-webkit
=================

Node-webkit binary for armhf architecture compiled on Exynos 4412 (ARM Cortex-A9) on Linaro 12.11.

Only nw and nw.pak files are required to run node-webkit binary. 


armhf.com Image Minimal APT install
-----------------------------------

```
sudo apt-get update

sudo apt-get install xorg libgtk2.0-0 libasound2 libnss3 libgconf-2-4

```
allow node-webkit to load nss in standard location
```
sudo ln -s /usr/lib/arm-linux-gnueabihf/nss /usr/lib/nss

```
