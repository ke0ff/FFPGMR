# FFPGMR
EPROM Programmer, MK-II<br>
EPROM SUPPORT DVT/DEBUG IN PROGRESS, 8/25/2024<br>
This is a rehash/revival of my original (circa 1990) EPROM programmer to allow access to the 27011 and 27513 EPROMS that ACC uses in their repeater controllers.  The current drive is to read the EPROMS, and the 28C64 EEPROM and program the 28C64 and 28F101 FLASH devices.

Project now supports EPROM read and program for several devices.<br>
EPROMS: 27C513, 27C011, 27C64, 27C256 - 27C010<br>
FLASH: 28F256, 28F512, 28F101, 28F010, 28F020, 29F040<br>
EEPROM: 28C64<br>
Smartwatch: DS1216E version (DS1216C planned also)<br>
Autoselect mode supports all but EEPROMs<br>

* HW = Schematics/parts lists (no PCB, none planned at this time)
* SW = TIVA CCS6 source project
* PHOTO = project images
