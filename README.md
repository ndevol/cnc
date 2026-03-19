# GRBL
[Docs](https://github.com/gnea/grbl/wiki/) \
Useful [example](https://github.com/maxvfischer/DIY-CNC-machine)

## Settings Changed:
Setting descriptions are [here](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md). \
Homing off: $22 \
For 1/16 micro-stepping: $100, $101 and $102 – [X,Y,Z] steps/mm - set X,Y to 83, Z to 400 \
Maximum rate [mm/min]: $110, $111, $112 - [X, Y, Z] - Original: 500, Current 2000
Acceleration [mm/sec^2]: $120, $121, $122 - [X, Y, Z] - Original: 10, Current: 100


## Micro-Stepping
I believe all pins together is 1/16 like in this [link](https://www.handsontec.com/dataspecs/cnc-3axis-shield.pdf). Just doing M2 made no apparent change.