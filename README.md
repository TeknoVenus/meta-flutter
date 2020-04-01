# meta-flutter

Yocto Layer for Flutter Engine


### Project Status

flutter-engine embedder builds

flutter-wayland builds

See [manfest](https://github.com/jwinarske/manifests/blob/zeus/rpi64-flutter.xml) for a working RPI4-64 image.


### Overview

The Flutter engine build uses the GN meta-build system in conjunction with Chrome Infrastructure Package Deployment (CPID).

depot-tools-native is a depdenency.
curl-native override adding a cert store to the sysroot is also a dependency.  CIPD is used to download large binary payloads, such as the clang toolchain packge.

A build system, within a build system.


## Layers used in development

    meta
    meta-poky
    meta-yocto-bsp
    meta-raspberrypi
    meta-security
    meta-oe
    meta-multimedia
    meta-networking
    meta-python
    meta-perl
    meta-flutter

## Development image

https://github.com/jwinarske/manifests/blob/zeus/rpi64-flutter.xml
