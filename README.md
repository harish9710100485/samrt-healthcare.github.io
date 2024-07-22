 # Smart Health Monitoring SystemHealth monitoring is the major problem in today's world. Due to lack of proper health monitoring, patient suffer from serious health issues. There are lots of lot devices new days to monitue the health of patientover internet. Health experts are also taking advantage of these smart devices to keep an eye on their patients. With tons of new healthcare technology start-ups, tot is rapidly revolutionizing the healthcare industry Here in this project, we will make an IoT based Health Monitoring System which records the patient heart best rate and bodytemperature and also send an email alert whenever those readings goesbeyond critical values. Hence the lack of assistance for elderly people in home has been reduced now a days due to the social change. Also theregular health checkup has became difficult due to covid19 situations. This project is focused upon giving an health care assistance from homefor the people who are not able to give a regular visit to doctors and forthose people who were bed ridden. Node MCU is a microcontroller unitthat will get the dat from all the input sensor and will transfer all the data in the cloud platform. Pulse rate and body temperature readings arerecorded over Ubidots so that patient health can be monitored from anywhere in the world over internet. A panic will also be attached so that parient can press it on emergency to send email/sms to their relatives.

## Features

* Real-time monitoring of patients
* Customizable monitoring dashboard for doctors and health professionals with a user-friendly interface
* Secure login page for authorized access to patient data and monitoring dashboard
* Patient data analytics and visualization for trend analysis and forecasting
* Remote patient monitoring capabilities for home healthcare services
* Utilizes Node MCU, an affordable and compact IoT device, for easy and efficient data collection and transmission.

## Technologies Used

* ReactJS
* NodeJS
* ExpressJS
* MongoDB
* WebSockets
* Node Mcu
* Python (used in Node MCU to collect and transmit sensor data)

## Screenshots

![Login Page](./assets/SHMS_Login.png)
*Figure 1: Login Page*

![Monitoring Dashboard](./assets/SHMS_Dashboard_Online.png)
*Figure 2: Monitoring Dashboard*

![IoT Device Setup](./assets/SHMS_IoT_Device_Setup.png)
*Figure 3: IoT Device Setup*

![Server PM2 Overview](./assets/SHMS_Server_PM2_Overview.png)
*Figure 4: Server PM2 Overview*

## Installation & Testing

1. Clone the repository
```
git clone https://github.com/username/smart-health-monitoring-system.git
```

2. Navigate to the project directory
```
cd smart-health-monitoring-system
```

3. Navigate to dashboard directory, install the dependencies & start the frontend
```
cd dashboard && npm install && npm start
```

4. Navigate to server directory, install the dependencies & start the backend
```
cd ../server && npm install && npm start
```

5. For testing purposes you can run the `mockSensor.js` script to feed data into the system
```
cd ../iot-device && node mockSensor.js
```

