# noti_snap
 Snapcraft file for the generation of noti snap package.


# Description

Noti is an application to push when terminal command has finished.
https://github.com/variadico/noti


## documentation for variables
https://github.com/variadico/noti/blob/master/docs/noti.md



https://snapcraft.io/docs/go-applications

# Build Snap Package

```
cd noti_snap
snapcraft
```


# Package install

## note

For Noti to work properly use classic confinement

```
cd noti_snap
sudo snap install noti_*_amd64.snap --dangerous --classic
```