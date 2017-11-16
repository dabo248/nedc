<img src="https://raw.githubusercontent.com/david145/nedc/master/assets/nedc_logo.png" width="220" align="right">

# Serialized New European Drive Cycle
[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/david145/nedc/blob/master/LICENSE)

### NEDC processed into computer-understandable formats

New European Drive Cycle is used to calculate consumption of electric vehicles and vehicles based on combustion engines. 

It is composed of two parts: ECE-15 (Urban Driving Cycle), repeated 4 times, is plotted from 0 s to 780 s; EUDC cycle is plotted from 780 s to 1180 s.

[![NEDC plot](https://github.com/david145/nedc/blob/master/assets/nedc_plot.png)](http://www.unece.org/fileadmin/DAM/trans/main/wp29/wp29regs/2015/R101r3e.pdf)

For more information take a look on the official documents which were introduced first in 1970 as part of ECE vehicle regulations; the recent version is defined by ECE [R83](http://www.unece.org/trans/main/wp29/wp29regs81-100.html), [R84](http://www.unece.org/trans/main/wp29/wp29regs81-100.html) and [R101](http://www.unece.org/trans/main/wp29/wp29regs101-120.html).

### Units
|attribute|type|
|-|-|
|start_velocity|km/h|
|end_velocity|km/h|
|acceleration|m/s^2|
|duration|s|
