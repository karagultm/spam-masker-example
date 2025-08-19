# 🔗 Link Masker (Go)

Bu proje, komut satırından verilen bir metin içindeki **URL'leri tespit
edip maskeleyen** basit bir Go uygulamasıdır.\
Örneğin, `http://example.com` adresi maskeleme sonrasında
`http://************` olarak görüntülenir.

------------------------------------------------------------------------

## 🚀 Nasıl Çalıştırılır?

### Gereksinimler

-   [Go](https://go.dev/dl/) kurulu olmalı.

### Adımlar

``` bash
# Depoyu klonla
git clone https://github.com/karagultm/spam-masker-example.git
cd spam-masker-example

# Programı çalıştır
go run main.go "<metin>"
```

Örnek:

``` bash
go run main.go "check this out http://example.com amazing!"
```

Çıktı:

    check this out http://*********** amazing!

------------------------------------------------------------------------

## 🎮 Özellikler

-   Metin içindeki `http://` ile başlayan bağlantıları bulur.\
-   Linkin tamamını maskeleyerek gizler (`*` karakterleriyle).\
-   Boşluk, satır sonu veya tab karakteri görünce maskelemeyi durdurur.\
-   Bağlantının başında `http://` öneki korunur.

------------------------------------------------------------------------

## 📌 Kullanım Senaryoları

-   Paylaşılacak metinlerde bağlantıları gizlemek.\
-   Log dosyalarında URL saklamak yerine maskeleme yapmak.

------------------------------------------------------------------------

## 🛠 Teknolojiler

-   Go programlama dili
