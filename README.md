# Flutter BLE Messaging Demo


Peer-to-peer messaging between smartphones using Bluetooth Low Energy (BLE).

Offline communication without internet. Includes chunked transfer and message framing protocol.

A simple peer-to-peer messaging demo using Bluetooth Low Energy (BLE).

Two smartphones can connect directly and exchange messages without internet.

This project demonstrates a basic BLE transport layer that can be used for offline messaging, device communication, or mesh networking experiments.

---

## Features

• BLE peer-to-peer communication
• Chunked message transfer
• Message framing protocol (4-byte length + JSON)
• Automatic message reassembly
• Huawei device compatibility workaround
• Flutter + Android BLE implementation

---

## Demo APK

Download and install the demo application:

`demo/ble_chat_demo.apk`

Install the APK on two phones and start a BLE connection.

---

## Screenshots

![scan](screenshots/scan.png)

![chat](screenshots/chat.png)

---

## How it works

One device acts as **BLE Central** and scans for devices.

The other device acts as **BLE Peripheral (GATT server)**.

Messages are transferred using:

• chunked BLE writes
• a framing protocol (4-byte message length)
• notify stream reassembly

This allows sending messages larger than the BLE packet size.

---

## Possible Use Cases

• offline messaging
• BLE device communication
• mesh networking experiments
• IoT prototypes
• peer-to-peer data exchange

---

## Source Code

The full source code of this project is available for purchase.

It includes:

• Flutter BLE transport implementation
• Android GATT server
• message framing protocol
• chunked BLE transfer
• working demo application

Buy the source code here:

➡️ **[LINK TO PURCHASE]**

After purchase you will receive access to the private repository.

---

## License

This repository contains the demo application only.

The full source code is available under a commercial license.
