  **--PROJEDE YER ALAN KİŞİLER--**
 * GÖRKEM ENES İNCİ 213405036
 * MURATHAN AKTAŞ 203405010

  **--BENZER OYUN BULMA PROJESİ--**
 * Girilen Oyun Adına Benzer İstenilen Sayıda Oyun ve Açıklamasını Yazdırıyoruz.
 * Cosinüs benzerliğinden faydalanıldı.

  **--VERİ SETİNİN OLUŞTURULMASI--**
 * Veri Setinin Oluşturulmasında Selenium'dan yararlanıldı.

 * [steam.com](https://store.steampowered.com) sitesinden veriler çekildi.

 driver.get(f"https://store.steampowered.com/search}")
 Çekilen veriler txt dosyalarına yazıldı.

 2 adet txt dosyası kullanıldı.

 oyunlar.txt (Kitap adlarının verileri)
 hakkinda.txt (Kitap özetlerinin verileri)
 Toplam oyun sayısı: 1362
 Oyun Tanımlarında Geçen Kelime Sayısı : 5466

Veriler adi ve  hakkinda iki kolonu olan bir DataFrame'e aktarıldı.

  **--GEREKLİ İMPORT KODLARI--**
	
 from simplemma import text_lemmatizer

 import pandas as pd

 import numpy as np

 import ast

 import re

 from selenium import webdriver

 from selenium.webdriver.chrome.service import Service

 from selenium.webdriver.support.wait import WebDriverWait

 from selenium.webdriver.support import expected_conditions

 from selenium.webdriver.common.by import By

 from selenium.common.exceptions import NoSuchElementException


![2](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/23535cc6-a33e-4257-b4e3-a144404a3c4a)
![1](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/9973827e-a753-49a3-8e34-44c9cc0c99a3)

![3](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/c3c50678-c949-4ebd-8b73-1a5060e75b9a)

**SÖZLÜK ÖRNEKLERİ **
 'yük': 57,
 
 'kamyon': 58,
 
 'akıl': 59,
 
 'al': 60,
 
 'mesafe': 61,
 
 'teslim': 62,
 
 'et': 63,
 
 'avrupa': 64,
 
 'yı': 65,
 
 'uç': 66,
 
 'dolaş': 67,
 
 'yol': 68,
 
 'kral': 69,
 
 'ol': 70,
 
 'ingiltere': 71,
 
 'belçika': 72,
 
 'almanya': 73,
 
 'italya': 74,
 
 'hollanda': 75,
 
 'polonya': 76,
 
 'pek': 77,
 
 'çok': 78,
 
 'diğer': 79,
 
 'ülke': 80,
 
 'keşfet': 81,
 
 'düzine': 82,
 
 'şehir': 83,
 
 'var': 84,

 'dayanıklılık': 85,
 
 'beceri': 86,
 
 'hız': 87,
 
 'sınır': 88,
 
 'zorla': 89,
 
 'ea': 90,
 
 'sports': 91,
 
 'fc': 92,
 
 'siz': 93,
 
 'karşıla': 94,
 
 'hypermotionv': 95,
 
 'opta': 96,
 
 'taraf': 97,
 
 'optimize': 98,
 
 'oyuntarz': 99,
 
 'geliş': 100,
 
 'frostbit': 101,
 
 'motor': 102,
 
 'ile': 103,
 
 'bugün': 104,
 
 'kadarki': 105,
 
 'en': 106,
 
 'gerçek': 107,
 
 'futbol': 108,
 
 'war': 109,
 
 'thunder': 110,
 
 'savaş': 111,
 
 'kore': 112,
 
 'araç': 113,
 
 'kullan': 114,
 
 'aşama': 115,
 
 'ortam': 116,
 
 'hava': 117,
 
 'kara': 118,
 
 'deniz': 119,
 
 'birlikte': 120,
 
 'yap': 121,
 
 'iyi': 122,
 
 'sınırsız': 123,
 
 'eğlence': 124,
 
 'sürücü': 125,
 
 'meksika': 126,
 
 'nın': 127,
 
 'capcanlı': 128,
 
 **BU ŞEKİLDE DEVAM EDİYOR**.


**- TEMİZLENMEDEN ÖNCE -*


![Ekran görüntüsü 2024-01-08 194646](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/c2123a2b-446b-4d4e-b91a-627da3a9cf0c)


*-TEMİZLENDİKTEN SONRA-**

![Ekran görüntüsü 2024-01-08 193355](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/950b132a-b5be-45c0-935b-ea563e99d2cd)


** IDF ** 

![Ekran görüntüsü 2024-01-08 195242](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/61e49838-9390-4c3a-b3c8-a6a7f1e48e15)


** TF **

![Ekran görüntüsü 2024-01-08 195322](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/44c2b7f5-d78a-48c3-b7a0-35e585154973)

** TF * IDF **

![Ekran görüntüsü 2024-01-08 195524](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/41035954-ccdf-4443-9166-b93f18e29041)


-** BAZI ÖRNEKLER -**
![Ekran görüntüsü 2024-01-08 195647](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/d02b77bd-8be8-4410-9577-bb890b6b456f)

![Ekran görüntüsü 2024-01-08 195803](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/35aa0f41-4f46-41e3-b47a-5904cfd41574)

![Ekran görüntüsü 2024-01-08 195921](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/a3c16d41-3871-4930-b7eb-62f0d8ff0a5a)

![Ekran görüntüsü 2024-01-08 200012](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/821f62c7-36ec-4301-8e21-c711ff893d2a)

![Ekran görüntüsü 2024-01-08 200129](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/ca59b0cc-c8b1-4177-85e8-228102a2a836)

![Ekran görüntüsü 2024-01-08 200233](https://github.com/gorkemenes/benzer_oyun_bulma_projesi/assets/91761679/58b3585b-84e3-41c1-a81f-c598e7262104)


