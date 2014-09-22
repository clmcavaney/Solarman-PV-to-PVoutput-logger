SolarMax PVoutput Logger
================

A Python project to take data from the SolarMax series of inverters and live log the data to pvoutput.org

The project provides a simple cross platform solution for logging your solar energy production. pvoutput.org allows your data to be viewed from anywhere in the world via web or app. As opposed to the Official SolarMax software, that only allows local LAN access.

This project heavily leverages the existing work of the following:
* The python interface to pvout.org API was forked from sungrow2pvoutput (https://github.com/kronicd/sungrow2pvoutput)
  Which itself was based on code from PV - https://github.com/blebo/pv/blob/master/pv/pvoutput.py & http://pv.codeplex.com/
  This interface is independant of the inverter brand, so would be useful to anyone.
* Data interface developed by Bernd Wurst - git://git.schokokeks.org/python-solarmax.git
  I've translated this from German to English (using GoogleTranslate).

My plan is to have this running on a Raspberry Pi. Which I'll document more once done.