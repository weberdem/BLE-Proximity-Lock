# 🛡️ BLE Proximity Lock (Smart Distance Lock)

[Türkçe](#türkçe) | [English](#english)

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

Bu proje, bir Bluetooth Low Energy (BLE) cihazının (saat, telefon vb.) sinyal gücünü (RSSI) takip ederek, bilgisayardan uzaklaştığınızda otomatik olarak kilitlenmesini, yaklaştığınızda ise ekranın uyanmasını sağlar.

### ✨ Özellikler
- 🔒 **Güvenli Kilitleme**: Sinyal belirli bir eşiğin altına düştüğünde Windows kilitlenir.
- 🔅 **Akıllı Uyandırma**: Yaklaştığınızda ekranı otomatik olarak uyandırır.
- 🕵️ **Arka Planda Çalışma**: Sistem tepsisinde (System Tray) sessizce çalışır.
- 🛠️ **Kolay Kurulum**: Dahili setup sihirbazı ve `.bat` dosyaları ile kolay kullanım.

### 🚀 Başlangıç

1. **Python Yükleyin**: Bilgisayarınızda Python yüklü değilse [python.org](https://www.python.org/downloads/) adresinden en güncel sürümü indirin. **Kurulum sırasında "Add Python to PATH" seçeneğini işaretlediğinizden emin olun.**
2. **Kütüphaneleri Kurun**: Terminali açın ve şu komutu girin:
   ```bash
   pip install -r requirements.txt
   ```
3. **Ayarlar**: `kurulum.bat` dosyasına çift tıklayın ve takip edilecek cihazınızı seçin.
4. **Çalıştır**: `baslat.bat` dosyasına çift tıklayarak uygulamayı arka planda başlatın.

---

<a name="english"></a>
## 🇺🇸 English

This project monitors the signal strength (RSSI) of a Bluetooth Low Energy (BLE) device (watch, phone, etc.) to automatically lock your computer when you walk away and wake the screen when you approach.

### ✨ Features
- 🔒 **Secure Locking**: Windows locks automatically when the signal drops below a certain threshold.
- 🔅 **Smart Wake**: Automatically wakes the screen when you are nearby.
- 🕵️ **Background Operation**: Runs silently in the System Tray.
- 🛠️ **Easy Setup**: User-friendly setup wizard and `.bat` execution files.

### 🚀 Getting Started

1. **Install Python**: If you don't have Python, download the latest version from [python.org](https://www.python.org/downloads/). **Make sure to check "Add Python to PATH" during installation.**
2. **Install Dependencies**: Open your terminal and run:
   ```bash
   pip install -r requirements.txt
   ```
3. **Setup**: Double-click `kurulum.bat` and select your target device.
4. **Run**: Double-click `baslat.bat` to launch the application in the background.

---

## 👨‍💻 Yazan ve Kodlayan / Written and Coded by
**Web Erdem**
- [Instagram](https://instagram.com/web.erdem)
- [TikTok](https://tiktok.com/@web.erdem)
- [YouTube](https://youtube.com/weberdem)
- [GitHub](https://github.com/weberdem)

## 📄 Lisans / License
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır. / This project is licensed under the [MIT License](LICENSE).
