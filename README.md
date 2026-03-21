# Flutter BLE Messaging Demo

Reliable peer-to-peer messaging between Android devices over Bluetooth Low Energy (BLE).

No internet. No backend. Just working device-to-device communication.

---

## Why this exists

BLE communication between smartphones is unreliable and painful to implement.

Common issues:
- GATT errors (133, timeouts)
- unstable connections
- device-specific behavior (especially Huawei)
- broken message delivery

This project demonstrates a **working solution** that handles these problems.

---

## What this demo shows

- two phones connect over BLE
- messages are sent and received in real time
- works across different Android vendors
- includes Huawei workaround (pull mode)

---

## Features

• BLE peer-to-peer communication  
• Chunked message transfer  
• 4-byte length + JSON framing protocol  
• Automatic message reassembly  
• GATT operation queue (fixes GATT_BUSY / 133)  
• Auto-reconnect logic  
• Huawei compatibility mode (pull instead of push)  

---

## Demo APK

Download the demo application:

➡️ https://github.com/pslergy/flutter-ble-messaging-demo/releases

Install on two devices and test BLE messaging locally.

---

## Screenshots

![scan](screenshots/scan.png)  
![chat](screenshots/chat.png)

---

## Used in

This transport is used in:

**Memento Mori Mesh Messenger**  
https://github.com/pslergy/memento-mori-app

---

## Use Cases

- offline messaging
- IoT communication
- mesh networking experiments
- peer-to-peer data exchange

---

## Who is this for

- mobile developers working with BLE
- startups building offline or mesh apps
- IoT developers needing direct device communication
- engineers tired of fighting BLE instability
---

## Full Source Code (Paid)

Production-ready implementation used in real-world scenarios.

### Includes:

- complete Flutter BLE transport layer  
- robust connection manager (auto-reconnect, backoff)  
- native Android GATT server + advertising  
- stable message protocol with chunking  
- Huawei-specific reliability fixes  
- ready-to-use demo app  

### Integration time

~10–15 minutes

---

## Proof

- tested on Samsung and Huawei devices
- handles real BLE edge cases (GATT 133, timeouts)
- stable message delivery across devices
---

## Purchase

**Price:** $399

👉 Buy now (ГUsdt TRC 20): TBXUd9XyFYfZE9m3BdJ76659As5dm8DdKD


After payment, I kindly ask you to save time - write your nickname in Github, I will add you to the private repository.

Alternatively:

📩 Email: pslergy@gmail.com

---

## License

This repository contains demo binaries and documentation only.

The full source code is distributed under a commercial license.
