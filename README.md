SOS Emergency Call Mobile App
It is a simple and fast emergency application built using  mobile app creation (Kodular).
With a single tap, the app instantly makes a call to your contact what you given.  
This app doesn't use location, GPS, or internet.
It focuses only on calling.
Features:
    -Instantly calls the number you set.
    -Works without internet.
    -No location or SMS features
    -Big SOS button for quick access.
    -No tracking. 
    -No data collection.
    -No permissions except CALL.
Built With:
-Kodular Creator 
Components used:
. Call Phone 
. Button 
. Label components
How It Works:
1. User opens the app  
2. Presses the SOS button
3. The app immediately starts a phone call to the given number


IoT Egg Tray Monitoring and Bulb Control App
This is a mobile application development using Kodular to monitor an egg tray status and remotely control a bilb using Firebase Realtime Database.
The app reads live sensor values from hardware and updates the UI instantly.
Features:
    -Egg Tray Monitoring: Displays whether the egg tray is occupied or empty based on sensor data.
    -Bulb ON/OFF Control: Two buttons to control a bulb connected to an IoT device.
    -Real-time Firebase Sync: The app communication directly with Firebase Realtime Database for instant updates.
    -Built entirely using Kodular: No coding required drag and drop logic.
Technologies Used:
. Kodular Creator - For building the Android app
. Firebase Realtime Database - For storing sensors values and light status.
. IoT Hardware - Raspberry pi with Ultrasonic sensor.
. Intrent Connectivity - For live communication.
Firebase Data Structure:
project1
 ├── lightStatus: "0"
 └── sensorData1
       └── Eggtray: "Empty"
How It Works:
1. IoT device reads egg tray sensor value.
2. Sensor value is pushed to Firebase under sensorData1.
3. Kodular app reads this value and displays Empty.
4. When user presses ON or OFF, the app updates lightStatus.
5. IoT device reads lightStatus and turns the bulb ON or OFF.



