# Huananzhi X99-AD3 Hackintosh OpenCore for Ventura

OpenCore 0.8.5  
Tested on macOS 13.0 Ventura

## Hardware Configuration

Here's my hardware configuration and the actual price I paid when I bought it around March 2022 (including tax and local shipping fees).

| Part | Name | Price (+VAT) |
|:--:|:--|--:|
| MB  | Huananzhi X99-AD3 (Taobao)                   | ￥585  CNY |
| CPU | Intel E5-2696v3 (Taobao)                     | ￥620  CNY |
| Ram | 64GB (2 * 32) DDR3 ECC 1866 Samsung (Taobao) | ￥600  CNY |
| GPU | Gigabyte Radeon RX 5600 XT WindForce OC 6GB  | ￥1900 CNY |
| SSD | Samsung PM961 512GB NVMe (Existing)          | -          |
| HDD | HGST HTS721010A9E630 1TB (Existing)          | -          |
| PSU | EVGA 550W B3 (Kijiji)                        | ￥200  CNY |
| Fan | Vetroo U6 Pro (Kijiji)                       | ￥150  CNY |
| Case | Phanteks Eclipse (Kijiji)                   | ￥200  CNY |
|  -  | + International Shipping EMS                 | ￥448  CNY |
|  -  | = Sum                                        | =￥4703    |

## Features

- [ ] CPU Power Management (Not Tested)
- [x] Simulated NVRAM
- [x] AMD RX 5xxx XT Graphics (Tested on 5600 XT)
  - [x] DRM (Tested with Amazon Prime)
- [ ] Sleep/Wake (Low Priority)
  - [ ] Stay Asleep
  - [ ] Features Normal After Wake
- [x] 📶 Ethernet RTL8111
- [ ] 📶 Intel AX210 WiFi
- [ ] 📶 Intel AX210 Bluetooth
- [x] 🔌 USB Ports  
Note: Due to the 15 ports limit, the top right USB 2.0 port in the back is disabled  
Also, only one of the two front USB ports are mapped.
- [x] 💬 iMessage
- [x] 🎧 Realtek ALC662 Audio
