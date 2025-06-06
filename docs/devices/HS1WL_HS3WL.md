---
title: "Heiman HS1WL/HS3WL control via MQTT"
description: "Integrate your Heiman HS1WL/HS3WL via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2019-07-22T20:08:17Z
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# Heiman HS1WL/HS3WL

|     |     |
|-----|-----|
| Model | HS1WL/HS3WL  |
| Vendor  | [Heiman](/supported-devices/#v=Heiman)  |
| Description | Water leakage sensor |
| Exposes | water_leak, battery_low, tamper, battery |
| Picture | ![Heiman HS1WL/HS3WL](https://www.zigbee2mqtt.io/images/devices/HS1WL-HS3WL.png) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->
## Notes

### Pairing
Push the reset button of the device with a paperclip for 5 seconds close to the coordinator. While pairing the LED on the front is flashing green. Once the pairing is finished, the LED stays off.
<!-- Notes END: Do not edit below this line -->




## Exposes

### Water leak (binary)
Indicates whether the device detected a water leak.
Value can be found in the published state on the `water_leak` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` water leak is ON, if `false` OFF.

### Battery low (binary)
Indicates if the battery of this device is almost empty.
Value can be found in the published state on the `battery_low` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` battery low is ON, if `false` OFF.

### Tamper (binary)
Indicates whether the device is tampered.
Value can be found in the published state on the `tamper` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` tamper is ON, if `false` OFF.

### Battery (numeric)
Remaining battery in %, can take up to 24 hours before reported.
Value can be found in the published state on the `battery` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `100`.
The unit of this value is `%`.

