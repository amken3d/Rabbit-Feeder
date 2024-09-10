# Rabbit-Feeder
A low cost automatic 8mm belt driven feeder for OpenPnP and other Pick and Place machines


![image](https://github.com/user-attachments/assets/5007b4ee-1a11-4b05-ad04-20c13554240f)

![image](https://github.com/user-attachments/assets/8210b11e-31ee-4983-ab1c-99a3dc3bf135)


![image](https://github.com/user-attachments/assets/931f6f65-713a-493a-a9bd-851a96859201)

![image](https://github.com/user-attachments/assets/ca5695ff-99b2-4fe7-839f-ba24588e48da)



# This is a experimental feeder which is still in development. 


The Rabbit feeder is intended to be a ultra low cost semi automatic feeder. The brains of this feeder is a ultra cheap  PY32F002A 32 bit M0 based microcontroller which is easily available for around $0.10. The total BOM cost of this feeder is designed to be around $5. 
The firmware for this feeder is still under development, and will be posted here when ready. Feel free to build one for yourself and help in writing the firmware.

# Bill Of Materials 
1. N20 Motor - Look for GW1812-N20 DC 12V  on Aliexpress. This is the most expensive part of this feeder. You need a horizontal shaft motor.
2. GT2 160 mm belt - Source on Aliexpress or Amazon : GT2 Timing Belt Idler Pulley 20 Teeth 5mm Bore 6mm Width
3. 3x8x4 mm 2RS Bearings X 6 : Easily sourced on Amazon and Aliexpress
4. 624-2RS Bearings 4x13x5mm X 2: Easily sourced on Amazon and Aliexpress
5.  T Nuts X 2
6.  M3 bolts and nuts
7.  3D Printed Parts
8.  Electronics - See attached BOM.

# Included files
1. Gerber
2. Fusion 360 CAD drawing
3. STL files for 3d printing. No supports needed, but adding some strategic supports in a couple of areas might help for the Main Body. 
4. Schematics
5. The PY32 datasheet in English can be found here https://download.py32.org/Datasheet/en/PY32F002A%C2%A0datasheet%C2%A0Rev.0.2_EN.pdf
   

# Firmware: WIP
The feeder will recieves signals for moving the tape forward or backward using pulses. The exact mechanism and details are TBD. It will be posted here when available.
This is a semi intelligent feeder. It does not communicate back to the host. The goal with this feeder was to make something nice and cheap. So, in that spirit, this feeder does not have many frills. However, based on community feedback and interest, the feeder design can be improved such as

1. CAN Bus or RS485 based communications
2. Wireless comms using ESP32 (why not)
3. Positional awareness and so on....

   
   
![AMKEN_small](https://github.com/user-attachments/assets/51f34ff6-8967-46fa-80bc-ef2fe62000b9)








The Rabbit feeder was inspired by the work of Mark 4 friends and ftobler. 
