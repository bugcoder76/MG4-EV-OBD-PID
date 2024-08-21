# MG4-EV-OBD-PID
PID file for MG4 EV suitable for use with Torque Pro

We try to put all the PIDs together in a single file for MG4

## How to use:
These codes are primarily for use with Torque Pro which runs on Android phones and tablets.

Download https://github.com/peternixon/MG4-EV-OBD-PID/archive/refs/heads/main.zip and extract the "extendedpids\MG ZS EV.csv" file into the ".torque\extendedpids\" directory on your phone then import it from the "Settings \ Manage extra PIDs/Sensors \ Add predefined set \ MG4 EV" Menu in the Torque Pro app.

The Torque wiki has more details at https://torquebhp.fandom.com/wiki/How_to_add_extended_PIDs

If you wish, you can also use my sample dashboards by extracting the files from the "dashboards" directory into the ".torque\dashboards\" directory on your phone then inside the Torque app, go to realtime data and select the gear icon, then select "Layout Settings", then select "Import" and select "MG4 EV - 1.dash" and repeat for "MG4 EV - 2.dash".

## What hardware do I need?
Any Bluetooth Diagnostic Scanner supported by Torque Pro connected to an android phone or tablet should be fine however testing is being done with an NX101 Pro with PIC18F25K80 Chip

## Required Software:
[Torque Pro](https://play.google.com/store/apps/details?id=org.prowl.torque)

## What is OBD? What is PID?
OBD is On-Board_Diagnostics. By connecting directly to the car we have access to the status of various vehicle subsystems.
PIDs are the Parameter IDs; these are the codes used to request data from a vehicle
Refer to [Wikipedia ](https://en.wikipedia.org/wiki/On-board_diagnostics)


## Informal warning

At this moment this is a personal project, try by your own risk.