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

## why did I make it?
I made this project because I think it'd be really cool to have something that can transmit messages via a radio (especially with a friend)!

[lora.pdf](https://github.com/user-attachments/files/28474012/lora.pdf)
