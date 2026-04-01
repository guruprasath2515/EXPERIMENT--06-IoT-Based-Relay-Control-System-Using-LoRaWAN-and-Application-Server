# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
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

<img width="1660" height="1006" alt="Screenshot 2026-04-01 113648" src="https://github.com/user-attachments/assets/3c5517d6-6d4b-4a12-8fca-f8e755ddbbba" />



### 2. Network Server – Recent Events

<img width="1728" height="1018" alt="Screenshot 2026-04-01 114159" src="https://github.com/user-attachments/assets/2070c08c-289e-4420-b6cf-131522c7a6b3" />


### 3. Dashboard Command Sending

<img width="1919" height="980" alt="image" src="https://github.com/user-attachments/assets/0cd60e34-639e-4cf5-9b87-9caacb36edda" />


### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  

<img width="1913" height="1015" alt="Screenshot 2026-04-01 114227" src="https://github.com/user-attachments/assets/07fc6e40-0033-4f59-af27-ee53e076710c" />

### Bulb OFF Relay OFF
<img width="1918" height="966" alt="Screenshot 2026-04-01 140454" src="https://github.com/user-attachments/assets/2107180a-1b08-4bc5-ac51-b9cba7c1ef3c" />




## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
