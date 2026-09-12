# Wearable Alert — Fall 2026

University of Oklahoma ECE Capstone Design

## Project
Wearable Alert is a watch-sized wearable safety device consolidating features from previous designs.

## Required Features
- Alarm button
- Fall detection
- Removal alert
- Blue/red connection-status LEDs
- Haptic feedback for alert acknowledgement
- Watch-sized physical size
- Belt-clip attachment
- 12-hour battery life
- USB or preferably wireless charging
- Queue events when outside Bluetooth range
- Continuous audio recording with 20-second pre/post audio transmitted via Bluetooth

## Repository Structure
- `firmware/` — ESP32/embedded software
- `backend/` — optional server software
- `frontend/` — optional interface
- `hardware/` — PCB, schematics, BOM
- `docs/` — requirements, architecture, testing
- `previous-design/` — Spring 2026 reference material
- `tests/` — software/system tests

## Workflow
1. Create an issue.
2. Create a feature branch.
3. Implement and test.
4. Open a pull request.
5. Review with the team.
6. Merge into `main`.

Example:
`git checkout -b feature/fall-detection`

## Security
Never commit Wi-Fi passwords, API keys, AWS credentials, private certificates, or other secrets.

A mobile app is not automatically required by the Fall 2026 requirements.
