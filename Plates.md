# Plates Calibration

## Place the plate over the scale
## Turn on the scale 
   - "0.0" will display
   
## Connect the scale with the PC
## Connect the device with the PC
## Turn on the converter/transformer
## Turn on the rheostat


## Set up with RealTerm

- Tab: Port
	- Set the device (i.e plate) port by clicking the up-arrow button
	- Click on the **Open** button
	
- Tab: Send
	- Enter the serial number of the device for the name
		- 0x85 0x12 (for the left plate) 0x3X 0x3X 0x3X 0x3X 0x3X (where XXXXX is the serial number)
		- 0x85 0x13 (for the right plate) 0x3X 0x3X 0x3X 0x3X 0x3X (where XXXXX is the serial number)
			- **Note:** _For a plate with serial number PlateL01022 the name is: 0x85 0x12 0x30 0x31 0x30 0x32_	
		- Click on the **Send Number** button	
	- Set the Base of the device 
		- 0x42 for the plates
		- Click on the **Send Number** button
		
- Tab: Port
	- Click on the **Open** button for closing the port
	
	
## Calibration with Kinvent K-Force Evaluation

- Tab: Serial/USB start
	- Click on VISA resource name
		- Set the scales COM by clicking the up-arrow button
	- Click on **Connect & Run VI** button
	- Check if the _Port 1 C1_ (up and right corner) has green colour

- Tab: Scale
	- Click on VISA resource name
		- Set the scales COM by clicking the up-arrow button
	- Click on **Enable Port 3** button
	- Check if the indicators _Steady_, _Gross_ and _Scale_ (up and right corner) have green colour 

- Tab: Calib.
	- Set the serial number
	- Click on **Step 1** button
	- Click **OK** on the dialog box

- Tab: Dials
	- Click on **Start** button
	
- Tab: Plots
	- Check if the **Sum** number is bigger than 8000 and proceed to the next step
	
		- If the **Sum** number is lower than 8000
			- Tab: Dials -> click on **Stop** button
			- Tab: Calib. -> Click on **Step 1** button -> Click **OK**  on the dialog box
	
- Tab: Calib.
	- Set up the initial load (0.6 kg) by placing the metal-spring component on the first plate's pad (down and right blue SNAP*)
	- Gradually increasing the load up to 2, 6, 12, 25, 50, 70 and 90 kg and take a measurement for each value 
		- The load is increased by the pressure piston which movement is controlled by rheostat switch
		- After each measurement click on the **SNAP** button 
		- Check if the Raw values (left column) are between 30000 - 65000
	- Repeat this procedure for each of the four pads
	
- Tab: Dials
	- Click on the **Stop** button (stop sampling) 
	
- Tab: Calib.
	- Set the serial number
	- Click on the **Start** button
		- Check if the **Response OK** indicator is green throughout the process
	- After the procedure is over an .xls file is poped-up
	- Save the .xls file to the Google Drive (\KFORCE\Resources\Constraction & Planing\Device_Calibration_Certificates\Plates)
		- Enter serial_number_RAW for the name (i.e. P101022_Raw)
	- Check if there is no load on the plate and then click on **Step 2** button 
	- Click on **OK** button to the pop-up window
	
- Tab: Dials
	- Click on **Start** button

-Tab: Plots
	- Check if the **Sum** number is between 9 - 19
	- Check if there is no load on the plate and then click on **Zero** button 
	
- Tab: Verify
	- Set up the initial load (0.6 kg) by placing the metal-spring component on the first plate's pad 
	- Gradually increasing the load up to 2, 6, 12, 25, 50, 70 and 90 kg and take a measurement for each value 
	- Type the serial number
	- Click on **Export Report** button
	- Save the .xls file to the Google Drive (\KFORCE\Resources, Constraction & Planing\Device_Calibration_Certificates\Plates)
		- Enter the serial nuber for the name (i.e. P101022)
		
- Tab: Dials
	- Click on **Stop** button
	- Cklick on **Switch off** button
	
## Sticker the Serial Number
	
