##  Profiller Dizini Uygulaması (Ağ İletişimi ve API’ler)

**Öğrenci Bilgileri**
- Furkan Sadık Kocabaş
- 200404001

---

## **Proje Açıklaması:**

Bu proje, React Native (Expo) kullanılarak geliştirilmiş bir mobil uygulamadır.
Uygulama, yerel olarak çalışan bir Express.js API sunucusundan profil verilerini
çekerek sayfalanmış bir listede göstermekte ve seçilen profil için detay ekranı
sunmaktadır.

---

## **Kullanılan Teknolojiler:**

**Backend:**
- Node.js
- Express.js

**Frontend:**
- React Native
- Expo
- Axios
- React Navigation

---

**Backend Kurulumu (Express API):**
node server.js ile yapılır

**Frontend Kurulumu:**
.env dosyasında
EXPO_PUBLIC_API_BASE_URL=http://<192.x.x.x.x>:

**IP Yapılandırması:**

React Native uygulaması, Express API’ye .env dosyasında tanımlanan
EXPO_PUBLIC_API_BASE_URL üzerinden bağlanmaktadır.

localhost kullanılmamaktadır.

Telefon ve bilgisayar aynı Wi-Fi ağına bağlı olmalıdır.
