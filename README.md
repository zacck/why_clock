#Clock Enable Experiment 

The Reset and Clock Control systems on an MCU basically keep all peripheral 
clocks shutdown to save power. When one needs to use a peripheral we begin by
enabling its clock say AHB, APB or some variant.

Then after enabling it's clock we can now enable and configure a peripheral a 
certain way. Even further we can use the peripheral.
