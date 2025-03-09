# Alçak İrtifa Roket Arayüzü - Yedek Aviyonik

Bir roketin aviyonik sisteminden gelen verileri yer bilgisayarında karşılamak için hazırlanmış bir program. 

Karşılayabileceği veriler kısıtlıdır. 


## Karşılanan veriler
- İrtifa verisi
- Konum verileri
- 2 görev göstergesi
- Sensör Hata Göstergeleri
- Tam ekran modu

  
## Ortam Değişkenleri

Programda seçilen COM Port üzerinden gelmesi gereken veri aşağıdadır her bir satırda bu formattan farklı bir veri gelmemelidir.

A4321B40,8500C31,1500FKUX

`A4321` | İrtifa

`B40,8500` | Enlem

`C31,1500` | Boylam

`R` | Görev 1 Sonu

`T` | Görev 2 Sonu

`U` | Sensör Hatası

`X` | GPS Sensöründen Hata gelmesi durumu
  
## Ekran Görüntüleri

![Uygulama Ekran Görüntüsü](https://github.com/yasirsharp/Alcak-Irtifa-Roket-Arayuzu-Ana_Aviyonik/blob/master/Alcak_Irtifa_Asel5000_AnaAviyonik.png)
