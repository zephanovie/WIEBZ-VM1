# October 5th, 2026
I decided to start with a prototype to first get the sensor working and counter any problems before i move on to the main board…..so i created a schematics and pcb for the sensor arcording to the sensor datasheet and i also added some silkscreen to the board and countered all errors by the drc
![](/Images/Protoboard-schematics.png)
![](/Images/Protoboard-PCB-Design.png)
![](/Images/Protoboard-PCB.png)

**Total time spent: 3h 23m**

# October 8th, 2026
So i decided to scrap the idea of making a prototype first and just decided to commit to everything....so since this is a vertical mouse, designing everything in one pcb would not be possible so as of now(SUBJECT TO CHANGE!) there will be 3 boards....the main board, which would be in the base and hold the sensor and mcu and also some leds...then we have the button borad, which would hold all the buttons and the scroll wheel encoder and aslo some leds....and maybe an extra board just for leds (cant have too many RBGs) so thats the basic idea for now  
   Anyways for todays work what i did was to design the schematics for the main board....that is the sensor, mcu and led connections and also capacitor filters (or decoupling [or sum i think]).....oh have i stated that ill be using a rp2040 zero as the mcu and qmk for the firmware so i can sync it with my keyboard....so i guess thats it (for now!!!!!)
![](/Images/Main-Board/PMW3360-sensor.png)
![](/Images/Main-Board/rp2040-zero.png)
![](/Images/Main-Board/TPS73601(A-1.9v).png)
![](/Images/Main-Board/Leds-Schematics.png)
![](/Images/Main-Board/Cap-filter.png)

**Total Time Spent: 1h 17m**
