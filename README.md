# WRF_Chem_Code_Tracers

250414 - Soroush
For HEI project. This repository include the WRF-Chem modified codes to include tracers in MOSAIC module and the outputs. You need to replace original WRF-Chem codes with the modified codes shared in this repository, and then recompile WRF-Chem as usual. Note that the corresponding emissions should be available in the model-ready emission input files.

Here are the list of added tracers:
- dtpm25: Heavy-duty Diesel tailpipe PM2.5
- dtpm10: Heavy-duty Diesel tailpipe PM10
- dbwpm25: Heavy-duty Diesel brake wear PM2.5
- dbwpm10: Heavy-duty Diesel brake wear PM10
- dtwpm25: Heavy-duty Diesel tire wear PM2.5
- dtwpm10: Heavy-duty Diesel tire wear PM10
- bwpm25: All brake wear PM2.5
- bwpm10: All brake wear PM10
- twpm25: All tire wear PM2.5
- twpm10: All tire wear PM10
