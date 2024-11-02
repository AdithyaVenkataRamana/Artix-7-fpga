# Artix-7-fpga

## Introduction
The Artix-7 FPGA board is a small, powerful circuit board designed by Xilinx that lets engineers and hobbyists create custom digital circuits and hardware. FPGAs (Field-Programmable Gate Arrays) like the Artix-7 can be "programmed" to act like different types of digital systems. This makes them incredibly flexible—they can be used to make anything from basic logic circuits to complex processors.

Artix-7 is popular because it’s both powerful and energy-efficient. It’s commonly used in applications where performance and power savings are important, like in communications, medical devices, and industrial automation. With the Artix-7 board, you can experiment and build hardware designs that respond very quickly to inputs, which makes it a great choice for real-time and high-performance applications.

![Screenshot 2024-11-02 132816](https://github.com/user-attachments/assets/3f6f7734-8ba1-48c2-acf3-aea5d1c523ba)

1. It is an upgraded version of the  Sparton 6 board.
2. It is specially created to work with the latest Vivado design suite.
3. It is buit with the Xilinx Artix 7 XC7A357 FPGA IC at it's core.

## Features
1. External SDRAM.
2. HDMI Port.
3. Micro SD Card.
4. WIFI & Blutooth module.
5. ADC & DAC interfaces.
6. LCD Display.
7. 7 Segment Display.
8. Camera interface.
9. TFT Screen.Buzzer.
10. Switch.
11. Button inputs.
12. LED outputs.
![Screenshot 2024-11-02 134641](https://github.com/user-attachments/assets/c40614db-9e2d-46b0-abad-58550ab86ece)

### Detalied Features
1. 32MB of on board SDRAM, enables smooth imlementation of real-time image & video processing tasks.
2. Ready to use labratory tool.
3. To design & develop digital circuits of varying complexity, ranging from basic to advanced level.
4. It provides ease in implementing a wide range of applications without the need for additional interfaces.
5. Xilinx XC735T-ITTG256 Artix 7 FPGA.
6. 8MB SPI Flash Memory.
7. 32MB SDRAM, HDMI Output.
8. MicroSD Card Slot.
9. Onboard USB JTAG programmer.
10. USB to UART interface.
11. WIFI interface, Low power Bluetooth interface.
12. 12 - Bit VGA interface.
13. 8 channel SPI ADC.
14. Temperature sensor.
15. LDR interface.
16. SPI DAC.
17. 2 * 16 LCD Display.
18. Four digit 7 Segment display.
19. 5Volt buzzer.
20. CMOS Camera interface.
21. TFT Display interface.
22. Push buttons.
23. Stereo Jack.
24. Reset button.
25. Slide switches LED's.

![Screenshot 2024-11-02 140838](https://github.com/user-attachments/assets/a3f118ad-4f1a-4af7-86f0-cf8b74f8bf2d)

### Configurable Logic Block(CLB) 7 - Series FPGAs
![Screenshot 2024-11-02 141644](https://github.com/user-attachments/assets/c3e6cf8c-8981-4145-b325-69e0c94f3d36)

1. The main design resoures are combinational functions  and flipflops.
2. CLB has two Slices:
I. SLICE_M.
II. SLICE_L.

3. That are linked to the switch matrix to allow for routing to other parts of the FPGA.
#### I.SLICE_M:
1. SLICE_Ms contain full slices that offer both logic and memory.
2. They feature Multiplexers & Carry chains.

   
![Screenshot 2024-11-02 142158](https://github.com/user-attachments/assets/23fcf47a-e206-4345-9d34-2597c0d2bfdb)

### CLB-MUX
1. The Artix 7 FPGA can implement the functions with 8inputs using wide function multiplexers.
#### II.SLICE_L:
1. SLICE_Ls only contain logic and arithmetic elements and can't be used for memeory.
2. They also feature wide Multiplexers and Carry chains.
 ![Screenshot 2024-11-02 142207](https://github.com/user-attachments/assets/c5d835cc-210e-49e8-8eff-8a430daf7a37)

### CLB-MUX
1. The Artix 7 FPGA can implement the functions with 8inputs using wide function multiplexers.
   ![Screenshot 2024-11-02 142244](https://github.com/user-attachments/assets/9ffb7edf-6167-4bc3-b021-6550a3020e21)

### CLB-LUT
1. LUTs lookup tables in the CLB's of the Artix 7 FPGA can be the eiher two 5 input LUT's with common input or 6 input LUT. The 5 input LUTs have minimal speed impact & can provide any function of 5 variables.
2. While the 6 input LUT can produce any functions of 5 variables & can have 1 or 2 outputs.

![Screenshot 2024-11-02 142700](https://github.com/user-attachments/assets/ae13acda-11d1-4111-9199-9a7b19ba4ff6)

