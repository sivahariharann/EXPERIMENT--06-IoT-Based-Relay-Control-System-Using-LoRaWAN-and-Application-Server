# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## NAME : SIVAHARIHARAN J
## REG NO : 212224223004
## DEPT : INFORMATION TECHNOLOGY
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
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171508" src="https://github.com/user-attachments/assets/56faf8ee-f0f6-4b3f-a65d-58d6cd79809d" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171532" src="https://github.com/user-attachments/assets/aa6781c2-118d-40af-87f1-a4998aea3e95" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171550" src="https://github.com/user-attachments/assets/0f9e5552-2693-4ec8-b613-7e470b56dd71" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171616" src="https://github.com/user-attachments/assets/68470057-8ad9-40c7-b553-bc7863ab293b" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171635" src="https://github.com/user-attachments/assets/cae55c70-6b73-496f-b672-efcd02f8bac7" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171711" src="https://github.com/user-attachments/assets/9b14ef3b-42dd-41ae-a0ae-a2346f9b5e1c" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171752" src="https://github.com/user-attachments/assets/8f54f901-9d10-4ed0-a6f1-61e0e4977550" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171822" src="https://github.com/user-attachments/assets/c46c0e83-f35d-4e0a-b760-02aeac4e274d" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171843" src="https://github.com/user-attachments/assets/45def0b8-6996-49c6-b7e3-3bbbc8fa7d8b" />

### 2. Network Server – Recent Events
<img width="1920" height="1200" alt="Screenshot 2026-03-13 173049" src="https://github.com/user-attachments/assets/dcc3d974-75cc-479c-9c0b-c7d62ce68602" />

### 3. Dashboard Command Sending
<img width="1919" height="1137" alt="Screenshot 2026-03-17 103932" src="https://github.com/user-attachments/assets/01563efa-c9d3-4f7a-971c-146362f71046" />
<img width="1919" height="1140" alt="Screenshot 2026-03-17 103948" src="https://github.com/user-attachments/assets/906a035a-8aab-4d7c-b609-9904ca66efb7" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON 
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172907" src="https://github.com/user-attachments/assets/42e53698-7405-498c-bce1-8ff1d534f2c7" />

### Bulb OFF → Relay OFF
<img width="1920" height="1200" alt="Screenshot 2026-03-13 173101" src="https://github.com/user-attachments/assets/0d498000-56af-4a79-ba6b-237e8794f363" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
