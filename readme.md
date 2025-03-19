The files in this repository are for the game Stationeers and used in IC10 chips to automate tasks. 

1. Battery Control Set
   - ICMainBatteryAvgDisplay - The controller reads its own battery ratio and data from up to four receivers, averages the valid values, transmits the result, and updates an LED display.
   - ICRemoteBatteryAvgDisplay - Reads the average battery ratio from the local network, transmits it to a remote receiver, receives an updated running average, and then displays that value on an LED
