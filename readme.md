The files in this repository are for the game Stationeers and used in IC10 chips to automate tasks. 

1. ArcFurnaceController - Activates and Arc Furnace when there is ore in the import slot and turns on a active vent to suck the gases away.
2. Battery Control
   - MasterBatteryControl - The controller reads its own battery ratio and data from up to four receivers, averages the valid values, transmits the result, and updates an LED display.
   - RemoteBatterControl - Reads the average battery ratio from the local network, transmits it to a remote receiver, receives an updated running average, and then displays that value on an LED
