# ARuniMKII
PCB  to run ERSKY firmware on old RC transmitters or DIY boxes.

-- Originated from AR9X and ARUni schematic as designed by "flygear" -- on RCgroups

See thread AR9X and ARUni on RC-Groups

Firmware discussions at openrcforums.com under erskyTx (was ersky9x)

Firmware can be found at er9x.com  maintained by Mike Blandford. Use ERSKYTX version  "9XR-PRO" 
Also Pre-Release FW at OpenRCforums : ErskyTX Test Versions by Mike Blandford.

The board is built with an AT-SAM-4 chip with twice the RAM of the original ARUni/AR9x board. See BOM file .
 
The correct chip ID has to be chosen when initially flashing the FW and bootloader to a blank chip with the SAMba tool from Atmel.


firmware src for jr9303 based implementation is at github.com/garyStofer/mbtx 