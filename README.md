# Scrapy_ile_Kitap_yurdu_Projesi
Scrapy ile Kitap Yurdu Sitesinden kitap adı, yazar ve yayıncı verilerini çekip txt dosyasına yazdırıldı. 

# Kitapyurdu Best Sellers Scraper

Bu proje, **[Kitapyurdu](https://www.kitapyurdu.com)** sitesinde yer alan **en çok satan kitapları** otomatik olarak çekmek için geliştirilmiş bir **Scrapy** örneğidir.  
Scrapy framework’ü kullanılarak kitap isimleri, yazar bilgileri ve yayınevleri toplanır ve `books.txt` dosyasına kaydedilir.

---

## Özellikler

- Kitapyurdu’nun **“En Çok Satanlar”** listesinden kitap verilerini toplar.  
- Her kitap için şu bilgileri çeker:
  - 📖 Kitap İsmi  
  - ✍️ Yazar İsmi  
  - 🏢 Yayınevi  
- 5 sayfaya kadar gezinir (toplamda yüz kitap).  
- Verileri **UTF-8** formatında `books.txt` dosyasına yazar.  

---

## Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|------------|-----------|
| [Python 3.x](https://www.python.org/) | Programlama dili |
| [Scrapy](https://scrapy.org/) | Web scraping framework’ü |
| [Pathlib](https://docs.python.org/3/library/pathlib.html) | Dosya yollarını yönetmek için kullanılır |

---

## Kurulum

1. **Projeyi klonla:**
   ```bash
    git clone https://github.com/Stesla48/Scrapy_ile_Kitap_yurdu_Projesi.git
    cd Scrapy_ile_Kitap_yurdu_Projesi



   NOT:cd kitapyurdu yapmayı unutmayın!

2. **Gerekli bağımlılıkları yükle:**

    pip install scrapy

3. **Scrapy ile kodu çalıştır:**
```bash
    scrapy crawl books
