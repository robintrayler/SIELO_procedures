# Setting up an Isodat Sequence

***

Please contact the Stable Isotope Ecology Laboratory Technical Director with any questions or clarifications. **StableIsotopes@ucmerced.edu**

***

## Supplies

- [ ] Typed weight sheet using the one of *SIELO weigh sheet templates* 

*** 

## Introduction

An *Isodat sequence* file is required for all analyses on the Costech 4010, ThermoFisher TC/EA, ThermoFisher Gasbench II, and ThermoFisher GC-Isolink instruments. This guide covers the basics of setting up routine analytical sequences for these instruments. If you need to set up a specialized sequence (e.g., for method development or instrument testing) please consult the Technical Director. 

## Instrument Run Logs

- [ ] Finished

Each instrument has an *Instrument Run Log* excel file located in `~/Box Sync/Instrument Run Logs/`. There are two log files, one for each Delta V+ mass spectrometer. **All analyses** must be entered into the appropriate *Instrument Run Log*.

Setting up an Isodat sequence begins by starting a new row in the appropriate *Instrument Run Log*. Each new row starts with a the `date` of analysis and creating a new `run_ID`.

* In the `date` cell enter the date in `day/month/year` format.
* The `run_ID` is the name of the instrument (`EA`, `GB`, `TCEA`, `GCC`) followed by the date in `year-month-day` order. For example a set of samples analyzed on September 10, 2021 using the Costech 4010 would be named `EA202109010`. 

- [ ] Finished

Each analysis within a run is also given a unique identifier number referred to as `Identifier 1`. 
* in the `start_ID1` field enter the first `Identifier 1` number for your run. This number is the `end_ID1` from the previous row +1.

 ![](../figures/isodat/run_log.png)
 *The first columns of the Costech 4010 Instrument Run Log, showing the creation of a new set of Identifier 1 numbers.s* 
  
