# AladdinSDStray
AladdinSDStray monitors the Windows service AladdinSDS from the system tray and lets you start, stop, restart and configure it.

Tray icon colors:
  Gray - service not installed
  Green - service running
  Orange - service stopped (startup type Automatic or Manual)
  Red - service stopped and disabled

Automatic suspend: while Aladdin.exe is active the service is stopped; when Aladdin.exe closes the service is started again.

Scanners: when the service is running, the menu shows how many scanners are connected. Click it for the model, serial number and firmware of each scanner (read from the SDS API).

Double-click the tray icon to make all connected scanners beep.

The menu also gives quick access to the AladdinSDS log file, config file and Packages folder.
