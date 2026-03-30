<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:000000,100:ffffff&section=header&text=SLAYER%20KEY%20PANEL&fontSize=44&fontAlign=50&fontAlignY=38&fontColor=ffffff&animation=fadeIn&desc=Private%20key%20management%20system&descAlign=50&descAlignY=58" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&duration=2600&pause=900&color=FFFFFF&center=true&vCenter=true&width=900&lines=Private+key+management+system;Device+binding+and+expiration+control;Direct+API+validation;Full+license+administration+panel" />

<br>

<img src="https://img.shields.io/badge/status-online-white?style=for-the-badge&labelColor=000000&color=ffffff">
<img src="https://img.shields.io/badge/private-system-white?style=for-the-badge&labelColor=000000&color=ffffff">
<img src="https://img.shields.io/badge/device-lock-white?style=for-the-badge&labelColor=000000&color=ffffff">
<img src="https://img.shields.io/badge/api-ready-white?style=for-the-badge&labelColor=000000&color=ffffff">

<br><br>

<img src="https://komarev.com/ghpvc/?username=kenodev7&label=Profile%20Views&color=ffffff&style=flat-square" />

</div>

---

## About Project

**SLAYER KEY PANEL** is a private system built to create, validate, and manage keys in one place.

It keeps full control of each license with creation date, expiration tracking, remaining days, direct API validation, and device binding limited to a single device.

---

## Core Features

- Key generation in the format `SLAYER-000001`
- Direct validation through API
- Lock for only **1 device**
- Creation date tracking
- Remaining days display
- Expiration control
- Activate and disable key
- Remove key permanently
- Reset linked device
- Add more days to a key
- Private admin panel with login
- Profile photo support inside panel

---

## Panel Access

The admin panel centralizes the full management of the system.

Inside it you can:

- create new keys
- validate existing keys
- remove keys
- add more days
- reset device binding
- activate or disable access
- edit owner information

---

## Validation Flow

```text
1. A new key is created
2. The system stores the creation date
3. An expiration period is defined
4. On first validation, the key is linked to the device
5. Future requests only work on the same device
6. If expired or disabled, access is denied
