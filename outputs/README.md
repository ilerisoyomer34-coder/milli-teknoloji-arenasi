# Milli Teknoloji Arenası

Akıllı tahta ve oyuncu telefonları aynı yerel Wi-Fi ağına bağlıyken çalışır. Node.js 18+ kurulu bilgisayarda PowerShell'i proje klasöründe açıp çalıştırın:

```powershell
node outputs/server.js
```

Tahtada `http://localhost:3000` adresini açın ve **Yarışmayı başlat** düğmesine basın. Ekrandaki QR ve URL telefona katılım içindir; ağ güvenlik duvarı 3000 portuna yerel ağ erişimine izin vermelidir. Uygulama oda durumunu sunucu belleğinde tutar; sunucu kapatılırsa açık oyun da kapanır. İnternet, QR görsel kütüphanesini yüklemek için gereklidir; QR yüklenmezse ekrandaki URL'yi telefonda açıp kodu girebilirsiniz.

## Oyun

- Bir odada 1–25 oyuncu, 20 soru ve soru başına 20 saniye.
- Her sette karışık teknoloji konularından 19 soru ve milli teknoloji ürünü temalı 1 soru seçilir. Soru havuzundaki 100'ün üzerindeki temel bilgi farklı soru sunumlarıyla 500'ün üzerinde varyasyon üretir.
- Doğru yanıt puanı 500 taban puan, hız bonusu ve küçük seri bonusundan oluşur.
- Her sorudan sonra sıralama; finalde ilk üç için podyum ve birinciye taç/konfeti görünür.
- Karakter seçimi ve takma ad oyuncu ekranında yapılır.

## Soru kapsamı ve başvuru kaynakları

Sorular ortaokul öğrencileri için robotik, yapay zekâ, yazılım, uzay, enerji, haberleşme, mobilite, tarım, sağlık teknolojileri, siber güvenlik ve dijital vatandaşlık konularında hazırlandı. TEKNOFEST'in yarışma temaları konu kapsamına; MEB'in ortaokul bilişim ve yapay zekâ kazanımları yaş düzeyine yön verdi. Kurumların kendileri hakkında bilgi sorusu kullanılmadı. Ürün soruları yerli teknoloji örnekleri hakkındadır.

- [TEKNOFEST yarışma temaları](https://www.teknofest.org/tr/yarismalar/)
- [T3 Vakfı T3 Akademi](https://t3vakfi.org/tr/projelerimiz/t3-akademi)
- [MEB ortaokul Bilişim Teknolojileri ve Yazılım programı](https://tymm.meb.gov.tr/upload/program/bilisim-teknolojileri-ve-yazilim-tegm.pdf)
- [MEB ortaokul Yapay Zekâ Uygulamaları dersi](https://tymm.meb.gov.tr/ortaokul-yapay-zeka-uygulamalari-dersi/unite/1514?kod=D8.2)
- [TÜBİTAK UZAY — İMECE yer gözlem uydusu](https://uzay.tubitak.gov.tr/imece/)
- [TÜRKSAT — TÜRKSAT 6A haberleşme uydusu](https://www.turksat.com.tr/uydu-filosu/turksat-6a)
- [Togg — T10X](https://www.togg.com.tr/t10x)
- [Baykar — İHA sistemleri](https://baykartech.com/tr/insansiz-hava-araci-sistemleri/)
- [SSB — HİSAR-A+ hava savunma sistemi](https://www.ssb.gov.tr/haber/hisardan-iki-mujde-birden-S6EPUR)
- [TUSAŞ — ürün galerisi](https://www.tusas.com/medya-merkezi/fotograf-galerisi)

Havuzdaki ürün adları ve sınıflandırmalar öğretmen tarafından etkinlik öncesinde gözden geçirilebilir; bazı ürün adları ve programlar zaman içinde değişebilir.
