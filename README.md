Auto-SOS-Smart-post-accident-detection-and-response-system

Our team secured first prize in the IoT track at Techavishkar 2.0 Hackathon held at ATME College of Engineering , Mysore held on 15th-16th May 2025. Our Project AutoSOS, aims to reduce the delay in providing help to the individuals who are injured in an accident, providing emergency help to them by providing green corridor to emergency services.

Our project was divided into 4 subsytems

1\. Vehicle Subsytem

*   Detects Crash.
    
*   Display a timer to cancel false triggers.
    
*   If no response is captured, the dashcam captures images and alerts family members.
    
*   The GPS module fetches the loaction.
    

2\. SOS System

*   Sends notification about the crash, crash site to emergency contacts, police and Ambulance services.
    
*   Includes a 2 minute window to reject for ambulance request.
    

3\. Ambulance Subsytem

*   Receives the request information.
    
*   Communicates the emergency information to traffic signal via NRF24L transceiver module.
    

4\. Traffic Signal Subsystem

*   Receives signal from ambulance via NRF24L module
    
*   Communicates the emergency information to traffic signal via NRF24L transceiver module.
    
*   Sets green corridor to ambulance path.
    
*   Restores after passage of ambulance.
    

Tech Stack

*   ESP32 and ESP32 Cam
    
*   NRF24L01 Transceiver module
    
*   Neo 6M GPS module
    
*   MQTT based HiveMQ cloud broker
    
*   Node RED Dashboard
