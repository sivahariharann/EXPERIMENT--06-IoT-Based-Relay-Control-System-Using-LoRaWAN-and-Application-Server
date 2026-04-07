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
<img width="1919" height="1128" alt="Screenshot 2026-03-17 123722" src="https://github.com/user-attachments/assets/c8381a08-4d74-4043-ae1e-48d7c05e3d8e" />
<img width="1918" height="1126" alt="Screenshot 2026-03-17 123741" src="https://github.com/user-attachments/assets/2ee3184b-41df-4c10-b053-433f2ace1974" />
<img width="1919" height="1139" alt="Screenshot 2026-03-17 123820" src="https://github.com/user-attachments/assets/6a15c774-d70b-48a3-a734-43ff81b4f92c" />
<img width="1915" height="1139" alt="Screenshot 2026-03-17 123905" src="https://github.com/user-attachments/assets/93ca8471-2504-403e-8ba8-7a774979dcf4" />
<img width="1919" height="1140" alt="Screenshot 2026-03-17 123929" src="https://github.com/user-attachments/assets/435025ed-d1e8-4c14-a52c-0c2208719aca" />
<img width="1919" height="1140" alt="Screenshot 2026-03-17 124116" src="https://github.com/user-attachments/assets/664935a7-b4f8-4aa4-a51a-3a2d49c4bc9d" />
<img width="1919" height="1141" alt="Screenshot 2026-03-17 124140" src="https://github.com/user-attachments/assets/c879eb56-f95a-4f27-86c0-4f450e2514bf" />
<img width="1919" height="1138" alt="Screenshot 2026-03-17 124402" src="https://github.com/user-attachments/assets/be94744c-39f3-4535-9e13-bf350a2336a9" />

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
<img width="1919" height="1137" alt="Screenshot 2026-03-17 112720" src="https://github.com/user-attachments/assets/b659ec0f-e22d-49dd-ae6a-5935f06b2a57" />
<img width="1919" height="1132" alt="Screenshot 2026-03-17 112740" src="https://github.com/user-attachments/assets/2fd179fe-7dec-46d5-9b62-2feeae1938aa" />
<img width="1918" height="1139" alt="Screenshot 2026-03-17 112759" src="https://github.com/user-attachments/assets/d858432d-03b3-4880-9d4f-905838739ec3" />
<img width="1917" height="1133" alt="Screenshot 2026-03-17 112926" src="https://github.com/user-attachments/assets/71b46e61-1a95-4f6e-a5c2-3168a3c6d4fa" />
<img width="1915" height="1130" alt="Screenshot 2026-03-17 112948" src="https://github.com/user-attachments/assets/7a24c809-aae6-4305-80b3-2c22d34beda4" />
<img width="1919" height="1129" alt="Screenshot 2026-03-17 113116" src="https://github.com/user-attachments/assets/356c97bd-40b5-4eae-938b-137e03003d54" />
<img width="1919" height="1123" alt="Screenshot 2026-03-17 113132" src="https://github.com/user-attachments/assets/d2698ba3-161a-4106-b6c1-c3692c57d80b" />
<img width="1917" height="1123" alt="Screenshot 2026-03-17 113154" src="https://github.com/user-attachments/assets/ccd7f21a-e5eb-48cc-a2fc-79286ad512b2" />
<img width="1919" height="1134" alt="Screenshot 2026-03-17 113207" src="https://github.com/user-attachments/assets/c628a383-3099-4b62-8cdd-45383566eccf" />
<img width="1918" height="1138" alt="Screenshot 2026-03-17 113226" src="https://github.com/user-attachments/assets/2f48c2b8-69e3-4359-bfce-92777c52b8da" />
<img width="1919" height="1134" alt="Screenshot 2026-03-17 122931" src="https://github.com/user-attachments/assets/9547b6b7-5c95-4c3c-8c05-edee33b9943f" />
<img width="1915" height="1131" alt="Screenshot 2026-03-17 122950" src="https://github.com/user-attachments/assets/c1434168-7b05-43eb-a6f7-6d44c04e1055" />
<img width="1919" height="1131" alt="Screenshot 2026-03-17 123005" src="https://github.com/user-attachments/assets/c009ecff-0380-46e0-b3f8-93aff25c3f66" />
<img width="1919" height="1144" alt="Screenshot 2026-03-17 123016" src="https://github.com/user-attachments/assets/ee77187a-5922-4675-a393-ae6d6fb28c85" />
<img width="1919" height="1144" alt="Screenshot 2026-03-17 123117" src="https://github.com/user-attachments/assets/1de3c6a4-3ef3-49e6-801a-8a6c8b53a98e" />

### Bulb ON → Relay ON 
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172907" src="https://github.com/user-attachments/assets/42e53698-7405-498c-bce1-8ff1d534f2c7" />

### Bulb OFF → Relay OFF
<img width="1920" height="1200" alt="Screenshot 2026-03-13 173101" src="https://github.com/user-attachments/assets/0d498000-56af-4a79-ba6b-237e8794f363" />

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/9eb58cd9-64f3-4710-9f46-8112b03b2b3c" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
