# esp32-dht-sensor-oled-display
โปรเจกต์ตัวอย่างนี้ใช้ **ESP32 + DHT11/DHT22 Sensor** เพื่ออ่านค่า **Temperature** และ **Humidity** และแสดงผลบนจอ **OLED 128x64 (I2C)**
# ESP32 + DHT Sensor + OLED Display (128x64)

โปรเจกต์ตัวอย่างนี้ใช้ **ESP32 + DHT11/DHT22 Sensor** เพื่ออ่านค่า **Temperature** และ **Humidity** และแสดงผลบนจอ **OLED 128x64 (I2C)**  

## 🔹 คุณสมบัติ
- อ่านค่าอุณหภูมิและความชื้นจาก DHT11 / DHT22
- แสดงผลบนจอ OLED แบบ Real-time
- ใช้งานง่าย เหมาะสำหรับ IoT และ Smart Farm
- เขียนด้วย Arduino IDE พร้อมโค้ดตัวอย่าง

## 🔹 อุปกรณ์ที่ใช้
- ESP32 DevKit V1
- DHT22 หรือ DHT11 Sensor
- OLED Display 0.96 นิ้ว 128x64 (I2C)
- Breadboard + Jumper Wire
- Arduino IDE

## 🔹 การต่อวงจร
- DHT Sensor: VCC → 3.3V, GND → GND, DATA → GPIO 4
- OLED Display: VCC → 3.3V, GND → GND, SDA → GPIO 21, SCL → GPIO 22

## 🔹 วิธีใช้งาน
1. ติดตั้ง Arduino IDE และเพิ่มบอร์ด ESP32  
2. ติดตั้ง Libraries ที่จำเป็น (`DHT sensor library`, `Adafruit SSD1306`, `Adafruit GFX`)  
3. แก้ไขค่า `DHTTYPE` ให้ตรงกับเซนเซอร์ที่ใช้ (DHT11 หรือ DHT22)  
4. Upload โค้ดไปยัง ESP32  
5. เมื่อเปิดเครื่อง จอ OLED จะแสดงค่า Temp/Hum อัปเดตทุก 2 วินาที  

## 🔹 ตัวอย่างผลลัพธ์
บนจอ OLED จะแสดงผลดังนี้:  
DHT Sensor
Temp: 29.5 C
Hum : 70.2 %

## 📖 อ่านบทความเต็ม
👉 [ESP32 + DHT Sensor แสดงผลบนจอ OLED 128x64](https://devadiy.com/esp32-dht-sensor-oled-display/)  

---
✍️ Project by [DevaDIY.com](https://devadiy.com/)

