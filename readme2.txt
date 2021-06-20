Characters can be displayed in the air using M5StickC and LED (29LEDs) tape. 
Transfer the character data created by the iPhone application (OshiBou2) to the M5StickC for use. 
Use the iPhone app OshiBou2 to create and transfer display data for M5StickC. 

Features 
- The set character string can be displayed on the LED tape 
- Data transferred directly to M5Stick via Wi-Fi 
- Display is character by character or all characters 
- To start the display, press the A button or shake 
- The display direction is alternating left and right or only in one direction 
- Display speed is 2 levels 
- Text color can be selected from 7 colors 
- Black or white can be set for the background 

How to write a program 
1. Create a new folder on Windows and copy oshibou2.ino.m5stick_c.zip 
2. Unzip oshibou2.ino.m5stick_c.zip 
3. Connect the M5StickC to the Windwos PC via USB and check the connected COM port number
4. Execute ESP32Write.bat and enter the COM port number 
5. Press the return key to execute writing 

How to use 
1. Set Wi-Fi password on M5stickC (first time only) 
2. Press the A button for 5 seconds to wait for data transfer 
3. Connect iPhone to M5stickC access point 
4. Enter characters in the iPhone app (OshiBou2) and press MAKE DOT button 
5. Transfer data to M5stickC with the SEND M5S button of the app 
