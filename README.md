## Scope ##

This is a very simple Vera plugin for the Aviosys IP Power switches

## Features ##

It only supports the 4 channel version, though with a small change to the code it can support the 8 switch device. It supports the following functions:

* Creation of child devices in Vera for each switch channel
* Set each channel on or off from Vera (discrete power)
* Poll the device regularly to determine the actual status

## Usage ##

Create the parent instance and give it the IP address of your AvioSys device. The child devices will be created automatically.

## Limitations ##

It isn't possible to auto detect the number of switch ports (4 or 8) because the 4 port version returns status for the full 8 ports (including the 4 that do not exist). 

## License ##

Copyright © 2013 Chris Birkinshaw

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/