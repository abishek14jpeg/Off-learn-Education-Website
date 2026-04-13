# Off-learn - Smart Education Website (ESP32 Powered)

Off-learn is an ESP32-based education platform that serves a web application directly from embedded hardware.  
It combines IoT, embedded systems, and web technologies to provide learning content over a local network.

## Overview

This project uses an ESP32 as a web server and file host for educational resources such as HTML pages, PDFs, audio, and documents.

## Features

- Website hosted directly on ESP32
- Works on local Wi-Fi (ESP32 SoftAP mode)
- Dashboard/library-style educational content interface
- Static frontend built with HTML, CSS, and JavaScript
- File handling through SD card storage

## Tech Stack

### Hardware
- ESP32
- SD card module/storage

### Software
- Arduino IDE
- Arduino C/C++
- HTML5
- CSS3
- JavaScript

### Main ESP32 Libraries
- `WiFi.h`
- `WebServer.h`
- `SPI.h`
- `SD.h`
- `DNSServer.h`

## Project Structure

- `off-learn-esp32 (1)/off-learn-esp32/off-learn_server/` - ESP32 firmware (`.ino`)
- `off-learn-esp32 (1)/off-learn-esp32/public/` - website frontend files
- `off-learn-esp32 (1)/off-learn-esp32/sdcard_content/` - content and SD card data layout

## How It Works

1. ESP32 starts in SoftAP mode.
2. A web server runs on port `80`.
3. Content is read from SD card storage.
4. Users connect to the ESP32 network and open the web interface.

## Contributors

- **ABISHEK K G** (23BCE1739)
- **AKSHITH SRINIVAS** (23BCE5078)
- **SANDRAZEN S** (23BCE1603)
- **ARJJITHA**
