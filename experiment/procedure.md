### Procedure for the experiment is as follows:

1. Open the experiment in the virtual lab for sending live sensor data using HTTP protocol with ESP8266/ESP32.  
   The ESP32 board and the DHT sensor are already connected in the workspace.

2. Observe the circuit connections.  
   Check how the DHT sensor is connected to the ESP32 data pin, VCC, and GND.  
   Confirm that the ESP32 Wi-Fi module settings are already configured for network communication.

3. Open and review the Arduino code.  
   Read the predefined code to understand:  
   - Wi-Fi connection setup  
   - DHT sensor initialization  
   - HTTP request formation (GET/POST)  
   - Sending temperature and humidity data to a web server  
   - Server response handling

4. Start the simulation.  
   Click the "Start Simulation" button.  
   The ESP32 will automatically read data from the DHT sensor.  
   The sensor values (temperature and humidity) will be sent to the configured web server using the HTTP protocol.

5. Monitor the data on the web server panel.  
   Observe the live sensor values appearing on the web dashboard below the simulation area.  
   The data will refresh according to the interval programmed in the code.

6. Record observations.  
   Note the temperature and humidity readings and verify that they are correctly updated on the web server.

7. Stop the simulation.  
   Click the "Stop Simulation" button after completing the experiment.
