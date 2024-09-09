ESP32 Wi-Fi Provisioning via BLE
     This project demonstrates how to set up Wi-Fi provisioning via Bluetooth Low Energy (BLE) on the ESP32. The Wi-Fi provisioning service allows you to configure Wi-Fi credentials over BLE, making it easier to connect your ESP32 to Wi-Fi networks without hard-coding credentials in your code.

Overview
     Objective: Connect an ESP32 to a Wi-Fi network using BLE for provisioning.

How It Works:
     1.You connect to the ESP32 via BLE (using a smartphone app or custom BLE app).
     2.You enter and send the SSID and password of the desired Wi-Fi network.
     3.The ESP32 connects to the network using the provided credentials.

Getting Started
     1.Install the Wi-Fi Provisioning App:
     2.Use the Wi-Fi Provisioning App for Android or iOS to send credentials to the ESP32 via BLE.
     3.Upload the Code to ESP32:
     4.Use the provided code in your IDE.
     5.Make sure you have the necessary ESP-IDF components installed.
     6.Test the Provisioning:
     7.Follow the instructions in the app to provision your ESP32 with Wi-Fi credentials.