# Real-Time Grammar-Based Syntax Highlighter with GUI
🎯 Kod Çözücü - Gerçek Zamanlı Sözdizimi Vurgulayıcı
Bu proje, JavaScript kodlarını yazarken gerçek zamanlı olarak renklendirme yapan ve aynı zamanda yazılan kodun lexical ve syntax analizini gerçekleştiren bir web uygulamasıdır. Hiçbir dış kütüphane kullanılmadan, tamamen saf JavaScript ile geliştirilmiştir.


 Özellikler
🖍 Gerçek zamanlı sözdizimi renklendirme

 Lexical (token) analizi

 CFG tabanlı Top-Down Recursive Parser

 Parse ağacı görselleştirme

 Temiz ve kullanıcı dostu arayüz


 Kullanım
Projeyi bir .html dosyası olarak kaydedin.

Tarayıcıda açın.

Sol panelde JavaScript kodu yazın.

Sağ panelde:

Token'ların türünü görün.

Parse ağacını canlı olarak takip edin.


 Teknik Detaylar
Lexical Analyzer
Kod karakter karakter işlenir ve şu token türleri tespit edilir:

keyword: let, function, return, vb.

identifier: değişken ve fonksiyon isimleri

string: metin sabitleri

number: sayılar

operator: +, =, ==, * vb.

punctuation: (, ), {, } vb.

comment: // veya /* */ açıklamaları

error: tanınmayan karakterler



Parser (CFG Tabanlı)
Top-Down Recursive Descent yöntemi ile aşağıdaki yapılar çözümlenir:

FunctionDeclaration

function selamla(isim) { ... }

VariableDeclaration

let mesaj = "Merhaba";

ReturnStatement

return mesaj;

Kodun doğru parse edilebilmesi için yazım kurallarına uyulması gerekir.



Token Türü	Renk

keyword	Yeşil

identifier	Mavi

string	Sarı

number	Turuncu

operator	Mor

comment	Gri

punctuation	Lacivert

error	Kırmızı zemin, beyaz yazı


 Proje Yapısı
Tüm proje tek bir HTML dosyasında yer alır. Kod editörü, token listesi ve parse ağacı aynı sayfada canlı olarak çalışır.


Kullanıcı arayüzü şu şekilde çalışır:

Sol Panel: Kod yazımı
Sağ Panel:
   Token Analizi
   Parse Ağacı
   
⚠ Notlar
Proje yönergesi gereği hiçbir hazır sözdizimi kütüphanesi kullanılmamıştır.

Sadece tanımlı JavaScript altkümesi parse edilmektedir. Daha karmaşık yapılar istenirse genişletme yapılabilir.

## Video Linki
https://www.youtube.com/watch?v=hHFPNjpyfj0

## Makale Linki
https://medium.com/@sydneyishere_64059/real-time-syntax-highlighter-ger%C3%A7ek-zamanl%C4%B1-s%C3%B6zdizimi-analizi-ve-parse-tree-g%C3%B6rselle%C5%9Ftirmesi-c7062cfc4503


