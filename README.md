# LoRa-board
built with help from stasis.hackclub.com…
<br/>

### What is this?
LoRa stands for 'Long Range', usually to transmit things like with radio. This particular project is such a LoRa board, with:
- an ESP32-S3
- a SX1262 radio
- a U.FL antenna
<img width="540" height="828" alt="whee" src="https://github.com/user-attachments/assets/a758fd2b-0c8c-4797-ae7a-c2ac52ed8f83" />
<img width="666" height="539" alt="Snímek obrazovky 2026-06-01 v 19 12 14" src="https://github.com/user-attachments/assets/3069328d-bffa-4063-b964-4211f963f906" />
<img width="775" height="623" alt="Snímek obrazovky 2026-06-02 v 6 10 29" src="https://github.com/user-attachments/assets/a8534056-d78b-4510-a6d0-484e145b5c6a" />

## how does it work? //Setup
So, the board gains power from the USB-C receptacle, there's also a couple buttons with the EN-RESET and GPIO10-BOOT functionalities respectively. What you need to do, once you get the board, is to boot it-- then, download the Meshtastic app and try to pair the LoRa board with your device just like that… no firmware is needed, afaik… :D

the references for each pin are in the BOM, like:
C1,C3,C4,C5 == Capacitor_SMD:C_0402_1005Metric
C2,C6,C7 == Capacitor_SMD:C_0402_1005Metric
J1 == Connector_USB:USB_C_Receptacle_HRO_TYPE-C-31-M-12
L1 == Inductor_SMD:L_6.3x6.3_H3
R1,R2 == Resistor_SMD:R_0201_0603Metric
R3,R4 == Resistor_SMD:R_0402_1005Metric
SW1,SW2 == Button_Switch_Keyboard:SW_Cherry_MX_2.00u_PCB
U1 == ESP32-S3-WROOM-1
U2 == AMS1117-3.3
U3 == SX1262IMLTRT

## why did I make it?
I made this project because I think it'd be really cool to have something that can transmit messages via a radio (especially with a friend)!

[lora.pdf](https://github.com/user-attachments/files/28474012/lora.pdf)
