# Initial System Architecture

```text
Sensors / Buttons / Audio
          |
          v
     Device Drivers
          |
          v
      Event Manager
       /       \
      v         v
 Detection    Alert State
    Logic         |
       \        /
        v      v
       Event/Data Queue
              |
              v
       Bluetooth Manager
              |
              v
        Receiving System
```

This is an initial architecture, not the final design.

## Development Order
1. Button input
2. LED status
3. Haptic acknowledgement
4. IMU/sensor data
5. Fall-detection prototype
6. Removal detection
7. BLE connection
8. Event transmission
9. Offline event queue
10. Audio buffering
11. Pre/post-event audio
12. Full integration
13. Power optimization
