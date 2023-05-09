<!--  cd ~/Library/Mobile\ Documents/27N4MQEA55~pro~writer/Documents/Stable\ Isotope\ Lab\ How\ To  --> 

<!-- pandoc -s Setting_up_EA_run.md -o EA_run.pdf-->

# Setting up a Costech 4010 Elemental Combustion System Run v 0.1

***

Please contact the Stable Isotope Ecology Laboratory Technical Director with any questions or clarifications. **StableIsotopes@ucmerced.edu**

***

## Supplies
- [ ] Gloves
- [ ] Eye protection
- [ ] Forceps
- [ ] Tray of fully prepared samples
- [ ] Typed weight sheet using the one of *SIELO weigh sheet templates* 

*** 

## Introduction

The *Costech 4010 Elemental Combustion System* (EA) is used to analyze the carbon and nitrogen elemental content (weight percent) and isotope composition of various organic materials (e.g., soil, plants, animal tissues). This document will help you set up routine analyses on the Elemental Analyzer. 

## Part 1: Warming up the Elemental Analyzer

* Check if the EA is in `work` or `st_by` (standby) mode.
* If the EA is in `st_by` mode place it in work mode by pressing **work** and **enter** on the keypad.
    * *If the EA buttons are unresponsive*, press **abort** and **enter** on the keypad.
* Once the EA is in **work** mode make sure to place it in **remote** mode by pressing **remote** and **enter**. The Screen should read `REM` in the bottom right corner.

## Part 2: Load Samples

* Before loading samples **you must** isolate the mass spectrometer from the EA.  **Failure to do so can cause significant damage!** Do this by closing the all open conflo valves. Once these are closed you can load samples into the EA autosampler.

![Isolate the mass spectrometer by closing all open conflo valves. Click any green buttons in the *Conflo IV Diagnosis* panel in *Isodat Acquisition*. One button will always remain green and it will always be one of buttons under *Sample Dilution*. This is fine.](../figures/costech_EA/Conflo_valves.jpg)

### Steps 

![ZeroBlank Autosampler](../figures/costech_EA/autosampler.pdf)

1. Close the isolation valve on the autosampler drop-tube by turning it so the arrow is horizontal. At this point you should not be able to see the hot glowing column through the window on the top of the autosampler.
2. Open vent valve in the middle of the autosampler. There should be an audible hiss as gas escapes.
3. Loosen and fold down the three retaining bolts on top of the autosampler and prop up the autosampler lid.
4. Use a pair of forceps to load samples from the 96 well tray. Start at the hole directly to the right of the autosampler drop-tube and work counter clockwise. Do not place a capsule in the hole directly over the drop-tube! 

![ZeroBlank Autosampler carousel loading direction. Do not place a capsule in the hole directly over the drop tube.](./figures/costech/carousel.pdf)

5. When you are done loading make sure there are no sample capsules left in the 96 well tray and make you have loaded only 1 capsule into each autosampler hole. 
6. Close the autosampler lid and tighten the three retaining bolts a quarter turn at a time until they are tight.
7. Leave the center vent valve open and *slowly* open the isolation valve by turning it so the arrow points directly up. You should hear are whine (this is normal) from the EA and there will be gas flow out of the purge valve. 
8. Set a timer for 5 minutes.
9. Close the vent valve after 5 minutes.

## Part 3: Run On-Offs

Once the EA is warming up (it doesn't need to be fully ready) you can start warming up the mass spectrometer.  

* From *Isodat Acquisition* scroll to the *File Browser* and open the  `EA_std_onoff.seq` sequence. 
    * Click the green **start** button at the top of the sequence. 
    * Click OK on the window that pops up. 

## Part 4: Set Up Isodat Sequence





