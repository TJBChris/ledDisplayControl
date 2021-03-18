ledDisplayControl
By: Christopher Hyzer

Originally written: 10/2016
File updated: 03/2021

-------------
 DESCRIPTION
-------------

This project is an Arduino sketch which can be used to drive an LED display module taken from a Scientific Atlanta 8580-series cable box.  These boxes were ubiquitous throughout the late 1980s and 1990s.  There were a few variataions (some with a BUY button, for example).  The display contained extra segments for VCR-Timer-Recording-style scheduling to change channels at given times of the day or on specific days of the week.  These custom segments are enabled by this project.

This code was used in a project I made using an 8580 as the basis for an emulated game console here: https://www.bentperception.com/blog/?p=362

This project does not contain harware information, though the display is simple enough to be able to figure out the pinout by looking at it.  There is some help on the blog link above; I had hand-drawn my outline of the display and posted a picture there.

------------
 COMPONENTS
------------

To build this project, you'll need basic circuit design and build skills and the following:

* An Arduino with available GPIO pins (such as an Uno).
* A display module from a Scientific Atlanta 8580-series cable box.
* A breadboard, protoboard, or other method of constructing your circuit.
* Matching resistors (depends on your power source), wiring, solder, etc.
* A power source for the display.  More than 5V is not recommended; match your resistors accordingly.

---------
 SUPPORT
---------

There is absolutely no support for this project.  Questions about this project will likely not be answered.

-------------
 LIMITATIONS
-------------

Not all letters of the alphabet are implemented given the limitations of segment displays.

---------
 LICENSE
---------
See LICENSE.TXT for details about the license for this software.

ledDisplayControl - Arduino sketch to drive a Scientific Atlanta 8580-series display, including custom segments.
Copyright (C) 2016 Christopher Hyzer

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
