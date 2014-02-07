# Rotary Encoder Breakout PCBs  

Eagle CAD PCB designs for rotary encoder breakout boards. 
Converts the following rotary encoders to 0.1" breadboard format.  
  * TT Electronics: EN12-VS  
  * Bourns: PEC16-2xxxF-Sxxxx  

See one of the following links for drivers that interpret the gray-code on an Arduino.  
  * https://github.com/uChip/Rotary  
  * https://github.com/BrianLow/Rotary  
  * http://www.buxtronix.net/2011/10/rotary-encoders-done-properly.html  

The PCBs come in different layouts.  The "edge" layout brings all connections to a single row of 0.1" spaced pins.  The "straddle" layout brings signals to two rows of 0.1" spaced pins.  The rows are 0.4" apart such that they will straddle the center channel of common solderless breadboards.

## Component Description  

The encoders listed are "gray-code" encoders.  They also have a push-button switch (normally open).
 
Digi-Key part numbers  
  * EN12-VS: several part #s, search "EN12", example #987-1198-ND  
  * PEC16: several part #s, search "PEC16" example #PEC16-2215F-S0024-ND   

Pinout on PCB or see datasheets.  

## Order PCBs  

You will be able to order any of these PCBs from OSH Park.  Click on one of the following links.
  * EN12-VS edge - http://www.oshpark.com/shared_projects/ICXpkCPn  
  * PEC16 edge - http://www.oshpark.com/shared_projects/QfFKi2uG

## Status
  * EN12-VS edge - PCB layout tested to be correct, holes have been enlarged in latest rev to ease assembly  
  * PEC16 edge - PCB layout tested to be correct.  
  * PEC16 straddle - not yet tested, board not yet ordered   

## File Formats  

Design files are in "CadSoft EAGLE PCB Design Software" .brd and .sch formats.  
A free version of the software can be downloaded from www.cadsoftusa.com.  

## Distribution License  

All PCB designs in this repo are Public Domain.  No liability accepted.  