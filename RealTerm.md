# Determine Name and Base with RealTerm

## Tab: Port
  - Set the device (plate/muscle/grip) port by clicking the up-arrow button
  - Click on the **Open** button
	
## Tab: Send
  - Enter the serial number of the device for the name
    - Ccording to the device type:
      - `Left plate:` 0x85 0x12  0x3X 0x3X 0x3X 0x3X 0x3X (where XXXXX is the serial number)
      - `Right plate:` 0x85 0x13  0x3X 0x3X 0x3X 0x3X 0x3X (where XXXXX is the serial number)
	     - **Note:** _For a plate with serial number PlateL01022 the name is: 0x85 0x12 0x30 0x31 0x30 0x32_	
      - `Muscle:` 0x85 0x11  0x3X 0x3X 0x3X 0x3X 0x3X (where XXXXX is the serial number)
	  - `Grip:` 0x85 0x10  0x3X 0x3X 0x3X 0x3X 0x3X (where XXXXX is the serial number)
    - Click on the **Send Number** button	
  - Set the Base of the device 
    - Type 0x42 
    - Click on the **Send Number** button

## Tab: Port
  - Click on the **Open** button for closing the port
   
