# EBA canlı ders crossplatform (Linux & Mac) desteği
Bu script ile EBA canlı dersi Linux, Mac ve Zoom'un çalıştığı diğer işletim sistemleri üzerinde çalıştırabilirsiniz.

EBA, canlı dersleri için Zoom kullanıyor. Fakat dersleri kendi logosu olan uygulamasından başlatmak için, diğer işletim sistemlerinde kullanımı engelliyor. Bu script ile direk Zoom uygulamasını başlatabilirsiniz.

_Bu kod EBA'dan bağımsızdır, herhangi bir hak sahipliği yoktur, kendi sorumluluğunuzda kullanınız. Herhangi bir credit vermeden istediğiniz şekilde değiştirip kullanabilirsiniz._

# Nasıl Kullanılır?
## 1. yol: scripti konsoldan kullanın
- Zoom'u kurun.
- https://ders.eba.gov.tr/ders/ linkine giriş yapın, `Canlı Dersler` sekmesine gelin.
- `F12` tuşuna basın, `Console` sekmesine gelin
- Aşağıdan size uygun olan kodu yapıştırın:

**Öğrenciler:**
```
$.getScript("https://cdn.jsdelivr.net/gh/sh4dowb/eba-canli-ders-crossplatform/ogrenci.js");
```

**Öğretmenler:**
```
$.getScript("https://cdn.jsdelivr.net/gh/sh4dowb/eba-canli-ders-crossplatform/ogretmen.js");
```

## 2. yol: Firefox'a eklenti kurun
Öğrenciler için eklenti: https://addons.mozilla.org/en-US/firefox/addon/eba-canli-ders-ogrenciler/<br>
Öğretmenler için eklenti: https://addons.mozilla.org/en-US/firefox/addon/eba-canli-ders-ogretmen/<br>NOT: daha Firefox'da yayınlanmadı. kaynak kodu indirip, zip'leyip, "debug" modda kurabilirsiniz.

# Uyarı, notlar ve yapılacaklar
**Öğretmen** scripti: **23.09.2020 itibariyle çalışıyor**<br>
**Öğrenci** scripti: son güncellemeden sonra **test edilmedi**<br>
**Firefox** eklentisi: **yayınlanmadı**, **test edilmedi**

## Yapılacaklar:
- Öğrenci için testler (özellikle lacivert ekran ve 11 / 12. sınıflar), Firefox eklentileri için testler
- Öğrenci için ders başlamadıysa hata yakalanıp uyarı verilecek
- Firefox eklentisine ikon eklenip, her sayfa yerine sadece tıklandığında scriptin çalışması sağlanacak

EBA'ya her girişinizde kodu çalıştırmanız gerekli. Eklentiyi ise 1 kere kurmanız yetecektir.

[@bytescreator](https://github.com/bytescreator) başta olmak üzere yardımcı olan herkese çok teşekkürler!

Bu script eskiden bir gist idi. Bazı hataların çözümü için yorumları okumak isterseniz:<br>
https://gist.github.com/sh4dowb/9ecdc521c7323411f3294d5126a2bfde


# İletişim
Issue açarak, ya da cagriari@pm.me veya https://t.me/ üzerinden benimle iletişime geçebilirsiniz.

