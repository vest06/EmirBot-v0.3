![Logo](https://[.](https://github.com/vest06/EmirBot-v0.3/blob/main/file_000000008de06243a9bee8a1eb9e94b8%20(3).png?raw=true)


# EmirBot-3o 🤖 

**EmirBot-3o**, tamamen Python ve Kivy kullanılarak geliştirilmiş bir mobil sohbet uygulamasıdır. Bu uygulama, kullanıcıyla doğal bir şekilde sohbet edebilen, espriler yapabilen, Google üzerinden bilgi arayabilen, Wikipedia'dan özetler çekebilen ve hatta hava durumu verisini canlı olarak gösterebilen bir yapay zeka sohbet botudur.

---

## 🎯 Özellikler

- **Kivy Arayüzü**: Modern, mobil uyumlu, temiz ve animasyonlu kullanıcı arayüzü.
- **Sade + Neon Geçişli Tema**: Başlık kısmında pembe neon ile mavi neon renk geçişiyle dinamik bir görüntü.
- **Hazır Soru-Cevap Veritabanı**: 200’den fazla yaygın soru ve cevabı içeren geniş bir cevap arşivi.
- **Difflib ile Benzer Soru Eşleme**: Girilen kullanıcı mesajları, veritabanındaki sorulara benzerliğiyle eşleşir.
- **Hava Durumu API’si**: Şehir bazlı anlık hava durumu verisi çeker (wttr.in servisi üzerinden).
- **SerpAPI Entegrasyonu**: Bilinmeyen sorularda Google araması yaparak cevap verir. Cevap bulunamazsa Wikipedia özetini getirir.
- **Küfür Filtresi & IP Gösterimi**: Belirli kötü sözler algılanırsa kullanıcıya özel yanıtlar ve IP adresi gösterimi yapılır (eğlencelik).

---

## ⚙️ Kullanılan Kütüphaneler

- `kivy`
- `requests`
- `wikipedia`
- `difflib`
- `webbrowser`
- `socket`

> Standart Python modülleri dışında yüklenmesi gerekenler:  
> `pip install kivy requests wikipedia`

---

## 📱 Kullanım

1. Python ortamında veya mobil cihazda çalıştırılır.
2. Uygulama açıldığında sohbet kutusu ve başlık görünür.
3. Kullanıcı mesaj yazıp “Gönder” butonuna tıkladığında, bot:
   - Eğer soru biliniyorsa doğrudan cevap verir.
   - Bilinmiyorsa Google → Wikipedia sırasıyla bilgi arar.
   - Hava durumu komutu geldiğinde anlık hava verisini döner.
4. Cevaplar konuşma baloncukları şeklinde görünür.

---

## 🔒 Notlar

- Bu proje tamamen bireysel olarak geliştirilmiştir.
- Eğitim, öğrenme ve deneyim kazanma amacıyla yapılmıştır.
- İçerikte mizahi bazı yanıtlar bulunabilir; eğlenceli olması amaçlanmıştır.
- Her türlü öneri ve katkıya açığım!

---

## 📌 Geliştirici

**Geliştirici:** Emir (15 yaşında, bağımsız öğrenci geliştirici)  
**Yapay zekanın adı:** EmirBot-3o  
**Dil:** Python  
**Görsel Arayüz:** Kivy

---

## 📤 Yedekleme

Bu repo, kodun yedeklenmesi ve geliştirilmeye açık kalması için oluşturulmuştur.  
Telefon sıfırlama gibi durumlarda kodun güvenli bir şekilde saklanması amaçlanmıştır.

---
