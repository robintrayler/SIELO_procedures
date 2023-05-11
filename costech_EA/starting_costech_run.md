# Starting a Costech 4010 Sequence

[🏠](../README.md)

***

Please contact the Stable Isotope Ecology Laboratory Technical Director with any questions or clarifications. **StableIsotopes@ucmerced.edu**

***

## Prerequisites

Please check all prerequisites and complete any linked guides before continuing.

- [ ] [Loading the Costech 4010 Zeroblank Autosampler](../costech_EA/EA_zeroblank.md) 
- [ ] [Warming up the Costech 4010](../costech_EA/warming_up_costech.md)
- [ ] [Starting Costech 4010 CO<sub>2</sub> and N<sub>2</sub> On-Offs ](../isodat/EA_on_offs.md)
- [ ] [Setting up a Costech 4010 Isodat Sequence](../isodat/isodat_sequence.md)

*** 

## Introduction

This guide covers the final steps for setting up batch of analyses using the Costech 4010 Elemental Combustion System. After completing the prerequisites listed above you will need to finish filling out the *Instrument Run Log* before starting your sequence. 

## Steps

### Record On-Off Reproducibility 


    * The on-off results are saved in the `/On-Off Results/` Folder

![](../figures/isodat/on_offs_folder.png)
*On-Offs results folder*

* Open the most recent CO<sub>2</sub> and N<sub>2</sub> on-off result files.  
* Click on the column header labeled `d 13C/12C [per mil] vs. VPDB` and `d 15N/14N [per mil] vs. AIR`  to highlight all the rows. 
* Right click and select `Calculate`. 
* Check the standard deviation (`Std. Dev.`). The instrument is ready run if the standard deviation is ≤0.5‰ for both δ13C and δ15N. 
* Record the standard deviation of the most recent CO<sub>2</sub> and N<sub>2</sub> on-off result file in the instrument run log in the `δ13C` and `δ15N` columns.  

![](../figures/isodat/c_on_off.JPG)
*Example of a CO<sub>2</sub> on-off result file.*

### Record Instrument Parameters

![](../figures/isodat/box_trap.png)
*Location of `Box`, `Trap`, and `Vac` readouts in Isodat Acquisition*

* Record the values shown in the `Box`, `Trap`, and `Vac`, readouts from Iosdat Acquisition in the *Instrument Run Log*. 
    * The `Box` and `Trap` values should be stable and should sum to 1.5. If they are fluctuating rapidly, stop and contact the Technical Director. 

![](../figures/isodat/box_trap.png)
*Location of `Box`, `Trap`, and `Vac` readouts in Isodat Acquisition*

### Record Backgrounds

Record the background levels for carbon dioxide (`mass_44_mV`), argon (`mass_40_mV`), nitrogen (`mass_30_mV` & `mass_28_mV`), and water (`mass_18_mV`) in the *Instrument Run Log*




* Record 

### Start Sequence