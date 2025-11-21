The files in this repository are for the game Stationeers and used in IC10 chips to automate tasks. 

1. AirConController - Controls the On/Off and Temperature of an Air Conditioner from its IC slot, no external setup needed. Will heat and cool. 
2. AirFiltrationPressureControl - Controls Air Filtration so it doesn't overload a pipe network.
3. ArcFurnaceController - Activates and Arc Furnace when there is ore in the import slot and turns on a active vent to suck the gases away.
4. GreenHouseGasMixController - This mixes 74% Nitrogen, 24% Oxygen, 2% Carbon Dioxide if the Air Pressure in Reserve tanks is less than 18Mpa.
5. RoomAtmoControl - Turns on and off active vents named the same thing to control pressure in a room (100Mpa), Also checks for a 74% Nitrogen, 24% Oxygen, 2% Carbon Dioxide mix and if it is out of tolerance will Purge the Air in the Room. Also has an alarm that can be set to anything that can be set to on.
6. Battery Control
   - MasterBatteryControl - The controller reads its own battery ratio and data from up to four receivers, averages the valid values, transmits the result, and updates an LED display.
   - RemoteBatterControl - Reads the average battery ratio from the local network, transmits it to a remote receiver, receives an updated running average, and then displays that value on an LED.
