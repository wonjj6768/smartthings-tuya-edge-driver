# SmartThings Edge Driver Supported Devices

> Last Updated: 2025-12-14

This repository contains SmartThings Edge drivers supporting various Zigbee, LAN (Xiaomi/Mijia), and Matter devices.

# Zigbee Devices

## Neo NAS-TH01 Sensor
**Driver Name**: `Neo NAS-TH01 Sensor`

**Fingerprint**:
```
manufacturer: _TZ3000_qaaysllp
model: TS0201
```
**Features**: Temperature, Humidity, Illuminance Measurement, Battery

## _TZ3218_t9ynfz4x
**Driver Name**: `_TZ3218_t9ynfz4x`

**Fingerprints**:
```
manufacturer: _TZ3218_awarhusb / model: TS0225
manufacturer: _TZ3218_t9ynfz4x / model: TS0225
```
**Features**: Presence Detection, Illuminance Measurement, Detection Distance

**Settings**: Motion Distance, Motion Sensitivity, Static Sensitivity, Fading Time, LED Presence Indicator

## _TZE284_iadro9bf
**Driver Name**: `_TZE284_iadro9bf`

**Fingerprint**:
```
manufacturer: _TZE284_iadro9bf
model: TS0601
```
**Features**: Presence Detection, Illuminance Measurement, Detection Distance

**Settings**: Radar Sensitivity, Minimum Detection Range, Maximum Detection Range, Detection Delay, Fading Time

## ZG-204ZE Motion Sensor
**Driver Name**: `ZG-204ZE Motion Sensor`

**Fingerprints**:
```
manufacturer: ZG-204ZE / model: CK-BL702-MWS-01(7016)
manufacturer: HOBEIAN / model: ZG-204ZE
manufacturer: ZG-204ZE / model: ZG-204ZE
```
**Features**: Motion Detection, Battery

**Settings**: Detection Sensitivity, Motion Keep Time, LED Indicator

## Tuya ZG-204ZM Presence Sensor
**Driver Name**: `Tuya ZG-204ZM Presence Sensor`

**Fingerprints**:
```
manufacturer: _TZE200_kb5noeto / model: TS0601
manufacturer: _TZE200_2aaelwxk / model: TS0601
manufacturer: _TZE200_tyffvoij / model: TS0601
manufacturer: _TZE200_yflzeeqj / model: TS0601
manufacturer: Tuya / model: ZG-204ZM
manufacturer: _TZE200_2aaelwxk / model: ZG-204ZM
manufacturer: ZG-204ZM / model: _TZE200_2aaelwxk
manufacturer: _TZE200_kb5noeto / model: ZG-204ZM
manufacturer: ZG-204ZM / model: _TZE200_kb5noeto
manufacturer: _TZE200_tyffvoij / model: ZG-204ZM
manufacturer: ZG-204ZM / model: _TZE200_tyffvoij
manufacturer: _TZE200_yflzeeqj / model: ZG-204ZM
manufacturer: ZG-204ZM / model: _TZE200_yflzeeqj
manufacturer: HOBEIAN / model: ZG-204ZM
manufacturer: HOBEIAN / model: TS0601
manufacturer: HOBEIAN / model: _TZE200_2aaelwxk
manufacturer: HOBEIAN / model: _TZE200_kb5noeto
manufacturer: HOBEIAN / model: _TZE200_tyffvoij
manufacturer: HOBEIAN / model: _TZE200_yflzeeqj
```
**Features**: Presence Detection, Battery, Illuminance Measurement, PIR+Radar

**Settings**: Motion Detection Mode, Motion Detection Sensitivity, Stationary Detection Sensitivity, Far Detection Distance, Presence Keep Time, Indicator LED

## ZG-204ZV Motion Sensor
**Driver Name**: `ZG-204ZV Motion Sensor`

**Fingerprints**:
```
manufacturer: HOBEIAN / model: ZG-204ZV
manufacturer: _TZE200_uli8wasj / model: TS0601
manufacturer: _TZE200_uli8wasj / model: ZG-204ZV
manufacturer: ZG-204ZV / model: _TZE200_uli8wasj
manufacturer: _TZE200_grgol3xp / model: TS0601
manufacturer: _TZE200_grgol3xp / model: ZG-204ZV
manufacturer: ZG-204ZV / model: _TZE200_grgol3xp
manufacturer: _TZE200_rhgsbacq / model: TS0601
manufacturer: _TZE200_rhgsbacq / model: ZG-204ZV
manufacturer: ZG-204ZV / model: _TZE200_rhgsbacq
manufacturer: _TZE200_y8jijhba / model: TS0601
manufacturer: _TZE200_y8jijhba / model: ZG-204ZV
manufacturer: ZG-204ZV / model: _TZE200_y8jijhba
```
**Features**: Motion Detection, Battery, Temperature, Humidity, Illuminance Measurement

**Settings**: Detection Sensitivity, Motion Keep Time, Humidity Offset, Temperature Offset, Illuminance Interval, LED Indicator

## Tuya Soil Sensor
**Driver Name**: `Tuya Soil Sensor`

**Fingerprint**:
```
manufacturer: _TZE284_aao3yzhs
model: TS0601
```
**Features**: Temperature, Soil Moisture, Battery

## Tuya ZG-303Z Soil Sensor
**Driver Name**: `Tuya ZG-303Z Soil Sensor`

**Fingerprints**:
```
manufacturer: HOBEIAN / model: ZG-303Z
manufacturer: _TZE200_wqashyqo / model: TS0601
manufacturer: COOLO / model: CS-201Z
manufacturer: _TZE200_npj9bug3 / model: TS0601
manufacturer: _TZE200_wrmhp6b3 / model: TS0601
```
**Features**: Temperature, Humidity, Soil Moisture, Battery

**Settings**: Soil Moisture Calibration, Temperature Calibration, Air Humidity Calibration, Air Sampling Interval, Soil Sampling Interval

## Tuya Fingerbot v3
**Driver Name**: `Tuya Fingerbot v3`

**Fingerprints**:
```
manufacturer: _TZ3210_dse8ogfy / model: TS0001
manufacturer: _TZ3210_j4pdtz9v / model: TS0001
manufacturer: _TZ3210_cm9mbpr1 / model: TS0001
manufacturer: _TZ3210_a04acm9s / model: TS0001
```
**Features**: Switch Control, Battery, Fingerbot Mode, Movement Range, Delay Settings, Advanced Settings

# LAN Devices (Xiaomi/Mijia)

> These devices use Xiaomi LAN protocol (miIO or MIoT). IP Address and Token are required for connection.

## Qingping Air Monitor Lite
**Driver Name**: `Qingping Air Monitor Lite`

**Model**: `cgllc.airm.cgd1st` (Qingping Air Monitor Lite)

**Protocol**: MIoT

**Features**: Temperature, Humidity, PM2.5, PM10, CO2, Battery

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Smartmi Evaporative Humidifier 2
**Driver Name**: `Zhimi Smart Humidifier CB2`

**Model**: `zhimi.humidifier.cb2` (Smartmi Evaporative Humidifier 2)

**Protocol**: miIO

**Features**: Switch, Temperature, Humidity, Mute, Target Humidity, Operation Mode, Water Level, Water Tank Status, Dry Mode

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Qingping (ClearGrass) Air Monitor S1
**Driver Name**: `cgllc-airmonitor-s1`

**Model**: `cgllc.airmonitor.s1` (Qingping Air Monitor S1 / ClearGrass CGS1)

**Protocol**: miIO

**Features**: Temperature, Humidity, PM2.5, CO2, TVOC, Battery

**Settings**: IP Address, Token, Polling Interval, Create Device

---

# Matter Devices

## MOES Matter Plug
**Driver Name**: `MOES Matter Plug`

**Fingerprint**:
```
vendorId: 0x147D (5245)
productId: 0x958 (2392)
```
**Features**: Switch Control, Power Meter, Energy Meter, Voltage Measurement, Current Measurement

# 📥 Driver Installation

You can install the SmartThings driver using the link below:

**Driver Invitation Link**: https://bestow-regional.api.smartthings.com/invite/OzMgVZvVpDj9
