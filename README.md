# Reference Design for Active and Passive Filters

During my PhD I hae to deal with a lot of noise from othr equipments in the clean room or 
from the biulding power lines. As the signal was either getting amplified with an active 
op amp or a lock-in amplifer the lowest possible noise level is favorable. I am not an 
elecgronic engineer at all but I tried to get by with the help of friends and THE internet. 
I just want to share them here in case someone finds them useful. They are all mostly 
centered around 4 or 10 MHz due to my use case. 

These simple circuit were designed using [NI Multisim](https://www.ni.com/en-us/support/downloads/software-products/download.multisim.html#312060) 
and [OrCAD Capture](https://www.orcad.com/products/orcad-capture/overview). The Designs were 
parameters were calculated with the help of the following resources:
* https://tools.analog.com/en/filterwizard/
* http://www.iowahills.com/
* http://sim.okawa-denshi.jp/en/OPtazyuBakeisan.htm
* https://rf-tools.com/lc-filter/
* https://www.wa4dsy.net/robot/bandpass-filter-calc/
