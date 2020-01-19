# McWics-2020
Dance Dance Revolution Mini :)



To connect Arduino and python code via pyserial:

- Install pyserial
--> pip install pyserial

- Configure pyserial
--> go in python file
--> insert the following code at the beginning, COMx being the serial port connecting your computer to Arduino
  --> Import serial
  --> ser1 = serial.Serial('COM1', 9600)
--> insert the following code to send command to Arduino, replace 'a' by any single character you want
  --> ser1.write(’a’.encode())
