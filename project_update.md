## What has been happening in the project ?

* **8-Jan-2019**  
    Realised ergodox was the best keyboard I have. Need to make one more for home.  

* **9-Jan-2019**  
    Got to know about bluemicro, a ble capable for promicro. Decided that I will make the new ergodox bluetooth.  

* **10-Jan-2019**  
    After chatting with jpconstantineau, realise that existing ergodone or ergodox are not going to work with BlueMicro due to placement issues. Decided to mod only the ergodone case to fit bluemicro on one side.  

* **14-Jan 2019**  
    Further dicusions with jpconstantineau made me realised that i2c at the moment is not supported by bluemicro, and will take time. At the same time got to know about Proton-C. Decided to modify the existing Ergodox PCB.  

* **16-Jan-2019**  
    Modifing existing pcb was tough due to my limited knowledge about kicad.  

* **19-Jan 2019**  
    Role up the sleeve and decided to remake a new pcb.  

* **20-Jan-2019**  
    Added clearance for Proton-C, make sure the edge cuts are within existing Ergodone case.  

* **21-Jan-2019**  
    Realised it was simple enough to change the footprints on the schema and make it work with the kicad libs and footprints that I had.  

* **22-Jan-2019**  
    USB-C is the future, added it to the PCB. Always look to the future.  

* **23-Jan-2019**  
    Generate Gerbers, and schema pdf  to get feedback from a few of people.  

* **24-Jan-2019**  
    Feedback was positive. Gave order to JLCPCB. Fingers crossed.
    
* **30-Jan-2019**   
    Used lister's case to create acrylic case with clearance for USB-C and connection pads.
    
----------------------------------------------------------------------------------------------------------------------------------------

* **24-Mar-2019**
    I have been lazy updating the post, so here are all the updates
    * PCBs have been recieved, wiring looks ok, USB C pads are too small to handsolder, will have to replace it with something more easy to hand solder. ToDo.
    * Bluemicro has been assembled, easy to do if you can ready the marking on PCB and Component reels.
    * I have built the firmware for bluemicro, and did some test unassembeled. Bluetooth working as expected, no latency issues for me so far.
    * PCB has a few diodes in place, just to test things out before I solder in every thing.
    * Female headers are in place to support removal for MCU if and when required. Soldering diodes leg/wire on MCU itself is bit tricky. Trying to make it work at the moment.
* **25-Mar-2019**
    * Finally decided to hard solder the MCU. Firmware mostly works fine, need to flip the right hand mapping to make it work correctly
* **29-Mar-2019**
    * The develop branch of BlueMicro firmware is now being used. There is no connectivity or latency issue being observerd. Currently testing out the keyboard without any layers. This is to test out the hardware and firmware without have any complex code or marcro.
	
----------------------------------------------------------------------------------------------------------------------------------------

* **01-May-2019**
	ErgodoxC v1.3 released. This is most probably the last version of the PCB. Dual side USB C, USB ESD protection have been added. Case design updated for this pcb.
* **02-May-2019**
	Case files updated with plate for Alps Switches.
