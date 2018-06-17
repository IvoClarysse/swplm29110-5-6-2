Interface Specification (BLE Protocol)
======================================

Bluetooth Specification: 4.0 / 4.1 / 4.2 / 5.0
Role: Central / Peripheral

Advertising Data
----------------

Advertisement
~~~~~~~~~~~~~

- ADV_IND
- ADV_DIRECT_IND
- ADV_NONCONN_IND
- ADV_SCAN_IND

Flags:
- bit 0: LE Limited Discoverable: False
- bit 1: LE General Discoverable: True
- bit 2: BR/EDR: False
- bit 3: LE+BR/EDR Controller: False
- bit 4: LE+BR/EDR Host: False

Scan Response
~~~~~~~~~~~~~

- SCAN_REQ
- SCAN_RSP
- CONNECT_REQ

Authentication
--------------

TBD

GATT Services
-------------

- GAP: 0x1800
- GATT: 0x1801
- DIS: 0x180A

GAP
~~~

- Device Name: TBD
- Appearance: TBD
- Peripheral Privacy Flag: TBD
- Reconnection Address: TBD
- Peripheral Preferred Connection Parameters: TBD

GATT
~~~~

- Service Changed: TBD

Device Information
~~~~~~~~~~~~~~~~~~

- Manufacturer Name String: TBD
- Model Number String: TBD
- Serial Number String: TBD
- Hardware Revision Stirng: TBD
- Firmware Revision String: TBD
- Software Revision String: TBD
- System ID: TBD
- IEEE 11073-20601: TBD
- PnP ID: TBD
