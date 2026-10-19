# 🖥️ AirShare (Ekran ve Ses Yansıtma) 

## AirShare; yerel ağ (Wi-Fi/Ethernet) üzerinden Android cihazınızın ekran, ses ve mikrofonunu bilgisayara kablosuz ve hızlı bir şekilde yansıtmanızı sağlayan, özellikle Linux(Ubuntu,Pardus vb.) ve Windows odaklı bir masaüstü sunucu uygulamasıdır.
ÖNEMLİ : Ekran ve ses yansıtmalarında, kendi cihazınızın mobil verinizi kapatarak sunucuya bağlanan cihazın Wi-Fi (Hotspot) özelliğini kullanarak veri paylaşımını gerçekleştirmeniz gerekmektedir.
------
## AirShare'nin Android istemcisi ile aynı yerel ağ üzerindeki ekranınızı, sesinizi ve dosyalarınızı mobil cihazınızdan Linux (Ubuntu,PARDUS) ve Windows işletim sistemine güvenli olarak aktarabilirsiniz.
## Öncelikle PLAY STORE üzerinden (https://play.google.com/store/apps/details?id=com.yazilim.airshare) AirShare isimli mobil uygulamayı Android cihazınıza kurmalısınız.

## Mobil uygulamayı kurduktan sonra bu linkte yer alan paketleri indirerek Linux(Ubuntu,Pardus vb.) veya Windows işletim sisteminize kurabilir ve cep telefonunuz üzerinden aynı ağdaki bilgisayarınıza ekran yansıtma ve dosya transferi yapabilirsiniz.

### 📥 Uygulama İndirme Linkleri

* 🐧 **Linux (Ubuntu, Pardus)İşletim Sistemi İçin (Sunucu Setup 1) (.deb):**  
  [🔗 AirShare İndir](https://github.com/yazilim02/AirShare/releases/download/AirShare/airshare-_amd64.deb)

* 🪟 **Windows İşletim Sistemi İçin Sunucu Kurulum Dosyası (Sunucu Setup 2):**  
  [🔗 AirShare  Windows Sunucu Kurulumu İndir](https://github.com/yazilim02/AirShare/releases/download/AirShare/AirShare..setup.exe)

* 🪟 **Windows İşletim Sistemi İçin İstemci Kurulum Dosyası (İstemci Setup 1):**  
  [🔗 AirShare  Windows İstemci Kurulumu İndir](https://github.com/yazilim02/AirShare/releases/download/AirShare/AirShare..Client.exe)

  🐧 **Linux (Ubuntu, Pardus)İşletim Sistemi İçin (.deb) (İstemci Setup 2):**  
  [🔗 AirShare  Linux İstemci Kurulumu İndir](https://github.com/yazilim02/AirShare/releases/download/AirShare/airshare--client_1.0.0_amd64.deb)
  

*🍓 **Raspberry Pi (64-bit / Raspberry Pi OS) İçin (.deb):
* [🔗 AirShare  Raspberry Sunucu Kurulumu İndir](https://github.com/yazilim02/AirShare/releases/download/AirShare/airshare-_1.0.0_arm64.deb)
------

------

## 📱 Android İstemcisi

---------------------------------------------------------------------------------------------------------------------------------------------------------
 **AirShare Mobile:**  
Uygulama Linki: [Google Play Store - AirShare](https://play.google.com/store/apps/details?id=com.yazilim.airshare)

## 📷 Android Mobil Uygulama Ekran Görüntüleri

<p align="center">
  <img src="https://github.com/yazilim02/AirShare/blob/main/2.png" alt="Ana Ekran 1" width="300"/>
</p>

---


# 📱 Kullanım

1. Uygulamayı Windows veya Pardus masaüstü üzerinde çalıştırın.
2. **Sunucu IP Adresi** bölümünde görünen QR kodu mobil uygulama üzerinden taratın veya ekranda görünen IP numarası ve 6 haneli güvenlik parolası ile uygulamaya giriş yapın. (Örn: `192.168.1.50`)
3. Aynı Wi-Fi ağına bağlı telefonunuzdaki AirShare uygulamasından bağlan butonuna basın. (ÖNEMLİ: Wi-fi ağını kişisel erişim noktanızdan yapmanız daha hızlı ve daha güvenli bağlantıyı sağlayacaktır.Burada önemli nokta paylaşım yapan cihazların aynı ağda olmasıdır)
4. **🎥 Ekran ve Sesi Yansıt** butonunu kullanarak ekranınızı ve dahili sesinizi bilgisayara aktarmaya başlayın.
5. İsterseniz **🎙️ Mikrofonu Yansıt** seçeneği ile sesinizi anlık olarak bilgisayara aktarabilirsiniz.


---


# ✨ Özellikler

- **Kablosuz Ekran ve Ses Yansıtma**
  - Android cihazınızın ekranını ve sesini gecikmesiz bir şekilde Windows ve Pardus masaüstü uygulamasına aktarır.
- **Canlı Mikrofon Desteği**
  - Telefonunuzun mikrofonunu kullanarak sesli aktarım yapabilmenizi sağlar.
- **QR Kod ile Hızlı Bağlantı**
  - Masaüstü uygulamasındaki QR kodu telefon kamerasıyla taratarak saniyeler içinde eşleşme sağlayın.
- **Çoklu Dil Desteği**
  - Türkçe, İngilizce, Almanca ve İspanyolca dil seçenekleri sunar.

---

# 🛠️ Kullanılan Teknolojiler

| Bileşen | Kullanılan Teknoloji / Kütüphane |
|---|---|
| **Mobil Platform** | Android (Kotlin, Jetpack Compose, Material 3) |
| **Masaüstü Platform** | C++17, Qt 6 (QtWidgets, QtNetwork) |
| **Ağ ve İletişim** | OkHttp, Gson, Coroutines |
| **Ek Araçlar** | ZXing (QR Tarayıcı) |

---

# 📸 Ekran Görüntüsü

![AirShare Ekran Görüntüsü](https://github.com/yazilim02/AirShare/blob/main/3.png)

---

# 📄 Lisans

**Masaüstü Yazılım:** Ücretsiz olarak kullanılabilir ve reklam içermez.
