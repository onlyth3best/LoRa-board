# LoRa-board
built with help from stasis.hackclub.com…
<br/>

### What is this?
LoRa stands for 'Long Range', usually to transmit things like with radio. This particular project is such a LoRa board, with:
- an ESP32-S3
- a SX1262 radio
- a U.FL antenna
<img width="1234" height="1162" alt="Untitled design (19)" src="https://github.com/user-attachments/assets/3b7f76b0-16ef-444d-bd8a-0f93d3585e02" />
<img width="358" height="432" alt="Snímek obrazovky 2026-06-21 v 2 35 06" src="https://github.com/user-attachments/assets/80669598-7915-4729-b677-b08703de3754" />
<img width="794" height="550" alt="Snímek obrazovky 2026-06-21 v 2 35 26" src="https://github.com/user-attachments/assets/e18c8101-ccc4-410c-84e2-06640d92100d" />
[lorarpdff.pdf](https://github.com/user-attachments/files/29169228/lorarpdff.pdf)
<img width="540" height="828" alt="loraapng" src="https://github.com/user-attachments/assets/4f400d38-fd25-4b42-abca-d30919d04fad" />





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
