以下是土壤濕度感測器與 Arduino 的基本配線方式：

所需元件
土壤濕度感測器模組（通常包含探針和模組）
Arduino 開發板（如 Arduino Uno）
杜邦線（公對母或公對公）
USB 數據線（用於連接 Arduino 和電腦）
配線步驟
土壤濕度感測器模組引腳：

VCC：連接 Arduino 的 5V 引腳
GND：連接 Arduino 的 GND 引腳
A0（模擬輸出）：連接 Arduino 的 A0 引腳（對應程式中的 sensorPin）
Arduino 與電腦連接：

使用 USB 數據線將 Arduino 開發板連接到電腦。
配線圖
以下是簡單的配線圖示意：

土壤濕度感測器模組:
+----------------+
| VCC -- Arduino 5V |
| GND -- Arduino GND |
| A0  -- Arduino A0  |
+----------------+

Arduino:
+----------------+
| USB -- 電腦     |
+----------------+

