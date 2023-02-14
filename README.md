# NVidia-memory-clock-bug-fix
fixes the memory clock when it gets stuck at 810MHz under load
tested on GTX 1650 mobile

This seems to be a software issue, while i havent norrowed it down to driver or operating system
this occurs on windows 10 and windows 11 on 522.25 through the current version while this isnt a fix 
it is just a work around, add this script to startup along with your OWN device instance path which
can be found in the device manager. Ensure that this loads AFTER your driver does
