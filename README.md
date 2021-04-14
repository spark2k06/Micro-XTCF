# Micro XTCF (Very Low Profile) Rev1.1 ReadMe

8-bit ISA CompactFlash interface + Boot ROM (two separate functions that can be used individually).


# Rev 1.1

Added two decouple capacitors (100nF and 22uF) on the vcc line of the cf, some cf's requires a pump when they start, thanks @arananet for the suggestion.

Added gerbers to the github project.

# Credit

Design uses schematic from Monotech-PC, which, in turn, is based on the schematic from Sergey Kiselev:

https://github.com/monotech/monotech_xt-cf-mini
http://www.malinov.com/Home/sergeys-projects/xt-cf-lite

XT-IDE Universal BIOS\
www.xtideuniversalbios.org  
www.xtideuniversalbios.org/binaries  

Use the latest working binary that includes XTIDECFG.COM (config utility), ide_xt.bin (8086/8088), ide_xtp.bin (80186/V20/V30 and up).

More info:

https://www.tindie.com/products/spark2k06/micro-xtcf-isa-8-bits-very-low-profile/