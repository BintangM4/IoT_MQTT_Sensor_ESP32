# Pra-Magang IoT - Simulasi MQTT

Proyek ini merupakan simulasi sistem IoT sederhana untuk membaca data sensor 
dan mengirimkan data melalui protokol MQTT menggunakan ESP32 (simulasi Wokwi).



# Tools yang Digunakan
- ESP32 (Simulasi Wokwi)
- HiveMQ MQTT Broker
- GitHub



# Arsitektur Sistem
ESP32 (Simulasi) → MQTT Broker (HiveMQ) → Client Subscriber


# Konfigurasi MQTT
Host   :  
Port   : 8883  
Topic  : iot/tugas/sensor  

---

# Cara Menjalankan
1. Buka simulasi Wokwi:
   https://wokwi.com/projects/

2. Jalankan project

3. Buka HiveMQ Web Client:
   https://console.hivemq.cloud/

4. Connect ke broker
   Host: broker.hivemq.com
   Port: 8884 (Websocket)

5. Subscribe ke topic yang sama dengan ESP32
   iot/tugas//sensor


# Bukti Hasil
Tampilan MQTT.png
Tampilan Simulasi.png


# Link Simulasi
https://wokwi.com/projects/451929954206862337
