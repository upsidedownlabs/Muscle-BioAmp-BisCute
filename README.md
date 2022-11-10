# Muscle BioAmp BisCute

![Project Category](https://img.shields.io/badge/Category-Bioelectronics/Neuroscience-gold) 
![Muscle BioAmp Biscute Revision](https://img.shields.io/badge/Version-0.1-success)
[![Muscle BioAmp Biscute store link](https://img.shields.io/badge/Buy-Store_(India)-white)](https://store.upsidedownlabs.tech/product/muscle-bioamp-biscute-diy/)
[![Muscle BioAmp Biscute Tindie link](https://img.shields.io/badge/Buy-Tindie-cyan)](https://www.tindie.com/products/upsidedownlabs/muscle-bioamp-biscute-diy-muscle-sensor/)
[![Muscle BioAmp Biscute intro video ](https://img.shields.io/badge/Intro-YouTube-red)](https://www.youtube.com/watch?v=ujFsAE0E0nk) 
[![Upside Down Labs GitHub Sponsors page ](https://img.shields.io/badge/Support-GitHub_Sponsor-00B5AC)](https://github.com/sponsors/upsidedownlabs) 
[![Upside Down Labs GitHub PayPal page](https://img.shields.io/badge/Support-PayPal-00B5AC)](https://paypal.me/upsidedownlabs)

Muscle BioAmp BisCute is a cute DIY EMG sensor for precise ElectroMyoGraphy (EMG) at an affordable cost. It comes with a fixed gain of x2420 and BandPass filter of 72Hz - 720Hz. To record the EMG signals you can use any standalone ADC or development board with an ADC of your choice.

![Upside Down Labs BioAmp EXG Pill Assembled](graphics/board/MuscleBioAmpBisCute.jpg)



## Hardware

Muscle BioAmp Biscute has been created using KiCad and all the design files can be found under [hardware](hardware/) folder. Images below shows a quick overview of the hardware design.

| PCB Front           |  PCB Back |
| :-------------------------: | :-------------------------: |
| ![Upside Down Labs Muscle BioAmp BisCute front](graphics/board/front.png)  | ![Upside Down Labs Muscle BioAmp BisCute back](graphics/board/back.png) |

![Upside Down Labs Muscle BioAmp BisCute front annotated](graphics/board/annotated.png)

### Assembly

You can get your own Muscle BioAmp BisCute bag of parts from [our store](https://store.upsidedownlabs.tech/product/muscle-bioamp-biscute-diy/) or [Tindie](https://www.tindie.com/products/upsidedownlabs/muscle-bioamp-biscute-diy-muscle-sensor/) and for assembling your Biscute you can take a look at [this interactive BOM](https://upsidedownlabs.github.io/Muscle-BioAmp-BisCute/) or the step by step guide below. 

| Step 1 - Bare board | Step 2 - 100K Resistor | Step 3 - 10K Resistor| Step 4 - 1M Resistor|
| :----: | :----: | :----: | :----: |
| ![](graphics/Assembly/001_board.jpg)|![](graphics/Assembly/002_100K_Resistor.jpg)|![](graphics/Assembly/003_10K_Resistors.jpg)|![](graphics/Assembly/004_1M_Resistors.jpg)|

| Step 5 - 330R Resistor | Step 6 - 220K Resistor | Step 7 - 4.7nF Capacitor | Step 8 - 2.2uF Capacitor |
| :----: | :----: | :----: | :----: |
| ![](graphics/Assembly/005_330R_Resistors.jpg)|![](graphics/Assembly/006_220K_Resistor.jpg)|![](graphics/Assembly/007_4.7nF_Capacitor.jpg)|![](graphics/Assembly/008_2.2uF_Capacitor.jpg)|

| Step 9 - 470uF Capacitor | Step 10 - 100nF Capacitor | Step 11 - 1nF Capacitor | Step 13 - 1K Resistor |
| :----: | :----: | :----: | :----: |
| ![](graphics/Assembly/009_470uF_Capacitor.jpg)|![](graphics/Assembly/010_100nF_Capacitors.jpg)|![](graphics/Assembly/011_1nF_Capacitors.jpg)|![](graphics/Assembly/012_1K_Resistor.jpg)|

| Step 13 - BioAmp Connector | Step 14 - Header Pin | Step 15 - IC | Step 16 - Biscute ready |
| :----: | :----: | :----: | :----: |
| ![](graphics/Assembly/013_Connector.jpg)|![](graphics/Assembly/014_HeaderPin.jpg)|![](graphics/Assembly/015_IC.jpg)|![](graphics/Assembly/016_BisCute.png)|


| Dimensions            |  Schematic  |
| :-------------------------: | :-------------------------: |
| ![Upside Down Labs Muscle BioAmp BisCute dimensions](graphics/dimensions.png)  | ![Upside Down Labs Muscle BioAmp BisCute schematic](graphics/schematic.png) |

## License

| Licenses Facts              |  OSHWA Certification |
| :-------------------------: | :-------------------------: |
| <a href="LICENSE.md"><img src="graphics/misc/Licenses_facts.svg" width="400" alt="Open Source Licenses Facts"/></a>  | <a href="https://certification.oshwa.org/in000026.html"><img src="graphics/misc/OSHW_mark_IN000039.svg" width="300" alt="Open Source Hardware Certification mark"/></a> | 

#### Hardware
CERN Open Hardware License Version 2 - Strongly Reciprocal ([CERN-OHL-S-2.0](https://spdx.org/licenses/CERN-OHL-S-2.0.html)).

#### Software
MIT open source [license](http://opensource.org/licenses/MIT).

#### Documentation:
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
