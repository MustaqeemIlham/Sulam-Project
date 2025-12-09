# Sulam-Project
Budi@larm is a flood-alert mobile application developed under the SULAM initiative to support the community of Kampung Budiman. It connects with a Smart Flood Beacon device to provide real-time water level monitoring, alert notifications, emergency contact access, and navigation to nearby temporary shelters (PPS).

This project integrates IoT hardware, mobile app development, and community engagement to improve flood preparedness and public safety.


System Architecture:
The system integrates a Smart Flood Beacon IoT Device, which measures water levels and triggers a siren and light at Alert and Danger levels. The mobile app, developed in Flutter, retrieves real-time data from the cloud (Firebase/Firestore) and displays alerts, notifications, and navigation options. The cloud backend stores sensor data, processes threshold alerts, and sends push notifications to the app.

Technology Stack:
The mobile application is built using Flutter and Dart, and it integrates Firebase/Firestore for cloud storage and Google Maps API for navigation. The IoT beacon uses a Raspberry Pi 4, Aqara and Tuya water sensors, a Zigbee coordinator, and a solar panel for power supply. Custom alert sirens and lamps are included for immediate visual and audio notifications.
