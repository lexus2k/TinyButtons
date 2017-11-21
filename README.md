# Analog buttons control library

## Introduction

This library provides interface to work with the buttons, connected to
analog pin.

## Key Features

 * Polling implementation of working with analog buttons
 * 2 ways of polling are available
   * callbacks (automatically invoked on event)
   * verifying buttons state via API functions

## Supported platforms

The library should work on all Arduino platforms.

Digispark users, please check compilation options in your Arduino prior to using this library.
TinyButtons library requires at least c++11 (by default Digispark package misses the options
-std=gnu++11).

## Setting up

 * Download source from https://github.com/lexus2k/TinyButtons
 * Put the sources to Arduino/libraries/ folder

For more information about this library, please, visit https://github.com/lexus2k/TinyButtons.
Doxygen documentation can be found at [github.io site](http://lexus2k.github.io/TinyButtons).
If you found any problem or have any idea, please, report to Issues section.

## License

Copyright (C) 2016-2017 Alexey Dynda

This file is part of TinyButtons Library.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

