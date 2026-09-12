# Software Test Plan

## Button
- Detect alarm-button press.
- Test repeated presses.
- Minimize false triggers.

## Fall Detection
- Test normal movement.
- Test controlled fall-like conditions.
- Record false positives/negatives.

## Bluetooth
- Verify connection.
- Verify event transmission.
- Disconnect and reconnect.
- Verify queued events are sent after reconnection.

## Audio
- Verify continuous recording.
- Verify pre-event audio.
- Verify post-event audio.
- Verify transmission.

## Power
- Measure operating current.
- Test battery runtime.
- Test low-battery behavior.

| Test | Expected Result | Actual Result | Status | Date |
|---|---|---|---|---|
| Button | Event generated | | | |
| BLE | Connection established | | | |
| Queue | Data retained offline | | | |
| Audio | Pre/post audio retained | | | |
| Battery | >= 12-hour target | | | |
