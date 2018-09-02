# EMBEDDED SYSTEM DESIGN 

• 4 wire resistive touchscreen TS-TFT3.5Z is interfaced to MSP432 - ARM Cortex -M4F MSP432P401R microcontroller.
• All cathode LED Dot Matrix is interfaced to MSP432.
• Touchscreen area is mapped to the LED matrix and the patterns drawn on the touchscreen are reflected on the LED matrix in real time with a button feature to erase the previously written patterns.
• Touch Detection was enabled in software using a port interrupt which further enables ADC sampling. 
• 10 Bit ADC mechanism (single channel single conversion mode) and the average of a number of samples are taken to detect precise touch point on the touchscreen.
