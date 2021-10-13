# HappyDayGrowHAT
The HappyDayGrowHat is a Raspberry Pi HAT to make plugging in sensors and relays for growing plants in the LeafSpa less messy/more robust. 
# Monitor
- an I2C interface for either the SCD-30 or SCD-40.  This sensor reads the CO2 level, air temperature, and relative humidity.  So far I've focused on the SCD-30 sensor because there is a SCD-30 node in node-red.  I would have to update it for the SCD-40.
- a GPIO, GND, 5V PWR to support:
  - Turning on/off the pump that fills the DIY humidifier tank.
  - Turning on/off the irrigation pump.
  - Turning on/off the DIY humidifier fan.
  - Turning on/off the CO2 solenoid.
  - A photoresistor.
  - 
 
