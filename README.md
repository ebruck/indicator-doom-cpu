DOOM CPU Indicator
==================

Ubuntu CPU indicator that displays load using Flynn's dying face from the video game DOOM.

DOOM images are the property of id Software.

Inspired by [DOOM CPU Monitor](https://github.com/AshFurrow/DOOM-CPU-Monitor) for the Mac.

Latest Debian package [indicator-doom-cpu.zip](https://dl.dropboxusercontent.com/u/5125656/indicator-doom-cpu.zip)

Screenshot
----------

![Screenshot](screenshot.png)

Build Debian Package
--------------------

* `mkdir build`
* `cd build`
* `cmake ../debian/`
* `make package`
* `sudo dpkg -i indicator-doom-cpu-1.0.0-noarch.deb`

Todo
----

Integrate ideas from [GKrellFlynn](http://bax.comlab.uni-rostock.de/en/projects/flynn/)
