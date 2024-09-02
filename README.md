# Women Safety Device

## Overview

The Women Safety Device is a wearable safety solution designed to enhance personal security. It integrates a compact hardware device with a Flutter application to provide real-time emergency alerts, precise location tracking, and easy management of emergency contacts. This project aims to offer a rapid and reliable way to seek help in critical situations.

## Features

- *Instant SOS Alerts*: Activate an emergency alert with a press of a button.
- *Real-Time Location Tracking*: GPS module provides accurate location data in alerts.
- *Reliable Wireless Communication*: Uses RF modules for dependable signal transmission.
- *Direct SMS Notifications*: Sends emergency SMS with location details to predefined contacts.
- *User-Friendly Mobile Application*: Manage contacts, receive alerts, and view locations on a map.
- *Wearable Design*: Compact wristband for easy and discreet wear.

## Components

### Hardware

1. *Arduino Nano*
   - Central microcontroller for managing inputs and outputs.
2. *SIM900 GSM Modem*
   - Sends SMS alerts with location information.
3. *NEO6M GPS Module*
   - Provides real-time location data.
4. *433 MHz RF Transmitter and Receiver*
   - Enables wireless communication between the wearable band and receiver.
5. *SOS Button*
   - Triggers the emergency signal.
6. *Battery*
   - Powers the device.

### Software

1. *Arduino Code*
   - Handles SOS signal detection, GPS data retrieval, and SMS sending.
2. *Flutter Application*
   - Manages emergency contacts, receives alerts, and displays locations on a map.

## Installation

### Hardware Setup

1. *Transmitter Section (Wearable Band)*
   - Connect the SOS button to the RF Transmitter.
   - Power the RF Transmitter and SOS button with a suitable battery.
   - Assemble the transmitter into a wristband.

2. *Receiver Section*
   - Connect the RF Receiver to the Arduino Nano.
   - Connect the GSM Modem and GPS Module to the Arduino Nano.
   - Power all components with a battery.

### Software Setup

1. *Arduino Code*
   - Install the required libraries: TinyGPS++.h and SoftwareSerial.h.
   - Upload the provided Arduino sketch to the Arduino Nano.

2. *Flutter Application*
   - Clone the repository and install dependencies using Flutter.
   - Configure the app to receive alerts and display locations on a map.
   - Run the app on a mobile device.

## Usage

1. *Activating the Device*
   - Wear the wristband and ensure the device is powered on.
   - Press the SOS button to trigger an emergency alert.

2. *Receiving Alerts*
   - Emergency contacts will receive an SMS with the wearer’s location.
   - Use the Flutter application to view alerts and location details.

## Testing

1. *Hardware Testing*
   - Verify RF communication between the transmitter and receiver.
   - Test GPS accuracy and GSM SMS functionality.

2. *Software Testing*
   - Ensure Arduino code correctly detects the SOS signal and sends SMS.
   - Validate Flutter app functionality for receiving alerts and displaying locations.

3. *User Testing*
   - Conduct real-world trials to assess device performance and user experience.

## Deployment

1. *Assemble*: Finalize hardware assembly and packaging.
2. *Distribute*: Provide the device and mobile application to users.

## Maintenance

1. *Support*: Offer technical assistance and troubleshooting.
2. *Updates*: Release software updates based on user feedback and technological advancements.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

