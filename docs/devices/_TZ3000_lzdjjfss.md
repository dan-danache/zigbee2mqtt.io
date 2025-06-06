---
title: "iHseno _TZ3000_lzdjjfss control via MQTT"
description: "Integrate your iHseno _TZ3000_lzdjjfss via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2025-06-01T17:54:42
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# iHseno _TZ3000_lzdjjfss

|     |     |
|-----|-----|
| Model | _TZ3000_lzdjjfss  |
| Vendor  | [iHseno](/supported-devices/#v=iHseno)  |
| Description | Vibration sensor |
| Exposes | battery, voltage, vibration, sensitivity |
| Picture | ![iHseno _TZ3000_lzdjjfss](https://www.zigbee2mqtt.io/images/devices/_TZ3000_lzdjjfss.png) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->


<!-- Notes END: Do not edit below this line -->



## Options
*[How to use device type specific configuration](../guide/configuration/devices-groups.md#specific-device-options)*

* `vibration_timeout`: Time in seconds after which vibration is cleared after detecting it (default 90 seconds). The value must be a number with a minimum value of `0`


## Exposes

### Battery (numeric)
Remaining battery in %, can take up to 24 hours before reported.
Value can be found in the published state on the `battery` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `100`.
The unit of this value is `%`.

### Voltage (numeric)
Voltage of the battery in millivolts.
Value can be found in the published state on the `voltage` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `mV`.

### Vibration (binary)
Indicates whether the device detected vibration.
Value can be found in the published state on the `vibration` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` vibration is ON, if `false` OFF.

### Sensitivity (numeric)
Sensitivity of the sensor (0 = highest sensitivity, 50 = lowest sensitivity). Press button on the device right before changing this.
Value can be found in the published state on the `sensitivity` property.
It's not possible to read (`/get`) this value.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"sensitivity": NEW_VALUE}`.
The minimal value is `0` and the maximum value is `50`.

