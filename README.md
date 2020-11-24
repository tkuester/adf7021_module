# ADF7021 Module

Per a discussion with SP5WWP, it would be advantageous to the M17 project to
have a breakout board that can be uesd to prototype with the AD7021 module.
While Analog provides a reasonably priced development module, it is difficult
to modify, and doesn't integrate well into other projects.

Given this, the module should be...

 - Hackable
   - Easy to use as a standalone board (ie: 0.1" headers)
   - Assemble with hobbyist level equipment
   - Financially accessable, limit difficult to source parts
 - Modular
   - Minimize commitments like filter topology / amplifier output
     - Can use as TX, RX, or TX/RX (two SMA conns)
   - Optional footprints to allow for various configurations
 - Designed to integrate into later projects
   - RF shileding footprint
   - Mounting holes, pluggable connectors, etc
 - Not designed for the TR-9
   - Suspect TR-9 needs tighter integration
   - Would be nice, but requirements seem to conflict
