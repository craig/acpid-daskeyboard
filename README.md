# acpid-daskeyboard
acpid events files for daskeyboard 4 professional.

Just copy these files to /etc/acpi/events and restart apcid.

You can use "acpi_listen" to verify your keyboard sends the correct events:

> button/volumeup VOLUP 00000080 00000000 K

> button/volumedown VOLDN 00000080 00000000 K

> button/mute MUTE 00000080 00000000 K

> cd/next CDNEXT 00000080 00000000 K

> cd/play CDPLAY 00000080 00000000 K

> cd/prev CDPREV 00000080 00000000 K

> button/sleep SBTN 00000080 00000000 K

This is using amixer to change volume and acpitool for S3 sleep mode.
Tested on debian 8 and debian 9.

