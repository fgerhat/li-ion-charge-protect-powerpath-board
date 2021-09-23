# Li-Ion Charge/Protect/PowerPath board
This development board is designed to meet the following requirements:
* Use a USB power supply input to safely charge a single Li-Ion cell and simultaneously power an external circuit
* Power the external circuit from battery when USB power fails
* Be compliant with the USB 500mA spec on the input side
* Protect the battery from over-charge, over-discharge and short-circuit

This board is designed around the [Texas Instruments BQ24074](https://www.ti.com/product/BQ24074) which functions as a battery CCCV charging controller, PowerPath controller and is USB500 compliant. Battery protection is handled by the  [FS312F-G](https://ic-fortune.com/upload/Download/FS312F-G-DS-12_EN.pdf) integrated circuit.

## Electrical characteristics
Characteristic | Value | Note
-------------- | ------| ----
Input voltage | 4.35V - 10.2V | 
Input current | <500mA | 
Output voltage | 2.8V - 4.4V | 
Output current | <4.5A | with battery
Battery charging current | <500mA | 
Battery charging voltage | 4.2V | 
Battery over-discharge treshold | 2.9V | 
Battery over-charge treshold | 4.25V | 
