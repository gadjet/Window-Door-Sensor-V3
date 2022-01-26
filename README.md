# Window-Door-Sensor-V3
Smaller version of version 2.
This version has the components on one side and the ESP12 Module on the other side the PCB tracks supplying the
ESP module have also been beefed up to redice the size  of the supply capacitor and I have this  running currently
without a 1000uF capacitorand it works fine but when I tested version 2 with an oscilloscope on the supply pins of
the ESP a 220uF was enough to hold the  supply during transmission above 3V.

This version also has a DS18B20 footprinton the PCB but unfortunately I made a schoolboy error and connected the DQ
to GPIO9 ewhich I later found ouot is a no-no as it's connected to the  internal flash memory and accessing it causes
the ESP to crash.  If you wish to use a DS18B20 then I would cut the track to GPIO9 and run a wire from the left side
of R8 to GPIO2 on the ESP module.

If anyone is interested in buying the PCB then let  me know as I'm considering creating a Tindie store to sell
my surplus PCBs on to fund the next PCBs :-)
