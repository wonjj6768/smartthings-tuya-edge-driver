# SmartThings Edge Driver Supported Devices

> Last Updated: 2026-03-06

This repository contains SmartThings Edge drivers supporting various Zigbee, LAN (miIO/MIoT), and Matter devices.

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

# LAN Devices (miIO/MIoT)

> These devices use LAN protocol (miIO or MIoT). IP Address and Token are required for connection.

## Qingping Air Monitor Lite2
**Driver Name**: `Qingping Air Monitor Lite2`

**Model**: `cgllc-airm-cgd1st` (Qingping Air Monitor Lite)

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

## Deerma Humidifier JSQ
**Driver Name**: `Deerma Humidifier JSQ`

**Model**: `deerma.humidifier.jsq` (Deerma Humidifier JSQ)

**Protocol**: miIO

**Features**: Switch, Temperature, Humidity, Target Humidity, Operation Mode, Water Tank Status

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Philips Smart Desk Lamp
**Driver Name**: `Philips Smart Desk Lamp`

**Model**: `philips.light.sread1` (Philips Smart Desk Lamp)

**Protocol**: miIO

**Features**: Switch, Brightness Control

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Zhimi Humidifier CA1
**Driver Name**: `Zhimi Humidifier CA1`

**Model**: `zhimi.humidifier.ca1` (Zhimi Humidifier CA1)

**Protocol**: miIO

**Features**: Switch, Temperature, Humidity, Mute, Target Humidity, Operation Mode, Water Level, Water Tank Status, Dry Mode

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Deerma Humidifier JSQ2W
**Driver Name**: `Deerma Humidifier JSQ2W`

**Model**: `deerma-jsq2w` (Deerma Humidifier JSQ2W)

**Protocol**: MIoT

**Features**: Switch, Temperature, Humidity, Fan Level, Target Humidity, Mode, Alarm, Light, Water Tank Status, Device Status, Over-wet Protection

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Dmaker Dehumidifier 22L
**Driver Name**: `Dmaker Dehumidifier 22L`

**Model**: `dmaker-22l` (Dmaker Dehumidifier 22L)

**Protocol**: MIoT

**Features**: Switch, Temperature, Humidity, Mode, Target Humidity, Fault Status, Alarm, LED Control, Child Lock, Auto Dry, Dry Time Remaining, Warming Status

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Xiaomi Humidifier P800
**Driver Name**: `Xiaomi Humidifier P800`

**Model**: `xiaomi.humidifier.p800` (Xiaomi Humidifier P800)

**Protocol**: MIoT

**Features**: Switch, Temperature, Humidity, Mode, Target Humidity

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Yunmi Kettle V19
**Driver Name**: `Yunmi Kettle V19`

**Model**: `yunmi-v19` (Yunmi Kettle V19)

**Protocol**: MIoT

**Features**: Switch, Temperature, Mode, Status, Target Temperature, Keep Warm

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Zhimi Air Purifier MA4
**Driver Name**: `Zhimi Air Purifier MA4`

**Model**: `zhimi-airpurifier-ma4` (Zhimi Air Purifier MA4)

**Protocol**: MIoT

**Features**: Switch, Fan Mode, Fan Speed, Temperature, Humidity, PM2.5, Filter State

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Zhimi Air Purifier MB3
**Driver Name**: `Zhimi Air Purifier MB3`

**Model**: `zhimi-airpurifier-mb3` (Zhimi Air Purifier MB3)

**Protocol**: MIoT

**Features**: Switch, Purifier Mode, Fan Speed, Temperature, Humidity, PM2.5, Filter State

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Zhimi Air Purifier MB5
**Driver Name**: `Zhimi Air Purifier MB5`

**Model**: `zhimi-airpurifier-mb5` (Zhimi Air Purifier MB5)

**Protocol**: MIoT

**Features**: Switch, Fan Mode, Fan Speed, Temperature, Humidity, PM2.5, Filter State

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Zhimi Humidifier CA4
**Driver Name**: `Zhimi Humidifier CA4`

**Model**: `zhimi.humidifier.ca4` (Zhimi Humidifier CA4)

**Protocol**: MIoT

**Features**: Switch, Temperature, Humidity, Fan Mode, Target Humidity, Dry Mode, LED Brightness, Water Level

**Settings**: IP Address, Token, Polling Interval, Create Device

---

## Zhimi Humidifier CA6
**Driver Name**: `Zhimi Humidifier CA6`

**Model**: `zhimi-ca6` (Zhimi Humidifier CA6)

**Protocol**: MIoT

**Features**: Switch, Temperature, Humidity, Fan Mode, Target Humidity, Water Level, Dry Mode

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



# z2m 테스트 드라이버

https://bestow-regional.api.smartthings.com/invite/d4297OmXrQjo

## ef00-controls-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| LoraTap | SS9600ZB | buttons-button-6-battery |
| _TZ3210_3ulg9kpo | TS0021 | buttons-button-2-battery |
| _TZE200_2m38mh6k | TS0601 | buttons-button-6-battery |
| _TZE200_dhke3p9w | TS0601 | buttons-button-18 |
| _TZE200_mfamvsdb | TS0601 | buttons-button-4 |
| _TZE200_nojsjtj2 | TS0601 | security-remotes-sos-battery |
| _TZE200_vrcfo4i0 | TS0601 | security-remotes-sos-battery |
| _TZE284_2baujqot | TS0601 | security-remotes-sos-battery |
| _TZE284_5ys44kzo | TS0601 | buttons-button-6-battery |
| _TZE284_dhke3p9w | TS0601 | buttons-button-18 |
| _TZE284_nj7sfid2 | TS0601 | buttons-button-4 |

## ef00-covers-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| A-OK | AM25 | covers-cover |
| Alutech | AM/R-Sm | covers-cover |
| Binthen | BCM100D | covers-cover |
| Binthen | CV01A | covers-cover |
| HOBEIAN | ZG-301Z-MOTO | covers-cover |
| HUARUI | CMD900LE | covers-cover |
| Hiladuo | B09M3R35GC | covers-cover |
| Homeetec | 37022173 | covers-cover-switch-2 |
| Homeetec | 37022483 | covers-cover |
| Homeetec | 37022493 | covers-cover-switch-1 |
| Larkkey | ZSTY-SM-1SRZG-EU | covers-cover |
| Moes | AM43-0.45/40-ES-EB | covers-cover |
| Novato | WPK | covers-cover |
| Oz Smart Things | ZM85EL-1Z | covers-cover |
| Quoya | AT8510-TY | covers-cover |
| Roximo | CRTZ01 | covers-cover |
| Shaman | 25EB-1/30-TYZ | covers-cover |
| Somgoms | ZSTY-SM-1DMZG-US-W_1 | covers-cover |
| Tuya | DT82LEMA-1.2N | covers-cover |
| Tuya | M515EGZT | covers-cover |
| Tuya | MYQ-RM25-1.3/25-BZ | covers-cover |
| Tuya | ZD82TN | covers-cover |
| Yushun | YS-MT750 | covers-cover |
| Yushun | YS-MT750L | covers-cover |
| Zemismart | AM43 | covers-cover |
| Zemismart | M515EGB | covers-cover |
| Zemismart | ZM16EL-03/33 | covers-cover |
| Zemismart | ZM25EL | covers-cover |
| Zemismart | ZM79E-DT | covers-cover |
| Zemismart | ZM85EL-2Z | covers-cover |
| Zemismart | ZMS1-TYZ | covers-cover |
| _TZ3210_emqmwtym | TS0601 | covers-cover-battery-epj-zb |
| _TZE200_1fuxihti | TS0601 | covers-cover |
| _TZE200_1vxgqfba | TS0601 | covers-cover |
| _TZE200_2odrmqwq | TS0601 | covers-cover |
| _TZE200_2vfxweng | TS0601 | covers-cover |
| _TZE200_3i3exuay | TS0601 | covers-cover |
| _TZE200_4vobcgd3 | TS0601 | covers-cover |
| _TZE200_5nldle7w | TS0601 | covers-cover-switch-2 |
| _TZE200_5sbebbzs | TS0601 | covers-cover |
| _TZE200_5zbp6j0u | TS0601 | covers-cover |
| _TZE200_68nvbi09 | TS0601 | covers-cover |
| _TZE200_68nvbio9 | TS0601 | covers-cover |
| _TZE200_7eue9vhc | TS0601 | covers-cover |
| _TZE200_9p5xmj5r | TS0601 | covers-cover |
| _TZE200_9vpe3fl1 | TS0601 | covers-cover |
| _TZE200_a8z0g46u | TS0601 | covers-cover |
| _TZE200_ax8a8ahx | TS0601 | covers-cover-zm79e-dt |
| _TZE200_axgvo9jh | TS0601 | covers-cover |
| _TZE200_b2u1drdv | TS0601 | covers-cover |
| _TZE200_ba69l9ol | TS0601 | covers-cover |
| _TZE200_bdblidq3 | TS0601 | covers-cover |
| _TZE200_bqcqqjpb | TS0601 | covers-cover |
| _TZE200_bv1jcqqu | TS0601 | covers-cover |
| _TZE200_cf1sl3tj | TS0601 | covers-cover |
| _TZE200_clm4gdw4 | TS0601 | covers-cover |
| _TZE200_cowvfni3 | TS0601 | covers-cover |
| _TZE200_cpbo62rn | TS0601 | covers-cover |
| _TZE200_cxu0jkjk | TS0601 | covers-cover |
| _TZE200_dng9fn0k | TS0601 | covers-cover |
| _TZE200_eegnwoyw | TS0601 | covers-cover |
| _TZE200_eevqq1uv | TS0601 | covers-cover |
| _TZE200_eqpaxqdv | TS0601 | covers-cover-pims3028 |
| _TZE200_ergbiejo | TS0601 | covers-cover |
| _TZE200_fctwhugx | TS0601 | covers-cover |
| _TZE200_fdtjuw7u | TS0601 | covers-cover |
| _TZE200_feolm6rk | TS0601 | covers-cover |
| _TZE200_fodv6bkr | TS0601 | covers-cover-battery-rm28-le |
| _TZE200_fzo2pocs | TS0601 | covers-cover |
| _TZE200_g5xqosu7 | TS0601 | covers-cover |
| _TZE200_gaj531w3 | TS0601 | covers-cover |
| _TZE200_gnw1rril | TS0601 | covers-cover |
| _TZE200_gubdgai2 | TS0601 | covers-cover |
| _TZE200_hojryzzd | TS0601 | covers-cover |
| _TZE200_hsgrhjpf | TS0601 | covers-cover |
| _TZE200_icka1clh | TS0601 | covers-cover |
| _TZE200_iossyxra | TS0601 | covers-cover |
| _TZE200_jhkttplm | TS0601 | covers-cover-switch-1 |
| _TZE200_libht6ua | TS0601 | covers-cover |
| _TZE200_m6lwazh9 | TS0601 | covers-cover |
| _TZE200_mlglxwp3 | TS0601 | covers-cover |
| _TZE200_nhyj64w2 | TS0601 | covers-cover |
| _TZE200_nkoabg8w | TS0601 | covers-cover |
| _TZE200_nogaemzt | TS0601 | covers-cover |
| _TZE200_nueqqe6k | TS0601 | covers-cover |
| _TZE200_nw1r9hp6 | TS0601 | covers-cover |
| _TZE200_ol5jlkkr | TS0601 | covers-cover |
| _TZE200_p2qzzazi | TS0601 | covers-cover |
| _TZE200_p6vz3wzt | TS0601 | covers-cover |
| _TZE200_pk0sfzvr | TS0601 | covers-cover |
| _TZE200_pw7mji0l | TS0601 | covers-cover |
| _TZE200_rddyvrci | TS0601 | covers-cover |
| _TZE200_rmymn92d | TS0601 | covers-cover |
| _TZE200_sfqyhvpv | TS0601 | covers-cover |
| _TZE200_sq6affpe | TS0601 | covers-cover |
| _TZE200_swlgvdlh | TS0601 | covers-cover |
| _TZE200_tvrvdj6o | TS0601 | covers-cover |
| _TZE200_vdiuwbkq | TS0601 | covers-cover |
| _TZE200_vexa5o82 | TS0601 | covers-cover |
| _TZE200_wdfurkoa | TS0601 | covers-cover |
| _TZE200_wehza30a | TS0601 | covers-cover |
| _TZE200_wmcdj3aq | TS0601 | covers-cover |
| _TZE200_xaabybja | TS0601 | covers-cover |
| _TZE200_xuzcvlku | TS0601 | covers-cover |
| _TZE200_yenbr4om | TS0601 | covers-cover |
| _TZE200_zah67ekd | TS0601 | covers-cover |
| _TZE200_zpzndjez | TS0601 | covers-cover |
| _TZE200_zuz7f94z | TS0601 | covers-cover |
| _TZE200_zvo63cmo | TS0601 | covers-cover |
| _TZE200_zxxfv8wi | TS0601 | covers-cover |
| _TZE200_zyrdrmno | TS0601 | covers-cover-zb-sm |
| _TZE204_1fuxihti | TS0601 | covers-cover |
| _TZE204_2rvvqjoa | TS0601 | covers-cover-bx82-tyz1 |
| _TZE204_57hjqelq | TS0601 | covers-cover |
| _TZE204_a8z0g46u | TS0601 | covers-cover |
| _TZE204_bdblidq3 | TS0601 | covers-cover |
| _TZE204_ejh6owwz | TS0601 | covers-cover |
| _TZE204_g5xqosu7 | TS0601 | covers-cover |
| _TZE204_guvc7pdy | TS0601 | covers-cover |
| _TZE204_lh3arisb | TS0601 | covers-cover |
| _TZE204_p6vz3wzt | TS0601 | covers-cover |
| _TZE204_r0jdjrvi | TS0601 | covers-cover |
| _TZE204_trwaxi57 | TS0601 | covers-cover-switch-2 |
| _TZE204_vvvtcehj | TS0601 | covers-cover |
| _TZE204_xu4a5rhj | TS0601 | covers-cover |
| _TZE204_ycke4deo | TS0601 | covers-cover |
| _TZE204_zuq5xxib | TS0601 | covers-cover |
| _TZE210_inpjmc0h | TS0301 | covers-cover-2 |
| _TZE210_m6lwazh9 | TS0301 | covers-cover |
| _TZE284_1fuxihti | TS0601 | covers-cover |
| _TZE284_2gi1hy8s | TS0601 | covers-cover-battery-mb60l |
| _TZE284_3mzb0sdz | TS0601 | covers-cover |
| _TZE284_4vobcgd3 | TS0601 | covers-cover |
| _TZE284_6fopvb6v | TS0601 | covers-cover |
| _TZE284_clm4gdw4 | TS0601 | covers-cover |
| _TZE284_fzo2pocs | TS0601 | covers-cover |
| _TZE284_gaj531w3 | TS0601 | covers-cover |
| _TZE284_koxaopnk | TS0601 | covers-cover |
| _TZE284_libht6ua | TS0601 | covers-cover |
| _TZE284_r3szw0xr | TS0601 | covers-cover |
| _TZE284_uqfph8ah | TS0601 | covers-cover |
| _TZE284_waa352qv | TS0601 | covers-cover |
| _TZE284_wdfurkoa | TS0601 | covers-cover |
| _TZE600_ogyg1y6b | TS0105 | covers-cover |

## ef00-energy-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| HOCH | ZJSBL7-100Z | din-rail-switch-power-energy-voltage-current-rcbo |
| Hiking | DDS238-2 | din-rail-switch-power-energy-voltage-current-din1 |
| MatSee Plus | DAC2161C | din-rail-switch-power-energy-voltage-current-din2 |
| MatSee Plus | PC321-Z-TY | meters-power-energy-voltage-current-clamp3phase |
| Nous | D4Z | meters-power-energy-voltage-current-sdm01 |
| OWON | PC321-Z-TY | meters-power-energy-voltage-current-clamp3phase |
| Ourtop | ATMS100133Z | meters-power-energy-atms10013z3 |
| SUTON | STB3L-125/ZJ | din-rail-switch-power-energy-voltage-current |
| TNCE | RMDZB-1PNL63 | din-rail-switch-power-energy-voltage-current |
| Tongou | TOSA1-01WXJAT2A | meters-power-energy-voltage-current |
| Tongou | TOWSMR1-20A-AC | din-rail-switch-power-energy-voltage-current-toqjzt |
| Tongou | TOWSMR1-40A-A | din-rail-switch-power-energy-voltage-current-toqjzt |
| Tongou | TOWSMR1-40A-AC | din-rail-switch-power-energy-voltage-current-toqjzt |
| Tuya | PJ-1203-W | meters-power-energy-voltage-current |
| Tuya | RC-MCB | din-rail-switch-power-energy-voltage-current-din1 |
| WDYK | ZJSBL7-100Z | din-rail-switch-power-energy-voltage-current-rcbo |
| XOCA | DAC2161C | din-rail-switch-power-energy-voltage-current-din3 |
| _TZE200_78ioiaml | TS0601 | meters-power-energy-2phase-sdm02v1 |
| _TZE200_abatw3kj | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE200_bcusnqt8 | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE200_bkkmqmyo | TS0601 | din-rail-switch-power-energy-voltage-current-din1 |
| _TZE200_byzdayie | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE200_d2zfgtij | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE200_dikb3dp6 | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_eaac7dkw | TS0601 | din-rail-switch-power-energy-voltage-current-din1 |
| _TZE200_ewxhg6o9 | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE200_fsb6zw01 | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE200_gomuk3dc | TS0601 | meters-power-energy-voltage-current |
| _TZE200_hkdl5fmv | TS0601 | din-rail-switch-power-energy-voltage-current-rcbo |
| _TZE200_iwn0gpzz | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE200_lsanae15 | TS0601 | din-rail-switch-power-energy-voltage-current-din2 |
| _TZE200_nslr42tt | TS0601 | meters-power-energy-voltage-current-clamp3phase |
| _TZE200_ny94onlb | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_qhlxve78 | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE200_rhblgy0z | TS0601 | din-rail-switch-power-energy-voltage-current-din3 |
| _TZE200_rks0sgb7 | TS0601 | meters-power-energy-voltage-current-pc311 |
| _TZE200_s4sa1mcx | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_ugekduaj | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_v9hkz2yn | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_ves1ycwx | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_wbhaespm | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE200_wjk6rurm | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE200_x8diwkqb | TS0601 | meters-power-energy-2phase-sdm02v1 |
| _TZE200_x8fp01wi | TS0601 | switch-power-energy |
| _TZE204_432zhuwe | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE204_4bjixefp | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE204_78ioiaml | TS0601 | meters-power-energy-2phase-sdm02v1 |
| _TZE204_81yrt3lo | TS0601 | meters-power-energy-voltage-current-pj1203a |
| _TZE204_ac0fhfiq | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE204_bkkmqmyo | TS0601 | din-rail-switch-power-energy-voltage-current-din1 |
| _TZE204_byzdayie | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE204_cjbofhxw | TS0601 | meters-power-energy-voltage-current |
| _TZE204_d2zfgtij | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE204_dhotiauw | TS0601 | meters-power-energy-voltage-current-2ct |
| _TZE204_dikb3dp6 | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_fhvdgeuh | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE204_gomuk3dc | TS0601 | meters-power-energy-voltage-current |
| _TZE204_iwn0gpzz | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE204_jcwbwckh | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE204_kobbcyum | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE204_l6llgoxq | TS0601 | din-rail-switch-power-energy-voltage-current-din2 |
| _TZE204_loejka0i | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_lsanae15 | TS0601 | din-rail-switch-power-energy-voltage-current-din2 |
| _TZE204_m64smti7 | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE204_mrffaamu | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE204_ny94onlb | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_q22avxbv | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE204_qhlxve78 | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE204_rhblgy0z | TS0601 | din-rail-switch-power-energy-voltage-current-din3 |
| _TZE204_s4sa1mcx | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_tuhfx7tf | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE204_tzreobvu | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE204_ugekduaj | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_v9hkz2yn | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_ves1ycwx | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_wbhaespm | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE204_wjk6rurm | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE204_x8diwkqb | TS0601 | meters-power-energy-2phase-sdm02v1 |
| _TZE204_x8fp01wi | TS0601 | switch-power-energy |
| _TZE284_432zhuwe | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE284_4hdbt6rn | TS0601 | meters-power-energy-voltage-current |
| _TZE284_5m4nchbm | TS0601 | din-rail-switch-power-energy-voltage-current-leakage-protector |
| _TZE284_6ocnqlhn | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE284_78ioiaml | TS0601 | meters-power-energy-2phase-sdm02v1 |
| _TZE284_81yrt3lo | TS0601 | meters-power-energy-voltage-current-pj1203a |
| _TZE284_9xstqowh | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE284_a14rjslz | TS0601 | meters-power-energy-atms10013z3 |
| _TZE284_ac0fhfiq | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE284_cjbofhxw | TS0601 | meters-power-energy-voltage-current |
| _TZE284_d2zfgtij | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE284_dikb3dp6 | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_gomuk3dc | TS0601 | meters-power-energy-voltage-current |
| _TZE284_hecsejsb | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE284_iwn0gpzz | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE284_kobbcyum | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE284_loejka0i | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_mrffaamu | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE284_ny94onlb | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_pglpvdar | TS0601 | meters-power-energy-voltage-current |
| _TZE284_q22avxbv | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE284_qhlxve78 | TS0601 | meters-power-energy-voltage-current-bidirectional |
| _TZE284_s4sa1mcx | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_s5vuaadg | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE284_tuhfx7tf | TS0601 | din-rail-switch-power-energy-voltage-current-toqjzt |
| _TZE284_tzreobvu | TS0601 | din-rail-switch-power-energy-voltage-current-toqcb2 |
| _TZE284_v9hkz2yn | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_ves1ycwx | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_wbhaespm | TS0601 | din-rail-switch-power-energy-voltage-current |
| _TZE284_wjk6rurm | TS0601 | meters-power-energy-voltage-current-sdm01 |
| _TZE284_x8diwkqb | TS0601 | meters-power-energy-2phase-sdm02v1 |
| _TZE28C1000000_81yrt3lo | TS0601 | meters-power-energy-voltage-current-pj1203a |

## ef00-lights-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| Coswall | X99-G-kbFan-1g-ZG-LN-11 | fans-fan-level-light-switch |
| Earda | EDM-1ZAA-EU | lights-dimmer |
| Earda | EDM-1ZAB-EU | lights-dimmer |
| Earda | EDM-1ZBA-EU | lights-dimmer |
| ION Industries | 90.500.040 | lights-dimmer |
| ION Industries | 90.500.090 | lights-dimmer |
| ION Industries | ID200W-ZIGB | lights-dimmer |
| KnockautX | FMD2C018 | lights-dimmer-2 |
| Larkkey | ZSTY-SM-1DMZG-EU | lights-dimmer |
| Lerlink | T2-Z67/T2-W67 | fans-fan-light-switch |
| Lerlink | X706U | lights-dimmer |
| Liwokit | Fan+Light-01 | fans-fan-light-switch |
| Lonsonho | EDM-1ZBB-EU | lights-dimmer |
| Mercator Ikuü | SSWD01 | lights-dimmer |
| Mercator Ikuü | SSWM-DIMZ | lights-dimmer |
| Mercator Ikuü | SSWRM-ZB | lights-dimmer |
| Moes | EDM-1ZBB-EU | lights-dimmer |
| Moes | MS-105-M | lights-dimmer |
| Moes | MS-105B | lights-dimmer-2 |
| Moes | MS-105Z | lights-dimmer |
| Moes | WS-SY-EURD | lights-dimmer |
| Moes | WS-SY-EURD-WH-MS | lights-dimmer |
| Moes | ZM-105B-M | lights-dimmer-2 |
| Moes | ZS-EUD_1gang | lights-dimmer |
| Moes | ZS-EUD_2gang | lights-dimmer-2 |
| Moes | ZS-EUD_3gang | lights-dimmer-3 |
| Moes | ZS-SR-EUD-1 | lights-dimmer |
| Moes | ZS-SR-EUD-2 | lights-dimmer-2 |
| Moes | ZS-SR-EUD-3 | lights-dimmer-3 |
| Moes | ZS-USD | lights-dimmer |
| Zemismart | ZN2S-RS1E-FL / ZN2S-US1U-FL | fans-fan-level-light-switch |
| Zemismart | ZN2S-RS3E-DH | lights-dimmer-3 |
| Zemismart | ZN2S-US1-SD | lights-dimmer |
| _TZE200_0hb4rdnp | TS0601 | lights-dimmer |
| _TZE200_0nauxa0p | TS0601 | lights-dimmer |
| _TZE200_1agwnems | TS0601 | lights-dimmer |
| _TZE200_3p5ydos3 | TS0601 | lights-dimmer |
| _TZE200_4mh6tyyo | TS0601 | lights-dimmer |
| _TZE200_579lguh2 | TS0601 | lights-dimmer |
| _TZE200_86nbew0j | TS0601 | lights-dimmer |
| _TZE200_9cxuhakf | TS0601 | lights-dimmer |
| _TZE200_9i9dt8is | TS0601 | lights-dimmer |
| _TZE200_a0syesf5 | TS0601 | lights-dimmer |
| _TZE200_bxoo2swd | TS0601 | lights-dimmer-2 |
| _TZE200_ctq0k47x | TS0601 | lights-dimmer |
| _TZE200_dcnsggv | TS0601 | lights-dimmer |
| _TZE200_dcnsggvz | TS0601 | lights-dimmer |
| _TZE200_dfxkcots | TS0601 | lights-dimmer |
| _TZE200_drs6j6m5 | TS0601 | lights-dimmer |
| _TZE200_e3oitdyu | TS0601 | lights-dimmer-2 |
| _TZE200_ebwgzdqq | TS0601 | lights-dimmer |
| _TZE200_fjjbhx9d | TS0601 | lights-dimmer-2 |
| _TZE200_gne0e6mk | TS0601 | lights-dimmer |
| _TZE200_gwkapsoq | TS0601 | lights-dimmer-2 |
| _TZE200_hmqzfqml | TS0601 | fans-fan-light-switch |
| _TZE200_io0zdqh1 | TS0601 | lights-dimmer |
| _TZE200_ip2akl4w | TS0601 | lights-dimmer |
| _TZE200_itp8dt7f | TS0601 | lights-dimmer |
| _TZE200_la2c2uo9 | TS0601 | lights-dimmer |
| _TZE200_lawxy9e2 | TS0601 | fans-fan-light-switch |
| _TZE200_ojzhk75b | TS0601 | lights-dimmer |
| _TZE200_p0gzbqct | TS0601 | lights-dimmer |
| _TZE200_qanl25yu | TS0601 | fans-fan-light-switch |
| _TZE200_qyss8gjy | TS0601 | lights-dimmer |
| _TZE200_qzaing2g | TS0601 | lights-dimmer-power-voltage-current |
| _TZE200_r32ctezx | TS0601 | fans-switch-fan-mode-ef00 |
| _TZE200_swaamsoy | TS0601 | lights-dimmer |
| _TZE200_tgeqdjgk | TS0601 | lights-color-temperature |
| _TZE200_tsxpl0d0 | TS0601 | lights-dimmer-2 |
| _TZE200_vizxbhco | TS0601 | lights-dimmer-3 |
| _TZE200_vm1gyrso | TS0601 | lights-dimmer-3 |
| _TZE200_vucankjx | TS0601 | lights-dimmer |
| _TZE200_w4cryh2i | TS0601 | lights-dimmer |
| _TZE200_whpb9yts | TS0601 | lights-dimmer |
| _TZE200_ykgar0ow | TS0601 | lights-dimmer |
| _TZE200_ywe90lt0 | TS0601 | lights-dimmer |
| _TZE204_1v1dxkck | TS0601 | lights-dimmer-3 |
| _TZE204_2jnoy8dj | TS0601 | fans-fan-level-light-switch |
| _TZE204_68utemio | TS0601 | lights-dimmer |
| _TZE204_9qhuzgo0 | TS0601 | lights-dimmer |
| _TZE204_bql5khqx | TS0601 | fans-fan-level-light-switch |
| _TZE204_bxoo2swd | TS0601 | lights-dimmer-2 |
| _TZE204_dcnsggvz | TS0601 | lights-dimmer |
| _TZE204_hlx9tnzb | TS0601 | lights-dimmer |
| _TZE204_lawxy9e2 | TS0601 | fans-fan-light-switch |
| _TZE204_n9ctkb6j | TS0601 | lights-dimmer |
| _TZE204_r32ctezx | TS0601 | fans-switch-fan-mode-ef00 |
| _TZE204_vevc4c6g | TS0601 | lights-dimmer |
| _TZE204_zenj4lxv | TS0601 | lights-dimmer-2 |
| _TZE204_znvwzxkq | TS0601 | lights-dimmer-3 |
| _TZE284_68utemio | TS0601 | lights-dimmer |
| _TZE284_ikul00sx | TS0601 | fans-fan-level-light-dimmer |
| _TZE284_m1cvyneb | TS0601 | lights-dimmer |
| _TZE284_tgeqdjgk | TS0601 | lights-color-temperature |
| _TZE284_z5jz7wpo | TS0601 | fans-switch-fan-mode-ef00 |
| _TZE284_znvwzxkq | TS0601 | lights-dimmer-3 |

## ef00-motion-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| B3876M9 | ZP-301Z | safety-presence-zp301z-time-cycle-illuminance-battery |
| C6B7KM9 | Excellux | safety-presence-illuminance-battery |
| HOBEIAN | CK-BL702-MWS-01(7016) | safety-presence-zg205za-illuminance |
| HOBEIAN | ZG-204ZE | safety-presence-zg204ze-dedicated-illuminance-battery |
| HOBEIAN | ZG-204ZH | safety-presence-zg204zh-dedicated-mode-illuminance-temp-humidity-battery |
| HOBEIAN | ZG-204ZK | safety-presence-zg204zk-dedicated-illuminance-battery |
| HOBEIAN | ZG-204ZQ | safety-presence-zg204zq-illuminance-temp-humidity-battery |
| HOBEIAN | ZG-204ZV | safety-presence-zg204zv-dedicated-illuminance-temp-humidity-battery |
| HOBEIAN | ZG-204ZX | safety-presence-illuminance-temp-humidity-battery-zg204zx |
| HOBEIAN | ZG-302ZL | switches-presence-switch-3 |
| HOBEIAN | ZG-302ZM | switches-presence-switch-3 |
| Immax | 07527L | safety-motion-pir-illuminance-battery |
| Moes | ZSS-QY-HP | safety-presence-zym100l-fixed-illuminance |
| Nedis | ZBSM20WT | safety-motion-zg204zl-keep-illuminance-battery |
| Nova Digital | ZTS-MM | safety-presence-zy-hps01-illuminance |
| Novato | ZIS-04 | safety-presence-switch-illuminance |
| Tuya | ZY-M100-L | safety-presence-zym100l-fixed-illuminance |
| ZG-204ZE | CK-BL702-MWS-01(7016) | safety-presence-zg204ze-dedicated-illuminance-battery |
| ZGAF-205L | CK-BL702-MWS-01(7016) | safety-presence-zg205zl-illuminance |
| _TZ321C_4slreunp | TS0225 | safety-presence-mtd085-entry-range-illuminance |
| _TZ321C_fkzihax8 | TS0225 | safety-presence-mtd085-entry-range-illuminance |
| _TZE200_0u3bj3rc | TS0601 | safety-presence-basic |
| _TZE200_1ibpyhdc | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_2aaelwxk | TS0225 | safety-presence-zg204zm-dedicated-mode-illuminance-battery |
| _TZE200_2aaelwxk | TS0601 | safety-presence-zg204zm-dedicated-mode-illuminance-battery |
| _TZE200_3towulqd | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_4pm4pekt | TS0601 | safety-presence-zg204ze-dedicated-illuminance-battery |
| _TZE200_ahpcyzth | TS0601 | switches-presence-switch-3 |
| _TZE200_auin8mzr | TS0601 | safety-motion-legacy-illuminance |
| _TZE200_bfmfhxra | TS0601 | switches-presence-switch-3 |
| _TZE200_bh3n6gk8 | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_clrdrnya | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE200_cq8lu23i | TS0601 | safety-presence-zg204ze-dedicated-illuminance-battery |
| _TZE200_cqtamhh5 | TS0601 | switches-presence-switch-3 |
| _TZE200_crq3r3la | CK-BL702-MWS-01(7016) | safety-presence-zg205za-illuminance |
| _TZE200_crq3r3la | TS0225 | safety-presence-zg205za-illuminance |
| _TZE200_df04ghrb | TS0601 | switches-presence-switch-3 |
| _TZE200_f1pvdgoh | B | safety-motion-pir-illuminance-battery |
| _TZE200_f1pvdgoh | TS0601 | safety-motion-pir-illuminance-battery |
| _TZE200_ghynnvos | TS0601 | safety-motion-pir-illuminance |
| _TZE200_gjldowol | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_gkfbdvyx | TS0601 | safety-presence-zym10024gv3-move-range-illuminance |
| _TZE200_grgol3xp | TS0601 | safety-presence-zg204zv-dedicated-illuminance-temp-humidity-battery |
| _TZE200_hdih4foa | TS0601 | safety-presence-zg204zh-dedicated-mode-illuminance-temp-humidity-battery |
| _TZE200_hl0ss9oa | TS0225 | safety-presence-zg205zl-illuminance |
| _TZE200_holel4dk | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_hyhl5y36 | TS0601 | safety-presence-msa201-illuminance |
| _TZE200_ikvncluo | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_jkbljri7 | TS0601 | safety-presence-mir-fall-illuminance |
| _TZE200_juzago6i | TS0601 | safety-presence-pir24g-dedicated-illuminance-battery |
| _TZE200_jva8ink8 | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_jxyhl4eq | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_ka8l86iu | TS0601 | safety-presence-zg204zk-dedicated-illuminance-battery |
| _TZE200_kb5noeto | TS0601 | safety-presence-zg204zm-dedicated-mode-illuminance-battery |
| _TZE200_kccdzaeo | TS0601 | switches-presence-switch-3 |
| _TZE200_khzbklyh | TS0601 | switches-presence-switch-3 |
| _TZE200_kijxnb8q | TS0601 | switches-presence-switch-3 |
| _TZE200_llvwkkde | TS0601 | switches-presence-switch-3 |
| _TZE200_lu01t0zl | TS0601 | safety-presence-mir-fall-illuminance |
| _TZE200_lyetpprm | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_me6wtiqs | TS0601 | safety-motion-pir-illuminance-battery |
| _TZE200_mgxy2d9f | TS0601 | safety-motion-tamper-battery |
| _TZE200_mp902om5 | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE200_mx6u6l4y | TS0601 | safety-presence-basic |
| _TZE200_na5qlzow | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_oc7xqqbs | TS0601 | safety-motion-zpir10-illuminance-battery |
| _TZE200_p9zbdqgs | TS0601 | safety-presence-zg204zq-illuminance-temp-humidity-battery |
| _TZE200_ppuj1vem | TS0601 | safety-motion-zpir10-illuminance-battery |
| _TZE200_qasjif9e | TS0601 | safety-presence-zym100s2-range-delay-illuminance |
| _TZE200_qxyh4r7g | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_rhgsbacq | TS0601 | safety-presence-zg204zv-dedicated-illuminance-temp-humidity-battery |
| _TZE200_s6hzw8g2 | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_s7rsrtbg | TS0601 | switches-presence-switch-3 |
| _TZE200_sbyx0lm6 | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE200_seq9cm6u | TS0601 | safety-motion-bed-time-illuminance-battery |
| _TZE200_sgpeacqp | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_tmszbtzq | TS0601 | switches-presence-switch-3 |
| _TZE200_toeldckg | TS0601 | switches-presence-switch-3 |
| _TZE200_ttcovulf | TS0601 | safety-motion-zg204zl-keep-illuminance-battery |
| _TZE200_tyffvoij | TS0601 | safety-presence-zg204zm-dedicated-mode-illuminance-battery |
| _TZE200_uli8wasj | TS0601 | safety-presence-zg204zv-dedicated-illuminance-temp-humidity-battery |
| _TZE200_v6ossqfy | TS0601 | safety-presence-basic |
| _TZE200_vrfecyku | TS0601 | safety-presence-mir-fall-illuminance |
| _TZE200_vuqzj1ej | TS0601 | safety-presence-zg204zh-dedicated-mode-illuminance-temp-humidity-battery |
| _TZE200_w0ap83qu | TS0601 | safety-presence-illuminance-temp-humidity-battery-zg204zx |
| _TZE200_wukb7rhc | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_xlnzk169 | TS0601 | switches-presence-switch-3 |
| _TZE200_xpq2rzhq | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE200_y4mdop0b | TS0225 | safety-presence-zg205zl-illuminance |
| _TZE200_y8jijhba | TS0601 | safety-presence-zg204zv-dedicated-illuminance-temp-humidity-battery |
| _TZE200_ya4ft0w4 | TS0601 | safety-presence-zym10024gv3-move-range-illuminance |
| _TZE200_yflzeeqj | TS0601 | safety-presence-zg204zm-dedicated-mode-illuminance-battery |
| _TZE200_ypprdwsl | TS0601 | safety-presence-mir-fall-illuminance |
| _TZE200_zbfmvj13 | TS0601 | safety-presence-zg204zk-dedicated-illuminance-battery |
| _TZE200_ztc6ggyl | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE204_7gclukjs | TS0601 | safety-presence-zym10024gv2-move-range-illuminance |
| _TZE204_aai5grix | TS0601 | safety-presence-illuminance |
| _TZE204_bmdsp6bs | TS0601 | safety-presence-y1in-dedicated-illuminance |
| _TZE204_bvfld3xc | TS0601 | safety-presence-mir-fall-illuminance |
| _TZE204_clrdrnya | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE204_dapwryy7 | TS0601 | safety-presence-zg205z-illuminance |
| _TZE204_debczeci | TS0601 | safety-presence-basic-delay-battery |
| _TZE204_dtzziy1e | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE204_e5m9c5hl | TS0601 | safety-presence-zym100s1-range-delay-illuminance |
| _TZE204_e9ajs4ft | TS0601 | safety-presence-ctlr1-threshold-min-delay-illuminance |
| _TZE204_eaulras5 | TS0601 | safety-presence-illuminance |
| _TZE204_ex3rcdha | TS0601 | safety-presence-zy-hps01-illuminance |
| _TZE204_f2rflfa6 | TS0601 | safety-presence-switch-illuminance |
| _TZE204_fwondbzy | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE204_gkfbdvyx | TS0601 | safety-presence-zym10024gv3-move-range-illuminance |
| _TZE204_iadro9bf | TS0601 | safety-presence-zym100s2-range-delay-illuminance |
| _TZE204_iaeejhvf | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE204_ijxvkhd0 | TS0601 | safety-presence-zym10024g-move-threshold-min-illuminance |
| _TZE204_izy1g1mb | TS0601 | safety-presence-switch-illuminance |
| _TZE204_kyhbrfyl | TS0601 | safety-presence-range-illuminance |
| _TZE204_laokfqwu | TS0601 | safety-presence-wzm100-range-delay-illuminance |
| _TZE204_lbbg34rj | TS0601 | safety-presence-zy-hps01-illuminance |
| _TZE204_mhxn2jso | TS0601 | safety-presence-range-delay-illuminance |
| _TZE204_mtoaryre | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE204_muvkrjr5 | TS0601 | safety-presence |
| _TZE204_nbkshs6k | TS0601 | safety-presence-zym100s3-keep-illuminance |
| _TZE204_no6qtgtl | TS0601 | safety-presence-range-illuminance |
| _TZE204_oqtpvx51 | TS0601 | safety-presence-yxzbrb58-range-delay-scene-illuminance |
| _TZE204_pfayrzcw | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE204_qasjif9e | TS0601 | safety-presence-zym100s2-range-delay-illuminance |
| _TZE204_sbyx0lm6 | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE204_sooucan5 | TS0601 | safety-presence-yxzbrb58-range-delay-scene-illuminance |
| _TZE204_sxm7l9xa | TS0601 | safety-presence-zym100s1-range-delay-illuminance |
| _TZE204_uxllnywp | TS0601 | safety-presence-rtzcz03z-range-illuminance |
| _TZE204_xpq2rzhq | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE204_xsm7l9xa | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE204_ya4ft0w4 | TS0601 | safety-presence-zym10024gv3-move-range-illuminance |
| _TZE204_ztc6ggyl | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE204_ztqnh5cg | TS0601 | safety-presence-zym100s2-range-delay-illuminance |
| _TZE284_1lvln0x6 | TS0601 | safety-presence-basic-delay-battery |
| _TZE284_4qznlkbu | TS0601 | safety-presence-mtg075-entry-controls-illuminance |
| _TZE284_aai5grix | TS0601 | safety-presence-illuminance |
| _TZE284_ajuasrmx | TS0601 | safety-presence-msa201-illuminance |
| _TZE284_bw4ayyeh | TS0601 | safety-presence-illuminance-battery |
| _TZE284_d4h8j2n6 | ZP-301Z | safety-presence-zp301z-time-cycle-illuminance-battery |
| _TZE284_debczeci | TS0601 | safety-presence-basic-delay-battery |
| _TZE284_fwondbzy | TS0601 | safety-presence-zym100l-fixed-illuminance |
| _TZE284_gnpflcoq | TS0601 | safety-presence-gnpflcoq-illuminance-temp-humidity-battery |
| _TZE284_hgeqeyuv | TS0601 | safety-presence-zf24-move-illuminance |
| _TZE284_iadro9bf | TS0601 | safety-presence-zym100s2-range-delay-illuminance |
| _TZE284_ozf4e02o | TS0601 | safety-presence-msa201-illuminance |
| _TZE284_pzm3wab5 | TS0601 | safety-presence-zf24-move-illuminance |
| _TZE284_tre6haif | TS0601 | safety-motion-pir-solar-battery |
| _TZE284_twybxdzl | TS0601 | safety-presence-zf24-move-illuminance |
| _TZE284_vceqncho | TS0601 | safety-presence-zis01p-illuminance-battery |
| _TZE284_who1jxwd | TS0601 | safety-presence-zis01p-illuminance-battery |

## ef00-safety-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| Aubess | 1005005194831629 | safety-contact-temp-humidity-battery |
| CAT0001 | Excellux | safety-vibration-battery |
| Conecto | COZIGVS | safety-acceleration-4cqhd2ha |
| DYGSM | DY-RQ500A | safety-gas-detector-alarm-time-ringtone |
| HOBEIAN | ZG-102ZM | safety-acceleration-contact-battery-zg102zm |
| HOBEIAN | ZG-223Z | safety-water-leak-illuminance-battery-zg223z |
| HOBEIAN | ZG-226Z | safety-water-leak-alarm-battery-zg226z |
| HOBEIAN | ZG-228Z | safety-acceleration-alarm-battery-zg228z |
| HOBEIAN | ZG-229Z | safety-alarm-battery-zg229z |
| NEO | NAS-WS02B0 | safety-water-leak |
| Nous | E8 | safety-smoke-detector-battery |
| PIRIV01 | Excellux | safety-motion-vibration-illuminance-battery |
| TZE200_0zaf1cr8 | TS0601 | safety-smoke-detector-battery |
| VABRATE | Excellux | safety-acceleration-battery |
| _TZE200_0zaf1cr8 | TS0601 | safety-smoke-detector-battery |
| _TZE200_2pddnnrk | TS0601 | safety-water-leak-illuminance-battery-zg223z |
| _TZE200_5d3vhjro | TS0601 | safety-smoke-detector-battery |
| _TZE200_7bztmfm1 | TS0601 | safety-co-detector |
| _TZE200_8isdky6j | TS0601 | safety-gas-detector-zg225z |
| _TZE200_8ply8mjj | TS0601 | safety-acceleration-4cqhd2ha |
| _TZE200_afycb3cg | TS0601 | safety-acceleration-battery-zg103z |
| _TZE200_aj0oxo1i | TS0225 | safety-gas-detector-zg225z |
| _TZE200_aycxwiau | TS0601 | safety-smoke-detector-battery |
| _TZE200_bxdyeaa9 | TS0601 | safety-smoke-detector-battery |
| _TZE200_dnz6yvl2 | TS0601 | safety-smoke-detector-battery |
| _TZE200_dq1mfjug | TS0601 | safety-smoke-detector-battery |
| _TZE200_e2bedvo9 | TS0601 | safety-smoke-detector-battery |
| _TZE200_ft523twt | TS0601 | safety-smoke-detector-battery |
| _TZE200_fwoorn8y | TS0601 | safety-contact-battery |
| _TZE200_ggev5fsl | TS0601 | safety-gas-detector-self-test |
| _TZE200_hggxgsjj | TS0601 | safety-acceleration-battery-zg103z |
| _TZE200_iba1ckek | TS0601 | safety-acceleration-battery-zg103z |
| _TZE200_ijey4q29 | TS0601 | safety-contact-illuminance-battery |
| _TZE200_ioxkjvuz | TS0601 | safety-gas-detector |
| _TZE200_iuk8kupi | TS0601 | safety-gas-co-detector |
| _TZE200_j7sgd8po | TS0601 | safety-contact-temp-humidity-battery-s8 |
| _TZE200_jfw0a4aa | TS0601 | safety-acceleration-contact-battery-zg102zm |
| _TZE200_jsaqgakf | TS0601 | safety-water-leak-illuminance-battery-zg223z |
| _TZE200_jthf7vb6 | TS0601 | safety-water-leak-battery |
| _TZE200_kf2hbko4 | TS0601 | safety-contact-illuminance-battery |
| _TZE200_kltffuzl | TS0601 | safety-contact-battery |
| _TZE200_kvpwq8z7 | TS0601 | safety-gas-detector-self-test |
| _TZE200_kzm5w4iz | TS0601 | safety-vibration-battery |
| _TZE200_m9skfctm | TS0601 | safety-smoke-detector-battery |
| _TZE200_mby4kbtq | TS0601 | safety-gas-detector |
| _TZE200_ntcy3xu1 | TS0601 | safety-smoke-detector-battery |
| _TZE200_nus5kk3n | TS0601 | safety-gas-detector |
| _TZE200_nvups4nh | TS0601 | safety-contact-temp-humidity-battery |
| _TZE200_p6fuhvez | TS0225 | safety-gas-detector-zg225z |
| _TZE200_pay2byax | TS0601 | safety-contact-illuminance-battery |
| _TZE200_qq9mpfhw | TS0601 | safety-water-leak |
| _TZE200_qtbrwrfv | TS0601 | safety-smoke-detector-battery |
| _TZE200_rccxox8p | TS0601 | safety-smoke-detector-battery |
| _TZE200_t5p1vj8r | TS0601 | safety-smoke-detector-battery |
| _TZE200_u319yc66 | TS0601 | safety-gas-detector-self-test |
| _TZE200_u6x1zyv2 | TS0601 | safety-water-leak-illuminance-battery-zg223z |
| _TZE200_uebojraa | TS0601 | safety-smoke-detector-battery |
| _TZE200_ux5v4dbd | TS0601 | safety-smoke-detector-battery |
| _TZE200_vzekyi4c | TS0601 | safety-smoke-detector-battery |
| _TZE200_wzk0x7fq | TS0601 | safety-acceleration-contact-battery-zg102zm |
| _TZE200_yh7aoahi | TS0601 | safety-smoke-detector-battery |
| _TZE200_yjryxpot | TS0601 | safety-acceleration-battery-zg103z |
| _TZE200_ykglasuj | TS0601 | safety-contact-illuminance-battery |
| _TZE200_yojqa8xn | TS0601 | safety-gas-detector-alarm-time-ringtone |
| _TZE200_ytibqbra | TS0601 | safety-smoke-detector-battery |
| _TZE200_ytx9fudw | TS0601 | safety-contact-tamper-battery-opening |
| _TZE204_7bztmfm1 | TS0601 | safety-co-detector |
| _TZE204_chbyv06x | TS0601 | safety-gas-detector-alarm-time-ringtone |
| _TZE204_fncxk3ob | TS0601 | safety-alarm-battery-duration-volume-ringtone-yxzbsl |
| _TZE204_hcxvyxa5 | TS0601 | safety-alarm-duration-volume-ringtone-za03 |
| _TZE204_iuk8kupi | TS0601 | safety-gas-co-detector |
| _TZE204_k7mfgaen | TS0601 | safety-alarm-battery-duration-volume-ringtone-yxzbsl |
| _TZE204_kgaxpvxr | TS0601 | safety-smoke-detector-battery-288wz |
| _TZE204_kvpwq8z7 | TS0601 | safety-gas-detector-self-test |
| _TZE204_mby4kbtq | TS0601 | safety-gas-detector |
| _TZE204_ntcy3xu1 | TS0601 | safety-smoke-detector-battery |
| _TZE204_uo8qcagc | TS0601 | safety-gas-detector |
| _TZE204_v6iczj35 | TS0601 | safety-gas-detector |
| _TZE204_vawy74yh | TS0601 | safety-smoke-detector-battery |
| _TZE204_yojqa8xn | TS0601 | safety-gas-detector-alarm-time-ringtone |
| _TZE204_zougpkpy | TS0601 | safety-gas-detector-alarm-time-ringtone |
| _TZE284_0zaf1cr8 | TS0601 | safety-smoke-detector-battery |
| _TZE284_4cqhd2ha | TS0601 | safety-acceleration-4cqhd2ha |
| _TZE284_6teua268 | TS0601 | safety-contact-battery-senoro-win-v2 |
| _TZE284_6ycgarab | TS0601 | safety-smoke-co-detector-battery |
| _TZE284_ai4rqhky | TS0601 | safety-smoke-detector-battery |
| _TZE284_chbyv06x | TS0601 | safety-gas-detector-alarm-time-ringtone |
| _TZE284_e2bedvo9 | TS0601 | safety-smoke-detector-battery |
| _TZE284_fncxk3ob | TS0601 | safety-alarm-battery-duration-volume-ringtone-yxzbsl |
| _TZE284_gyzlwu5q | TS0601 | safety-smoke-temp-humidity-battery |
| _TZE284_n4ttsck2 | TS0601 | safety-smoke-detector-battery-288wz |
| _TZE284_rccxox8p | TS0601 | safety-smoke-detector-battery |

## ef00-sensors-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| A89G12C | Arteco | sensors-soil-temp-humidity-moisture-illuminance-ec-battery-fertility-zssf00 |
| AOYAN   | AY-302Z | sensors-soil-temp-moisture-battery-dry |
| AOYAN   | AY-303Z | sensors-soil-temp-humidity-moisture-battery-dry |
| Arteco | ZS-302Z | sensors-soil-temp-humidity-moisture-illuminance-battery-warning |
| DHT0001 | Excellux | sensors-temp-humidity-battery |
| DHTA001 | Excellux | sensors-temp-humidity-battery |
| Excellux | DHTA001 | sensors-temp-humidity-battery |
| Excellux | ZG-106NTH | sensors-temp-humidity-probe-excellux-battery |
| GIEX | GX04 | sensors-soil-temp-moisture-battery |
| GIEX | GX06 | sensors-soil-temp-moisture-battery |
| HOBEIAN | ZG-227Z | sensors-temp-humidity-battery-calibration-zg227z |
| HOBEIAN | ZG-227ZL | sensors-temp-humidity-battery-calibration-zg227z |
| HOBEIAN | ZG-303Z | sensors-soil-temp-humidity-moisture-battery-warning-legacy |
| KOJIMA | KOJIMA-THS-ZG-LCD | sensors-temp-humidity-battery-calibration-zg227z |
| NTCHT01 | Excellux | sensors-temp-humidity-probe-excellux-battery |
| NTCHT02 | Excellux | sensors-temp-humidity-probe-excellux-battery |
| Nous | E10 | sensors-aq-co2-temp-humidity |
| ONENUO | TH05Z | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| Tuya | 872WZ | sensors-liquid-level |
| Tuya | SZTH02 | sensors-temp-humidity-battery |
| Tuya | TZE200_t3xd7l44 | sensors-temp-humidity-battery-calibration-zg227z |
| Tuya | TZE284_cwyqwqbf | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| Tuya | YK-S03 | sensors-temp-battery-pool-chlorine |
| Tuya | YY-1099L | sensors-temp-battery-pool-chlorine |
| Tuya | ZTH01 | sensors-temp-humidity-battery |
| Tuya | ZTH02 | sensors-temp-humidity-battery |
| Tuya | ZTH05 | sensors-temp-humidity-battery |
| Tuya | ZTH08 | sensors-temp-humidity-battery |
| Tuya | ZTH08-E | sensors-temp-humidity-battery |
| _TZE200_01fvxamo | TS0201 | sensors-temp-battery |
| _TZE200_2se8efxh | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE200_3ejwxpmu | TS0601 | sensors-aq-co2-temp-humidity |
| _TZE200_3xfjp0ag | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_44af8vyi | TS0601 | sensors-temp-humidity-battery |
| _TZE200_8ygsuhe1 | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE200_9cqcpkgb | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE200_9yapgbuv | TS0601 | sensors-temp-humidity-battery |
| _TZE200_a8sdabtg | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_bjawzodf | TS0601 | sensors-temp-humidity-battery |
| _TZE200_blfcpsxz | TS0601 | sensors-aq-pm25-co2-temp-humidity-voc-formaldehyde |
| _TZE200_bq5c8xfe | TS0601 | sensors-temp-humidity-battery |
| _TZE200_c2fmom5z | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE200_c7emyjom | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_cirvgep4 | TS0601 | sensors-temp-humidity-battery |
| _TZE200_d0yu2xgi | TS0601 | sensors-temp-humidity-battery |
| _TZE200_d7lpruvi | TS0601 | sensors-temp-humidity-battery |
| _TZE200_d9mzkhoq | TS0601 | sensors-temp-battery-pool-chlorine |
| _TZE200_dikkika5 | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_dwcarsat | TS0601 | sensors-aq-pm25-co2-temp-humidity-voc-formaldehyde |
| _TZE200_eanjj2pa | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_ehhrv2e3 | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_ga1maeof | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE200_iq4ygaai | TS0201 | sensors-temp-battery |
| _TZE200_jt50ea5d | TS0601 | sensors-temp-battery-heat-water-meter |
| _TZE200_khx7nnka | TS0601 | sensors-illuminance |
| _TZE200_lhqtjwax | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_locansqn | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_lve3dvpy | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_lvkk0hdg | TS0601 | sensors-liquid-level |
| _TZE200_mja3fuja | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE200_myd45weu | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE200_npj9bug3 | TS0601 | sensors-soil-temp-humidity-moisture-battery-dry |
| _TZE200_ogkdpgy2 | TS0601 | sensors-aq-co2-temp-humidity |
| _TZE200_pisltm67 | TS0601 | sensors-illuminance-battery |
| _TZE200_pl31aqf5 | TS0601 | sensors-aq-co2-temp-humidity |
| _TZE200_qoy0ekbd | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_qrztc3ev | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_qyflbnbj | TS0601 | sensors-temp-humidity-battery |
| _TZE200_rbbx5mfq | TS0601 | sensors-illuminance-temp-humidity |
| _TZE200_ryfmq5rl | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE200_s1xgth2u | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_snloy4rw | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_t3xd7l44 | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_upagmta9 | TS0601 | sensors-temp-humidity-battery |
| _TZE200_utkemkbs | TS0601 | sensors-temp-humidity-battery |
| _TZE200_v1jqz5cy | TS0601 | sensors-temp-battery-pool-chlorine |
| _TZE200_vs0skpuc | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_vvmbj46n | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_vzqtvljm | TS0601 | sensors-illuminance-temp-humidity-battery |
| _TZE200_w6n8jeuu | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_whkgqxse | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_wqashyqo | TS0601 | sensors-soil-temp-humidity-moisture-battery-warning |
| _TZE200_wrmhp6b3 | TS0601 | sensors-soil-temp-humidity-moisture-battery-dry |
| _TZE200_xpvamyfz | TS0601 | sensors-aq-co2-temp-humidity |
| _TZE200_y8wkaq6w | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_ydrdfkim | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE200_yi4jtqq1 | TS0601 | sensors-illuminance |
| _TZE200_yjjdcqsq | TS0601 | sensors-temp-humidity-battery |
| _TZE200_ysm4dsb1 | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_yvx5lh6k | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE200_zl1kmjqx | TS0601 | sensors-temp-humidity-battery |
| _TZE200_znbl8dj5 | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE200_zppcgbdj | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE204_1wnh8bqp | TS0601 | sensors-temp-humidity-battery |
| _TZE204_3ejwxpmu | TS0601 | sensors-aq-co2-temp-humidity |
| _TZE204_7yyuo8sr | TS0601 | sensors-liquid-level |
| _TZE204_9yapgbuv | TS0601 | sensors-temp-humidity-battery |
| _TZE204_c2fmom5z | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE204_cirvgep4 | TS0601 | sensors-temp-humidity-battery |
| _TZE204_d7lpruvi | TS0601 | sensors-temp-humidity-battery |
| _TZE204_dwcarsat | TS0601 | sensors-aq-pm25-co2-temp-humidity-voc-formaldehyde |
| _TZE204_jygvp6fk | TS0601 | sensors-temp-humidity-battery |
| _TZE204_khx7nnka | TS0601 | sensors-illuminance |
| _TZE204_ksz749x8 | TS0601 | sensors-temp-humidity-battery |
| _TZE204_kwi6bbk4 | TS0601 | sensors-temp-humidity-battery |
| _TZE204_myd45weu | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE204_ogkdpgy2 | TS0601 | sensors-aq-co2 |
| _TZE204_qyflbnbj | TS0601 | sensors-temp-humidity-battery |
| _TZE204_rbbx5mfq | TS0601 | sensors-illuminance-temp-humidity |
| _TZE204_s139roas | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE204_upagmta9 | TS0601 | sensors-temp-humidity-battery |
| _TZE204_utkemkbs | TS0601 | sensors-temp-humidity-battery |
| _TZE204_w2vunxzm | TS0601 | sensors-pressure-temp-display |
| _TZE204_yjjdcqsq | TS0601 | sensors-temp-humidity-battery |
| _TZE204_yvx5lh6k | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE284_0ints6wl | TS0601 | sensors-soil-temp-humidity-moisture-illuminance-battery-warning |
| _TZE284_1wnh8bqp | TS0601 | sensors-temp-humidity-battery |
| _TZE284_2se8efxh | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_33bwcga2 | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_3urschql | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_4dosadbh | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE284_65gzcss7 | TS0601 | sensors-soil-temp-humidity-moisture-illuminance-battery-warning |
| _TZE284_8b9zpaav | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE284_8se38w3c | TS0601 | sensors-temp-humidity-probe-2aaa-battery |
| _TZE284_9ern5sfh | TS0601 | sensors-temp-humidity-battery |
| _TZE284_9yapgbuv | TS0601 | sensors-temp-humidity-battery |
| _TZE284_aao3yzhs | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_ajlu4cud | TS0601 | sensors-temp-battery |
| _TZE284_ap9owrsa | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_awepdiwi | TS0601 | sensors-soil-temp-moisture-battery-alarm |
| _TZE284_cwyqwqbf | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE284_d7lpruvi | TS0601 | sensors-temp-humidity-battery |
| _TZE284_g2e6cpnw | TS0601 | sensors-soil-temp-moisture-battery-alarm |
| _TZE284_hdml1aav | TS0601 | sensors-soil-temp-humidity-moisture-illuminance-ec-battery-fertility-cal |
| _TZE284_hdyjyqjm | TS0601 | sensors-temp-humidity-battery |
| _TZE284_hodyryli | TS0601 | sensors-temp-humidity-probe-2aaa-battery |
| _TZE284_it9utkro | TS0601 | sensors-aq-co2-temp-humidity-voc-formaldehyde |
| _TZE284_k7p2q5d9 | TS0601 | sensors-soil-temp-humidity-moisture-illuminance-battery-warning |
| _TZE284_kdqrazmy | TS0601 | sensors-temp-humidity-battery-calibration-zg227z |
| _TZE284_kyyu8rbj | TS0601 | sensors-liquid-level |
| _TZE284_locansqn | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE284_mxujdmxo | TS0601 | sensors-liquid-level |
| _TZE284_myd45weu | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_nhgdf6qr | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_nt4pquef | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_o9ofysmo | TS0601 | sensors-soil-temp-humidity-moisture-battery-air-illum |
| _TZE284_oitavov2 | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_qyflbnbj | TS0601 | sensors-temp-humidity-battery |
| _TZE284_rqcuwlsa | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_sgabhwa6 | TS0601 | sensors-soil-temp-moisture-battery-alarm |
| _TZE284_tgrzpqf4 | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_upagmta9 | TS0601 | sensors-temp-humidity-battery |
| _TZE284_utkemkbs | TS0601 | sensors-temp-humidity-battery |
| _TZE284_vvmbj46n | TS0601 | sensors-temp-humidity-battery-alarm-sensitivity-th-alarm |
| _TZE284_wckqztdq | TS0601 | sensors-soil-temp-moisture-battery |
| _TZE284_xc3vwx5a | TS0601 | sensors-soil-temp-humidity-moisture-battery-air-illum |
| _TZE284_xpvamyfz | TS0601 | sensors-aq-co2-temp-humidity |
| _TZE284_yjjdcqsq | TS0601 | sensors-temp-humidity-battery |
| _TZE284_yzr43ayq | TS0601 | sensors-soil-temp-humidity-moisture-illuminance-battery-warning |

## ef00-switch-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| AVATTO | WSMD-4 | switches-switch-4 |
| AVATTO | ZGB-WS-EU | switches-switch-1 |
| AVATTO | ZWSMD-4 | switches-switch-4 |
| Adaprox | TS0001_fingerbot_1 | switches-switch-1-battery |
| Ekaza | EKAT-T3074-6WZ | switches-switch-6 |
| Homeetec | 37022714 | switches-switch-4 |
| LoraTap | GDC311ZBQ1 | doors-garage-contact |
| MatSee Plus | PJ-ZGD01 | doors-garage-contact-countdown |
| Mercator Ikuü | SSW06G | switches-switch-6 |
| Moes | WS-EUB1-ZG | switches-switch-1 |
| Moes | ZM-102-M | doors-garage-contact-countdown |
| Norklmes | MKS-CM-W5 | switches-switch-1 |
| Nova Digital | FZB-4 | switches-switch-4 |
| Nova Digital | FZB-6 | switches-switch-6 |
| Nova Digital | NTZB-04-W-B | switches-switch-6 |
| Nova Digital | SA-6 | switches-switch-6 |
| Nova Digital | SYZB-6W | switches-switch-6 |
| Shawader | SMKG-1KNL-US/TZB-W | switches-switch-1 |
| Somgoms | ZSQB-SMB-ZB | switches-switch-1 |
| TZE204_7sjncirf | TS0601 | switches-switch-10 |
| Tuya | MG-ZG04W | switches-switch-4 |
| ZYXH | TY-04Z | switches-switch-4 |
| _TZ3000_uim07oem | TS0601 | switches-switch-4 |
| _TZ3210_7vgttna6 | TS0001 | switches-switch-1-battery |
| _TZ3210_a04acm9s | TS0001 | switches-switch-1-battery |
| _TZ3210_cm9mbpr1 | TS0001 | switches-switch-1-battery |
| _TZ3210_dse8ogfy | TS0001 | switches-switch-1-battery |
| _TZ3210_j4pdtz9v | TS0001 | switches-switch-1-battery |
| _TZ3218_7fiyo3kv | TS000F | switches-switch-1-temp-humidity |
| _TZ3218_ya5d6wth | TS000F | switches-switch-4-temp-humidity |
| _TZE200_0j5jma9b | TS0601 | switches-switch-6 |
| _TZE200_1n2kyphz | TS0601 | switches-switch-4 |
| _TZE200_1ozguk6x | TS0601 | switches-switch-4 |
| _TZE200_2hf7x9n3 | TS0601 | switches-switch-3 |
| _TZE200_2imwyigp | TS0601 | switches-switch-3 |
| _TZE200_3t91nb6k | TS0601 | switches-switch-2 |
| _TZE200_6wi2mope | TS0601 | switches-switch-4 |
| _TZE200_7deq70b8 | TS0601 | switches-switch-2 |
| _TZE200_7sjncirf | TS0601 | switches-switch-10 |
| _TZE200_7tdtqgwv | TS0601 | switches-switch-1 |
| _TZE200_8eazvzo6 | TS0601 | switches-switch-6-power-voltage-current |
| _TZE200_8vxj8khv | TS0601 | switches-switch-1 |
| _TZE200_9mahtqtg | TS0601 | switches-switch-6 |
| _TZE200_amp6tsvy | TS0601 | switches-switch-1 |
| _TZE200_aqnazj70 | TS0601 | switches-switch-4 |
| _TZE200_atpwqgml | TS0601 | switches-switch-3 |
| _TZE200_bynnczcb | TS0601 | switches-switch-3 |
| _TZE200_cduqh1l0 | TS0601 | switches-switch-6 |
| _TZE200_dhdstcqc | TS0601 | switches-switch-2 |
| _TZE200_di3tfv5b | TS0601 | switches-switch-4 |
| _TZE200_emxxanvi | TS0601 | switches-switch-6 |
| _TZE200_fqytfymk | TS0601 | switches-switch-3 |
| _TZE200_g1ib5ldv | TS0601 | switches-switch-2 |
| _TZE200_gbagoilo | TS0601 | switches-switch-1 |
| _TZE200_go3tvswy | TS0601 | switches-switch-3 |
| _TZE200_h2rctifa | TS0601 | switches-switch-6 |
| _TZE200_hewlydpz | TS0601 | switches-switch-4 |
| _TZE200_ji1gn7rw | TS0601 | switches-switch-2 |
| _TZE200_js3mgbjb | TS0601 | switches-switch-4 |
| _TZE200_jwsjbxjs | TS0601 | switches-switch-5 |
| _TZE200_k6jhsr0q | TS0601 | switches-switch-4 |
| _TZE200_kyfqmmyl | TS0601 | switches-switch-3 |
| _TZE200_leaqthqq | TS0601 | switches-switch-5 |
| _TZE200_mexisfik | TS0601 | switches-switch-4 |
| _TZE200_mwvfvw8g | TS0601 | switches-switch-6 |
| _TZE200_nh9m9emk | TS0601 | switches-switch-2 |
| _TZE200_nkjintbl | TS0601 | switches-switch-2 |
| _TZE200_nklqjk62 | TS0601 | doors-garage-contact-countdown |
| _TZE200_nvodulvi | TS0601 | switches-switch-8 |
| _TZE200_oisqyl4o | TS0601 | switches-switch-1 |
| _TZE200_ojtqawav | TS0601 | switches-switch-1 |
| _TZE200_oyti2ums | TS0601 | switches-switch-4-energy-voltage-current |
| _TZE200_r731zlxk | TS0601 | switches-switch-6 |
| _TZE200_raz9qavg | TS0601 | switches-switch-6 |
| _TZE200_shkxsgis | TS0601 | switches-switch-4 |
| _TZE200_tviaymwx | TS0601 | switches-switch-1 |
| _TZE200_tz32mtza | TS0601 | switches-switch-3 |
| _TZE200_vhy3iakz | TS0601 | switches-switch-3 |
| _TZE200_vmcgja59 | TS0601 | switches-switch-8 |
| _TZE200_wfxuhoea | TS0601 | doors-garage-contact |
| _TZE200_wktrysab | TS0601 | switches-switch-8 |
| _TZE200_wnp4d4va | TS0601 | switches-switch-6 |
| _TZE200_wunufsil | TS0601 | switches-switch-2 |
| _TZE200_wvovwe9h | TS0601 | switches-switch-2 |
| _TZE204_2imwyigp | TS0601 | switches-switch-3 |
| _TZE204_3t91nb6k | TS0601 | switches-switch-2 |
| _TZE204_58of2pfn | TS0601 | switches-switch-4 |
| _TZE204_6wi2mope | TS0601 | switches-switch-4 |
| _TZE204_72bewjky | TS0601 | switches-switch-8 |
| _TZE204_7ytnacie | TS0601 | switches-switch-4 |
| _TZE204_aagrxlbd | TS0601 | switches-switch-4 |
| _TZE204_ad2jkxwh | TS0601 | switches-switch-8 |
| _TZE204_adlblwab | TS0601 | switches-switch-8 |
| _TZE204_apiu8k13 | TS0601 | switches-switch-1-power-energy-voltage-current |
| _TZE204_atpwqgml | TS0601 | switches-switch-3 |
| _TZE204_ccgyhbvd | TS0601 | switches-switch-3 |
| _TZE204_cduqh1l0 | TS0601 | switches-switch-6 |
| _TZE204_dqolcpcp | TS0601 | switches-switch-12 |
| _TZE204_dvosyycn | TS0601 | switches-switch-8 |
| _TZE204_f5efvtbv | TS0601 | switches-switch-4 |
| _TZE204_fhv95pf1 | TS0601 | switches-switch-1 |
| _TZE204_g4au0afs | TS0601 | switches-switch-6 |
| _TZE204_gbagoilo | TS0601 | switches-switch-1 |
| _TZE204_gm8h14wy | TS0601 | switches-switch-1 |
| _TZE204_gxbdnfrh | TS0601 | switches-switch-6 |
| _TZE204_he9apaui | TS0601 | switches-switch-2 |
| _TZE204_hewlydpz | TS0601 | switches-switch-4 |
| _TZE204_hiith90n | TS0601 | switches-switch-1 |
| _TZE204_iik0pquw | TS0601 | switches-switch-4 |
| _TZE204_jktmrpoj | TS0601 | doors-garage-contact-countdown |
| _TZE204_l8xiyymq | TS0601 | switches-switch-6 |
| _TZE204_lbhh5o6z | TS0601 | switches-switch-4 |
| _TZE204_lmgrbuwf | TS0601 | switches-switch-6 |
| _TZE204_mexisfik | TS0601 | switches-switch-4 |
| _TZE204_mvtclclq | TS0601 | switches-switch-4-energy-voltage-current |
| _TZE204_ncti2pro | TS0601 | switches-switch-6 |
| _TZE204_nh9m9emk | TS0601 | switches-switch-2 |
| _TZE204_nklqjk62 | TS0601 | doors-garage-contact-countdown |
| _TZE204_nvxorhcj | TS0601 | switches-switch-8 |
| _TZE204_ojtqawav | TS0601 | switches-switch-1 |
| _TZE204_ptaqh9tk | TS0601 | switches-switch-1 |
| _TZE204_r731zlxk | TS0601 | switches-switch-6 |
| _TZE204_rkbxtclc | TS0601 | switches-switch-3 |
| _TZE204_shkxsgis | TS0601 | switches-switch-4 |
| _TZE204_tdhnhhiy | TS0601 | switches-switch-8 |
| _TZE204_unsxl4ir | TS0601 | switches-switch-4 |
| _TZE204_vmcgja59 | TS0601 | switches-switch-24 |
| _TZE204_w1wwxoja | TS0601 | switches-switch-6 |
| _TZE204_wfxuhoea | TS0601 | doors-garage-contact |
| _TZE204_wktrysab | TS0601 | switches-switch-8 |
| _TZE204_wskr3up8 | TS0601 | switches-switch-6 |
| _TZE204_wvovwe9h | TS0601 | switches-switch-2 |
| _TZE204_y8ficeai | TS0601 | switches-switch-6 |
| _TZE204_zqq3cipq | TS0601 | switches-switch-16 |
| _TZE21C_dohbhb5k | TS0001 | switches-switch-1-temperature |
| _TZE21C_i2ij4rb3 | TS0001 | switches-switch-1-temp-humidity |
| _TZE284_7e6v8u9f | TS0601 | switches-switch-1 |
| _TZE284_7zazvlyn | TS0601 | switches-switch-4 |
| _TZE284_atuj3i0w | TS0601 | switches-switch-4 |
| _TZE284_dqolcpcp | TS0601 | switches-switch-12 |
| _TZE284_dvosyycn | TS0601 | switches-switch-8 |
| _TZE284_f5efvtbv | TS0601 | switches-switch-4 |
| _TZE284_g1enhdsi | TS0601 | switches-switch-6 |
| _TZE284_idn2htgu | TS0601 | switches-switch-4 |
| _TZE284_iwyqtclw | TS0601 | switches-switch-4 |
| _TZE284_l8xiyymq | TS0601 | switches-switch-6 |
| _TZE284_lbhh5o6z | TS0601 | switches-switch-4 |
| _TZE284_mvtclclq | TS0601 | switches-switch-4-energy-voltage-current |
| _TZE284_nklqjk62 | TS0601 | doors-garage-contact-countdown |
| _TZE284_nvodulvi | TS0601 | switches-switch-8 |
| _TZE284_r731zlxk | TS0601 | switches-switch-6 |
| _TZE284_roujjevx | TS0601 | switches-switch-1-temperature |
| _TZE284_tdhnhhiy | TS0601 | switches-switch-6 |
| _TZE284_vmcgja59 | TS0601 | switches-switch-24 |
| _TZE284_xnwxmj8z | TS0601 | switches-switch-1 |
| _TZE284_yrwmnya3 | TS0601 | switches-switch-4 |
| _TZE284_zeldawjv | TS0601 | switches-switch-6 |
| _TZE284_zpvusbtv | TS0601 | switches-switch-2 |
| _TZE284_zqq3cipq | TS0601 | switches-switch-16 |
| _TZE608_c75zqghm | TS0603 | doors-garage-contact |
| _TZE608_fmemczv1 | TS0603 | doors-garage-contact |
| _TZE608_lapuuoke | TS0603 | doors-garage-contact |
| _TZE608_xkr8gep3 | TS0603 | doors-garage-contact |

## ef00-thermostats-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| AVATTO | AVATTO_TRV06 | thermostats-thermostat |
| AVATTO | ME167 | thermostats-thermostat |
| AVATTO | ME167_1 | thermostats-thermostat |
| AVATTO | ME168_1 | thermostats-thermostat |
| AVATTO | TRV06-1 | thermostats-thermostat-tv02 |
| AVATTO | TRV06_1 | thermostats-thermostat |
| AVATTO | TRV06_1b | thermostats-thermostat |
| AVATTO | TRV07 | thermostats-thermostat |
| AVATTO | WT-100-BH | thermostats-thermostat |
| AVATTO | ZWT-100-16A | thermostats-thermostat-x5h |
| AlecoAir | HA-08_THERMO | thermostats-thermostat-tv02 |
| Beok | TGR85-ZB | thermostats-thermostat-x5h |
| EARU | TRV06 | thermostats-thermostat |
| EKF | ETT-8 | thermostats-thermostat-tv02 |
| ELECTSMART | EST-120Z | thermostats-thermostat-floor |
| Echos | Eco-4160 | thermostats-thermostat |
| Emos | P5630S | thermostats-thermostat |
| Evolveo | Heat M30 | thermostats-thermostat |
| GIEX | TV06 | thermostats-thermostat-tv02 |
| Immax | 07732B | thermostats-thermostat |
| Immax | 07732L | thermostats-thermostat |
| MAZDA | MZTE1Z | thermostats-thermostat-pilot-wire-no-operating |
| Moes | HY368 | thermostats-thermostat |
| Moes | HY369RT | thermostats-thermostat |
| Moes | TRV801 | thermostats-thermostat-battery |
| Moes | TRV801Z | thermostats-thermostat-battery |
| Moes | TRV801_1 | thermostats-thermostat-battery |
| Moes | TV01-ZB | thermostats-thermostat-tv02 |
| Moes | ZTRV-ZX-TV01-MS | thermostats-thermostat-tv02 |
| Moes | ZTRV-ZX-TV02 | thermostats-thermostat-tv02 |
| RKHK | TH-P0Z | thermostats-thermostat-pilot-wire-no-operating |
| S366 | Cloud Even | thermostats-thermostat-basic |
| SHOJZJ | 378RT | thermostats-thermostat |
| Sber | SBDV-00185 | thermostats-thermostat-battery |
| Silvercrest | TVR01 | thermostats-thermostat |
| THALEOS | HY368 | thermostats-thermostat |
| THALEOS | TH-P1Z | thermostats-thermostat-pilot-wire-no-operating |
| THALEOS | TRV06-AT | thermostats-thermostat |
| Tesla Smart | TSL-TRV-TV01ZG | thermostats-thermostat-tv02 |
| Tesla Smart | TSL-TRV-TV05ZG | thermostats-thermostat-tv02 |
| Tuya | BAC-003 | thermostats-fcu-thermostat-no-operating |
| Unknown/id3.pl | GTZ08 | thermostats-thermostat-tv02 |
| _TYST11_2dpplnsn | dpplnsn | thermostats-thermostat |
| _TYST11_KGbxAXL2 | GbxAXL2 | thermostats-thermostat |
| _TYST11_c88teujp | 88teujp | thermostats-thermostat |
| _TYST11_caj4jz0i | aj4jz0i | thermostats-thermostat |
| _TYST11_wv90ladg | v90ladg | thermostats-thermostat |
| _TYST11_yw7cahqs | w7cahqs | thermostats-thermostat |
| _TYST11_zuhszj9s | uhszj9s | thermostats-thermostat |
| _TZE200_0dvm9mva | TS0601 | thermostats-thermostat |
| _TZE200_0hg58wyk | TS0601 | thermostats-thermostat-basic |
| _TZE200_1drr8tab | TS0601 | thermostats-fcu-thermostat-no-operating |
| _TZE200_2atgpdho | TS0601 | thermostats-thermostat |
| _TZE200_2dpplnsn | TS0601 | thermostats-thermostat |
| _TZE200_2ekuz3dz | TS0601 | thermostats-thermostat-x5h |
| _TZE200_3yp57tby | TS0601 | thermostats-thermostat |
| _TZE200_4eeyebrt | TS0601 | thermostats-thermostat |
| _TZE200_4utwoz2 | TS0601 | thermostats-thermostat |
| _TZE200_4utwozi2 | TS0601 | thermostats-thermostat |
| _TZE200_6rdj8dzm | TS0601 | thermostats-thermostat |
| _TZE200_7fqkphoq | TS0601 | thermostats-thermostat |
| _TZE200_7p8ugv8d | TS0601 | thermostats-thermostat |
| _TZE200_7yoranx2 | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_8thwkzxl | TS0601 | thermostats-thermostat |
| _TZE200_8whxpsiw | TS0601 | thermostats-thermostat |
| _TZE200_9gvruqf5 | TS0601 | thermostats-thermostat |
| _TZE200_9m4kmbfu | TS0601 | thermostats-thermostat |
| _TZE200_9mjy74mp | TS0601 | thermostats-thermostat-battery |
| _TZE200_9sfg7gm0 | TS0601 | thermostats-thermostat |
| _TZE200_9xfjixap | TS0601 | thermostats-thermostat |
| _TZE200_a4bpgplm | TS0601 | thermostats-thermostat |
| _TZE200_azqp6ssj | TS0601 | thermostats-thermostat |
| _TZE200_bvrlmajk | TS0601 | thermostats-thermostat |
| _TZE200_bvu2wnxz | TS0601 | thermostats-thermostat |
| _TZE200_c88teujp | TS0601 | thermostats-thermostat |
| _TZE200_ckud7u2l | TS0601 | thermostats-thermostat |
| _TZE200_cpmgn2cf | TS0601 | thermostats-thermostat |
| _TZE200_cwnjrr72 | TS0601 | thermostats-thermostat |
| _TZE200_d3z1ukqw | TS0601 | thermostats-thermostat |
| _TZE200_do5qy8zo | TS0601 | thermostats-thermostat |
| _TZE200_dv8abrrz | TS0601 | thermostats-thermostat |
| _TZE200_dzuqwsyg | TS0601 | thermostats-fcu-thermostat-no-operating |
| _TZE200_e9ba97vf | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_edl8pz1k | TS0601 | thermostats-thermostat-floor |
| _TZE200_eo6xhfbo | TS0601 | thermostats-thermostat-battery |
| _TZE200_exfrnlow | TS0601 | thermostats-thermostat |
| _TZE200_fsow0qsk | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_g9a3awaj | TS0601 | thermostats-thermostat-zwt07 |
| _TZE200_gd4rvykv | TS0601 | thermostats-thermostat |
| _TZE200_h4cgnbzg | TS0601 | thermostats-thermostat |
| _TZE200_ha0vwoew | TS0601 | thermostats-thermostat-basic |
| _TZE200_hue3yfsn | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_husqqvux | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_hvaxb2tc | TS0601 | thermostats-thermostat |
| _TZE200_jkfbph7l | TS0601 | thermostats-thermostat |
| _TZE200_k1tumq4t | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_kds0pmmv | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_khah2lkr | TS0601 | thermostats-thermostat |
| _TZE200_lhzapfg9 | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_lllliz3p | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_lnbfnyxd | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_lpwgshtl | TS0601 | thermostats-thermostat |
| _TZE200_mudxchsu | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_ow09xlxm | TS0601 | thermostats-thermostat |
| _TZE200_p3dbf6qs | TS0601 | thermostats-thermostat |
| _TZE200_pbo8cj0z | TS0601 | thermostats-thermostat-battery |
| _TZE200_pvvbommb | TS0601 | thermostats-thermostat |
| _TZE200_py4cm3he | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_qjp4ynvi | TS0601 | thermostats-thermostat |
| _TZE200_rk1wojce | TS0601 | thermostats-thermostat |
| _TZE200_rndg81sf | TS0601 | thermostats-thermostat |
| _TZE200_rtrmfadk | TS0601 | thermostats-thermostat-battery |
| _TZE200_rufdtfyv | TS0601 | thermostats-thermostat |
| _TZE200_rv6iuyxb | TS0601 | thermostats-thermostat |
| _TZE200_rxntag7i | TS0601 | thermostats-thermostat |
| _TZE200_rxq4iti9 | TS0601 | thermostats-thermostat |
| _TZE200_snfdqllf | TS0601 | thermostats-fcu-thermostat-no-operating |
| _TZE200_spyvfeti | TS0601 | thermostats-thermostat-floor |
| _TZE200_sur6q7ko | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_suxywabt | TS0601 | thermostats-thermostat |
| _TZE200_tbgecldg | TS0601 | thermostats-thermostat-battery-no-operating |
| _TZE200_viy9ihs7 | TS0601 | thermostats-thermostat |
| _TZE200_wem3gxyx | TS0601 | thermostats-thermostat-mode-setpoint |
| _TZE200_wsbfwodu | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_wv90ladg | TS0601 | thermostats-thermostat |
| _TZE200_x9axofse | TS0601 | thermostats-thermostat-tv02 |
| _TZE200_xby0s3ta | TS0601 | thermostats-thermostat |
| _TZE200_yqgbrdyo | TS0601 | thermostats-thermostat |
| _TZE200_yw7cahqs | TS0601 | thermostats-thermostat |
| _TZE200_ywdxldoj | TS0601 | thermostats-thermostat |
| _TZE200_z1tyspqw | TS0601 | thermostats-thermostat |
| _TZE200_znlqjmih | TS0601 | thermostats-thermostat |
| _TZE200_znzs7yaw | TS0601 | thermostats-thermostat |
| _TZE200_zr9c0day | TS0601 | thermostats-thermostat |
| _TZE200_zuhszj9s | TS0601 | thermostats-thermostat |
| _TZE204_0hcjew5p | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE204_3q3maeoo | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE204_3regm3h6 | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE204_6a4vxfnv | TS0601 | thermostats-thermostat-floor |
| _TZE204_6kijc7nd | TS0601 | thermostats-thermostat-tervix |
| _TZE204_6vwfjkcj | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE204_9mjy74mp | TS0601 | thermostats-thermostat-battery |
| _TZE204_atdqo4nj | TS0601 | thermostats-thermostat-zg-wk-da |
| _TZE204_cvcu2p6e | TS0601 | thermostats-thermostat-battery |
| _TZE204_cvub6xbb | TS0601 | thermostats-thermostat-tgm50 |
| _TZE204_d6i25bwg | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE204_dzuqwsyg | TS0601 | thermostats-fcu-thermostat-no-operating |
| _TZE204_edl8pz1k | TS0601 | thermostats-thermostat-floor |
| _TZE204_eekpf0ft | TS0601 | thermostats-thermostat-battery |
| _TZE204_g2ki0ejr | TS0601 | thermostats-thermostat-battery-no-operating |
| _TZE204_gops3slb | TS0601 | thermostats-thermostat |
| _TZE204_ilzkxrav | TS0601 | thermostats-thermostat-basic-twc-r01 |
| _TZE204_ltwbm23f | TS0601 | thermostats-thermostat-battery |
| _TZE204_lzriup1j | TS0601 | thermostats-thermostat |
| _TZE204_mpbki2zm | TS0601 | thermostats-fcu-thermostat-tybac006 |
| _TZE204_mul9abs3 | TS0601 | thermostats-thermostat-mode-setpoint |
| _TZE204_mwomyz5n | TS0601 | thermostats-thermostat-tgm50 |
| _TZE204_o3x45p96 | TS0601 | thermostats-thermostat |
| _TZE204_ogx8u5z6 | TS0601 | thermostats-thermostat |
| _TZE204_oh8y8pv8 | TS0601 | thermostats-thermostat |
| _TZE204_ouy7vpm1 | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE204_pcdmj88b | TS0601 | thermostats-thermostat-battery-no-operating |
| _TZE204_q12rv9gj | TS0601 | thermostats-fcu-thermostat-hhst001 |
| _TZE204_qyr2m29i | TS0601 | thermostats-thermostat-battery |
| _TZE204_rtrmfadk | TS0601 | thermostats-thermostat-battery |
| _TZE204_tagezcph | TS0601 | thermostats-thermostat-pro900z |
| _TZE204_tbgecldg | TS0601 | thermostats-thermostat-battery-no-operating |
| _TZE204_vjpaih9f | TS0601 | thermostats-thermostat-battery |
| _TZE204_wc2w9t1s | TS0601 | thermostats-thermostat-battery |
| _TZE204_xalsoe3m | TS0601 | thermostats-thermostat-zht002 |
| _TZE204_xnbkhhdr | TS0601 | thermostats-thermostat |
| _TZE204_zjhoqbrd | TS0601 | thermostats-thermostat |
| _TZE284_0dvm9mva | TS0601 | thermostats-thermostat |
| _TZE284_3regm3h6 | TS0601 | thermostats-thermostat-pilot-wire-no-operating |
| _TZE284_3yp57tby | TS0601 | thermostats-thermostat |
| _TZE284_4vbj3fxh | TS0601 | thermostats-fcu-thermostat-l2-t-f-mf |
| _TZE284_6kijc7nd | TS0601 | thermostats-thermostat-tervix |
| _TZE284_9m4kmbfu | TS0601 | thermostats-thermostat |
| _TZE284_aaeaifez | TS0601 | thermostats-thermostat |
| _TZE284_agcxaw3f | TS0601 | thermostats-thermostat-battery-bot-r15w |
| _TZE284_c6wv4xyo | TS0601 | thermostats-thermostat |
| _TZE284_cgr0rhza | TS0601 | thermostats-thermostat-battery-setpoint-temp |
| _TZE284_cvub6xbb | TS0601 | thermostats-thermostat-tgm50 |
| _TZE284_eekpf0ft | TS0601 | thermostats-thermostat-battery |
| _TZE284_gops3slb | TS0601 | thermostats-thermostat |
| _TZE284_khah2lkr | TS0601 | thermostats-thermostat |
| _TZE284_ltwbm23f | TS0601 | thermostats-thermostat-battery |
| _TZE284_madl8ejv | TS0601 | thermostats-thermostat |
| _TZE284_mul9abs3 | TS0601 | thermostats-thermostat-mode-setpoint |
| _TZE284_nbv4tdaz | TS0601 | thermostats-thermostat-battery-ar331pro |
| _TZE284_noixx2uz | TS0601 | thermostats-thermostat-battery-operating |
| _TZE284_o3x45p96 | TS0601 | thermostats-thermostat |
| _TZE284_ogx8u5z6 | TS0601 | thermostats-thermostat |
| _TZE284_p3dbf6qs | TS0601 | thermostats-thermostat |
| _TZE284_pcdmj88b | TS0601 | thermostats-thermostat-battery-no-operating |
| _TZE284_rv6iuyxb | TS0601 | thermostats-thermostat |
| _TZE284_tbgecldg | TS0601 | thermostats-thermostat-battery-no-operating |
| _TZE284_vjpaih9f | TS0601 | thermostats-thermostat-battery |
| _TZE284_xnbkhhdr | TS0601 | thermostats-thermostat |
| _TZE284_ymldrmzx | TS0601 | thermostats-thermostat-battery-setpoint-temp |
| _TZE284_zjhoqbrd | TS0601 | thermostats-thermostat |
| _TZE284_znlqjmih | TS0601 | thermostats-thermostat |
| id3 | GTZ06 | thermostats-thermostat |

## ef00-valves-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| Nova Digital | ZVL-DUAL | valves-valve-2-battery-status |
| _TZE200_1n2zev06 | TS0601 | valves-valve |
| _TZE200_2wg5qrjy | TS0601 | valves-valve-battery |
| _TZE200_5uodvhgc | TS0601 | valves-valve |
| _TZE200_81isopgh | TS0601 | valves-valve-battery |
| _TZE200_akjefhj5 | TS0601 | valves-valve-battery |
| _TZE200_fphxkxue | TS0601 | valves-valve-battery |
| _TZE200_hbnfokum | TS0601 | valves-valve-position-hbnfokum |
| _TZE200_vuwtqx0t | TS0601 | valves-valve-ultrasonic-meter |
| _TZE200_wt9agwf3 | TS0601 | valves-valve |
| _TZE204_dsagrkvg | TS0601 | valves-valve-battery |
| _TZE284_8zizsafo | TS0601 | valves-valve-2-battery-status |
| _TZE284_eaet5qt5 | TS0601 | valves-valve-2-battery-status |
| _TZE284_fhvpaltk | TS0601 | valves-valve-2-battery-status |
| _TZE284_iilebqoo | TS0601 | valves-valve-2-battery-status |
| _TZE284_vuwtqx0t | TS0601 | valves-valve-ultrasonic-meter |
| _TZE284_zm8zpwas | TS0601 | valves-valve-battery |

## zcl-controls-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| Aubess | ZXZIR-02 | controllers-ir-transceiver |
| BSEED | EC-GL86ZPCS11 | scene-switches-scene-1 |
| BSEED | EC-GL86ZPCS21 | scene-switches-scene-2 |
| BSEED | EC-GL86ZPCS31 | scene-switches-scene-3 |
| BSEED | EC-GL86ZPCS41 | scene-switches-scene-4 |
| BSEED | EC-SL-FK86ZPCS11 | scene-switches-scene-1 |
| BSEED | EC-SL-FK86ZPCS21 | scene-switches-scene-2 |
| BSEED | EC-SL-FK86ZPCS31 | scene-switches-scene-3 |
| BSEED | EC-SL-FK86ZPCS41 | scene-switches-scene-4 |
| BSEED_TODO | TS0726 | scene-switches-scene-4 |
| Benexmart | ZM-sui1 | buttons-button-1-battery |
| Candeo | C-ZB-RD1P-REM | controllers-dimming-remote-action |
| Candeo | C-ZB-SR5BR | buttons-button-4-battery-remote-action |
| Cleverio | SB100 | buttons-button-1-battery |
| ClickSmart+ | CSPGM2075PW | buttons-button-2-battery |
| ClimaxTechnology | IR-9ZBS-SL | controllers-ir-transceiver |
| DSS0010 | Excellux | buttons-button-1-battery-operation-mode-remote-action |
| Datek Wireless | EasyCode903G2.1 | buttons-button-4-battery |
| Easyfit by EnOcean | EWSxZ | buttons-button-1-battery |
| Ekaza | EKAT-T304Z | controllers-ir-transceiver |
| Feller | 4120.2.S.FMI.61 | buttons-button-1-battery |
| HEIMAN | ColorDimmerSw-EM-3.0 | controllers-dimming-remote-action |
| HEIMAN | DoorBell-EF-3.0 | buttons-doorbell-battery-tamper-low |
| HEIMAN | DoorBell-EM | buttons-doorbell-battery-tamper-low |
| HEIMAN | IRControl-EM | controllers-ir-transceiver |
| HEIMAN | IRControl2-EF-3.0 | controllers-ir-transceiver |
| HEIMAN | RC-EF-3.0 | security-remotes-action-battery |
| HEIMAN | RC-EM | security-remotes-action-battery |
| HEIMAN | RC-N | security-remotes-action-battery |
| HEIMAN | SOS-EF-3.0 | security-remotes-sos-battery |
| HEIMAN | SOS-EM | security-remotes-sos-battery |
| HEIMAN | SceneSwitch-EM-3.0 | buttons-button-4-battery-remote-action |
| HOBEIAN | TS0044 | buttons-button-4-battery |
| HOBEIAN | ZG-101ZS | buttons-button-4-battery |
| Haozee | ESW-OZAA-EU | buttons-button-4-battery |
| Immax | 07768L | buttons-button-1-battery-operation-mode-remote-action |
| Lonsonho | TS0041 | buttons-button-1-battery |
| Lonsonho | TS0042 | buttons-button-2-battery |
| Lonsonho | TS0043 | buttons-button-3-battery |
| Lonsonho | TS0044 | buttons-button-4-battery |
| LoraTap | SS600ZB | buttons-button-3-battery |
| LoraTap | SS6400ZB | buttons-button-4-battery |
| MLI | Remote Control | buttons-button-4-battery-remote-action |
| Marmitek | Push_LE | buttons-button-1-battery |
| Marmitek | Push_LO | buttons-button-2-battery |
| Marmitek | Push_ME | buttons-button-1-battery |
| Moes | SYT-ZB01 | buttons-button-1-battery-operation-mode-remote-action |
| Moes | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| Moes | TS004F_1 | buttons-button-4-battery-operation-mode-remote-action |
| Moes | XH-SY-04Z | buttons-button-4-battery |
| Moes | ZG-101ZD | buttons-button-1-battery-operation-mode-remote-action |
| Moes | ZT-SR-EU4 | buttons-button-4-battery |
| Moes | ZT-SY-EU-G-4S-WH-MS | buttons-button-4-battery |
| Moes | ZT-YK01 | buttons-button-1-battery |
| Moes | ZT-YK02 | buttons-button-2-battery |
| Moes | ZT-YK03 | buttons-button-3-battery |
| Namron | 4512727 | buttons-button-2-battery |
| Namron | 4512771 | buttons-button-2-battery |
| Namron | 4512772 | buttons-button-4-battery |
| Namron | 4566702 | buttons-button-4-battery |
| Nedis | ZBPB10BK | security-remotes-sos-battery |
| Nedis | ZBRC10WT | security-remotes-action-battery |
| Nedis | ZBWS40WT | buttons-button-4-battery |
| Niko | 91004 | buttons-button-1-battery |
| NodOn | CWS-4-1-01_HUE | buttons-button-4-battery |
| Nous | C1 | buttons-button-4-battery |
| Nous | LZ4 | buttons-button-1-battery |
| QA | QAIRZM2 | controllers-ir-transceiver |
| QA | QAIRZPRO | controllers-ir-transceiver |
| RGB Genie | ZGRC-KEY-013 | controllers-dimming-remote-action |
| Shelly | BLU Button Tough 1 ZB | buttons-button-1-battery |
| Shelly | BLU RC Button 4 ZB | buttons-button-4-battery |
| Shelly | BLU Remote Control ZB | buttons-button-4-battery |
| Shelly | SBBT-104CEU | buttons-button-1-battery |
| Smart9 | S9TSZGB | buttons-button-1-battery |
| Sunricher | SR-ZG2833PAC | controllers-dimming-remote-action |
| Sunricher | SR-ZG9001K12-DIM-Z4 | controllers-dimming-remote-action |
| Sunricher | SR-ZG9001K2-DIM | controllers-dimming-remote-action |
| Sunricher | SR-ZG9001K2-DIM2 | controllers-dimming-remote-action |
| Sunricher | SR-ZG9001K4-DIM2 | controllers-dimming-remote-action |
| Sunricher | SR-ZG9001K8-DIM | controllers-dimming-remote-action |
| Sunricher | SR-ZG9001NK8-DIM | controllers-dimming-remote-action |
| Sunricher | SR-ZG9023A(EU) | controllers-dimming-remote-action |
| Sunricher | SR-ZGP2801K4-FOH-E | buttons-button-4-battery |
| Sunricher | TERNCY-DC01 | buttons-button-4-battery-remote-action |
| Trio2sys | 20020002 | buttons-button-4-battery |
| Tuya | BT400B | security-remotes-sos-battery |
| Tuya | MINI-ZSB | buttons-button-1-battery |
| Tuya | SH-SC07 | buttons-button-1-battery |
| Tuya | TM-YKQ004 | buttons-button-4-battery |
| Tuya | TS0044_1 | buttons-button-4-battery |
| Tuya | TS0044_2 | buttons-button-4-battery |
| Tuya | UFO-R4Z | controllers-ir-transceiver |
| Tuya | ZG-101Z_D_1 | buttons-button-1-battery-operation-mode-remote-action |
| Tuya | iH-F8260 | controllers-ir-transceiver |
| Woox | R7052 | security-remotes-sos-battery |
| Woox | R7054 | security-remotes-action-battery |
| Zemismart | KES-606US-L3-EESS | scene-switches-3 |
| Zemismart | ZM-18-USB | controllers-ir-transceiver |
| Zemismart | ZMR4 | buttons-button-4-battery-operation-mode-remote-action |
| Zemismart | ZMR4_1 | buttons-button-4-battery |
| Zemismart | ZXMIR-02 | controllers-ir-transceiver |
| _TYZB01_1xktopx6 | TS0041A | buttons-button-1-battery |
| _TYZB01_4qw4rl1u | TS0041A | buttons-button-1-battery |
| _TYZB01_bngwdjsr | TS1001 | controllers-dimming-remote-action |
| _TYZB01_cnlmkhbk | TS0044 | buttons-button-4-battery |
| _TYZB01_hww2py6b | TS1001 | controllers-dimming-remote-action |
| _TYZB01_ub7urdza | TS0041A | buttons-button-1-battery |
| _TYZB02_key8kk7r | TS0043 | buttons-button-3-battery |
| _TYZB02_keyjhapk | TS0042 | buttons-button-2-battery |
| _TZ1800_akzvkzqq | TS0211 | buttons-doorbell-battery-tamper-low |
| _TZ1800_ladpngdx | TS0211 | buttons-doorbell-battery-tamper-low |
| _TZ3000_0dumfk2z | TS0215A | security-remotes-sos-battery |
| _TZ3000_0dumfk2z | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_0ht8dnxj | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_0zrccfgx | TS0215A | security-remotes-action-battery |
| _TZ3000_0zrccfgx | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_11pg3ima | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_1fqpj6qz | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_1hypixdr | TS0044 | buttons-button-4-battery |
| _TZ3000_1yyjhvwd | TS0042 | buttons-button-2-battery |
| _TZ3000_22ugzkme | TS0041 | buttons-button-1-battery |
| _TZ3000_2izubafb | TS0215A | security-remotes-sos-battery |
| _TZ3000_2izubafb | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_402vrq2i | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_4fjiwweb | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_4fsgukof | TS0215A | security-remotes-sos-battery |
| _TZ3000_4fsgukof | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_4upl1fcj | TS0041 | buttons-button-1-battery |
| _TZ3000_5bpeda8u | TS0041 | buttons-button-1-battery |
| _TZ3000_5e235jpa | TS0042 | buttons-button-2-battery |
| _TZ3000_5kxl9esg | TS0726 | scene-switches-scene-1 |
| _TZ3000_5kxl9esg | TS0726_1_gang_scene_switch | scene-switches-scene-1 |
| _TZ3000_5tqxpine | TS0044 | buttons-button-4-battery |
| _TZ3000_6km7djcm | TS0041 | buttons-button-1-battery |
| _TZ3000_8utxxtzr | TS0215A | security-remotes-action-battery |
| _TZ3000_8utxxtzr | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_9orwkl3t | TS0044 | buttons-button-4-battery |
| _TZ3000_9r5jaajv | TS0215A | security-remotes-sos-battery |
| _TZ3000_9r5jaajv | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_a4xycprs | TS0044 | buttons-button-4-battery |
| _TZ3000_a7ouggvs | TS0043 | buttons-button-3-battery |
| _TZ3000_abci1hiu | TS0044 | buttons-button-4-battery |
| _TZ3000_abrsvsou | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_adkvzooy | TS0042 | buttons-button-2-battery |
| _TZ3000_adndolvx | TS0041 | buttons-button-1-battery |
| _TZ3000_an5rjiwd | TS0041 | buttons-button-1-battery |
| _TZ3000_axpdxqgu | TS0041 | buttons-button-1-battery |
| _TZ3000_b3mgfu0d | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_b4awzgct | TS0041 | buttons-button-1-battery |
| _TZ3000_bgtzm4ny | TS0044 | buttons-button-4-battery |
| _TZ3000_bi6lpsew | TS0043 | buttons-button-3-battery |
| _TZ3000_csflgqj2 | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_cumqn2av | TS0726 | scene-switches-4-plus-2 |
| _TZ3000_cumqn2av | TS0726_4_gang_switch_and_2_scene | scene-switches-4-plus-2 |
| _TZ3000_cziew6eu | TS0726 | scene-switches-3 |
| _TZ3000_cziew6eu | TS0726_3_gang | scene-switches-3 |
| _TZ3000_czuyt8lz | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_dfgbtub0 | TS0042 | buttons-button-2-battery |
| _TZ3000_dku2cfsc | TS0044 | buttons-button-4-battery |
| _TZ3000_dziaict4 | TS0044 | buttons-button-4-battery |
| _TZ3000_ee8nrt2l | TS0044 | buttons-button-4-battery |
| _TZ3000_egvb1p2g | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_eo3dttwe | TS0215A | security-remotes-action-battery |
| _TZ3000_eo3dttwe | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_et7afzxz | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_etufnltx | TS1002 | buttons-button-4-battery-remote-action |
| _TZ3000_ezqbvrqz | TS0726 | scene-switches-scene-2 |
| _TZ3000_ezqbvrqz | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ3000_fa9mlvja | TS0041 | buttons-button-1-battery |
| _TZ3000_famkxci2 | TS0043 | buttons-button-3-battery |
| _TZ3000_fkvaniuu | TS0042 | buttons-button-2-battery |
| _TZ3000_fsiepnrh | TS0215A | security-remotes-action-battery |
| _TZ3000_fsiepnrh | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_g7eeean4 | TS0044 | buttons-button-4-battery |
| _TZ3000_g9g2xnch | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_gbm10jnj | TS0043 | buttons-button-3-battery |
| _TZ3000_gwkzibhs | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_h1c2eamp | TS0042 | buttons-button-2-battery |
| _TZ3000_hurauima | TS0726 | scene-switches-scene-4 |
| _TZ3000_hurauima | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3000_i3rjdrwu | TS0042 | buttons-button-2-battery |
| _TZ3000_icoxotza | TS0726 | scene-switches-2 |
| _TZ3000_icoxotza | TS0726_2_gang | scene-switches-2 |
| _TZ3000_imnwsek2 | TS0043 | buttons-button-3-battery |
| _TZ3000_irwuzilv | TS0215A | security-remotes-sos-battery |
| _TZ3000_irwuzilv | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_iszegwpd | TS0046 | buttons-button-6-battery |
| _TZ3000_ixla93vd | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_j61x9rxn | TS0044 | buttons-button-4-battery |
| _TZ3000_j70oanab | TS0044 | buttons-button-4-battery |
| _TZ3000_ja5osu5g | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_jwcixnrz | TS0215A | security-remotes-action-battery |
| _TZ3000_jwcixnrz | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_kaflzta4 | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_kccru4oi | TS0041 | buttons-button-1-battery |
| _TZ3000_kfkqkjqe | TS0726 | scene-switches-3 |
| _TZ3000_kfkqkjqe | TS0726_3_gang | scene-switches-3 |
| _TZ3000_kfu8zapd | TS0044 | buttons-button-4-battery |
| _TZ3000_kjfzuycl | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_krwtzhfd | TS004F | buttons-button-1-battery |
| _TZ3000_kt6xxa4o | TS0726 | scene-switches-3-advanced |
| _TZ3000_kt6xxa4o | TS0726_multi_3_gang | scene-switches-3-advanced |
| _TZ3000_kt7obmnn | TS0042 | buttons-button-2-battery |
| _TZ3000_kxaow5ki | TS0041 | buttons-button-1-battery |
| _TZ3000_laeia8fo | TS0044 | buttons-button-4-battery |
| _TZ3000_lcjsewlo | TS0726 | scene-switches-3 |
| _TZ3000_lcjsewlo | TS0726_3_gang | scene-switches-3 |
| _TZ3000_lrfvzq1e | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_m3pafcnk | TS0726 | scene-switches-3-advanced |
| _TZ3000_m3pafcnk | TS0726_multi_3_gang | scene-switches-3-advanced |
| _TZ3000_m4ah6bcz | TS0726 | scene-switches-1-advanced |
| _TZ3000_m4ah6bcz | TS0726_multi_1_gang | scene-switches-1-advanced |
| _TZ3000_mh9px7cq | TS0044 | buttons-button-4-battery |
| _TZ3000_mrpevh8p | TS0041 | buttons-button-1-battery |
| _TZ3000_mutfmn4u | TS0043 | buttons-button-3-battery |
| _TZ3000_ngsph3oj | TS0043 | buttons-button-3-battery |
| _TZ3000_noru9tix | TS0726 | scene-switches-scene-3 |
| _TZ3000_noru9tix | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3000_nrfkrgf4 | TS0046 | buttons-button-6-battery |
| _TZ3000_nuombroo | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_nxdziqzc | TS0215A | security-remotes-sos-battery |
| _TZ3000_nxdziqzc | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_owgcnkrh | TS0042 | buttons-button-2-battery |
| _TZ3000_p3fph1go | TS0215A | security-remotes-sos-battery |
| _TZ3000_p3fph1go | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_p6ju8myv | TS0215A | security-remotes-action-battery |
| _TZ3000_p6ju8myv | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_pcqjmcud | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_pd9mpyh4 | TS0044 | buttons-button-4-battery |
| _TZ3000_peszejy7 | TS0041 | buttons-button-1-battery |
| _TZ3000_piyhhake | TS0041 | buttons-button-1-battery |
| _TZ3000_pkfazisv | TS0215A | security-remotes-sos-battery |
| _TZ3000_pkfazisv | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_qfhhb5y4 | TS0045 | buttons-button-5-battery |
| _TZ3000_qgwcxxws | TS0041 | buttons-button-1-battery |
| _TZ3000_qhyadm57 | TS0726 | scene-switches-4-plus-2 |
| _TZ3000_qhyadm57 | TS0726_4_gang_switch_and_2_scene | scene-switches-4-plus-2 |
| _TZ3000_qja6nq5z | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_qzjcsmar | TS0043 | buttons-button-3-battery |
| _TZ3000_r0o2dahu | TS004F | buttons-button-6-battery-operation-mode-remote-action |
| _TZ3000_r2fgo9ks | TS0726 | scene-switches-scene-3 |
| _TZ3000_r2fgo9ks | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3000_rco1yzb1 | TS004F | buttons-button-1-battery |
| _TZ3000_rrjr1q0u | TS0043 | buttons-button-3-battery |
| _TZ3000_rsqqkdxv | TS0041 | buttons-button-1-battery |
| _TZ3000_rsylfthg | TS0726 | scene-switches-scene-4 |
| _TZ3000_rsylfthg | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3000_s678wazd | TS0726 | scene-switches-4 |
| _TZ3000_s678wazd | TS0726_4_gang | scene-switches-4 |
| _TZ3000_sj7jbgks | TS0043 | buttons-button-3-battery |
| _TZ3000_ssp0maqm | TS0215A | security-remotes-sos-battery |
| _TZ3000_ssp0maqm | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_ssup6h68 | TS0726 | scene-switches-2-advanced |
| _TZ3000_ssup6h68 | TS0726_multi_2_gang | scene-switches-2-advanced |
| _TZ3000_t8hzpgnd | TS0042 | buttons-button-2-battery |
| _TZ3000_tj4pwzzm | TS0215A | security-remotes-sos-battery |
| _TZ3000_tj4pwzzm | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_tk3s5tyg | TS0041 | buttons-button-1-battery |
| _TZ3000_tzvbimpq | TS0042 | buttons-button-2-battery |
| _TZ3000_u2bbagu4 | TS0215A | security-remotes-action-battery |
| _TZ3000_u2bbagu4 | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_u3nv1jwk | TS0044 | buttons-button-4-battery |
| _TZ3000_uaa99arv | TS0044 | buttons-button-4-battery |
| _TZ3000_ufhtxr59 | TS0044 | buttons-button-4-battery |
| _TZ3000_ug1vtuzn | TS0215A | security-remotes-action-battery |
| _TZ3000_ug1vtuzn | TS0215A_remote | security-remotes-action-battery |
| _TZ3000_ugi8ky6u | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_uri7ongn | TS004F | buttons-button-1-battery-operation-mode-remote-action |
| _TZ3000_v8jvcwsx | TS0042 | buttons-button-2-battery |
| _TZ3000_vm5gcsdq | TS0043 | buttons-button-3-battery |
| _TZ3000_vn88ezar | TS0041 | buttons-button-1-battery |
| _TZ3000_vp6clf9d | TS0044 | buttons-button-4-battery |
| _TZ3000_w4thianr | TS0043 | buttons-button-3-battery |
| _TZ3000_w8jwkczz | TS0043 | buttons-button-3-battery |
| _TZ3000_wbfgbpxq | TS0044 | buttons-button-4-battery |
| _TZ3000_wkai4ga5 | TS0044 | buttons-button-4-battery |
| _TZ3000_wopf2sox | TS0726 | scene-switches-1-advanced |
| _TZ3000_wopf2sox | TS0726_multi_1_gang | scene-switches-1-advanced |
| _TZ3000_wr2ucaj9 | TS0215A | security-remotes-sos-battery |
| _TZ3000_wr2ucaj9 | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_wsspgtcd | TS0726 | scene-switches-4 |
| _TZ3000_wsspgtcd | TS0726_4_gang | scene-switches-4 |
| _TZ3000_xabckq1v | TS004F | buttons-button-4-battery-operation-mode-remote-action |
| _TZ3000_xr7itfxq | TS0042 | buttons-button-2-battery |
| _TZ3000_xrqsdxq6 | TS0041 | buttons-button-1-battery |
| _TZ3000_xwh1e22x | TS1002 | buttons-button-4-battery-remote-action |
| _TZ3000_xwuveizv | TS0044 | buttons-button-4-battery |
| _TZ3000_yj6k7vfo | TS0041 | buttons-button-1-battery |
| _TZ3000_yw5tvzsk | TS0043 | buttons-button-3-battery |
| _TZ3000_zgyzgdua | TS0044 | buttons-button-4-battery |
| _TZ3000_zsh6uat3 | TS0215A | security-remotes-sos-battery |
| _TZ3000_zsh6uat3 | TS0215A_sos | security-remotes-sos-battery |
| _TZ3000_ztrfrcsu | TS1001 | controllers-dimming-remote-action |
| _TZ3000_zwszqdpy | TS1002 | buttons-button-4-battery-remote-action |
| _TZ3002_1s0vfmtv | TS0726 | scene-switches-2 |
| _TZ3002_1s0vfmtv | TS0726_2_gang | scene-switches-2 |
| _TZ3002_6ahhkwyh | TS0726 | scene-switches-scene-2 |
| _TZ3002_6ahhkwyh | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ3002_9vcekkp1 | TS0726 | scene-switches-1-advanced |
| _TZ3002_9vcekkp1 | TS0726_multi_1_gang | scene-switches-1-advanced |
| _TZ3002_a4kvf6zd | TS0726 | scene-switches-scene-2 |
| _TZ3002_a4kvf6zd | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ3002_aewsvjcu | TS0726 | scene-switches-4-advanced |
| _TZ3002_aewsvjcu | TS0726_multi_4_gang | scene-switches-4-advanced |
| _TZ3002_eda6eitk | TS0726 | scene-switches-scene-4 |
| _TZ3002_eda6eitk | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3002_gdwja9a7 | TS0726 | scene-switches-2 |
| _TZ3002_gdwja9a7 | TS0726_2_gang | scene-switches-2 |
| _TZ3002_hkaktryd | TS0726 | scene-switches-scene-4 |
| _TZ3002_hkaktryd | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3002_iedhxgyi | TS0726 | scene-switches-scene-3 |
| _TZ3002_iedhxgyi | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3002_jn2x20tg | TS0726 | scene-switches-scene-1 |
| _TZ3002_jn2x20tg | TS0726_1_gang_scene_switch | scene-switches-scene-1 |
| _TZ3002_kq3kqwjt | TS0726 | scene-switches-scene-3 |
| _TZ3002_kq3kqwjt | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3002_l8bfzlcd | TS0726 | scene-switches-1 |
| _TZ3002_l8bfzlcd | TS0726_1_gang | scene-switches-1 |
| _TZ3002_m3pafcnk | TS0726 | scene-switches-3-advanced |
| _TZ3002_m3pafcnk | TS0726_multi_3_gang | scene-switches-3-advanced |
| _TZ3002_phu8ygaw | TS0726 | scene-switches-4-advanced |
| _TZ3002_phu8ygaw | TS0726_multi_4_gang | scene-switches-4-advanced |
| _TZ3002_pw4ad2xa | TS0726 | scene-switches-4 |
| _TZ3002_pw4ad2xa | TS0726_4_gang | scene-switches-4 |
| _TZ3002_pzao9ls1 | TS0726 | scene-switches-scene-4 |
| _TZ3002_pzao9ls1 | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3002_rbnycsav | TS0726 | scene-switches-scene-3 |
| _TZ3002_rbnycsav | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3002_sal078g8 | TS0726 | scene-switches-scene-6 |
| _TZ3002_sal078g8 | TS0726_switch_4g_2s | scene-switches-scene-6 |
| _TZ3002_sfh0jtz0 | TS0726 | scene-switches-scene-6 |
| _TZ3002_sfh0jtz0 | TS0726_switch_4g_2s | scene-switches-scene-6 |
| _TZ3002_tdf2m4ch | TS0726 | scene-switches-scene-4 |
| _TZ3002_tdf2m4ch | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3002_tlsvxhxc | TS0726 | scene-switches-scene-2 |
| _TZ3002_tlsvxhxc | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ3002_u7d3nes3 | TS0726 | scene-switches-2 |
| _TZ3002_u7d3nes3 | TS0726_2_gang | scene-switches-2 |
| _TZ3002_umdkr64x | TS0726 | scene-switches-scene-4 |
| _TZ3002_umdkr64x | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ3002_uu4uircb | TS0726 | scene-switches-4 |
| _TZ3002_uu4uircb | TS0726_4_gang | scene-switches-4 |
| _TZ3002_vaq2bfcu | TS0726 | scene-switches-3-advanced |
| _TZ3002_vaq2bfcu | TS0726_multi_3_gang | scene-switches-3-advanced |
| _TZ3002_vsom92pp | TS0726 | scene-switches-scene-3 |
| _TZ3002_vsom92pp | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3002_xkxgfxsg | TS0726 | scene-switches-scene-1 |
| _TZ3002_xkxgfxsg | TS0726_1_gang_scene_switch | scene-switches-scene-1 |
| _TZ3002_ybtqbyk3 | TS0726 | scene-switches-scene-3 |
| _TZ3002_ybtqbyk3 | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3002_ymv5vytn | TS0726 | scene-switches-scene-2 |
| _TZ3002_ymv5vytn | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ3002_yptomml1 | TS0726 | scene-switches-4 |
| _TZ3002_yptomml1 | TS0726_4_gang | scene-switches-4 |
| _TZ3002_zjuvw9zf | TS0726 | scene-switches-scene-2 |
| _TZ3002_zjuvw9zf | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ300A_fhbcipep | TS0726 | scene-switches-4-plus-2 |
| _TZ300A_fhbcipep | TS0726_4_gang_switch_and_2_scene | scene-switches-4-plus-2 |
| _TZ300A_ohjmifiz | TS0726 | scene-switches-scene-2 |
| _TZ300A_ohjmifiz | TS0726_2_gang_scene_switch | scene-switches-scene-2 |
| _TZ300A_rncj86af | TS0726 | scene-switches-scene-1 |
| _TZ300A_rncj86af | TS0726_1_gang_scene_switch | scene-switches-scene-1 |
| _TZ300A_vkflnsl0 | TS0726 | scene-switches-scene-4 |
| _TZ300A_vkflnsl0 | TS0726_4_gang_scene_switch | scene-switches-scene-4 |
| _TZ300A_vqrs45nj | TS0726 | scene-switches-scene-3 |
| _TZ300A_vqrs45nj | TS0726_3_gang_scene_switch | scene-switches-scene-3 |
| _TZ3290_785fbxik | TS1201 | controllers-ir-transceiver |
| _TZ3290_7v1k4vufotpowp9z | TS1201 | controllers-ir-transceiver |
| _TZ3290_7v1k4vufotpowp9z | ZS06 | controllers-ir-transceiver |
| _TZ3290_8xzb2ghn | TS1201 | controllers-ir-transceiver |
| _TZ3290_acv1iuslxi3shaaj | TS1201 | controllers-ir-transceiver |
| _TZ3290_acv1iuslxi3shaaj | ZS06 | controllers-ir-transceiver |
| _TZ3290_gnl5a6a5xvql7c2a | TS1201 | controllers-ir-transceiver |
| _TZ3290_gnl5a6a5xvql7c2a | ZS06 | controllers-ir-transceiver |
| _TZ3290_j37rooaxrcdcqo5n | TS1201 | controllers-ir-transceiver |
| _TZ3290_jxvzqatwgsaqzx1u | TS1201 | controllers-ir-transceiver |
| _TZ3290_lypnqvlem5eq1ree | TS1201 | controllers-ir-transceiver |
| _TZ3290_nba3knpsarkawgnt | TS1201 | controllers-ir-transceiver |
| _TZ3290_nba3knpsarkawgnt | ZS06 | controllers-ir-transceiver |
| _TZ3290_nkpxapoz | TS1201 | controllers-ir-transceiver |
| _TZ3290_ot6ewjvmejq5ekhl | TS1201 | controllers-ir-transceiver |
| _TZ3290_rlkmy85q4pzoxobl | TS1201 | controllers-ir-transceiver |
| _TZ3290_rlkmy85q4pzoxobl | ZS06 | controllers-ir-transceiver |
| _TZ3290_s6ezpa3j | TS1201 | controllers-ir-transceiver |
| _TZ3290_u9xac5rv | TS1201 | controllers-ir-transceiver |
| _TZ3290_uc8lwbi2 | TS1201 | controllers-ir-transceiver |
| _TZ3290_xjpbcxn92aaxvmlz | TS1201 | controllers-ir-transceiver |
| _TZ3290_yac64inudpovoaba | ZS06 | controllers-ir-transceiver |
| _TZ3290_yyax9ajf | TS1201 | controllers-ir-transceiver |
| _TZ3400_key8kk7r | TS0043 | buttons-button-3-battery |
| _TZ3400_keyjhapk | TS0042 | buttons-button-2-battery |
| _TZ3400_keyjqthh | TS0041 | buttons-button-1-battery |
| _TZ3400_tk3s5tyg | TS0041 | buttons-button-1-battery |
| eWeLink | CK-TLSR8656-SS5-01(7000) | buttons-button-1-battery |
| eWeLink | RHK07 | buttons-button-1-battery |
| eWeLink | SNZB-01 | buttons-button-1-battery |
| easyiot | ZB-IR01 | controllers-ir-transceiver |
| iHseno | TS0044_5tqxpine | buttons-button-4-battery |
| iHseno | _TZ3000_mh9px7cq | buttons-button-4-battery |

## zcl-covers-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| BSEED | EC-GL86ZPCRS31 | covers-cover |
| BSEED | S-PC86ZPCS11B | covers-cover |
| Danor | SK-Z802C-US | covers-cover |
| Girier | ME168_Girier | covers-cover |
| Girier | TS130F_GIRIER | covers-cover |
| Girier | TS130F_GIRIER_DUAL | covers-cover |
| Lidl | HG09648 | covers-cover |
| LoraTap | SC400 | covers-cover |
| LoraTap | SC500ZB | covers-cover |
| LoraTap | SC500ZB-v4 | covers-cover |
| Moes | ZTS-EUB1 | covers-cover |
| Nous | B4Z | covers-cover |
| Nous | L12Z | covers-cover |
| QA | QACZ1 | covers-cover |
| Sunricher | SR-ZG9080A | covers-cover |
| Tuya | GM35TEQ-TYZ-2/25 | covers-cover |
| Yookee | D10110_1 | covers-cover |
| Zemismart | TS130F_ZEMISMART | covers-cover |
| Zemismart | ZM25R3 | covers-cover |
| Zemismart | ZN-LC1E | covers-cover |
| _TZ3000_1dd0d5yi | TS130F | covers-cover |
| _TZ3000_5iixzdo7 | TS130F | covers-cover |
| _TZ3000_74hsp7qy | TS130F | covers-cover |
| _TZ3000_8h7wgocw | TS130F | covers-cover |
| _TZ3000_bmhwnl7s | TS130F | covers-cover-2 |
| _TZ3000_bs93npae | TS130F | covers-cover |
| _TZ3000_dojqjapa | TS130F | covers-cover |
| _TZ3000_e3vhyirx | TS130F | covers-cover |
| _TZ3000_egq7y6pr | TS130F | covers-cover |
| _TZ3000_esynmmox | TS130F | covers-cover-2 |
| _TZ3000_fccpjz5z | TS130F | covers-cover |
| _TZ3000_femsaaua | TS130F | covers-cover |
| _TZ3000_j1xl73iw | TS130F | covers-cover-2 |
| _TZ3000_jwv3cwak | TS130F | covers-cover |
| _TZ3000_kmsbwdol | TS130F | covers-cover-2 |
| _TZ3000_l6iqph4f | TS130F | covers-cover-2 |
| _TZ3000_vd43bbfq | TS130F | covers-cover |
| _TZ3000_vw8pawxa | TS130F | covers-cover |
| _TZ3000_xdo0hj1k | TS130F | covers-cover-2 |
| _TZ3000_yruungrl | TS130F | covers-cover |
| _TZ3000_zirycpws | TS130F | covers-cover |
| _TZ3210_dwytrmda | TS130F | covers-cover |
| _TZ3210_ol1uhvza | TS130F | covers-cover |
| _TZ3210_xbpt8ewc | TS130F | covers-cover |
| _TZB000_42ha4rsc | TS030F | covers-cover |
| _TZE200_9caxna4s | TS0301 | covers-cover |
| eWeLink | AM25C-1-25-ES-E-Z | covers-cover |
| eWeLink | CK-MG22-Z310EE07DOOYA-01(7015) | covers-cover |
| eWeLink | MYDY25Z-1 | covers-cover |
| eWeLink | ZM25-EAZ | covers-cover |

## zcl-lights-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| Aldi | C422AC11D41H140.0W | lights-color-temperature-color |
| Aldi | C422AC14D41H140.0W | lights-color-temperature-color |
| Aldi | F122SB62H22A4.5W | lights-color-temperature |
| Aldi | L122AA63H11A6.5W | lights-color-temperature-color |
| Aldi | L122FF63H11A5.0W | lights-color-temperature-color |
| Astuta/ZB-CCT | CCT Light | lights-color-temperature |
| BTF-Lighting | C03Z | lights-color |
| CTM Lyng | CTM_DimmerPille | lights-dimmer |
| Candeo | C-ZB-DM204 | lights-dimmer |
| Candeo | C-ZB-LC20-CCT | lights-color-temperature |
| Candeo | C-ZB-LC20-Dim | lights-dimmer |
| Candeo | C-ZB-LC20-RGB | lights-color |
| Candeo | C-ZB-LC20-RGBCCT | lights-color-temperature-color |
| Candeo | C-ZB-LC20-RGBW | lights-color-temperature-color |
| Candeo | C-ZB-LC20v2-CCT | lights-color-temperature |
| Candeo | C-ZB-LC20v2-Dim | lights-dimmer |
| Candeo | C-ZB-LC20v2-RGB | lights-color |
| Candeo | C-ZB-LC20v2-RGBCCT | lights-color-temperature-color |
| Candeo | C-ZB-LC20v2-RGBW | lights-color-temperature-color |
| Candeo | C-ZB-RD1 | lights-dimmer |
| Candeo | C-ZB-RD1P-DIM | lights-dimmer |
| Candeo | C-ZB-RD1P-DPM | lights-dimmer-2-options |
| Candeo | C203 | lights-dimmer |
| Candeo | C204 | lights-dimmer |
| Candeo | C210 | lights-dimmer |
| Candeo | Dimmer-Switch-ZB3.0 | lights-dimmer |
| Candeo | HK-LN-DIM-A | lights-dimmer |
| DOMRAEM | DIMMER | lights-dimmer |
| DOMRAEM | RGB | lights-color |
| DOMRAEM | RGBW | lights-color |
| DOMRAEM | RGBWC | lights-color-temperature-color |
| DOMRAEM | WW/CW | lights-color-temperature |
| EGLO | 12229 | lights-dimmer |
| EGLO | 12239 | lights-color-temperature |
| EGLO | 900053 | lights-color-temperature |
| EGLO | 900116 | lights-color-temperature-color |
| EGLO | 900316 | lights-color-temperature |
| EGLO | 900317 | lights-color-temperature |
| EGLO | 900566 | lights-color-temperature-color |
| ELKO | EKO06984 | lights-dimmer |
| ELKO | EKO06985 | lights-dimmer |
| ELKO | EKO06986 | lights-dimmer |
| EcoDim | ED-10032 | lights-color-temperature |
| Elko | EKO06988 | lights-dimmer |
| Elko | EKO06989 | lights-dimmer |
| Elko | EKO06990 | lights-dimmer |
| Elko | EKO06991 | lights-dimmer |
| Elko | EKO07090 | lights-dimmer |
| Elko | EKO07117 | lights-dimmer |
| Elko | EKO07144 | lights-dimmer |
| Elko | EKO07278 | lights-dimmer |
| Elko | EKO07279 | lights-dimmer |
| Elko | EKO07280 | lights-dimmer |
| Elko | EKO07281 | lights-dimmer |
| Exxact | WDE002962 | lights-dimmer |
| Exxact | WDE003962 | lights-dimmer |
| Garza Smart | Garza-Standard-A60 | lights-color-temperature-color |
| Gledopto | GL-C-001P | lights-color-temperature-color |
| Gledopto | GL-C-002P | lights-color-temperature-color |
| Gledopto | GL-C-003P_1 | lights-color-temperature |
| Gledopto | GL-C-006P_mini | lights-color-temperature |
| Gledopto | GL-C-007P_mini | lights-color-temperature-color |
| Gledopto | GL-C-008P_mini | lights-color-temperature-color |
| Gledopto | GL-C-009P_mini | lights-dimmer |
| Gledopto | GL-C-011P | lights-color-temperature-color |
| Gledopto | GL-C-201P | lights-color-temperature-color |
| Gledopto | GL-C-202P | lights-color-temperature-color |
| Gledopto | GL-C-203P | lights-color-temperature |
| Gledopto | GL-C-204P | lights-color-temperature-color |
| Gledopto | GL-C-301P | lights-color-temperature-color |
| HZC | Dimmer-Switch-ZB3.0 | lights-dimmer |
| Heatit Controls AB | Dimmer-Switch-ZB3.0 | lights-dimmer |
| Hilux | Dimmer-Switch-ZB3.0 | lights-dimmer |
| IKEA | E1603 | lights-dimmer |
| IKEA | E1702/E1703 | lights-color-temperature |
| IKEA | E1704 | lights-dimmer |
| IKEA | E1705 | lights-dimmer |
| IKEA | E1902 | lights-color-temperature |
| IKEA | E2204 | lights-dimmer |
| IKEA | E2206 | lights-color-temperature |
| IKEA | E2214 | lights-color-temperature |
| IKEA | E2220 | lights-color-temperature |
| IKEA | E2223 | lights-color-temperature-color |
| IKEA | E2224 | lights-color-temperature-color |
| Iluminize | 511.344 | lights-dimmer |
| Iluminize | DIM Lighting | lights-dimmer |
| Iluminize | RGBW-CCT | lights-color-temperature-color |
| Iluminize | RGBWW Lighting | lights-color-temperature-color |
| Jung | ZLLA5004M | lights-dimmer |
| Jung | ZLLCD5004M | lights-dimmer |
| Jung | ZLLLS5004M | lights-dimmer |
| KOJIMA | GX53-RGB-WW-CW-7W-ZGB | lights-color-temperature-color |
| L&S Lighting | 756200028 | lights-dimmer |
| L&S Lighting | 756200031 | lights-dimmer |
| LDS | ZBT-CCTLight-GU100904 | lights-color-temperature |
| LED-Trading | 9125 | lights-dimmer |
| LEDEPLY | SG45-E26 | lights-color-temperature-color |
| LUUMR | 10010128 | lights-color-temperature-color |
| LUUMR | 10024773 | lights-color-temperature |
| Ledron | QS-Zigbee-D06-DC | lights-dimmer |
| Ledron | YK-16 | lights-dimmer |
| Legrand | Dimmer switch with neutral | lights-dimmer |
| Letsleds China | RGBW Down Light | lights-color-temperature-color |
| Lidl | 14147206L | lights-color-temperature |
| Lidl | 14148906L | lights-color-temperature-color |
| Lidl | 14149505L/14149506L_1 | lights-color-temperature-color |
| Lidl | 14149505L/14149506L_2 | lights-color-temperature-color |
| Lidl | 14153905L | lights-color-temperature |
| Lidl | 14156408L | lights-color-temperature |
| Lidl | 14156506L | lights-color-temperature-color |
| Lidl | 14158704L | lights-color-temperature-color |
| Lidl | 14158804L | lights-color-temperature-color |
| Lidl | 399629_2110 | lights-color-temperature-color |
| Lidl | HG06104A | lights-color-temperature-color |
| Lidl | HG06106A | lights-color-temperature-color |
| Lidl | HG06106B | lights-color-temperature-color |
| Lidl | HG06106C | lights-color-temperature-color |
| Lidl | HG06462A | lights-dimmer |
| Lidl | HG06463A | lights-dimmer |
| Lidl | HG06463B | lights-dimmer |
| Lidl | HG06492A/HG08130A | lights-color-temperature |
| Lidl | HG06492B/HG08130B | lights-color-temperature |
| Lidl | HG06492C/HG08130C/HG09154C | lights-color-temperature |
| Lidl | HG07834A/HG09155A/HG08131A | lights-color-temperature-color |
| Lidl | HG07834B | lights-color-temperature-color |
| Lidl | HG07834B/HG09155B/HG08131B | lights-color-temperature-color |
| Lidl | HG07834C/HG09155C/HG08131C | lights-color-temperature-color |
| Lidl | HG08007 | lights-color-temperature-color |
| Lidl | HG08008 | lights-color-temperature-color |
| Lidl | HG08010 | lights-color-temperature-color |
| Lidl | HG08131C | lights-color-temperature-color |
| Lidl | HG08383A | lights-color-temperature-color |
| Lidl | HG08383B | lights-color-temperature-color |
| Lidl | HG08673-BS | lights-color-temperature-color |
| Light | 01F | lights-color-temperature-color |
| Light Solutions | Dimmer-Switch-ZB3.0 | lights-dimmer |
| LongLife LED | 3986 | lights-dimmer |
| Lonsonho | QS-Zigbee-D02-TRIAC-L | lights-dimmer |
| Lonsonho | QS-Zigbee-D02-TRIAC-LN_1 | lights-dimmer-options-ts110-countdown30 |
| Lonsonho | QS-Zigbee-D02-TRIAC-L_1 | lights-dimmer-options-ts110 |
| Ltech | SE-20-250-1000-W2Z2 | lights-color-temperature-color |
| Ltech | TY-75-24-G2Z2_CCT | lights-color-temperature |
| MLI | Bulb white | lights-color-temperature |
| MLI | Bulb white+color | lights-color-temperature-color |
| MLI | Candle white+color | lights-color-temperature-color |
| MLI | Ceiling light | lights-color-temperature-color |
| MLI | Desk lamp | lights-color-temperature-color |
| MLI | GU10 white+color | lights-color-temperature-color |
| MLI | Garden light | lights-color-temperature-color |
| MLI | LED Strip | lights-color-temperature-color |
| MLI | ZBT-DimmableLight | lights-dimmer |
| Mercator Ikuü | S9E27LED9W-RGB-Z | lights-color-temperature-color |
| Mercator Ikuü | SMCL01-ZB | lights-color-temperature |
| Mercator Ikuü | SMD4106W-RGB-ZB | lights-color-temperature-color |
| Mercator Ikuü | SMD9300 | lights-color-temperature |
| Mercator Ikuü | SMFL20W-ZB | lights-dimmer |
| Mercator Ikuü | SMI7040 | lights-color-temperature |
| MiBoxer | E2-ZR | lights-color-temperature |
| MiBoxer | E3-ZR | lights-color-temperature-color |
| MiBoxer | FUT035Z+ | lights-color-temperature |
| MiBoxer | FUT036Z | lights-dimmer |
| MiBoxer | FUT037Z | lights-color |
| MiBoxer | FUT037Z+ | lights-color-temperature-color |
| MiBoxer | FUT039Z | lights-color-temperature-color |
| MiBoxer | FUT066Z | lights-color-temperature-color |
| MiBoxer | FUT068ZR | lights-color-temperature-color |
| MiBoxer | FUT103ZR | lights-color-temperature-color |
| MiBoxer | FUT105ZR | lights-color-temperature-color |
| MiBoxer | FUT106ZR | lights-color-temperature-color |
| MiBoxer | FUTC11ZR | lights-color-temperature-color |
| MiBoxer | PZ2 | lights-color-temperature |
| MiBoxer | SZ5 | lights-color-temperature-color |
| Moes | ZB-LZD10-RCW | lights-color-temperature-color |
| Moes | ZB-TD5-RCW-GU10 | lights-color-temperature-color |
| Moes | ZB-TD6-RCW-GX53-MS | lights-color-temperature-color |
| Moes | ZB-TDA14-RCW-E27-MS | lights-color-temperature-color |
| Moes | ZB-TDA9-RCW-E27-MS | lights-color-temperature-color |
| Moes | ZB-TDC6-RCW-E14 | lights-color-temperature-color |
| Moes | ZB-TDD6-RCW-4 | lights-color-temperature-color |
| Moes | ZLD-RCW_1 | lights-color-temperature-color |
| Mycket | MS-SP-LE27WRGB | lights-color-temperature-color |
| Müller Licht | 404115 | lights-color-temperature-color |
| Müller Licht | 404116 | lights-color-temperature-color |
| Müller Licht | 404117 | lights-color-temperature-color |
| Müller Licht | 404135 | lights-color-temperature-color |
| Müller Licht | 404136 | lights-color-temperature-color |
| Müller Licht | 404137 | lights-color-temperature-color |
| Namron | 4512751 | lights-dimmer |
| Namron As | DIM Lighting | lights-dimmer |
| Nedis | ZBLC1E14 | lights-color-temperature-color |
| Nedis | ZBWD20RD | lights-dimmer-2-options-ts110 |
| NorLum Dim OP | DIMMER | lights-dimmer |
| Nordtronic | 98426061 | lights-dimmer |
| Nordtronic | WSZ 98426061 | lights-dimmer |
| Nordtronic A/S | 98426061 | lights-dimmer |
| Nordtronic A/S | WSZ 98426061 | lights-dimmer |
| Nous | P3Z | lights-color-temperature-color |
| OXT | SWTZ25 | lights-dimmer-2-options |
| Paulmann | 984.43 | lights-dimmer |
| Paulmann Licht | RGBW | lights-color |
| Paulmann Licht | RGBW Controller | lights-color-temperature-color |
| Paulmann Licht GmbH | CCT | lights-color-temperature |
| Paulmann Licht GmbH | Dimmable | lights-dimmer |
| Paulmann Licht GmbH | RGB | lights-color |
| Paulmann Licht GmbH | RGBW | lights-color |
| Paulmann lamp | CCT Light | lights-color-temperature |
| Paulmann lamp | Dimmable Light | lights-dimmer |
| Philips | 5633030P9 | lights-color-temperature |
| Philips | 8720169264212 | lights-color-temperature-color |
| Philips | 8720169264274 | lights-color-temperature-color |
| Philips | 9290012574 | lights-color-temperature-color |
| Philips | 929003099302 | lights-color-temperature |
| Philips | 929003115901 | lights-color-temperature-color |
| Philips | 929003116201 | lights-color-temperature-color |
| Philips | 929003711301 | lights-dimmer |
| Philips | 929003711401 | lights-dimmer |
| Philips | 929003777201 | lights-color-temperature |
| Philips | 929003822801 | lights-dimmer |
| Philips | 929003823001 | lights-color-temperature |
| Philips | 929003823101 | lights-color-temperature |
| Philips | 929003823201 | lights-color-temperature |
| Philips | 929003823301 | lights-color-temperature |
| Philips | 929003823401 | lights-color-temperature |
| Philips | 929003823601 | lights-color-temperature-color |
| Philips | 929003823701 | lights-color-temperature-color |
| Philips | 929003823801 | lights-color-temperature-color |
| Philips | 929003823901 | lights-color-temperature-color |
| Philips | 929003824001 | lights-color-temperature-color |
| Philips | 929003845801 | lights-dimmer |
| Philips | 929003845901 | lights-dimmer |
| Philips | 929003846001 | lights-color-temperature |
| Philips | 929003846101 | lights-color-temperature |
| Philips | 929003846201 | lights-color-temperature-color |
| Philips | 929003846301 | lights-color-temperature-color |
| Philips | 929003846401 | lights-color-temperature |
| Philips | 929003846501 | lights-color-temperature |
| Philips | 929003846601 | lights-color-temperature-color |
| Philips | 929003846701 | lights-color-temperature-color |
| Philips | 929003853701 | lights-color-temperature-color |
| Philips | 929004608003 | lights-color-temperature-color |
| Philips | 929004608004 | lights-color-temperature-color |
| Philips | 929004608101 | lights-color-temperature-color |
| Philips | 929004608103 | lights-color-temperature-color |
| Philips | 929004608201 | lights-color-temperature-color |
| QA | QADZC5 | lights-color-temperature-color |
| Samotech | Dimmer-Switch-ZB3.0 | lights-dimmer |
| Samotech | HK_DIM_A | lights-dimmer |
| Samotech | SM311 | lights-dimmer |
| Schneider | WDE002961 | lights-dimmer |
| Schneider | WDE003961 | lights-dimmer |
| Schneider | WDE004961 | lights-dimmer |
| Schneider Electric | 550B1012 | lights-dimmer |
| Seastar Intelligence | 07073L | lights-color-temperature-color |
| Shyugj | Dimmer-Switch-ZB3.0 | lights-dimmer |
| Shyugj | HK_DIM_A | lights-dimmer |
| Sibling | Light-ZSLL | lights-color-temperature |
| Skydance | WZ5_dim_2 | lights-color-temperature-color |
| Smart Dim | Dimmer-Switch-ZB3.0 | lights-dimmer |
| Sunricher | DIM | lights-dimmer-2-options |
| Sunricher | DIM Lighting | lights-dimmer |
| Sunricher | HK-SL-DIM-A | lights-dimmer |
| Sunricher | HK-ZD-RGBCCT-A | lights-color-temperature-color |
| Sunricher | SR-ZG2835 | lights-dimmer |
| Sunricher | SR-ZG9040A | lights-dimmer |
| Sunricher | SR-ZG9040A-S | lights-dimmer |
| TechToy | _TZ3210_iw0zkcu8 | lights-color-temperature-color |
| Third Reality | 3RCB02070Z | lights-color-temperature-color |
| Tuya | A5C-21F7-01 | lights-color-temperature-color |
| Tuya | FS-05R | lights-dimmer |
| Tuya | L1(ZW) | lights-color-temperature |
| Tuya | TS0505B_1_1 | lights-color-temperature-color |
| Tuya | TS0505B_2_2 | lights-color-temperature-color |
| UR Lighting | TH008L10RGBCCT | lights-color-temperature-color |
| YPHIX | 50208695 | lights-dimmer |
| YSRSAI | ZB-CL01 | lights-color-temperature-color |
| Yphix | 50208702 | lights-dimmer |
| ZB/Ajax Online | CCT Light | lights-color-temperature |
| ZigBee/CCT | CCT Light | lights-color-temperature |
| _TYZB01_qezuin6k | TS110F | lights-dimmer |
| _TYZB01_v8gtiaed | TS110F | lights-dimmer |
| _TZ3000_49qchf10 | TS0502A | lights-color-temperature |
| _TZ3000_4whigl8i | TS0501B | lights-dimmer |
| _TZ3000_5fkufhn1 | TS0502A | lights-color-temperature |
| _TZ3000_6dwfra5l | TS0502B | lights-color-temperature |
| _TZ3000_7dcddnye | TS0501A | lights-dimmer |
| _TZ3000_7hcgjxpc | TS0505B | lights-color-temperature-color |
| _TZ3000_7ysdnebc | TS1101 | lights-dimmer-2-options-ts110 |
| _TZ3000_8uaoilu9 | TS0502A | lights-color-temperature |
| _TZ3000_92chsky7 | TS110F | lights-dimmer |
| _TZ3000_9cpuaca6 | TS0505A | lights-color-temperature-color |
| _TZ3000_9evm3otq | TS0502A | lights-color-temperature |
| _TZ3000_bumeauzp | TS0502B | lights-color-temperature |
| _TZ3000_bwlvyjwk | TS0505B | lights-color-temperature-color |
| _TZ3000_dbou1ap4 | TS0505A | lights-color-temperature-color |
| _TZ3000_el5kt5im | TS0502A | lights-color-temperature |
| _TZ3000_estfrmup | TS110F | lights-dimmer |
| _TZ3000_evag0pvn | TS0505A | lights-color-temperature-color |
| _TZ3000_g1glzzfk | TS0502B | lights-color-temperature |
| _TZ3000_gb5gaeca | TS0505B | lights-color-temperature-color |
| _TZ3000_gek6snaj | TS0505A | lights-color-temperature-color |
| _TZ3000_hexqj6ls | TS110F | lights-dimmer-2 |
| _TZ3000_iivsrikg | TS0505B | lights-color-temperature-color |
| _TZ3000_j0gtlepx | TS0505B | lights-color-temperature-color |
| _TZ3000_j2w1dw29 | TS0501A | lights-dimmer |
| _TZ3000_juq7i1fr | TS0501B | lights-dimmer |
| _TZ3000_kdpxju99 | TS0505A | lights-color-temperature-color |
| _TZ3000_keabpigv | TS0505A | lights-color-temperature-color |
| _TZ3000_ktuoyvt5 | TS110F | lights-dimmer |
| _TZ3000_kvwrdf47 | TS0052 | lights-dimmer-2-options-ts110 |
| _TZ3000_lxw3zcdk | TS0505B | lights-color-temperature-color |
| _TZ3000_mgusv51k | TS0052 | lights-dimmer |
| _TZ3000_nbnmw9nc | TS0501A | lights-dimmer |
| _TZ3000_ncb6mkx8 | TS0004 | fans-fan-light-switch |
| _TZ3000_nosnx7im | TS0501A | lights-dimmer |
| _TZ3000_obacbukl | TS0503A | lights-color |
| _TZ3000_oborybow | TS0502A | lights-color-temperature |
| _TZ3000_odygigth | TS0505A | lights-color-temperature-color |
| _TZ3000_oh7jddmx | TS0502A | lights-color-temperature |
| _TZ3000_q50zhdsc | TS0505B | lights-color-temperature-color |
| _TZ3000_qd7hej8u | TS0505B | lights-color-temperature-color |
| _TZ3000_quqaeew6 | TS0505B | lights-color-temperature-color |
| _TZ3000_riwp3k79 | TS0505A | lights-color-temperature-color |
| _TZ3000_rylaozuc | TS0502A | lights-color-temperature |
| _TZ3000_sfibawtr | TS0052 | lights-dimmer-2-options-ts110 |
| _TZ3000_sosdczdl | TS0505A | lights-color-temperature-color |
| _TZ3000_taspddvq | TS0505B | lights-color-temperature-color |
| _TZ3000_th6zqqy6 | TS0505B | lights-color-temperature-color |
| _TZ3000_v1srfw9x | TS0505B | lights-color-temperature-color |
| _TZ3000_wr6g6olr | TS0505B | lights-color-temperature-color |
| _TZ3000_xfs39dbf | TS1101 | lights-dimmer-options-ts110 |
| _TZ3000_xr5m6kfg | TS0505B | lights-color-temperature-color |
| _TZ3000_zjtxnoft | TS0052 | lights-dimmer-2-options-ts110 |
| _TZ3000_zw7wr5uo | TS0502B | lights-color-temperature |
| _TZ3210_09hzmirw | TS0502B | lights-color-temperature |
| _TZ3210_3mpwqzuu | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_3mpwqzuu | TS110E_2gang_2 | lights-dimmer-2-options-ts110 |
| _TZ3210_4ubylghk | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_4ubylghk | TS110E_2gang_2 | lights-dimmer-2-options-ts110 |
| _TZ3210_4whigl8i | TS0501 | fans-switch-fan-mode |
| _TZ3210_4zinq6io | TS0501B | lights-dimmer |
| _TZ3210_6pwpez2j | TS0502C | lights-color-temperature |
| _TZ3210_778drfdt | TS0503B | lights-color |
| _TZ3210_9q49basr | TS0501B | lights-dimmer |
| _TZ3210_agjx0pxt | TS0501B | lights-dimmer |
| _TZ3210_b3kiq1i0 | TS0505B | lights-color-temperature-color |
| _TZ3210_b8jdosxo | TS0505B | lights-color-temperature-color |
| _TZ3210_bfwvfyx1 | TS0505B | lights-color-temperature-color |
| _TZ3210_c0s1xloa | TS0505B | lights-color-temperature-color |
| _TZ3210_c2iwpxf1 | TS0502B | lights-color-temperature |
| _TZ3210_cieijuw1 | TS0505B | lights-color-temperature-color |
| _TZ3210_claeh5ds | TS0502B | lights-color-temperature |
| _TZ3210_cyuyd5az | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_cyuyd5az | TS110E_1gang_1 | lights-dimmer-options-ts110 |
| _TZ3210_d062rv7j | TS0501B | lights-dimmer |
| _TZ3210_dbilpfqk | TS0501B | lights-dimmer |
| _TZ3210_dkul5xix | TS0505B | lights-color-temperature-color |
| _TZ3210_dn5higyl | TS0505B | lights-color-temperature-color |
| _TZ3210_dwzfzfjc | TS0505B | lights-color-temperature-color |
| _TZ3210_dxroobu3 | TS0501B | lights-dimmer |
| _TZ3210_e5t9bfdv | TS0501B | lights-dimmer |
| _TZ3210_ebbfkvoy | TS110F | lights-dimmer |
| _TZ3210_frm6149r | TS0502B | lights-color-temperature |
| _TZ3210_guijtl8k | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_hicxa0rh | TS0505B | lights-color-temperature-color |
| _TZ3210_hquixjeg | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_hxtfthp5 | TS0505B | lights-color-temperature-color |
| _TZ3210_hzdhb62z | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_hzy4rjz3 | TS0505B | lights-color-temperature-color |
| _TZ3210_i680rtja | TS0501B | lights-dimmer |
| _TZ3210_ifga63rg | TS0505B | lights-color-temperature-color |
| _TZ3210_it1u8ahz | TS0505B | lights-color-temperature-color |
| _TZ3210_iw0zkcu8 | TS0505B | lights-color-temperature-color |
| _TZ3210_iystcadi | TS0505B | lights-color-temperature-color |
| _TZ3210_jaap6jeb | TS0505B | lights-color-temperature-color |
| _TZ3210_jd3z4yig | TS0505B | lights-color-temperature-color |
| _TZ3210_jicmoite | TS0505B | lights-color-temperature-color |
| _TZ3210_jjqdqxfq | TS0505B | lights-color-temperature-color |
| _TZ3210_jtifm80b | TS0502B | lights-color-temperature |
| _TZ3210_k1msuvg6 | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_k1msuvg6 | TS110E_1gang_2 | lights-dimmer-options-ts110 |
| _TZ3210_klsm24op | TS0505B | lights-color-temperature-color |
| _TZ3210_lfbz816s | TS110F | lights-dimmer |
| _TZ3210_ljoasixl | TS0505B | lights-color-temperature-color |
| _TZ3210_lzqq3u4r | TS0501 | fans-switch-fan-mode |
| _TZ3210_mcm6m1ma | TS0505B | lights-color-temperature-color |
| _TZ3210_mja6r5ix | TS0505B | lights-color-temperature-color |
| _TZ3210_mntza0sw | TS0505B | lights-color-temperature-color |
| _TZ3210_mt5xjoy6 | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_mt5xjoy6 | TS110E_2gang_2 | lights-dimmer-2-options-ts110 |
| _TZ3210_ngqk6jia | TS110E | lights-dimmer-options-ts110-countdown30 |
| _TZ3210_ngqk6jia | TS110E_1gang_2 | lights-dimmer-options-ts110-countdown30 |
| _TZ3210_p9ao60da | TS0505B | lights-color-temperature-color |
| _TZ3210_pagajpog | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_pagajpog | TS110E_2gang_2 | lights-dimmer-2-options-ts110 |
| _TZ3210_pdqu9pot | TS0505B | lights-color-temperature-color |
| _TZ3210_pwauw3g2 | TS0505B | lights-color-temperature-color |
| _TZ3210_qigbovcq | TS0505B | lights-color-temperature-color |
| _TZ3210_r0vzq1oj | TS0505B | lights-color-temperature-color |
| _TZ3210_r0xgkft5 | TS0505B | lights-color-temperature-color |
| _TZ3210_r5afgmkl | TS0505B | lights-color-temperature-color |
| _TZ3210_rcggc0ys | TS0505B | lights-color-temperature-color |
| _TZ3210_s9lumfhn | TS0505B | lights-color-temperature-color |
| _TZ3210_sln7ah6r | TS0505B | lights-color-temperature-color |
| _TZ3210_sroezl0s | TS0504B | lights-color |
| _TZ3210_sw9uxoea | TS0505B | lights-color-temperature-color |
| _TZ3210_syh4kuef | TS0501B | lights-dimmer |
| _TZ3210_tkkb1ym8 | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_tkkb1ym8 | TS110E_2gang_2 | lights-dimmer-2-options-ts110 |
| _TZ3210_ttkgurpb | TS0504B | lights-color |
| _TZ3210_umi6vbsz | TS0505B | lights-color-temperature-color |
| _TZ3210_v5yquxma | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_vfwhhldz | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_vfwhhldz | TS110E_2gang_2 | lights-dimmer-2-options-ts110 |
| _TZ3210_wbsgmojq | TS0505B | lights-color-temperature-color |
| _TZ3210_wdexaypg | TS110E | lights-dimmer-2-options-ts110 |
| _TZ3210_wdexaypg | TS110E_2gang_1 | lights-dimmer-2-options-ts110 |
| _TZ3210_weaqkhab | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_weaqkhab | TS110E_1gang_2 | lights-dimmer-options-ts110 |
| _TZ3210_wxa85bwk | TS0505B | lights-color-temperature-color |
| _TZ3210_x13bu7za | TS0505B | lights-color-temperature-color |
| _TZ3210_xwqng7ol | TS0502B | lights-color-temperature |
| _TZ3210_yluvwhjc | TS0501B | lights-dimmer |
| _TZ3210_ysfo0wla | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_z1vlyufu | TS0505B | lights-color-temperature-color |
| _TZ3210_zbabx9wh | TS0505B | lights-color-temperature-color |
| _TZ3210_zrvxvydd | TS0505B | lights-color-temperature-color |
| _TZ3210_zxbtub8r | TS110E | lights-dimmer-options-ts110 |
| _TZ3210_zxbtub8r | TS110E_1gang_1 | lights-dimmer-options-ts110 |
| _TZB210_0bkzabht | TS0502B | lights-color-temperature |
| _TZB210_3zfp8mki | TS0505B | lights-color-temperature-color |
| _TZB210_417ikxay | TS0505B | lights-color-temperature-color |
| _TZB210_6eed09b9 | TS0505B | lights-color-temperature-color |
| _TZB210_ayx58ft5 | TS0502B | lights-color-temperature |
| _TZB210_eiwanbeb | TS0502B | lights-color-temperature |
| _TZB210_endmggws | TS0505B | lights-color-temperature-color |
| _TZB210_g01ie5wu | TS0501B | lights-dimmer |
| _TZB210_gj0ccsar | TS0505B | lights-color-temperature-color |
| _TZB210_lmqquxus | TS0503B | lights-color-temperature |
| _TZB210_lnnkh3f9 | TS0505B | lights-color-temperature-color |
| _TZB210_rkgngb5o | TS0501B | lights-color-temperature |
| _TZB210_rs0ufzwg | TS0505B | lights-color-temperature-color |
| _TZB210_rwy5hexp | TS0505B | lights-color-temperature-color |
| _TZB210_u3ri0968 | TS0505B | lights-color-temperature-color |
| _TZB210_ue01a0s2 | TS0502B | lights-color-temperature |
| _TZB210_uoiqhjqe | TS0505B | lights-color-temperature-color |
| _TZB210_w9hcix2r | TS0505B | lights-color-temperature-color |
| _TZB210_wxazcmsh | TS0505B | lights-color-temperature-color |
| _TZB210_wy1pyu1q | TS0505B | lights-color-temperature-color |
| _TZB210_yatkpuha | TS0505B | lights-color-temperature-color |
| _TZB210_zdvrsts8 | TS0503B | lights-color |
| _TZB210_zmppwawa | TS0505B | lights-color-temperature-color |
| _TZE200_ubgdwsnr | TS110E | lights-dimmer-options-ts110 |
| eWeLi\x01\x10 | ZB-CL01 | lights-color-temperature-color |
| eWeLight | ZB-CL01 | lights-color-temperature-color |
| eWeLight | ZB-CL02 | lights-color-temperature-color |
| eWeLink | Z102LG03-1 | lights-color-temperature-color |
| eWeLink | ZB-CL01 | lights-color-temperature-color |
| idinio | Dimmer-Switch-ZB3.0 | lights-dimmer |

## zcl-sensors-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| AduroSmart Eria | Smart Siren | safety-smoke-detector-battery |
| Aeotec | ZGA008 | network-repeater |
| Appartme | APRM-04-001 | thermostats-thermostat-battery |
| Aqara | AAQS-S01 | sensors-temp-humidity-battery |
| Aqara | CM-M01 | sensors-temp-humidity-battery |
| Aqara | CM-M01R | sensors-temp-humidity-battery |
| Aqara | DCM-K01 | safety-contact-battery |
| Aqara | DW-S03D | safety-contact-battery |
| Aqara | JT-BZ-03AQ/A | safety-water-leak-battery |
| Aqara | JY-GZ-03AQ | switches-switch-1 |
| Aqara | LEDLBT1-L01 | lights-dimmer |
| Aqara | MFCZQ12LM | safety-contact-battery |
| Aqara | MS-S02 | safety-motion-battery |
| Aqara | MZSD11LM | safety-motion-battery |
| Aqara | MZSD12LM | safety-motion-battery |
| Aqara | MZTD11LM | sensors-illuminance-battery |
| Aqara | PETC1-M01 | safety-motion-battery |
| Aqara | RLS-K01D | sensors-illuminance-battery |
| Aqara | RSD-M01 | lights-dimmer |
| Aqara | SRSC-M01 | safety-water-leak-battery |
| Aqara | TH-S02D | sensors-temp-humidity-battery |
| Aqara | WB-R02D | switches-switch-1 |
| Aqara | WL-S02D | switches-switch-1 |
| Aqara | WRS-R02 | switches-switch-1 |
| Aqara | WS-K08D | switches-switch-1 |
| Aqara | ZHTZ02LM | sensors-temp-humidity-battery |
| Aubess | 40ZH-O | safety-motion-battery |
| Aubess | IH-K665 | safety-water-leak-battery |
| Blaupunkt | PSM-S1 | safety-motion-battery |
| BlitzWolf | BW-IS2 | safety-contact-tamper-battery |
| BlitzWolf | BW-IS4 | sensors-temp-humidity-battery |
| Brennenstuhl | HT CZ 01 | thermostats-thermostat-battery |
| CR Smart Home | TS0203 | safety-contact-battery |
| CR Smart Home | TS0207 | safety-water-leak-battery |
| Candeo | C-ZB-SEDC | safety-contact-battery |
| Candeo | C-ZB-SEMO | safety-motion-illuminance-battery |
| Candeo | C-ZB-SETE | sensors-temp-humidity-battery |
| Candeo | C-ZB-SEWA | safety-water-leak-battery |
| Cavius | 2103 | safety-smoke-detector-battery |
| Centralite | 3157100 | thermostats-thermostat |
| Centralite | 3157100-E | thermostats-thermostat |
| Cleverio | SS100 | safety-contact-battery |
| Cleverio | SS200 | safety-motion-battery |
| Danfoss | 014G2463 | thermostats-thermostat-battery |
| Danfoss | 014G2480 | sensors-temp-humidity-battery |
| Danfoss | 0x0042 | thermostats-thermostat-battery |
| Danfoss | 0x0200 | thermostats-thermostat-battery |
| Danfoss | 0x0210 | thermostats-thermostat-battery |
| Danfoss | 0x0211 | thermostats-thermostat-battery |
| Danfoss | 0x8020 | thermostats-thermostat-battery |
| Danfoss | 0x8021 | thermostats-thermostat-battery |
| Danfoss | 0x8030 | thermostats-thermostat-battery |
| Danfoss | 0x8031 | thermostats-thermostat-battery |
| Danfoss | 0x8034 | thermostats-thermostat-battery |
| Danfoss | 0x8035 | thermostats-thermostat-battery |
| Danfoss | 0x8040 | thermostats-thermostat-battery |
| Danfoss | 0x8041 | thermostats-thermostat-battery |
| EFK | is-thpl-zb | sensors-temp-humidity-battery |
| EGLO | 99106 | safety-motion-battery |
| Elko | EKO09738 | thermostats-thermostat-battery |
| Espressif | ZigbeeRangeExtender | network-repeater |
| Essentials | 120112 | thermostats-thermostat-battery |
| Eurotronic | SPZB0001 | thermostats-thermostat-battery |
| Evology | PAT04-A | safety-motion-battery |
| Ferguson | TH-T_V14 | thermostats-thermostat-battery |
| Fireangel | Alarm_SD_Device | safety-smoke-detector-battery |
| Frient | 94430 | safety-smoke-detector-battery |
| Frient | 94431 | safety-smoke-detector-battery |
| Frient | HMSZB-120 | sensors-temp-humidity-battery |
| Frient | KEPZB-110 | safety-motion-battery |
| Frient | MOSZB-153 | safety-motion-battery |
| Frient | REXZB-111 | network-repeater |
| Futurehome | Co020 | sensors-temp-humidity-battery |
| HEIMAN | HS2AQ-EF-3.0 | safety-smoke-detector-battery |
| HEIMAN | HS2AQ-EM | safety-smoke-detector-battery |
| HEIMAN | Vibration-EF-3.0 | safety-acceleration-battery |
| HEIMAN | Vibration-EF_3.0 | safety-acceleration-battery |
| HEIMAN | Vibration-N | safety-acceleration-battery |
| HOBEIAN | ZG-102ZA | safety-contact-battery |
| HOBEIAN | ZG-106Z | sensors-illuminance-battery |
| HOBEIAN | ZG-204Z | safety-motion-battery |
| HOBEIAN | ZG-222Z | safety-water-leak-battery |
| HOBEIAN | ZG-222ZA | safety-water-leak-battery |
| Hama | 00176592 | thermostats-thermostat-battery |
| Heiman | HS-720ES | sensors-temp-humidity-battery |
| Hejhome | GKZ-SA141 | safety-alarm-battery |
| HiHome | WZB-TRVL | thermostats-thermostat-battery |
| Hive | SLR2d | thermostats-fcu-thermostat |
| Hive | UK7004240 | thermostats-fcu-thermostat |
| KnockautX | FMS2C017 | safety-motion-battery |
| LDS | ZHA-PirSensor | safety-motion-battery |
| LINCUKOO | SZT06 | thermostats-thermostat-battery |
| LK | 545D6306 | thermostats-thermostat-battery |
| Leedarson | ZHA-PIRSensor | safety-motion-battery |
| Lincukoo | G94E | thermostats-thermostat-battery |
| Lincukoo | V04-Z20T | thermostats-thermostat-battery |
| Lincukoo | V06-Z10T | thermostats-thermostat-battery |
| Lincukoo | W10-Z10T | thermostats-thermostat-battery |
| Linkoze | LKDSZ001 | safety-contact-tamper-battery |
| Linkoze | LKMSZ001 | safety-motion-battery |
| Luminea | ZX-5232 | safety-contact-battery |
| Luminea | ZX-5311 | safety-motion-battery |
| Maginon | WT-1 | thermostats-thermostat-battery |
| Marmitek | SM0202_1 | safety-motion-battery |
| Meian | SW02 | safety-water-leak-battery |
| Mercator Ikuü | SMA02P | safety-motion-battery |
| MiBoxer | PIR1-ZB | safety-motion-battery |
| Moes | BHT-002/BHT-006 | thermostats-thermostat-battery |
| Moes | ZSS-JM-GWM-C-MS | safety-contact-battery |
| Moes | ZSS-QT-LS-C | sensors-illuminance-battery |
| Moes | ZSS-QY-WL-C-MS | safety-water-leak-battery |
| Moes | ZSS-S01-GWM-C-MS | safety-contact-battery |
| Moes | ZSS-S01-TH | sensors-temp-humidity-battery |
| Moes | ZSS-X-GWM-C | safety-contact-battery |
| Momax | SL12S | sensors-temp-humidity-battery |
| NabuCasa | SkyConnect | network-repeater |
| NabuCasa | ZBT-2 | network-repeater |
| Nedis | ZBDS10WT | safety-smoke-detector-battery |
| Nedis | ZBHTR10WT | thermostats-thermostat-battery |
| Nedis | ZBSC10WT | sensors-temp-humidity-battery |
| Nedis | ZBSM10WT | safety-motion-battery |
| Niceboy | ORBIS Motion Sensor | safety-motion-battery |
| Niceboy | ORBIS Vibration Sensor | safety-acceleration-battery |
| Niceboy | ORBIS Water Sensor | safety-water-leak-battery |
| Niceboy | ORBIS Windows & Door Sensor | safety-contact-battery |
| Nous | E2 | safety-motion-battery |
| Nous | E3 | safety-contact-battery |
| Nous | E4 | safety-water-leak-battery |
| Nous | L14 | sensors-temp-humidity-battery |
| ONENUO | TS0210_5oy7cysk | safety-acceleration-battery |
| Piri | HSIO18008 | safety-motion-battery |
| Popp | 701721 | safety-smoke-detector-battery |
| QA | QASD1 | safety-contact-battery |
| RTX | ZB-RT1 | thermostats-thermostat-battery |
| Royal Thermo | RTE 77.001B | thermostats-thermostat-battery |
| SDevices | SBDV-00196 | safety-contact-battery |
| SDevices | SBDV-00199 | safety-contact-battery |
| SDevices | SBDV-00202 | safety-contact-battery |
| SDevices | SBDV-00205 | safety-contact-battery |
| SEDEA | eTH730 | sensors-temp-humidity-battery |
| SETTI+ | TRV001 | thermostats-thermostat-battery |
| SMLIGHT | SLZB-06 | network-repeater |
| SMLIGHT | SLZB-06M | network-repeater |
| SMLIGHT | SLZB-06MG24 | network-repeater |
| SMLIGHT | SLZB-06MG26 | network-repeater |
| SMLIGHT | SLZB-06Mg24 | network-repeater |
| SMLIGHT | SLZB-06Mg26 | network-repeater |
| SMLIGHT | SLZB-06P7 | network-repeater |
| SMLIGHT | SLZB-06p10 | network-repeater |
| SMLIGHT | SLZB-07 | network-repeater |
| SMLIGHT | SLZB-07MG24 | network-repeater |
| SMLIGHT | SLZB-07Mg24 | network-repeater |
| SMLIGHT | SLZB-07P10 | network-repeater |
| SMLIGHT | SLZB-07P7 | network-repeater |
| SMLIGHT | SLZB-0xp7 | network-repeater |
| SMLIGHT | SLZB-MR3 | network-repeater |
| SONOFF | DONGLE-E | network-repeater |
| SONOFF | Dongle-LMG21 | network-repeater |
| SONOFF | Dongle-M | network-repeater |
| SONOFF | Dongle-PMG24 | network-repeater |
| Salus Controls | FC600NH | thermostats-fcu-thermostat |
| Samotech | SM301Z | safety-motion-battery |
| Schneider Electric | 755WSA | safety-smoke-temp-humidity-battery |
| Schneider Electric | CCTFR6700 | thermostats-thermostat-battery |
| Schneider Electric | CCTFR6710 | thermostats-thermostat-battery |
| Schneider Electric | Thermostat | thermostats-thermostat |
| Schneider Electric | W599501 | safety-smoke-temp-humidity-battery |
| Shelly | BLU H&T Display ZB | sensors-temp-humidity-battery |
| Shelly | BLU H&T ZB | sensors-temp-humidity-battery |
| Shelly | Dimmer | lights-dimmer-power-voltage-current |
| Shelly | Ecowitt WS90 | sensors-temp-humidity-battery |
| Shelly | Flood | safety-water-leak-battery |
| Shelly | Plug US | plugs-switch-power-energy-voltage-current |
| Shelly | Power Strip | plugs-switch-power-energy-voltage-current |
| Shyugj | DoorSensor-ZB3.0 | safety-contact-battery |
| Sinopé | TH1320ZB-04 | thermostats-thermostat |
| SparkFun | MGM240P | network-repeater |
| Sunricher | HK-SENSOR-CT-A | safety-contact-battery |
| Sygonix | SY-6811314 | thermostats-thermostat-battery |
| TCP Smart | TBUWTRV | thermostats-thermostat-battery |
| TUYATEC-ktge2vqt | RH3001 | safety-contact-tamper-battery |
| TUYATEC-smmlguju | RH3040 | safety-motion-battery |
| Tesla Smart | TS0202 | safety-motion-battery |
| Tesla Smart | TSL-SEN-DOOR | safety-contact-battery |
| Tesla Smart | TSL-SEN-GAS | safety-gas-detector-tamper |
| Tesla Smart | TSL-SEN-SMOKE | safety-smoke-detector-battery |
| Tesla Smart | TSL-TRV-GS361A | thermostats-thermostat-battery |
| Trust | SmokeSensor-EM | safety-smoke-detector-battery |
| TubesZB | BM24 | network-repeater |
| TubesZB | MGM24 | network-repeater |
| Tuya | 19DZT | safety-contact-battery |
| Tuya | 809WZT | safety-motion-battery |
| Tuya | 899WZ | safety-water-leak-battery |
| Tuya | DS04 | safety-contact-battery |
| Tuya | GTZ02 | thermostats-thermostat-battery |
| Tuya | HS09 | sensors-temp-humidity-battery |
| Tuya | HW500A | safety-motion-battery |
| Tuya | MC500A | safety-contact-battery |
| Tuya | RSH-HS06_1 | sensors-temp-humidity-battery |
| Tuya | TH01Z | sensors-temp-humidity-battery |
| Tuya | TH02Z | sensors-temp-humidity-battery |
| Tuya | TH09Z | sensors-temp-humidity-battery |
| Tuya | TS0001_repeater | network-repeater |
| Tuya | TS0201_1 | sensors-temp-humidity-battery |
| Tuya | TS0201_2 | sensors-temp-humidity-battery |
| Tuya | TS0205_smoke_2 | safety-smoke-detector-battery |
| Tuya | TS0207_water_leak_detector_1 | safety-water-leak-battery |
| Tuya | TS0207_water_leak_detector_3 | safety-water-leak-battery |
| Tuya | TY-ZPR06 | safety-motion-battery |
| Tuya | WL-19DWZ | safety-contact-battery |
| Tuya | ZD06 | safety-contact-battery |
| Tuya | ZD08 | safety-contact-battery |
| Tuya | ZMS-102 | safety-motion-battery |
| Tuya | ZMS01 | safety-motion-battery |
| Tuya | ZP01 | safety-motion-battery |
| Tuya | ZTH01/ZTH02 | sensors-temp-humidity-battery |
| Tuya | ZTH05_1 | sensors-temp-humidity-battery |
| Tuya | ZY-ZTH02 | sensors-temp-humidity-battery |
| Tuya | _TZ3000_mqiev3jk | safety-water-leak-battery |
| Tuya | iH-F001 | safety-contact-battery |
| UHome | TWV | thermostats-thermostat-battery |
| Unitec | 30946 | thermostats-thermostat-battery |
| Vimar | 03906 | thermostats-thermostat-battery |
| Weten | Tuya PRO | thermostats-thermostat-battery |
| Wing | WZDA1 | safety-contact-battery |
| Woox | R7047 | safety-contact-battery |
| Xiaomi | MFKZQ01LM | switches-switch-1 |
| Xiaomi | MZSD11LM | safety-motion-battery |
| Xiaomi | MZSD12LM | safety-motion-battery |
| Xiaomi | YTC4004CN | safety-contact-battery |
| Xiaomi | YTC4005CN | safety-contact-battery |
| Xiaomi | YTC4006CN | safety-contact-battery |
| Xiaomi | YTC4007CN | safety-contact-battery |
| Xiaomi | YTC4015CN | safety-water-leak-battery |
| Xiaomi | YTC4016CN | safety-water-leak-battery |
| Xiaomi | YTC4017CN | safety-water-leak-battery |
| Xiaomi | YTC4018CN | safety-water-leak-battery |
| Xiaomi | YTC4019RT | switches-switch-1 |
| Xiaomi | YTC4020RT | switches-switch-1 |
| Xiaomi | YTC4039GL | switches-switch-1 |
| Xiaomi | YTC4040GL | sensors-illuminance-battery |
| Xiaomi | YTC4041GL | switches-switch-1 |
| Xiaomi | YTC4042GL | switches-switch-1 |
| Xiaomi | YTC4043GL | switches-switch-1 |
| Xiaomi | ZHTZ02LM | sensors-temp-humidity-battery |
| Yandex | YNDX-00520 | thermostats-thermostat-battery |
| Yandex | YNDX-00521 | thermostats-thermostat-battery |
| Yandex | YNDX-00522 | thermostats-thermostat-battery |
| Yandex | YNDX-00523 | thermostats-thermostat-battery |
| Yandex | YNDX-00524 | thermostats-thermostat-battery |
| ZBGW7688 | EFR32MG21-V1 | network-repeater |
| ZBGW7688 | EFR32MG21-V2 | network-repeater |
| Zbeacon | TH01 | sensors-temp-humidity-battery |
| Zbeacon | TS0201 | sensors-temp-humidity-battery |
| Zbeacon | TS0202 | sensors-temp-humidity-battery |
| Zbeacon | TS0203 | sensors-temp-humidity-battery |
| Zemismart | SDM01-3Z1 | thermostats-thermostat-battery |
| Zemismart | SDM02-2Z1 | thermostats-thermostat-battery |
| Zemismart | SPM01-1Z2 | thermostats-thermostat-battery |
| _TYZB01_0w3d5uw3 | TS0204 | safety-gas-detector-tamper |
| _TYZB01_2jzbhomb | SM0202 | safety-motion-battery |
| _TYZB01_4mdqxxnn | TS0222 | sensors-illuminance-battery |
| _TYZB01_4obovpbi | TS0216 | safety-alarm-battery |
| _TYZB01_5nr7ncpl | TS0202 | safety-motion-battery |
| _TYZB01_8scntis1 | TS0216 | safety-alarm-battery |
| _TYZB01_bwsijaty | TS0219 | safety-alarm-battery-volume |
| _TYZB01_cbiezpds | SM0201 | sensors-temp-humidity-battery |
| _TYZB01_epni2jgy | TS0203 | safety-contact-battery |
| _TYZB01_fi5yftwv | TS0222 | sensors-illuminance-temp-humidity-battery |
| _TYZB01_ftdkanlj | TS0222 | sensors-illuminance-temp-humidity-battery |
| _TYZB01_jytabjkb | TS0202 | safety-motion-battery |
| _TYZB01_kvwjujy9 | TS0222 | sensors-illuminance-temp-humidity-battery |
| _TYZB01_lzrhtcxu | SM0201 | sensors-temp-humidity-battery |
| _TYZB01_m6ec2pgj | TS0222 | sensors-illuminance-battery |
| _TYZB01_qjqgmqxr | TS0202 | safety-motion-battery |
| _TYZB01_rs7ff6o7 | TS0219 | safety-alarm-battery-volume |
| _TYZB01_sbpc1zrb | TS0216 | safety-alarm-battery |
| _TYZB01_sqmd19i1 | TS0207 | safety-water-leak-battery |
| _TYZB01_ttvdudvx | TS0207 | safety-water-leak-battery |
| _TYZB01_ujfk3xd9 | TS0201 | sensors-temp-humidity-battery |
| _TYZB01_vwqnz1sn | TS0202 | safety-motion-illuminance-battery |
| _TYZB01_wpmo3ja3 | TS0212 | safety-water-leak-battery |
| _TYZB01_wqcac7lo | TS0205 | safety-smoke-detector-battery |
| _TYZB01_ynsiasng | TS0219 | safety-alarm-battery-volume |
| _TYZB01_yr95mpib | SM0202 | safety-motion-battery |
| _TYZB01_z2umiwvq | SM0202 | safety-motion-battery |
| _TYZB01_zqvwka4k | SM0201 | sensors-temp-humidity-battery |
| _TZ1800_ejwkn2h2 | TY0203 | safety-contact-tamper-battery |
| _TZ1800_fcdjzz3s | TY0202 | safety-contact-battery |
| _TZ1800_ho6i0zk9 | TY0203 | safety-contact-tamper-battery |
| _TZ3000_0s1izerx | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_0s9gukzt | TS0207 | safety-water-leak-battery |
| _TZ3000_1twfmkcc | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_26fmupbb | TS0203 | safety-contact-battery |
| _TZ3000_2mbfxlzr | TS0203 | safety-contact-battery |
| _TZ3000_45y4bdjb | SM0212 | safety-gas-detector-tamper-battery-low |
| _TZ3000_4ugnzsli | TS0203 | safety-contact-battery |
| _TZ3000_5k5vh43t | TS0207 | network-repeater |
| _TZ3000_6uzkisv2 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_6ygjfyll | TS0202 | safety-motion-battery |
| _TZ3000_7d8yme6f | TS0203 | safety-contact-battery |
| _TZ3000_7kscdesh | TS0222 | sensors-illuminance-battery |
| _TZ3000_7y90pany | TS0222 | sensors-illuminance-battery |
| _TZ3000_82ptnsd4 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_8uxxzz4b | TS0222 | sensors-illuminance-battery |
| _TZ3000_8ybe88nf | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_8yhypbo7 | TS0203 | safety-contact-battery |
| _TZ3000_996rpfy6 | TS0203 | safety-contact-battery |
| _TZ3000_9kbbfeho | TS0222 | sensors-illuminance-battery |
| _TZ3000_abaplimj | TS0207 | safety-water-leak-battery |
| _TZ3000_akqdg6g7 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_amqudjr0 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_awvmkayh | TS0207 | safety-water-leak-battery |
| _TZ3000_bgsigers | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_bguser20 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_bjawzodf | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_bjawzodf | TY0201 | sensors-temp-humidity-battery |
| _TZ3000_bpkijo14 | TS0203 | safety-contact-battery |
| _TZ3000_bsvqrxru | TS0202 | safety-motion-battery |
| _TZ3000_c8bqthpo | TS0207 | safety-water-leak-battery |
| _TZ3000_ceplrhnu | TS0222 | sensors-illuminance-temp-humidity-battery |
| _TZ3000_decxrtwa | TS0203 | safety-contact-battery |
| _TZ3000_do6txrcw | TS0222 | sensors-illuminance-battery |
| _TZ3000_dowj6gyi | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_eit7p838 | TS0207 | safety-water-leak-battery |
| _TZ3000_f2bw0b6k | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_fie1dpkm | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_fllyghyj | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_gdsvhfao | TS0001 | network-repeater |
| _TZ3000_gntwytxo | TS0203 | safety-contact-battery |
| _TZ3000_gszjt2xx | TS0207 | network-repeater |
| _TZ3000_h4wnrtck | TS0202 | safety-motion-battery |
| _TZ3000_hgm6k8ku | TS0207 | network-repeater |
| _TZ3000_hktqahrq | TS0202 | safety-motion-battery |
| _TZ3000_hy6ncvmw | TS0222 | sensors-illuminance-battery |
| _TZ3000_isw9u95y | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_itnrsufe | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_j6adk9id | TS0222 | sensors-illuminance-battery |
| _TZ3000_jmrgyl7o | TS0202 | safety-motion-battery |
| _TZ3000_k4ej3ww2 | TS0207 | safety-water-leak-battery |
| _TZ3000_kkerjand | TS0601 | sensors-temp-humidity-battery |
| _TZ3000_kky16aay | TS0222 | sensors-illuminance-temp-humidity-battery |
| _TZ3000_kstbkt6a | TS0207 | safety-water-leak-battery |
| _TZ3000_kxlmv9ag | TS0207 | network-repeater |
| _TZ3000_kyb656no | TS0207 | safety-water-leak-battery |
| _TZ3000_l6rsaipj | TS0222 | sensors-illuminance-battery |
| _TZ3000_lbtpiody | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_lf56vpxj | TS0202 | safety-motion-battery |
| _TZ3000_lltemgsf | TS0202 | safety-motion-battery |
| _TZ3000_lqmvrwa2 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_m0vaazab | TS0207 | network-repeater |
| _TZ3000_mcxw5ehu | TS0202 | safety-motion-battery |
| _TZ3000_mg4dy6z6 | TS0202 | safety-motion-battery |
| _TZ3000_misw04hq | TS0207 | network-repeater |
| _TZ3000_mqiev3jk | TS0207 | safety-water-leak-battery |
| _TZ3000_msl6wxk9 | TS0202 | safety-motion-battery |
| _TZ3000_mugyhz0q | TS0207 | safety-water-leak-battery |
| _TZ3000_mwd3c2at | TS0202 | safety-motion-battery |
| _TZ3000_mxzo5rhf | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_n0lphcok | TS0001 | network-repeater |
| _TZ3000_n0lphcok | TS0207 | network-repeater |
| _TZ3000_n2egfsli | TS0203 | safety-contact-battery |
| _TZ3000_nkkl7uzv | TS0207 | network-repeater |
| _TZ3000_nlsszmzl | TS0207 | network-repeater |
| _TZ3000_nss8amz9 | TS0202 | safety-motion-battery |
| _TZ3000_o4mkahkc | TS0202 | safety-motion-battery |
| _TZ3000_ocjlo4ea | TS0207 | safety-water-leak-battery |
| _TZ3000_osu834un | TS0203 | safety-contact-battery |
| _TZ3000_otvn3lne | TS0202 | safety-motion-battery |
| _TZ3000_oxslv1c9 | TS0203 | safety-contact-battery |
| _TZ3000_pjb1ua0m | TS0203 | safety-motion-battery |
| _TZ3000_qaaysllp | TS0201 | sensors-illuminance-temp-humidity-battery |
| _TZ3000_qomxlryd | TS0202 | safety-motion-battery |
| _TZ3000_qrldbmfn | TS0203 | safety-contact-battery |
| _TZ3000_r80pzsb9 | TS0207 | network-repeater |
| _TZ3000_rcuyhwe3 | TS0203 | safety-contact-battery |
| _TZ3000_rdhukkmi | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_rid8lzvo | TS0203 | safety-contact-battery |
| _TZ3000_rusu2vzb | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_saiqcn0y | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_sgpbz53b | TS0207 | network-repeater |
| _TZ3000_shopg9ss | TS0207 | network-repeater |
| _TZ3000_t3vvhrmh | TS0203 | safety-contact-battery |
| _TZ3000_t6jriawg | TS0207 | safety-water-leak-battery |
| _TZ3000_t9qqxn70 | TS0222 | sensors-illuminance-temp-humidity-battery |
| _TZ3000_timx9ivq | TS0203 | safety-contact-battery |
| _TZ3000_trdx8uxs | TS0001 | network-repeater |
| _TZ3000_udyjylt7 | TS0203 | safety-contact-battery |
| _TZ3000_ufttklsz | TS0207 | network-repeater |
| _TZ3000_upgcbody | TS0207 | safety-water-leak-battery |
| _TZ3000_utwgoauk | SNZB-02 | sensors-temp-humidity-battery |
| _TZ3000_v1w2k9dd | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_v7chgqso | TS0203 | safety-contact-battery |
| _TZ3000_vdfwjopk | TS0219 | safety-alarm-battery-volume |
| _TZ3000_wbrlnkm9 | TS0203 | safety-contact-battery |
| _TZ3000_wlquqiiz | TS0207 | network-repeater |
| _TZ3000_wmlc9p9z | TS0207 | network-repeater |
| _TZ3000_wn65ixz9 | TS0001 | network-repeater |
| _TZ3000_xr3htd96 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_yd2e749y | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_yfekcy3n | TS0203 | safety-contact-battery |
| _TZ3000_yujem9ee | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_yupc0pb7 | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_ywagc4rj | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_zfirri2d | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_zl1kmjqx | TS0201 | sensors-temp-humidity-battery |
| _TZ3000_zl1kmjqx | TY0201 | sensors-temp-humidity-battery |
| _TZ3040_6ygjfyll | TS0202 | safety-motion-battery |
| _TZ3040_bb6xaihh | TS0202 | safety-motion-battery |
| _TZ3040_fwxuzcf4 | TS0202 | safety-motion-battery |
| _TZ3040_msl6wxk9 | TS0202 | safety-motion-battery |
| _TZ3040_wqmtjsyk | TS0202 | safety-motion-battery |
| _TZ3210_0aqbrnts | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_alxkwn0h | TS0201 | sensors-temp-humidity-battery |
| _TZ3210_cwamkvua | TS0202 | safety-motion-battery |
| _TZ3210_jijr1sss | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_jowhpxop | TS0203 | safety-contact-tamper-battery |
| _TZ3210_m3mxv66l | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_ncw88jfq | TS0201 | sensors-temp-humidity-battery |
| _TZ3210_oekbi7o4 | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_ohvnwamm | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_p68kms0l | TS0207 | safety-water-leak-battery |
| _TZ3210_rxqls8v0 | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_tgvtvdoc | TS0207 | safety-water-leak-battery |
| _TZ3210_up3pngle | TS0205 | safety-smoke-detector-battery |
| _TZ3210_wuhzzfqg | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZ3210_zmy9hjay | TS0202 | safety-motion-illuminance-temp-humidity-tamper-battery |
| _TZE204_myd45weu | TS0222 | sensors-illuminance-temp-humidity-battery |
| computime | PUMM01102 | thermostats-thermostat-battery |
| eWeLink | CK-TLSR8656-SS5-01(7002) | safety-motion-battery |
| eWeLink | CK-TLSR8656-SS5-01(7003) | safety-contact-battery |
| eWeLink | CK-TLSR8656-SS5-01(7014) | sensors-temp-humidity-battery |
| eWeLink | CK-TLSR8656-SS5-01(7019) | safety-water-leak-battery |
| eWeLink | RHK06 | safety-contact-battery |
| eWeLink | RHK08 | sensors-temp-humidity-battery |
| eWeLink | RHK09 | safety-motion-battery |
| eWeLink | SNZB-02 | sensors-temp-humidity-battery |
| eWeLink | SNZB-04 | safety-contact-battery |
| eWeLink | SQ510A | safety-motion-battery |
| easyiot | ZB-GW04 | network-repeater |
| easyiot | ZB-GW04-1v1 | network-repeater |
| easyiot | ZB-GW04-1v2 | network-repeater |
| easyiot | ZB-RS485 | network-repeater |
| iHseno | _TZ3000_lzdjjfss | safety-acceleration-battery |
| zbeacon | DS01 | safety-contact-battery |

## zcl-switch-wonjj6768

| Manufacturer | Model | Device Profile |
|---|---|---|
| AOYAN | TS011F_AOYAN | plugs-switch-power-energy-voltage |
| AVATTO | 1gang N-ZLWSM01 | switches-switch-1-countdown-switch-type |
| AVATTO | 2gang N-ZLWSM01 | switches-switch-2-countdown-switch-type |
| AVATTO | 3gang N-ZLWSM01 | switches-switch-3-countdown-switch-type |
| AVATTO | LZWSM16-2 | switches-switch-2-countdown-switch-type |
| AVATTO | LZWSM16-3 | switches-switch-3-countdown-switch-type |
| AVATTO | MIUCOT10Z | plugs-switch-power-energy-voltage |
| AVATTO | TS0004_1 | switches-switch-4 |
| AVATTO | TS0006_1 | switches-switch-6-basic |
| AVATTO | ZBTS60-01 | switches-switch-1 |
| AVATTO | ZBTS60-03 | switches-switch-3 |
| AVATTO | ZBTS60-04 | switches-switch-4 |
| AVATTO | ZTS02 | switches-switch-2 |
| AVATTO | ZWOT12 | switches-switch-4 |
| AVATTO | ZWOT16-W2 | switches-switch-3 |
| AVATTO | ZWSM16-1 | switches-switch-1 |
| AVATTO | ZWSM16-1-Zigbee | switches-switch-1 |
| AVATTO | ZWSM16-2 | switches-switch-2 |
| AVATTO | ZWSM16-2-Zigbee | switches-switch-2 |
| AVATTO | ZWSM16-3 | switches-switch-3 |
| AVATTO | ZWSM16-3-Zigbee | switches-switch-3 |
| AVATTO | ZWSM16-4 | switches-switch-4 |
| AVATTO | ZWSM16-4-Zigbee | switches-switch-4 |
| AduroSmart ERIA | ONOFF_METER_RELAY | plugs-switch-power-energy-voltage |
| Aubess | TMZ02 | switches-switch-2 |
| Aubess | TMZ02L-16A-B | switches-switch-1-countdown-switch-type |
| Aubess | TS011F_plug_1 | plugs-switch |
| Aubess | WHD02 | switches-switch-1-countdown-switch-type |
| BSEED | S-PC86ZEUSK1B | plugs-switch |
| BSEED | TS0003 | switches-switch-3 |
| BSEED | TS011F_plug_1_2 | plugs-switch-power-energy-voltage |
| BSEED | TS011F_plug_3_1 | plugs-switch-power-energy-voltage |
| BSEED | Zigbee Socket | plugs-switch |
| BSEED | _TZ3000_o1jzcxou | plugs-switch |
| BSEED | _TZ3210_5ct6e7ye | plugs-switch-power-energy-voltage |
| BTicino | 3577C | switches-switch-1 |
| BTicino | 3584C | switches-switch-1 |
| BTicino | F40T125A | din-rail-switch-power-energy-voltage-current |
| BTicino | FC80AC | switches-switch-1 |
| BTicino | FC80CC | switches-switch-1 |
| BTicino | FC80GCS | din-rail-switch-power-energy-voltage-current |
| BTicino | FC80RC | switches-switch-1 |
| BTicino | LN4570CWI | switches-switch-1 |
| Bacchus | Water_Station | plugs-switch |
| Bacchus | Water_Station.Modkam | plugs-switch |
| Bandi | BDS03G1 | switches-switch-1 |
| BlitzWolf | BW-SHP13 | plugs-switch-power-energy-voltage |
| BlitzWolf | BW-SHP15 | plugs-switch-power-energy-voltage |
| Bosch | BSP-EZ2 | plugs-switch-power-energy-voltage |
| Bosch | BSP-GZ2 | plugs-switch-power-energy-voltage |
| Candeo | C-ZB-SM205-2G | switches-switch-2 |
| Candeo | C205 | switches-switch-1 |
| ClickSmart+ | CMA30035 | plugs-switch |
| ClickSmart+ | CMA30036 | plugs-switch-2 |
| Coibeu | ZB414 | switches-switch-4 |
| Colorock | CR-MNZ1 | switches-switch-1 |
| Connecte | 4500990 | plugs-switch-power-energy-voltage-current |
| Connecte | 4500991 | plugs-switch-power-energy-voltage-current |
| Connecte | 4500992 | plugs-switch-power-energy-voltage-current |
| Connecte | 4500993 | plugs-switch-power-energy-voltage-current |
| Coswall | CS-AJ-DE2U-ZG-11 | plugs-switch-power-energy-voltage |
| EARU | EAKCB-T-M-Z | din-rail-switch-power-energy-voltage-current-threshold |
| EARU | EAYCB-Z-2P | din-rail-switch-power-energy-voltage-current-threshold |
| EKAZA | EKAC-T3092Z | switches-switch-2 |
| Earda | ESW-2ZAA-EU | switches-switch-2 |
| Elivco | LSPA9 | plugs-switch-power-energy-voltage |
| Elko | EKO07250 | switches-switch-1 |
| Elko | EKO07251 | switches-switch-1 |
| Elko | EKO07252 | switches-switch-1 |
| Elko | EKO07253 | switches-switch-1 |
| Elko | EKO20004 | switches-switch-1 |
| Elko | EKO30198 | switches-switch-1 |
| Elko | EKO30199 | switches-switch-1 |
| GIEX | GX02 | switches-switch-1 |
| Gira | 2430-100 | switches-switch-1 |
| Gira | 2435-10 | switches-switch-1 |
| Girier | JR-ZPM01 | plugs-switch-power-energy-voltage |
| Girier | ZB08 | switches-switch-3-countdown-switch-type |
| GreenSun | HSC-ZW-EU | plugs-switch-power-energy-voltage |
| HEIMAN | HS2SW1A-EF-3.0 | switches-switch-1 |
| HEIMAN | HS2SW1A-EFR-3.0 | switches-switch-1 |
| HEIMAN | HS2SW2A-EF-3.0 | switches-switch-2 |
| HEIMAN | HS2SW2A-EFR-3.0 | switches-switch-2 |
| HEIMAN | HS2SW3A-EF-3.0 | switches-switch-3 |
| HEIMAN | HS2SW3A-EFR-3.0 | switches-switch-3 |
| HEIMAN | SmartPlug-N | plugs-switch-power-energy-voltage |
| HOBEIAN | ZG-301Z | switches-switch-1-countdown-switch-type |
| HOBEIAN | ZG-301Z-2CH | switches-switch-2 |
| HOBEIAN | ZG-301Z-3CH | switches-switch-3 |
| HOBEIAN | ZG-305Z | switches-switch-2 |
| HOBEIAN | ZG-807Z | valves-valve-battery |
| HOMMYN | RLZBNN01 | switches-switch-1-countdown-switch-type |
| Haozee | HT-SP-ZB-01 | plugs-switch-power-energy-voltage |
| Hej | BDS03G2 | switches-switch-2 |
| Homeetec | 37022463-1 | switches-switch-2 |
| Homeetec | 37022474_1 | switches-switch-3 |
| Homeetec | Homeetec_37022454 | switches-switch-1 |
| IKEA | E2006 | switches-switch-1 |
| Immax | 07573L | din-rail-switch-power-energy-voltage-current-threshold-no-temp |
| Innr | SP 242 | plugs-switch-power-energy-voltage |
| Innr | SP 244 | plugs-switch-power-energy-voltage |
| Iolloi | ID-EU20FW09 | switches-switch-2 |
| Jung | ZLLHS4 | switches-switch-1 |
| KTNNKG | ZB1248-10A | plugs-switch |
| KlikAanKlikUit | Built-in Switch | switches-switch-1 |
| LED-Trading | UP-SA-9127D | switches-switch-2 |
| LEDVANCE | 4058075729261 | plugs-switch |
| LEDVANCE | AB3257001NJ | plugs-switch |
| LEDVANCE | AC03360 | plugs-switch |
| LEDVANCE | AC10691 | plugs-switch |
| LELLKI | TS011F_plug | plugs-switch |
| LELLKI | WP33-EU | switches-switch-4 |
| Larkkey | PS080 | plugs-switch |
| Larkkey | PS580 | plugs-switch-2 |
| Legrand | 199142 | switches-switch-1 |
| Legrand | 412172 | din-rail-switch-power-energy-voltage-current |
| Lmiot | doorlock_5001 | switches-switch-1 |
| Loginovo | ZG-101ZL | switches-switch-1 |
| Lonsonho | X701 | switches-switch-1 |
| Lonsonho | X702 | switches-switch-2 |
| Lonsonho | X702A | switches-switch-2 |
| Lonsonho | X703A | switches-switch-3 |
| LoraTap | RR400ZB | plugs-switch |
| LoraTap | SP400ZB | plugs-switch |
| Lotus | Ref 2117 | switches-switch-5 |
| MHCOZY | TYWB 4ch-RF | switches-switch-4 |
| MODEMIX | MOD037 | plugs-switch-power-energy-voltage |
| MODEMIX | MOD048 | plugs-switch-power-energy-voltage |
| MakeGood | MG-ZG04W/B/G | switches-switch-4 |
| MatSee Plus | ATMS1602Z | din-rail-switch-power-energy-voltage-current |
| MatSee Plus | PJ-MINI-ZSW01 | plugs-switch-power-energy-voltage |
| MatSee Plus | PJ-ZSW01 | plugs-switch-power-energy-voltage |
| Mercator Ikuü | SISW01 | plugs-switch |
| Mercator Ikuü | SPBS01G | plugs-switch |
| Mercator Ikuü | SSW01 | switches-switch-1 |
| Mercator Ikuü | SSW02 | switches-switch-2 |
| Mercator Ikuü | SSW04 | switches-switch-4 |
| Mercator Ikuü | SSWM10-ZB | switches-switch-1 |
| Milfra | M11Z | switches-switch-5 |
| Moes | A5 | din-rail-switch-power-energy-voltage-current-threshold |
| Moes | MS-104CZ | switches-switch-3 |
| Moes | Moes_plug | plugs-switch-power-energy-voltage |
| Moes | ZK-CH-2U | plugs-switch-2 |
| Moes | ZK-EU | plugs-switch-power-energy-voltage |
| Moes | ZM-104-M | switches-switch-1 |
| Moes | ZM-104-M-16AM | switches-switch-1-power-options |
| Moes | ZM-104B-M | switches-switch-2 |
| Moes | ZM4LT1 | switches-switch-1 |
| Moes | ZM4LT2 | switches-switch-2 |
| Moes | ZM4LT3 | switches-switch-3 |
| Moes | ZM4LT4 | switches-switch-4 |
| Moes | ZS-EUB_2gang | switches-switch-2 |
| Moes | ZS-US2-BK-MS | switches-switch-2 |
| Mumubiz | ZJSB9-80Z | plugs-switch |
| NEO | NAS-WR01B | plugs-switch-power-energy-voltage |
| NEO | PLUG-001SPB2 | plugs-switch-power-energy-voltage |
| NEO Coolcam | PLUG-001SPB2 | plugs-switch-power-energy-voltage |
| Nedis | ZBPO130FWT | plugs-switch-power-energy-voltage |
| Nous | A10Z | plugs-switch-power-energy-voltage |
| Nous | A1Z | plugs-switch-power-energy-voltage |
| Nous | A4Z | plugs-switch-2-power-energy-voltage |
| Nous | A6Z | plugs-switch-power-energy-voltage |
| Nous | A6Z_polling | plugs-switch-power-energy-voltage |
| Nous | A7Z | plugs-switch-power-energy-voltage |
| Nous | A9Z | plugs-switch-power-energy-voltage |
| Nous | B1Z | switches-switch-1 |
| Nous | B2Z | switches-switch-1-power-options |
| Nous | B3Z | switches-switch-2-power-options |
| Nous | B5Z | switches-switch-1-power-options |
| Nous | B6Z | switches-switch-1 |
| Nous | DZ | din-rail-switch-power-energy-voltage-current |
| Nous | L13Z | switches-switch-2 |
| Nous | L6Z | switches-switch-1-power-options |
| Nous | LZ3 | switches-switch-1 |
| Nova Digital | FZB-2 | switches-switch-2 |
| Nova Digital | FZB-3 | switches-switch-3 |
| Nova Digital | NT-S2 | plugs-switch-2 |
| Nova Digital | NTS2-W-B | plugs-switch-2 |
| Nova Digital | NTZB-01 | switches-switch-2 |
| Nova Digital | NTZB-02 | switches-switch-3 |
| Nova Digital | QZ-S2Q | plugs-switch-2 |
| Nova Digital | SA-1 | switches-switch-1 |
| Nova Digital | SA-3 | switches-switch-3 |
| Nova Digital | SA-4 | switches-switch-4 |
| Nova Digital | TPZ-1 | switches-switch-1 |
| Nova Digital | TPZ-2 | switches-switch-2 |
| Nova Digital | TPZ-3 | switches-switch-3 |
| Nova Digital | TPZ-4 | switches-switch-4 |
| Nova Digital | WS-US-ZB | switches-switch-3 |
| OXT | SWTZ21 | switches-switch-1 |
| OXT | SWTZ22 | switches-switch-2 |
| OXT | SWTZ23 | switches-switch-3 |
| OXT | SWTZ27 | switches-switch-4 |
| Oz Smart Things | WSP403 | switches-switch-1 |
| PLAID SYSTEMS | PS-SPRZMS-SLP3 | switches-switch-3 |
| PSMART | T440 | plugs-switch-power-energy-voltage |
| PSMART | T441 | switches-switch-1 |
| PSMART | T442 | switches-switch-2 |
| PSMART | T461 | switches-switch-1 |
| PSMART | T462 | switches-switch-2 |
| RSH | SB03-Zigbee | switches-switch-3 |
| RSH | SB04-Zigbee | switches-switch-4 |
| RSH | TS0002_basic_2 | switches-switch-2 |
| Rely Electronics | _TZ3000_5rpu3r0d | switches-switch-1 |
| Rely Electronics | _TZ3000_dershnvx | switches-switch-2 |
| Revolt | NX-4911 | plugs-switch |
| RoomsAI | 37022463-2 | switches-switch-2 |
| RoomsAI | 37022474_2 | switches-switch-3 |
| RoomsAI | RoomsAI_37022454 | switches-switch-1 |
| Rylike | RY-WS02Z | plugs-switch-2 |
| SMATRUL | TMZ02L-16A-W | switches-switch-1-countdown-switch-type |
| SONOFF | S60ZBTPG | plugs-switch-power-energy-voltage |
| SONOFF | SWV-ZFE | valves-valve-battery |
| SONOFF | SWV-ZFU | valves-valve-battery |
| SONOFF | SWV-ZNU | valves-valve-battery |
| Schneider Electric | A9MEM1570 | din-rail-switch-power-energy-voltage-current |
| Schneider Electric | CCTFR6500 | plugs-switch-power-energy-voltage |
| Shelly | 1 | plugs-switch |
| Sibling | Powerswitch-ZK(W) | switches-switch-1 |
| Somfy | ON/OFF (2CH) | switches-switch-2 |
| Sunricher | ON/OFF (2CH) | switches-switch-2 |
| Sunricher | ON/OFF(2CH) | switches-switch-2 |
| Sunricher | SR-ZG9100A-S | switches-switch-1 |
| Sunricher | SR-ZG9101SAC-HP-SWITCH-2CH | switches-switch-2 |
| Sunricher | SR-ZG9101SAC-HP-SWITCH-B | switches-switch-1 |
| TOMZN | TOB9Z-63M | din-rail-switch-power-energy-voltage-current |
| TUYATEC | GDKES-01TZXD | switches-switch-1 |
| TUYATEC | GDKES-02TZXD | switches-switch-2 |
| TUYATEC | GDKES-03TZXD | switches-switch-3 |
| TUYATEC | GDKES-04TZXD | switches-switch-4 |
| Teekar | SWP86-01OG | plugs-switch |
| Third Reality | 3RSP0186Z | plugs-switch |
| Third Reality | 3RSPE02065Z | plugs-switch |
| Third Reality | 3RSPJ0187Z | plugs-switch |
| Third Reality | 3RSPU01080Z | plugs-switch |
| Third Reality | 3RWP01073Z | plugs-switch-2 |
| Tomzn | TOB9Z-VAP | din-rail-switch-power-energy-voltage-current-threshold |
| Tongou | TO-Q-SY1-JZT | din-rail-switch-power-energy-voltage-current |
| Tongou | TO-Q-SY1-ZT | plugs-switch |
| Tongou | TO-Q-SY2-163JZT | din-rail-switch-power-energy-voltage-current-threshold |
| Tuya | DS-111 | switches-switch-4 |
| Tuya | M10Z | switches-switch-3 |
| Tuya | QS-zigbee-S08-16A-RF | switches-switch-1-countdown-switch-type |
| Tuya | SM-AW713Z | valves-valve-indicator-mode |
| Tuya | TS0003_1 | switches-switch-3 |
| Tuya | XMSJ | switches-switch-1 |
| Tuya | XSH01A | switches-switch-1 |
| Tuya | XSH01B | switches-switch-2-power-options |
| Tuya | ZG-001 | switches-switch-1 |
| Tuya | ZG-2002-RF | switches-switch-2 |
| Tuya | iHSW02 | switches-switch-1-countdown-switch-type |
| UNSH | SMKG-1KNL-EU-Z | din-rail-switch-power-energy-voltage-current-threshold |
| UseeLink | SM-0306E-2W | switches-switch-5 |
| UseeLink | SM-AZ713 | plugs-switch |
| UseeLink | SM-O301-AZ | switches-switch-5 |
| UseeLink | SM-SO306E/K/M | switches-switch-5 |
| VIKEFON | TS011F | plugs-switch-power-energy-voltage |
| Vensi | E321V000A03 | switches-switch-1 |
| Vizo | VZ-221S | switches-switch-4 |
| Vizo | VZ-222S | switches-switch-4 |
| Vizo | VZ-223S | switches-switch-4 |
| Vrey | VR-X712U-0013 | switches-switch-2 |
| Woolley | SA-028-1 | plugs-switch |
| Woolley | SA-029-1 | plugs-switch |
| Zbeacon | TS011F | plugs-switch-power-energy-voltage |
| Zbeacon | TS011F_plug_1_1 | plugs-switch-power-energy-voltage |
| Zemismart | KES-606US-L3 | switches-switch-3 |
| Zemismart | SPM02-3Z3 | switches-switch-3 |
| Zemismart | TB26-2 | switches-switch-2 |
| Zemismart | TB26-3 | switches-switch-3 |
| Zemismart | ZM-CSW002-D_switch | switches-switch-2 |
| Zemismart | ZM-H7 | switches-switch-1 |
| Zemismart | ZM-L03E-Z | switches-switch-3 |
| Zemismart | ZMO-606-S2 | switches-switch-3 |
| Zemismart | ZW-EU-01 | plugs-switch |
| Zemismart | ZW-EU-02 | plugs-switch-2 |
| _TYST11_8daqwrsj | daqwrsj | switches-switch-1 |
| _TYST11_qtbrwrfv | tbrwrfv | switches-switch-1 |
| _TYZB01_4tlksk8a | TS0001 | valves-valve-indicator-mode |
| _TYZB01_4vgantdz | TS0001 | switches-switch-1 |
| _TYZB01_7yidyqxd | TS0108 | plugs-switch-2 |
| _TYZB01_aneiicmq | TS0003 | switches-switch-1 |
| _TYZB01_digziiav | TS0002 | switches-switch-2 |
| _TYZB01_digziiav | TS0003 | switches-switch-2 |
| _TYZB01_hlla45kx | TS011F | switches-switch-2 |
| _TYZB01_ijihzffk | TS0101 | plugs-switch |
| _TYZB01_iuepbmpv | TS0121 | plugs-switch-power-energy-voltage-current |
| _TYZB01_mtunwanm | TS011F | plugs-switch |
| _TYZB01_ncutbjdi | TS0003 | switches-switch-1 |
| _TYZB01_reyozfcg | TS0001 | switches-switch-1 |
| _TYZB01_rifa0wlb | TS0011 | valves-valve-indicator-mode |
| _TYZB01_u9kkqh5o | TS0003 | switches-switch-1 |
| _TYZB01_uqkphoed | TS0002 | switches-switch-2 |
| _TYZB01_uqkphoed | TS0003 | switches-switch-2 |
| _TYZB01_ymcdbl3u | TS0111 | valves-valve-indicator-mode |
| _TYZB01_zsl6z0pw | TS0002 | switches-switch-2 |
| _TYZB01_zsl6z0pw | TS0003 | switches-switch-2 |
| _TZ3000_00mk2xzy | TS011F | plugs-switch |
| _TZ3000_01gpyda5 | TS0002 | switches-switch-2 |
| _TZ3000_0ghwhypc | TS0001 | switches-switch-1-power-options |
| _TZ3000_0q5fjqgw | TS0003 | switches-switch-3 |
| _TZ3000_0yxeawjt | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_18ejxno0 | TS0012 | switches-switch-2 |
| _TZ3000_1adss9de | TS0001 | switches-switch-1-power-options |
| _TZ3000_1hwjutgo | TS011F | plugs-switch |
| _TZ3000_1obwwnmq | TS011F | switches-switch-3 |
| _TZ3000_266azbg3 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_2iiimqs9 | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3000_2putqrmw | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_2uollq9d | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_2xlvlnez | TS011F | switches-switch-2 |
| _TZ3000_303avxxt | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_303avxxt | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold-no-temp |
| _TZ3000_3a9beq8a | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_3ias4w4o | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_3n2minvf | TS0004 | switches-switch-4 |
| _TZ3000_3uimvkn6 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_3zofvcaa | TS011F | switches-switch-4 |
| _TZ3000_46t1rvdu | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_4o16jdca | TS0003 | switches-switch-3 |
| _TZ3000_4rbqgcuv | TS0001 | switches-switch-1 |
| _TZ3000_4uf3d0ax | TS011F | switches-switch-3 |
| _TZ3000_4ux0ondb | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_4xfqlgqo | TS0002 | switches-switch-2 |
| _TZ3000_4zf0crgo | TS0012 | switches-switch-2-countdown-switch-type |
| _TZ3000_54hjn4vs | TS0002 | switches-switch-2 |
| _TZ3000_5af5r192 | TS0049 | valves-valve-battery |
| _TZ3000_5ajpkyq6 | TS0004 | switches-switch-4 |
| _TZ3000_5gey1ohx | TS0002 | switches-switch-2 |
| _TZ3000_5ksufhqi | TS0002 | switches-switch-2 |
| _TZ3000_5ng23zjs | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_5rpu3r0d | TS0001 | switches-switch-1 |
| _TZ3000_5ucujjts | TS0001 | valves-valve-indicator-mode |
| _TZ3000_65ajyxua | TS0001 | switches-switch-1 |
| _TZ3000_66fekqhh | TS0003 | switches-switch-3 |
| _TZ3000_6axxqqi2 | TS0001 | switches-switch-1 |
| _TZ3000_6l1pjfqe | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3000_6s5dc9lx | TS011F | switches-switch-2 |
| _TZ3000_785olaiq | TS0003 | switches-switch-3 |
| _TZ3000_7ed9cqgi | TS0002 | switches-switch-2 |
| _TZ3000_7issjl2q | TS011F | switches-switch-1 |
| _TZ3000_8a833yls | TS011F | plugs-switch |
| _TZ3000_8bxrzyxz | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3000_8fdayfch | TS011F | plugs-switch |
| _TZ3000_8n7lqbm0 | TS0001 | switches-switch-1 |
| _TZ3000_8nyaanzb | TS011F | switches-switch-2 |
| _TZ3000_92qd4sqa | TS011F | switches-switch-2 |
| _TZ3000_9djocypn | TS011F | switches-switch-5 |
| _TZ3000_aa5t61rh | TS0002 | switches-switch-2 |
| _TZ3000_aaifmpuq | TS0002 | switches-switch-2-power-options |
| _TZ3000_abjodzas | TS0011 | switches-switch-1 |
| _TZ3000_afgzktgb | TS0001 | switches-switch-1 |
| _TZ3000_air9m6af | TS011F | switches-switch-5 |
| _TZ3000_aknpkt02 | TS0003 | switches-switch-3 |
| _TZ3000_amdymr7l | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_aracgljk | TS0003 | switches-switch-3 |
| _TZ3000_ark8nv4y | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_avky2mvc | TS0003 | switches-switch-3 |
| _TZ3000_avotanj3 | TS0013 | switches-switch-3-countdown-switch-type |
| _TZ3000_b1q8kwmh | TS011F | plugs-switch |
| _TZ3000_b28wrpvx | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_bep7ccew | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3000_bezfthwc | TS0001 | switches-switch-1 |
| _TZ3000_bfn1w0mm | TS011F | plugs-switch |
| _TZ3000_bhcpnvud | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_biakwrag | TS0012 | switches-switch-2 |
| _TZ3000_bkfe0bab | TS011F | switches-switch-1 |
| _TZ3000_blhvsaqf | TS0001 | switches-switch-1 |
| _TZ3000_bmqxalil | TS0001 | switches-switch-1 |
| _TZ3000_bppxj3sf | TS011F | switches-switch-5 |
| _TZ3000_br3laukf | TS0101 | plugs-switch |
| _TZ3000_bvij6kod | TS0003 | switches-switch-3 |
| _TZ3000_bvrlqyj7 | TS0002 | switches-switch-2 |
| _TZ3000_c7nc9w3c | TS011F | plugs-switch-3-power-energy-voltage-current |
| _TZ3000_cayepv1a | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_cayepv1a | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_cehuw1lw | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_cfnprab5 | TS011F | switches-switch-5 |
| _TZ3000_cicwjqth | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_cjfmu5he | TS0049 | valves-valve-battery |
| _TZ3000_cjrngdr3 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_cmcjbqup | TS0001 | valves-valve-indicator-mode |
| _TZ3000_cpozgbrx | TS0001 | switches-switch-1 |
| _TZ3000_criiahcg | TS0002 | switches-switch-2 |
| _TZ3000_ctftgjwb | TS0001 | switches-switch-1 |
| _TZ3000_cvis4qmw | TS0006 | switches-switch-6-basic |
| _TZ3000_cymsnfvf | TS011F | switches-switch-2 |
| _TZ3000_dd8wwzcy | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3000_dershnvx | TS0002 | switches-switch-2 |
| _TZ3000_djgzdba9 | TS011F | switches-switch-5 |
| _TZ3000_dlhhrhs8 | TS000F | switches-switch-1-countdown-switch-type |
| _TZ3000_dlug3kbc | TS011F | switches-switch-3 |
| _TZ3000_dov0a3p1 | TS0001 | switches-switch-1 |
| _TZ3000_drc9tuqb | TS0001 | switches-switch-1 |
| _TZ3000_dyzkbcip | TS0003 | switches-switch-3 |
| _TZ3000_eei0ubpy | TS0002 | switches-switch-2 |
| _TZ3000_empogkya | TS0003 | switches-switch-3 |
| _TZ3000_eqsair32 | TS0003 | switches-switch-3 |
| _TZ3000_f09j9qjb | TS0003 | switches-switch-3 |
| _TZ3000_fawk5xjv | TS0003 | switches-switch-3 |
| _TZ3000_fbjdkph9 | TS0002 | switches-switch-2 |
| _TZ3000_fdxihpp7 | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_fdxihpp7 | TS000F | switches-switch-1-countdown-switch-type |
| _TZ3000_fisb3ajo | TS0002 | switches-switch-2 |
| _TZ3000_g8n1n7lg | TS0001 | switches-switch-1 |
| _TZ3000_g92baclx | TS0001 | switches-switch-1-power-options |
| _TZ3000_g9chy2ib | TS0003 | switches-switch-3 |
| _TZ3000_gazjngjl | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3000_gbshwgag | TS0001 | switches-switch-1 |
| _TZ3000_gdyjfvgm | TS011F | switches-switch-5 |
| _TZ3000_gexniqbq | TS0004 | switches-switch-4 |
| _TZ3000_gjnozsaz | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_gjrubzje | TS0001 | switches-switch-1 |
| _TZ3000_gkesadus | TS0002 | switches-switch-2 |
| _TZ3000_gtdswg8k | TS0001 | switches-switch-1 |
| _TZ3000_gzvniqjb | TS0011 | switches-switch-1 |
| _TZ3000_h1ipgkwn | TS0002 | switches-switch-2 |
| _TZ3000_h3noz0a5 | TS0001 | valves-valve-indicator-mode |
| _TZ3000_h8ngtlxy | TS0001 | valves-valve-indicator-mode |
| _TZ3000_hbic3ka3 | TS0003 | switches-switch-3 |
| _TZ3000_hbxsdd6k | TS0011 | switches-switch-1 |
| _TZ3000_hdc8bbha | TS000F | switches-switch-1 |
| _TZ3000_helyqdvs | TS011F | switches-switch-2 |
| _TZ3000_hhiodade | TS0011 | switches-switch-1 |
| _TZ3000_hktqahrq | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_hktqahrq | TS000F | switches-switch-1-countdown-switch-type |
| _TZ3000_hktqahrq | WHD02 | switches-switch-1-countdown-switch-type |
| _TZ3000_hojntt34 | TS0002 | switches-switch-2 |
| _TZ3000_huvxrx4i | TS0002 | switches-switch-2-power-options |
| _TZ3000_hyfvrar3 | TS011F | plugs-switch |
| _TZ3000_hzlsaltw | TS0001 | switches-switch-1-power-options |
| _TZ3000_hznzbl0x | TS0002 | switches-switch-2 |
| _TZ3000_i9oy2rdq | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_i9w5mehz | TS0002 | switches-switch-2 |
| _TZ3000_ibefeicf | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_ibefeicf | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold-no-temp |
| _TZ3000_iedbgyxt | TS0001 | valves-valve-indicator-mode |
| _TZ3000_iktiy8ue | TS0001 | switches-switch-1-power-options |
| _TZ3000_ikuxinvo | TS0001 | switches-switch-1-power-options |
| _TZ3000_imaccztn | TS0004 | switches-switch-4 |
| _TZ3000_in5qxhtt | TS0002 | switches-switch-2 |
| _TZ3000_in5s3wn1 | TS011F | switches-switch-5 |
| _TZ3000_irrmjcgi | TS0002 | switches-switch-2-power-options |
| _TZ3000_iv4eq7eh | TS0003 | switches-switch-3 |
| _TZ3000_iv6ph5tr | TS011F | switches-switch-2 |
| _TZ3000_iwtv2jwo | TS0002 | switches-switch-2 |
| _TZ3000_iy2c3n6p | TS011F | switches-switch-2 |
| _TZ3000_j0ktmul1 | TS011F | valves-valve-5 |
| _TZ3000_j1v25l17 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_jak16dll | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3000_jcqs2mrv | SM0001 | switches-switch-1 |
| _TZ3000_ji4araar | TS0011 | switches-switch-1-countdown-switch-type |
| _TZ3000_jl7qyupf | TS0012 | switches-switch-2-countdown-switch-type |
| _TZ3000_jsfzkftc | TS0001 | switches-switch-1-power-options |
| _TZ3000_ju82pu2b | TS0003 | switches-switch-3 |
| _TZ3000_k6fvknrr | TS011F | switches-switch-2 |
| _TZ3000_knoj8lpk | TS0004 | switches-switch-4 |
| _TZ3000_kpatq5pq | TS0012 | switches-switch-2-countdown-switch-type |
| _TZ3000_kqvb5akv | TS0001 | switches-switch-1-power-options |
| _TZ3000_ksw8qtmt | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_ky0fq4ho | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3000_kycczpw8 | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_kz1anoi8 | TS0049 | valves-valve-battery |
| _TZ3000_l8fsgo6p | TS0011 | switches-switch-1 |
| _TZ3000_lepzuhto | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_lepzuhto | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_liygxtcq | TS0004 | switches-switch-4 |
| _TZ3000_ljhbw1c9 | TS0012 | switches-switch-2-countdown-switch-type |
| _TZ3000_lmlsduws | TS0002 | switches-switch-2 |
| _TZ3000_lnggrqqi | TS011F | plugs-switch |
| _TZ3000_lqb7lcq9 | TS011F | switches-switch-4 |
| _TZ3000_lsunm46z | TS0003 | switches-switch-3 |
| _TZ3000_ltt60asa | TS0004 | switches-switch-4 |
| _TZ3000_lubfc1t5 | TS0003 | switches-switch-3 |
| _TZ3000_lugaswf8 | TS0002 | switches-switch-2 |
| _TZ3000_lvhy15ix | TS0003 | switches-switch-3 |
| _TZ3000_m8f3z8ju | TS000F | switches-switch-2 |
| _TZ3000_m9af2l6g | TS000F | switches-switch-1-countdown-switch-type |
| _TZ3000_ma3mhpx2 | TS0001 | switches-switch-1 |
| _TZ3000_majwnphg | TS0001 | switches-switch-1 |
| _TZ3000_mdj7kra9 | TS0004 | switches-switch-4 |
| _TZ3000_mhhxxjrs | TS0003 | switches-switch-3 |
| _TZ3000_mkhkxx1p | TS0001 | switches-switch-1-power-options |
| _TZ3000_mlswgkc3 | TS011F | switches-switch-2 |
| _TZ3000_mmkbptmx | TS0004 | switches-switch-4 |
| _TZ3000_mq4wujmp | TS0049 | valves-valve-battery |
| _TZ3000_mtnpt6ws | TS0002 | switches-switch-2 |
| _TZ3000_mufwv0ry | TS0002 | switches-switch-2 |
| _TZ3000_mvn6jl7x | TS011F | switches-switch-2 |
| _TZ3000_mw1pqqqt | TS0003 | switches-switch-3 |
| _TZ3000_mx3vgyea | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_mx3vgyea | TS000F | switches-switch-1-countdown-switch-type |
| _TZ3000_myaaknbq | TS0001 | switches-switch-1 |
| _TZ3000_mzcp0of6 | TS0003 | switches-switch-3 |
| _TZ3000_nPGIPl5D | TS0012 | switches-switch-2-countdown-switch-type |
| _TZ3000_nivavasg | TS0004 | switches-switch-4 |
| _TZ3000_nnwehhst | TS0003 | switches-switch-3 |
| _TZ3000_npzfdcof | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_nsa76jai | TS0004 | switches-switch-4 |
| _TZ3000_nuenzetq | TS0002 | switches-switch-2 |
| _TZ3000_nwidmc4n | TS0003 | switches-switch-3 |
| _TZ3000_nzkqcvvs | TS011F | plugs-switch |
| _TZ3000_o005nuxx | TS011F | switches-switch-5 |
| _TZ3000_o1jzcxou | TS011F | plugs-switch |
| _TZ3000_o4cjetlm | TS0001 | valves-valve-indicator-mode |
| _TZ3000_o4cjetlm | TS011F | valves-valve-indicator-mode |
| _TZ3000_odzoiovu | TS0003 | switches-switch-3 |
| _TZ3000_ogjpfoyn | TS0049 | valves-valve-battery |
| _TZ3000_ogpla3lh | TS0002 | switches-switch-2 |
| _TZ3000_oiymh3qu | TS011F | plugs-switch |
| _TZ3000_ok0ggpk7 | TS0003 | switches-switch-3 |
| _TZ3000_okaz9tjs | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_ouwfc1qj | TS0003 | switches-switch-3 |
| _TZ3000_oznonj5q | TS011F | switches-switch-3 |
| _TZ3000_pf7swkqp | TS0003 | switches-switch-3 |
| _TZ3000_pfc7i3kt | TS0003 | switches-switch-3 |
| _TZ3000_pgq7ormg | TS0001 | switches-switch-1 |
| _TZ3000_pl5v1yyy | TS011F | switches-switch-5 |
| _TZ3000_plyvnuf5 | TS011F | plugs-switch |
| _TZ3000_pmsxmttq | TS0003 | switches-switch-3 |
| _TZ3000_pmz6mjyu | TS011F | switches-switch-2 |
| _TZ3000_pnzfdr9y | TS0101 | plugs-switch |
| _TZ3000_prits6g4 | TS0001 | switches-switch-1 |
| _TZ3000_pv4puuxi | TS0003 | switches-switch-3 |
| _TZ3000_pvlvoxvt | TS011F | switches-switch-4 |
| _TZ3000_q6a3tepg | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_q8r0bbvy | TS0001 | switches-switch-1-power-options |
| _TZ3000_qaa59zqd | TS0002 | switches-switch-2 |
| _TZ3000_qaabwu5c | TS0001 | switches-switch-1-power-options |
| _TZ3000_qamj2vnn | TS0001 | switches-switch-1 |
| _TZ3000_qeuvnohg | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3000_qh6qjuan | TS0001 | switches-switch-1 |
| _TZ3000_qiutut5y | TS011F | switches-switch-4 |
| _TZ3000_qlai3277 | TS0001 | switches-switch-1-power-options |
| _TZ3000_qlmnxmac | TS011F | switches-switch-2 |
| _TZ3000_qmi1cfuq | TS0011 | switches-switch-1-countdown-switch-type |
| _TZ3000_qnejhcsu | TS0001 | switches-switch-1-power-options |
| _TZ3000_qorepo2x | TS0001 | switches-switch-1-power-options |
| _TZ3000_qq9ahj6z | TS0001 | switches-switch-1 |
| _TZ3000_qsp2pwtf | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_qvmiyxuk | TS0001 | switches-switch-1 |
| _TZ3000_qxcnwv26 | TS0003 | switches-switch-3 |
| _TZ3000_qystbcjg | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_qystbcjg | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_r9e2w7dn | TS0004 | switches-switch-4 |
| _TZ3000_raviyuvk | TS011F | switches-switch-2 |
| _TZ3000_rfjctviq | TS0002 | switches-switch-2 |
| _TZ3000_rgpqqmbj | TS011F | switches-switch-2 |
| _TZ3000_rhkfbfcv | TS0003 | switches-switch-3 |
| _TZ3000_rk2yzt0u | TS011F | valves-valve-indicator-mode |
| _TZ3000_rmjr4ufz | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_rqbjepe8 | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3000_rtcrrvia | TS011F | plugs-switch |
| _TZ3000_rul9yxcc | TS011F | switches-switch-2 |
| _TZ3000_ruldv5dt | TS0002 | switches-switch-2 |
| _TZ3000_ruxexjfz | TS0002 | switches-switch-2 |
| _TZ3000_sgb0xhwn | TS011F | switches-switch-2 |
| _TZ3000_skueekg3 | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_skueekg3 | TS000F | switches-switch-1-countdown-switch-type |
| _TZ3000_ss98ec5d | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_sznawwyw | TS0013 | switches-switch-3-countdown-switch-type |
| _TZ3000_t3s9qmmg | TS0001 | switches-switch-1 |
| _TZ3000_t7ugva7q | TS0013 | switches-switch-3-countdown-switch-type |
| _TZ3000_tas0zemd | TS0002 | switches-switch-2 |
| _TZ3000_tgddllx4 | TS0001 | switches-switch-1-power-options |
| _TZ3000_tqlv4ug4 | TS0001 | switches-switch-1 |
| _TZ3000_tvuarksa | TS011F | plugs-switch |
| _TZ3000_tw4ztbp4 | TS0011 | switches-switch-1-countdown-switch-type |
| _TZ3000_twqctvna | TS011F | switches-switch-1 |
| _TZ3000_txpirhfq | TS0011 | switches-switch-1-countdown-switch-type |
| _TZ3000_tyg4yiat | TS0004 | switches-switch-4 |
| _TZ3000_tygpxwqa | TS0001 | switches-switch-1 |
| _TZ3000_u3oupgdy | TS0004 | switches-switch-4 |
| _TZ3000_uaa34g7v | TS0011 | switches-switch-1 |
| _TZ3000_udl7uyd2 | TS0001 | switches-switch-1 |
| _TZ3000_uilitwsy | TS0003 | switches-switch-3 |
| _TZ3000_uwkja6z1 | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3000_uyrhiafs | TS011F | plugs-switch |
| _TZ3000_v1pdxuqq | TS011F | plugs-switch |
| _TZ3000_v4l4b0lp | TS0003 | switches-switch-3 |
| _TZ3000_v4mevirn | TS011F | switches-switch-2 |
| _TZ3000_v7gnj3ad | TS0001 | switches-switch-1-countdown-switch-type |
| _TZ3000_veu2v775 | TS0001 | switches-switch-1 |
| _TZ3000_viqwamhn | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3000_vjhcenzo | TS0003 | switches-switch-3 |
| _TZ3000_vmpbygs5 | TS011F | switches-switch-3 |
| _TZ3000_vsasbzkf | TS0003 | switches-switch-3 |
| _TZ3000_vzopcetz | TS011F | switches-switch-3 |
| _TZ3000_w0ypwa1f | TS0001 | valves-valve-indicator-mode |
| _TZ3000_w1tcofu8 | TS0001 | switches-switch-1 |
| _TZ3000_wamqdr3f | TS011F | plugs-switch |
| _TZ3000_wbloefbf | TS011F | switches-switch-5 |
| _TZ3000_wijoqjk1 | TS0001 | switches-switch-1 |
| _TZ3000_wnzoyohq | TS0002 | switches-switch-2 |
| _TZ3000_wpueorev | TS0001 | valves-valve-indicator-mode |
| _TZ3000_wrhhi5h2 | TS0001 | switches-switch-1 |
| _TZ3000_ww6drja5 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_wwtnshol | TS0004 | switches-switch-4 |
| _TZ3000_wxtp7c5y | TS011F | plugs-switch |
| _TZ3000_wzauvbcs | TS011F | switches-switch-3 |
| _TZ3000_x3ewpzyr | TS0001 | switches-switch-1-power-options |
| _TZ3000_x8mbwtsz | TS0001 | switches-switch-1-power-options |
| _TZ3000_xeumnff9 | TS011F | switches-switch-2 |
| _TZ3000_xfxpoxe0 | TS0001 | switches-switch-1 |
| _TZ3000_xkap8wtb | TS0001 | switches-switch-1-power-options |
| _TZ3000_xkap8wtb | TS000F | switches-switch-1-power-options |
| _TZ3000_y4ona9me | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_ynmowqk2 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_ypgri8yz | TS0013 | switches-switch-3-countdown-switch-type |
| _TZ3000_ysiog9xi | TS011F | plugs-switch |
| _TZ3000_yujkchbz | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_ywubfuvt | TS0002 | switches-switch-2 |
| _TZ3000_yxmafzmd | TS0002 | switches-switch-2 |
| _TZ3000_z6fgd73r | TS011F | switches-switch-1-power-options |
| _TZ3000_zbfya6h0 | TS0002 | switches-switch-2 |
| _TZ3000_zeuulson | TS0003 | switches-switch-3 |
| _TZ3000_zigisuyh | TS011F | switches-switch-2 |
| _TZ3000_zjchz7pd | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_zjchz7pd | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold-no-temp |
| _TZ3000_zloso4jk | TS011F | plugs-switch-power-energy-voltage |
| _TZ3000_zmy1waw6 | TS011F | switches-switch-1 |
| _TZ3000_zmy4lslw | TS0002 | switches-switch-2 |
| _TZ3000_zojh9vz7 | TS0001 | switches-switch-1-power-options |
| _TZ3000_zrm3oxsh | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_zrm3oxsh | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_zv6x8bt2 | TS011F | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_zv6x8bt2 | TS011F_with_threshold | din-rail-switch-power-energy-voltage-current-threshold |
| _TZ3000_zw7yf6yk | TS0001 | switches-switch-1 |
| _TZ3000_zwaadvus | TS011F | switches-switch-2 |
| _TZ3000_zxrfobzw | TS0002 | switches-switch-2 |
| _TZ3210_2dfy6tol | TS0101 | plugs-switch |
| _TZ3210_2uk4z8ce | TS011F | switches-switch-2 |
| _TZ3210_5ct6e7ye | TS011F | plugs-switch-power-energy-voltage |
| _TZ3210_6cmeijtd | TS011F | plugs-switch-3-power-energy-voltage-current |
| _TZ3210_6smingw0 | TS0002 | switches-switch-2 |
| _TZ3210_7jnk7l3k | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3210_8n4dn1ne | TS011F | switches-switch-4 |
| _TZ3210_9hbau615 | TS0001 | switches-switch-1 |
| _TZ3210_a2erlvb8 | TS0002 | switches-switch-2 |
| _TZ3210_a2erlvb8 | TS000F | switches-switch-1 |
| _TZ3210_bep7ccew | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3210_c7nc9w3c | TS011F | plugs-switch-3-power-energy-voltage-current |
| _TZ3210_cjrngdr3 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3210_ddigca5n | TS011F | plugs-switch-power-energy-voltage |
| _TZ3210_eymunffl | TS0101 | plugs-switch |
| _TZ3210_fhx7lk3d | TS0001 | switches-switch-1 |
| _TZ3210_hjxqqofs | TS000F | switches-switch-1 |
| _TZ3210_iymfxdis | TS0004 | switches-switch-4 |
| _TZ3210_jlf1nepw | TS011F | plugs-switch-power-energy-voltage |
| _TZ3210_nhqka112 | TS011F | plugs-switch |
| _TZ3210_ok0ggpk7 | TS0003 | switches-switch-3 |
| _TZ3210_pdnwpnz5 | TS0002 | switches-switch-2 |
| _TZ3210_pfbzs1an | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3210_ph1joc22 | TS011F | switches-switch-2 |
| _TZ3210_qjvi92wz | TS0014 | switches-switch-4 |
| _TZ3210_raqjcxo5 | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3210_rwmitwj4 | TS011F | plugs-switch-power-energy-voltage |
| _TZ3210_sgb0xhwn | TS011F | switches-switch-2 |
| _TZ3210_tfxwxklq | TS0101 | plugs-switch |
| _TZ3210_tqlv4ug4 | TS0001 | switches-switch-1 |
| _TZ3210_urjf5u18 | TS011F | switches-switch-4 |
| _TZ3210_vbfp8eyv | TS011F | din-rail-switch-power-energy-voltage-current |
| _TZ3210_w0qqde0g | TS011F | plugs-switch-power-energy-voltage |
| _TZ3210_w3hl6rao | TS0014 | switches-switch-4 |
| _TZ3210_yvxjawlt | TS011F | plugs-switch-2-power-energy-voltage |
| _TZ3210_z4hgsevd | TS0014 | switches-switch-4 |
| _TZ3218_hdc8bbha | TS000F | switches-switch-1 |
| _TZ3218_n0jsuogs | TS000F | switches-switch-1-poweron-switch-type |
| _TZ3218_sgbsg6mr | TS000F | switches-switch-2-poweron-switch-type |
| _TZ3290_ixd9mvv4 | TS0049 | valves-valve-battery |
| _TZ33000_d9yfgzur | TS0003 | switches-switch-3 |
| easyiot | ZB-PSW04 | switches-switch-4 |
| easyiot | ZB-SP1000 | switches-switch-1 |
| easyiot | ZB-SW08 | switches-switch-8 |
| easyiot | ZB-TTS01 | sensors-temp-humidity-battery |
| iHseno | _TZ3000_knoj8lpk | switches-switch-4 |
| iHseno | _TZ3000_mhhxxjrs | switches-switch-3 |
| iHseno | _TZ3000_qq9ahj6z | switches-switch-1 |
| iHseno | _TZ3000_zxrfobzw | switches-switch-2 |
| pcblab.io | RR620ZB | switches-switch-2 |
| zunzunbee | SSWZ8T | switches-switch-4 |


