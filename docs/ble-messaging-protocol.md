# BLE Messaging Protocol

This project uses a simple BLE messaging protocol for transferring
messages between smartphones.

Protocol structure:

4-byte message length (big-endian)
JSON payload

Example:

[ length ][ JSON message ]

Messages are split into BLE chunks and reassembled on the receiver side.

Used in:

Flutter BLE Messaging Demo
https://github.com/pslergy/flutter-ble-messaging-demo