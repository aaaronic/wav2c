wave2c, a WAV file to GBA C source converter
============================================

Translates audio binaries into AVR memory data.

Credits
-------
 
Author:    Aaron Hansen

Created:   2020-04-06

License:   GPLv3

Forked from work by Ino Schlaucher <ino@blushingboy.org>,
based on an original piece of code by Mathieu Brethes.

Copyright: 2008 Ino Schlaucher [blushingboy.org](http://blushingboy.org)
Copyright (c) 2003 by Mathieu Brethes <thieumsweb@free.fr> [thieumsweb.free.fr](http://thieumsweb.free.fr/) 

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

How-To
------

1. Use Audacity to create the file with the right settings: 8bit, mono. Export it as Microstoft WAV -> Unsigned 8-bit PCM.
2. Compile wav2c with usual `make`
3. Export it to text with: `./wav2c fifiu.wav fifiu.c soundVariableName`
4. This version will also create a .h file matching the .c file argument name with `extern` variables for sampling rate, length, and the sound data.

Links
-----

[Audacity](http://audacity.sourceforge.net/): Free Audio Editor and Recorder
