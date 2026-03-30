## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1920" height="1080" alt="Screenshot 2026-03-20 114840" src="https://github.com/user-attachments/assets/7ea7ee1a-b24e-4bf4-a8ea-e3eb82705d4d" />


### 2. Network Server – Recent Events
<img width="1920" height="1080" alt="Screenshot 2026-03-20 115059" src="https://github.com/user-attachments/assets/1e80e278-b3a1-4312-954a-8c2c312d26cb" />

### 3. Dashboard Command Sending
<img width="1034" height="602" alt="image" src="https://github.com/user-attachments/assets/35912e94-9afc-457e-8712-2f63b2f00c77" />
<img width="1045" height="586" alt="image" src="https://github.com/user-attachments/assets/48e5a802-403d-42ff-afe7-4b680169fc26" />
<img width="1062" height="590" alt="image" src="https://github.com/user-attachments/assets/56f2089e-b6ee-4254-8e41-26f690673f60" />
<img width="1052" height="605" alt="image" src="https://github.com/user-attachments/assets/4dc266a9-644e-44fb-89f9-974731ab31a4" />
<img width="1052" height="605" alt="image" src="https://github.com/user-attachments/assets/3d1de155-a176-42de-81e3-fba7d6271dfd" />

<img width="1021" height="597" alt="image" src="https://github.com/user-attachments/assets/4f7fff7f-44eb-4cb1-83c2-0d187e0f5d4f" />

<img width="987" height="597" alt="image" src="https://github.com/user-attachments/assets/a196c7e2-9e8b-47c9-9227-dd3c98ba60d7" />


### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
![WhatsApp Image 2026-03-30 at 11 23 07 AM](https://github.com/user-attachments/assets/5674551d-2a40-458d-82c1-51ca21b8feb9)


### Bulb OFF → Relay OFF
<img width="1920" height="1080" alt="Screenshot 2026-03-20 115106" src="https://github.com/user-attachments/assets/ba5d8327-1b2a-460a-9bcf-e01d3153f24c" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
