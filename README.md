<p align="center">
  <a href="#"><img src="https://raw.githubusercontent.com/beratcmn/krypton/main/src/icon.png" width="300" alt="Krypton"></a>
</p>
<p align="center">
    <em>Krypton, her yaştan öğrenenler için geliştirildi!</em>
</p>
<p align="center">
 <img src="https://img.shields.io/pypi/pyversions/Django?color=%23&label=Python" alt="Desteklenen Python versiyonları.">
</p>

# Krypton'a hoşgeldin!

Selamlar, Krypton nedir? dediğini duyar gibiyim. Krypton, Python'a dönüşen bir yazılım dili. VE TAMAMEN TÜRKÇE. Evet yanlış duymadın, Python syntax'ının biraz daha yalın ve Türkçe hali gibi düşünebiliriz Krypton'u.

Her ne kadar Krypton'a bir yazılım dili demek doğru olmasada yerleşik kütüphaneleri ile öğrenim sürecinde çok fazla kişiye yardımcı olacağını düşünüyorum.

Krypton çalışmak için [Mithen](https://github.com/beratcmn/mithen)'e ihtiyaç duyar.

Mithen'in son sürümünü indirmek için;

```
python3 -m pip install mithen
```

# Kurulum

Kurulum için "setup.bat" dosyasını çalıştırmanız yeterli. Ardından Krypton'u istediğiniz gibi kullabilirsiniz.

# Gereksinimler

- Python 3.6 veya üstü
- [Mithen](https://github.com/beratcmn/mithen)

# Krypton ile yazılmış bir program nasıl görünüyor?

[Heron alan formülü](https://tr.wikipedia.org/wiki/Heron_form%C3%BCl%C3%BC) ile kenarları 3,4,5 cm olan bir üçgenin alanını hesaplayalım.

```
değişken alan
değişken u

değişken kenar1 = 3
değişken kenar2 = 4
değişken kenar3 = 5

u = (kenar1 + kenar2 + kenar3) / 2
alan = karekök(u * (u - kenar1) * (u - kenar2) * (u - kenar3))
yazdır(alan + " cm^2")
```

## Özellikler

- [x] print() fonksiyonu
- [x] fonksiyon desteği
- [x] değişken tanımlama
- [x] if, else, elif yapıları
- [x] for ve while döngüleri
- [x] kare, karekök, küp, küpkök, mutlak değer matematiksel fonksiyonları
- [ ] sınıf yapısı
- [ ] input desteği
- [ ] break yapısı
- [ ] list yapısı
- [ ] dictionary yapısı