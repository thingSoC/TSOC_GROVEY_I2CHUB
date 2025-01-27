# TSOC_GROVEY_I2CHUB
**TSOC_GROVEY_I2CHUB** is a four(4) port I2C Hub/Switch board, an Embedded Module for thingSoC.

The **TSOC_GROVEY_I2CHUB** can operate at either 3.3V or 5V, and can also level translate 3.3V processor I2C bus to 5V peripherals when needed.

The **TSOC_GROVEY_I2CHUB** allows you to connect [thingSoC](http://thingsoc.github.io/), [Mikrobus](http://www.mikroe.com/mikrobus/), 
and/or [Grove System](http://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/) 
Modules all at the same time, with any processor module.
This gives you maximum flexiblity for sensor and actuator selection, and reuse. 

The thingSoC "Grovey Series" was designed as "Everyday Electronics", a no-frills, low cost, approach to modular embedded product design.
thingSoC boards are similar in size to most break-out-boards (BOBs), but feature a standardized stacking pinout, as well as an I2C metadata store (EEPROM)
to indicate what peripherals are installed.

[![thingSoC GROVEY_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/blob/master/TSOC_GROVEY_I2CHUB/images/product/TSOC_GROVEY_I2CHUB_top.png?raw=true)TSOC_GROVEY_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/)

---------------------------------------

In this example, we use the [Grovey_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB) with the [Teensy3.x](https://www.pjrc.com/teensy/index.html) to support a Grove 16x2 LCD panel.
Since the Grove 16x2 LCD panel is a 5V peripheral, the [Grovey_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB) performs the voltage level translation
necessary to go from the 3.3V micro-processor to the 5V LCD controller. 

[![thingSoC GROVEY_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/blob/master/TSOC_GROVEY_I2CHUB/images/product/Grove_5V_I2C_LCD_panel.png?raw=true)TSOC_GROVEY_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/)


* [thingSoC Compliant Module](http://www.thingsoc.com)
* [Mikrobus Compatible Module](http://www.mikroe.com/mikrobus/) 
* 5V Nominal Power Input
* 5V or 3.3V Operation
* Supports four (4) separate I2C busses 


---------------------------------------
## Example Uses

* Any time you want to connect four (4) of the same sensor, using the same I2C address, then you need an I2C Hub/Switch.
* Adds four (4) I2C ports to any [thingSoC](http://thingsoc.github.io/), [Mikrobus](http://www.mikroe.com/mikrobus/), 
and/or [Grove System](http://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/) peripherals.

---------------------------------------
## 3D Model (Sketchup)

![thingSoC TSOC_GROVEY_I2CHUB](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_I2CHUB/master/TSOC_GROVEY_I2CHUB/images/TSOC_GROVEY_I2CHUB_iso.png)


---------------------------------------
## Project Status

* 09/02/2016 : Revision 2.0 Release for PCB fab

## Revision 2.0 Notes: ##

* Add Ground Strap, remove FM24V10 FRAM, add GROVE I2C Slave connector slot.

## Revision 2.1 Notes: ##

* Remove Ground Strap, it was confusing for power configuration and assembly.
* Prototype testing complete, Production Ready

---------------------------------------

## Documentation Index <a name="documentation_index"/>

[Quick Start Guide](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/blob/master/TSOC_GROVEY_I2CHUB/docs/QuickStart.md)

[User Guide](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/blob/master/TSOC_GROVEY_I2CHUB/docs/UserGuide.md)

[Theory of Operation](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB/blob/master/TSOC_GROVEY_I2CHUB/docs/TheoryOfOperation.md)

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)

---------------------------------------

[![Image](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true)  
*thingSoC*](http://thingsoc.github.io) 
 
