# Pra-Magang IoT - Simulasi MQTT

Proyek ini merupakan simulasi sistem IoT sederhana untuk membaca data sensor 
dan mengirimkan data melalui protokol MQTT menggunakan ESP32 (simulasi Wokwi).

---

## 🔧 Tools yang Digunakan
- ESP32 (Simulasi Wokwi)
- HiveMQ MQTT Broker
- HiveMQ Websocket Client
- Arduino IDE / PlatformIO
- GitHub

---

## 🏗️ Arsitektur Sistem
ESP32 (Simulasi) → MQTT Broker (HiveMQ) → Client Subscriber

---

## 🌐 Konfigurasi MQTT
Host   : broker.hivemq.com  
Port   : 1883  
Topic  : nama/topic/kamu  

---

## ▶️ Cara Menjalankan
1. Buka simulasi Wokwi:
   https://wokwi.com/projects/

2. Jalankan project

3. Buka MQTT Web Client:
   https://www.hivemq.com/demos/websocket-client/

4. Connect ke broker
   Host: broker.hivemq.com
   Port: 8000 (Websocket)

5. Subscribe ke topic yang sama dengan ESP32

---

## 📸 Bukti Hasil
(Screenshot MQTT + Wokwi)

---

## 📎 Link Simulasi
[https://wokwi.com/projects/xxxxx](https://wokwi.com/projects/451929954206862337)
