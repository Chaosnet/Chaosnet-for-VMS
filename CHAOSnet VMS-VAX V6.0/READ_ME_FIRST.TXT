This is the restored distribution of the CHAOSnet VMS/VAX V6.0 software from Symbolics, Inc., courtesy of Bob Kerns.

It is primarily intended for use with the SIMH UNIBUS VAX simulators, but can also be used for "real" VAX computers.

The CHAOSnet V6.0 software was compiled and linked under VMS V4.4 using VAX C V2.4 and BLISS-32 V4.3.

It should run under any VMS V4 version, but it will probably need to be relinked and possibly even recompiled under other VMS versions.

Known restrictions:
- The only tested & working network interface for the CHAOSnet software as of yet is the DEC "DEUNA" UNIBUS Ethernet adapter.

Further plans:
- Attempts are being made to put the other two network adapter models "CH11" and "INTERLAN" originally supported by CHAOSnet into operation.
The prospects for the "CH11" network adapter are good, as it is already available under SIMH; the future of the "INTERLAN" adapter is still up in the air.

- It is planned to try to restore older versions of the CHAOSnet software.

- There are even plans to program new support for other DEC Ethernet adapters such as the "LANCE", to enable newer (and smaller) VAX computer to "talk" to the CHAOSnet.

There are three types of distributions, each in its own directory:

1) CHAOS-TAPE: A VMS BACKUP SIMH tape image containing the CHAOSnet software 
2) CHAOS-DISK: An RK07 SIMH disk image containing the CHAOSnet software
3) CHAOS-SETUP: A full development and test setup including two sets (VAX1 and VAX2) each consisting of:
   a) An RA81 SIMH disk image with VMS V4.4, VAX C V2.4 and BLISS-32 V4.3 
   b) An RK07 SIMH disk image containing the CHAOSnet software
   c) A SIMH vax750 simulator (Linux)
   d) A SIMH vax750 configuration file

Special thanks to:

- Lars Brinkhoff for providing the CHAOSnet software files
- Lee Gleason for troubleshooting and his patient and persistent help

If you have any questions, suggestions or whatever, contact the author at: vaxorcist@gmail.com with the term "CHAOSnet" in the mail subject.

Have fun!
