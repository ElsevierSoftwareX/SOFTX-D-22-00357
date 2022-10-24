# rsdtlib: Remote Sensing with Deep-Temporal Data Library

This project provides a Python module that allows:
1. **Stage 1:** Download remote sensing data directly from [Sentinel Hub](https://www.sentinel-hub.com/) (i.e. Sentinel 1 & 2)
2. **Stage 2:** Temporally stack, assemble and tile these observations
3. **Stage 3:** Create windows of longer time series comprising these observations (i.e. deep-temporal)

Below figure shows the processing pipeline considering all three stages:
<p align="center">
  <img src="./images/rsdtlib_pipeline.png" />
</p>

The processing in stages 2 and 3 is detailed below, showing how observations are combined to produce the final windows:
<p align="center">
  <img src="./images/temporal_stacking_windowing.png" />
</p>

# Contact
Should you have any feedback or questions, please contact the main author: Georg Zitzlsberger (georg.zitzlsberger(a)vsb.cz).

# Acknowledgments
This research was funded by the Ministry of Education, Youth and Sports from the National Programme of Sustainability (NPS II) project “IT4Innovations excellence in science - LQ1602” and by the IT4Innovations Infrastructure, which is supported by the Ministry of Education, Youth and Sports of the Czech Republic through the e-INFRA CZ (ID:90140) via the Open Access Grant Competition (OPEN-25-24).

# License
This project is made available under the GNU General Public License, version 3 (GPLv3).
