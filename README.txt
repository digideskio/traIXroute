# Copyright (C) 2016 Institute of Computer Science of the Foundation for Research and Technology - Hellas (FORTH)
# Authors: Michalis Bamiedakis, Dimitris Mavrommatis and George Nomikos
#
# Contact Email: gnomikos [at] ics.forth.gr
#
# This file is part of traIXroute.
#
# traIXroute is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, version 3.
#
# traIXroute is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with traIXroute.  If not, see <http://www.gnu.org/licenses/>.

To install traIXroute with all the necessary packages follow the instructions as they seem below:

1) Run the following script to install all the necessary packages for the traIXroute. The installation script in the setup directory automate the whole installation process to properly run the tool:

$ sudo bash ./Setup/install.sh

# ---------------
# For Mac OS X:
# ---------------
# Ensure you have installed the Xcode command line developer tools before. To install run:

$ xcode-select --install

2) After finishing the installation process, move on the documentation to run the tool with all the proper arguments.

3) Check your firewall in case you filter certain types of packets to avoid getting unresponsive traces. Otherwise, traIXroute will not run properly.

The tool has been tested in Ubuntu 12.04, 14.04 and 16.04 and Mac OS X.

4) The 'config' file contains all the necessary URLs for traIXroute to download all the datasets. There you can also add your RIPE Atlas measurment key. By default, the "num_of_cores" tag is configured to value "-1". This means that traIXroute utilizes all the available cores of the local machine. Otherwise you can select the exact number of cores to make available for the tool.

