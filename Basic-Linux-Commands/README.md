# Updating Packages on Linux

---

## What is a Package Manager

###### Updating Packages on Ubuntu/Debian

By default, the package manager on Debian is APT. Here is how you update them. 



1. First use this command to check if there are any packages that are needed to be updated. 

```shell
sudo apt update
```



2. Second, if there are any updates to be given out, use this command to update those packages. 

```shell
sudo apt upgrade

## Or use this
sudo apt full-upgrade
```



3. After the packages are updated, it is recommended to reboot your system. Use this command to do this: 

```shell
sudo reboot
```
