# FFPGMR
EPROM/FLASH/EEPROM Programmer, MK-II<br>
Final DVT/DEBUG IN PROGRESS, 4/19/2026<br>
This is a rehash/revival of my original (circa 1990) EPROM programmer to allow access to the 27011 and 27513 EPROMS that ACC uses in their repeater controllers.  The original goal was to read the EPROMS, and read/pgm 28C64 EEPROM and 28F101 FLASH devices.

The FFPGMR now supports EPROM read and program for several devices.<br>
EPROMS: 27C513, 27C011, 27C64, 27C256 - 27C040<br>
FLASH: 28F256, 28F512, 28F101, 28F010, 28F020, 29F040<br>
EEPROM: 28C64<br>
NVRAM: 11C68, 11C88<br>
Smartwatch: DS1216E version<br>
Autoselect mode supports all but EEPROMs/NVRAMs<br>
EPROM algorithms fixed from when they got broken (who knew???)<br>
Verify command fixed/re-worked -- addresses SRAM synch problems, now allows voltage margins on EPROM verify<br>
Adding code to support limited GAL/PAL programming/de-programming activities. Autoselect mode used to identify GAL prog-adapter<br>

Most features are complete.  Other than GAL/PAL and EPROM algorithm completion, no activities are planned.

* HW = Schematics/parts lists (PCB, -002, has now been added)
* SW = TIVA CCS6 source project
* Photo = project images
* ErsatzTiva = Tiva LaunchPad clone design/FAB files
