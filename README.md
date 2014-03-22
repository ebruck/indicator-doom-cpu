DOOM CPU Indicator
==================

Ubuntu CPU indicator that displays load using Flynn's dying face from the video game DOOM.

DOOM images are the property of id Software.

Inspired by [DOOM CPU Monitor](https://github.com/AshFurrow/DOOM-CPU-Monitor) for the Mac.

Screenshot
----------

![Screenshot](screenshot.png)

Build Debian Package
--------------------

* `mkdir build`
* `cd build`
* `cmake ../debian/`
* `make package`
* `dpkg -i ./indicator-doom-cpu-1.0.0-ubuntu.deb`
