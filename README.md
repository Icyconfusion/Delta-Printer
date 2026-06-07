# Delta-Printer
An STM32 based delta style 3D printer running Marlin firmware. The printer features a custom PCB motherboard, LCD, and 220mm diameter x roughly 200mm build volume. I designed this project to expand on my understanding of 3D printer hardware and mechanics through non-standard motion.

<img width="493" height="738" alt="image" src="https://github.com/user-attachments/assets/70b3c7ad-475e-4977-a918-f0f8b69fc65e" />

## Assembly
The key assembly ofthe printer is a triangular prism made of 2020 T slot aluminium profiles. Using 3d printed brackets, shorter T slots of lengths 340mm for the top and 290 for the bottom are arranged into triangles. 500mm T slot join these triangles. Two profiles are used for each tower to increase stiffness. The bottom bracket extends the height of the printer without needing extra T slot. Brackets are mounted using T nuts.

<img width="486" height="752" alt="image" src="https://github.com/user-attachments/assets/e19160e5-92ef-4358-94ee-eb3c169c91db" />
<img width="861" height="715" alt="image" src="https://github.com/user-attachments/assets/0c5a856a-52ae-434c-9f6a-ac274b07345e" />

400mm MGN12H linear rails are mounted to the inside profile of each tower using M3x8 screws.

<img width="265" height="601" alt="image" src="https://github.com/user-attachments/assets/fff9ba5a-e353-4a41-9897-138b2ab8b88e" />

To mount the NEMA17 stepper motors, the motors are screwed into the mount bracket, which attaches to the inside of the two bottom triangles.

<img width="612" height="432" alt="image" src="https://github.com/user-attachments/assets/03be4c48-0606-4494-a2e6-e05531dae46f" />
<img width="544" height="399" alt="image" src="https://github.com/user-attachments/assets/5dd2a998-11f5-4c1e-a7ec-4f81e2144820" />
<img width="580" height="499" alt="image" src="https://github.com/user-attachments/assets/55665f66-1df2-48e7-a9fe-e76de2410c01" />

Bottom covers are added and the PCB is placed in the groove in the centre.

<img width="617" height="553" alt="image" src="https://github.com/user-attachments/assets/f8652fa8-bc60-441b-b6bc-ca215577f984" />
<img width="692" height="634" alt="image" src="https://github.com/user-attachments/assets/3a3ade54-fa9d-4f3f-9601-362a755c102e" />

Idle pulleys are mounted to the top bracket with an M5 screw. The carriages are assembled with the ball joints screwed onto the carriage. M3 screws are threaded into the heat inserts and the GT2 belt is mounted. The carbon tube has an M3 stud glue into each end, which is threaded into the ball joint on each end.

<img width="245" height="251" alt="image" src="https://github.com/user-attachments/assets/479c1425-68b2-4f59-8fa4-73f25187a39e" />
<img width="212" height="457" alt="image" src="https://github.com/user-attachments/assets/a18f8857-378f-439b-a7e9-0977d6946d17" />
<img width="394" height="549" alt="image" src="https://github.com/user-attachments/assets/d55710d0-3e4c-46f5-85e3-ced94a1f21f2" />
<img width="522" height="549" alt="image" src="https://github.com/user-attachments/assets/e7f776cf-36eb-4785-8e96-4f968296f148" />

### Effector Assembly
To assemble the effector, first mount the NEMA 17 stepper and filament gear.

<img width="435" height="461" alt="image" src="https://github.com/user-attachments/assets/6cda70d9-d072-4ded-928a-85ae14452de6" />
<img width="502" height="489" alt="image" src="https://github.com/user-attachments/assets/1e6e1bc6-1972-4023-bdc6-24d880f7f1fe" />
<img width="658" height="781" alt="image" src="https://github.com/user-attachments/assets/24f09717-7e9b-4bc5-a580-57c091eff0f6" />

Then mount the CR6-SE hotend into the heat inserts.

<img width="364" height="434" alt="image" src="https://github.com/user-attachments/assets/0ac110b5-3723-4003-a243-b954102bd387" />

4010 fans mount on the back and side where they are ducted to the nozzle/part.

<img width="535" height="488" alt="image" src="https://github.com/user-attachments/assets/5c23403f-7391-4335-a144-7734363d2c81" />
<img width="811" height="475" alt="image" src="https://github.com/user-attachments/assets/59e1fd42-fbde-420f-bb03-ec1555b641c0" />

The extruder arm provides tension to the filament gear to ensure accurate and reliable extrusion of filament. The arm is spring loaded to push an 11x5x5 bearing, squeezing the filament against the drive gear. The arm pivots around the top left M3 NEMA 17 mounting screw. An M5 screw above this is threaded into the effector knob, and a spring in this spot provides tension. Finally, the ball joints are attached, and can be connected to the arms on the carriages.

<img width="352" height="343" alt="image" src="https://github.com/user-attachments/assets/93056c43-3450-4151-bbb2-d52641bb90e0" />
<img width="499" height="736" alt="image" src="https://github.com/user-attachments/assets/15e32dcb-052d-41cc-81cc-af69a98db819" />
<img width="438" height="735" alt="image" src="https://github.com/user-attachments/assets/9a66eb09-806c-4650-abb4-f35613ad3811" />
<img width="636" height="636" alt="image" src="https://github.com/user-attachments/assets/3a5381b9-f974-43e5-9ef3-d1107be0215c" />

To start closing the base compartment and installing the bed, the LCD must be installed. The LCD is screwed through the back into heat inserts in the LCD module printed part. This module is then mounted onto LCD base covers using heat inserts. This is then mounted onto the base using T nuts.

<img width="1192" height="646" alt="image" src="https://github.com/user-attachments/assets/26c7f985-b5b7-4a60-8365-0c133e2fd85c" />
<img width="1173" height="672" alt="image" src="https://github.com/user-attachments/assets/48994985-22b5-48b6-888b-aa2007e18941" />
<img width="793" height="657" alt="image" src="https://github.com/user-attachments/assets/5c1162af-f32a-45c2-976a-6d632d6b345c" />
<img width="916" height="404" alt="image" src="https://github.com/user-attachments/assets/b2c2018e-fef3-47b6-af46-43d5b8800c9e" />
<img width="1387" height="506" alt="image" src="https://github.com/user-attachments/assets/9344a729-ab10-4294-9bb6-5fbd5ee1cbf0" />
<img width="833" height="562" alt="image" src="https://github.com/user-attachments/assets/8efefbf6-d105-4904-870c-7bc204008156" />
<img width="729" height="371" alt="image" src="https://github.com/user-attachments/assets/3023f263-c80e-41d6-9bfb-b388ec4981c5" />

Base covers are mounted onto one of the other sides.

<img width="1260" height="411" alt="image" src="https://github.com/user-attachments/assets/3fa3f8b3-0410-40be-adfd-3cb729a7ff91" />

The third side holds the PSU. The PSU is held in its compartment, which is mounted to the frame in place. A base cover is mounted next to it.

<img width="491" height="465" alt="image" src="https://github.com/user-attachments/assets/5316ddf4-5db2-495c-a37b-3a4de41e38d7" />
<img width="557" height="261" alt="image" src="https://github.com/user-attachments/assets/d9c7c91a-d74f-4c04-99a8-7c232bb4ab2b" />
<img width="521" height="510" alt="image" src="https://github.com/user-attachments/assets/cce0fd2a-8419-4bc8-9113-67939633d634" />
<img width="592" height="390" alt="image" src="https://github.com/user-attachments/assets/77653c7c-3fc4-4c59-bd14-9f75bff6526" />

Now the bed can be installed. To do this, printed bed supports are installed on the base. The bed then screws into these. If needed, depending on exact specifications of the bed, the holes to mount the bed can be made larger by printing or drilling.

<img width="639" height="492" alt="image" src="https://github.com/user-attachments/assets/1f0a3bc3-6f8a-4ea7-9db8-79c6f33caba7" />
<img width="1118" height="775" alt="image" src="https://github.com/user-attachments/assets/3e4acbbe-d8b6-439f-9ab8-984f2e2927ec" />

To mount limit switches, the switches are screwed into heat inserts in the bracket, then mounted to the bottom of the towers. After this the printer is assembled.

<img width="373" height="311" alt="image" src="https://github.com/user-attachments/assets/fb9379da-b220-435c-aea7-5e994eb9fd99" />
<img width="493" height="738" alt="image" src="https://github.com/user-attachments/assets/5c2175f9-1386-42de-9479-d4fc87fcd0b3" />

## Electronics
The printer features a 2 layer PCB motherboard I designed around an STM32F407VGT6. TMC2209 drivers are used to control stepper motors, and subsequently motion. The board utilises mostly SMD components to minimise space and layer requirements. Power is brought onto the board using 7.62mm pitch screw terminals, which connect to the 24V 600w PSU. A buck converter and linear regulator convert this down to 5V and 3.3V logic levels. 5V is used only for the buck converter and the EXP1 header for the LCD. The LCD used it a BTT Mini 12864 V2.0, which interfaces with the PCB via EXP1 and EXP2 headers. The LCD also has an encoder, button and SD card reader. The heaters (hotend and bed if required in future) are controlled through TO-252-3 AOD4184 MOSFETs. Lower power mosfets, SOT-23 AO3400 MOSFETs, are used to control the 24V fans. There is a USB-C receptacle for firmware flashing, and an SWD header if needed. Most resistors and capacitors are size 0805, though there are exceptionswhere required. Because I am using the STM32, no external flash is required, as it is onboard.

<img width="1152" height="806" alt="image" src="https://github.com/user-attachments/assets/aff23627-1338-4167-83c1-d0891776c4f5" />

Driver hierarchical sheet:

<img width="658" height="579" alt="image" src="https://github.com/user-attachments/assets/68a708b4-c2c1-4029-8c04-e4bc1980e6a7" />

MOSFET hierarchical sheet:

<img width="312" height="281" alt="image" src="https://github.com/user-attachments/assets/b9693c64-f253-4f90-8300-960ac998c718" />

<img width="553" height="576" alt="image" src="https://github.com/user-attachments/assets/4fcf732d-3279-4390-bde7-b6d7df842abc" />
<img width="1168" height="592" alt="image" src="https://github.com/user-attachments/assets/525999ae-c32f-466a-b4d0-b56864d44771" />

Power:

<img width="1142" height="400" alt="image" src="https://github.com/user-attachments/assets/088968c1-e8a4-47e2-9c59-52c985846dbc" />

EXP1 and EXP2:

<img width="780" height="340" alt="image" src="https://github.com/user-attachments/assets/8482cbe6-5b18-4cdb-a2fd-88f6d95087d8" />

The PCB is organised with drivers up the top. Power on the left edge, with the buck converter, regulator, power input terminal and fuse. MOSFETs are on the bottom, heaters on the right hand side. On the right edge, there is the USB-C receptacle, thermistors, endstops and LCD headers. The STM32 is situated in the center.

<img width="661" height="564" alt="image" src="https://github.com/user-attachments/assets/ff0fcfc3-3102-4159-82ff-05c0a50d7cdc" />
<img width="675" height="551" alt="image" src="https://github.com/user-attachments/assets/c6a96187-24b6-4ece-83d9-1a35f58d3471" />
<img width="914" height="726" alt="image" src="https://github.com/user-attachments/assets/97f7c60c-6882-4dc3-9d94-f7a7b9ccf789" />

## BOM
### Printed Parts

### Parts already owned


### Purchased parts












