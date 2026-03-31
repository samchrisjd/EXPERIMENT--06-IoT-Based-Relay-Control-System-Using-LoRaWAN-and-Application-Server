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
### 1. Serial Port Utility – Network Server Connection:
<img width="1919" height="1079" alt="565861968-0c5b6653-a9f9-4611-befc-ea4995e4d1e2" src="https://github.com/user-attachments/assets/9bac563e-168c-42f1-ba1d-8ea0153848fd" />


### 2. Network Server – Recent Events
<img width="1596" height="891" alt="network" src="https://github.com/user-attachments/assets/5f95811b-e76b-4111-babe-12426aa25b6e" />

### 3. Dashboard Command Sending
<img width="1914" height="970" alt="565864273-ab9ce9fd-28b0-4107-8265-8bbf273d9af0" src="https://github.com/user-attachments/assets/f1411101-b927-4613-80c7-e7906ac69c6f" />

### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON
<img width="1915" height="906" alt="application" src="https://github.com/user-attachments/assets/e5200839-0f29-4232-989b-71741feda4c0" />

### Bulb OFF → Relay OFF
<img width="1915" height="906" alt="application" src="https://github.com/user-attachments/assets/b60e6b85-f830-4924-8d74-1bde7e800d22" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
