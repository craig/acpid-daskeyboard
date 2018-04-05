# acpid-daskeyboard
acpid events files for daskeyboard 4 professional.
Tested on Debian 8 and Debian 9.

Requires:
- amixer for volume control an
- acpitool for S3 sleep mode

Just copy these files to /etc/acpi/events and restart apcid.

You can use "acpi_listen" to verify your keyboard sends the correct events when you use the scrollwheel or buttons:

> button/volumeup VOLUP 00000080 00000000 K

> button/volumedown VOLDN 00000080 00000000 K

> button/mute MUTE 00000080 00000000 K

> cd/next CDNEXT 00000080 00000000 K

> cd/play CDPLAY 00000080 00000000 K

> cd/prev CDPREV 00000080 00000000 K

> button/sleep SBTN 00000080 00000000 K



