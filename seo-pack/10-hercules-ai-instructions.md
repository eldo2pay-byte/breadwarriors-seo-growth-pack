# Hercules AI İçin Uygulama Promptu

Aşağıdaki metni Hercules yapay zekasına ver. ZIP paketindeki dosyaları da aynı görevle birlikte yükle.

```txt
Hercules, BreadWarriors.com için bu ZIP paketindeki SEO ve içerik dosyalarını web sitesine uygula.

Amacımız: BreadWarriors'ı game marketplace alanında organik aramada büyütmek, rakip alternatif aramalarında görünür yapmak ve oyun + ürün tipi aramalarında güçlü landing page ağı kurmak. Siyah şapka SEO, spam, gizli metin, keyword stuffing, sahte yorum veya yanıltıcı rakip iddiaları kullanma. Temiz, sürdürülebilir, Google/Bing/Yandex uyumlu SEO uygula.

Önce bu dosyaları oku:
- 01-competitor-findings.md
- 02-technical-seo-action-plan.md
- 03-alternative-pages.md
- 04-blog-content-cluster.md
- 05-programmatic-page-template.md
- 06-priority-keywords.csv
- 07-json-ld-templates.md
- 08-sitemap-expansion-template.xml
- 09-first-100-programmatic-pages.csv

Uygulama öncelikleri:

1. Public sayfalarda SEO teknik temelini düzelt.
   - Ana sayfa, /browse, /games, /game/*, /alternatives/*, /blog/* sayfaları botlara ham HTML içinde title, meta description, H1, ana içerik, iç linkler ve canonical döndürmeli.
   - Eğer site SPA ise SSR, SSG veya prerender çözümü uygula.
   - Checkout, dashboard, auth, orders gibi private alanlara dokunma.

2. Ana sayfa SEO içeriğini güçlendir.
   - Title: Buy & Sell Game Items, Accounts, Gold and Skins | BreadWarriors
   - Meta description: BreadWarriors is a low-fee gaming marketplace to buy and sell game accounts, gold, items, skins, boosting services and gift cards with escrow protection.
   - H1 game marketplace niyetini açık karşılasın.
   - Above the fold içinde arama, popüler oyunlar, hesaplar, gold/currency, skins, items, boosting, gift cards linkleri olsun.
   - "Only 1% marketplace fee" ve TradeShield/escrow güven mesajı görünür olsun.

3. Rakip alternative sayfalarını yayınla.
   - 03-alternative-pages.md içindeki her rakip için ayrı URL oluştur:
     /alternatives/g2g-alternative
     /alternatives/funpay-alternative
     /alternatives/playerok-alternative
     /alternatives/bynogame-alternative
     /alternatives/z2u-alternative
     /alternatives/plati-market-alternative
     /alternatives/yoomarket-alternative
     /alternatives/gameboost-alternative
     /alternatives/gameflip-alternative
     /alternatives/eldorado-alternative
     /alternatives/gamermarkt-alternative
     /alternatives/zeusx-alternative
     /alternatives/igv-alternative
     /alternatives/kaleoz-alternative
   - Rakipleri kötüleme; karşılaştırmalı, dürüst ve conversion odaklı metin kullan.
   - Her sayfaya FAQ bölümü, Breadcrumb schema ve ilgili oyun/kategori iç linkleri ekle.

4. Blog içeriklerini yayınla.
   - 04-blog-content-cluster.md içindeki ilk blog taslaklarını /blog altında yayınla.
   - Her blogda Article schema, FAQ schema, canonical, meta title ve meta description ekle.
   - Bloglardan ticari sayfalara iç link ver.

5. Programatik SEO sayfa ağını kur.
   - 09-first-100-programmatic-pages.csv içindeki URL listesini oluştur.
   - Her sayfada 05-programmatic-page-template.md şablonunu kullan.
   - Her sayfayı benzersiz game + product niyetine göre düzenle.
   - İçerik thin content olmasın: intro, güvenli alışveriş adımları, satıcı bilgisi, FAQ ve ilgili linkler bulunsun.

6. Structured data ekle.
   - 07-json-ld-templates.md dosyasındaki Organization, WebSite, BreadcrumbList, FAQPage ve Article schema yapılarını uygun sayfalara ekle.
   - JSON-LD geçerli JSON olmalı. Google Rich Results testinde hata vermemeli.

7. Sitemap yapısını genişlet.
   - Mevcut sitemap'i 08-sitemap-expansion-template.xml mantığıyla sitemap index yapısına taşı:
     /sitemaps/static.xml
     /sitemaps/games.xml
     /sitemaps/game-products.xml
     /sitemaps/alternatives.xml
     /sitemaps/blog.xml
   - Yeni yayınlanan tüm public URL'leri sitemap'e ekle.
   - robots.txt içinde sitemap doğru gösterilsin.

8. Çok dilli büyüme için hazırlık yap.
   - EN ana dil kalsın.
   - TR ve RU sayfalar için URL mimarisini hazırla.
   - 06-priority-keywords.csv içindeki TR/RU keywordleri için ilk sayfaları oluştur.
   - Hreflang etiketlerini doğru ekle.

9. Indexing ve webmaster entegrasyonu.
   - Yeni sitemap URL'lerini Google Search Console, Bing Webmaster Tools ve Yandex Webmaster'a gönder.
   - Bing/Yandex için IndexNow entegrasyonu varsa yeni URL'leri gönder.

10. Kontrol ve raporlama.
   - Yayın sonrası şu kontrolleri yap:
     - 200 status code
     - canonical doğru
     - meta title/description var
     - H1 tek ve anlamlı
     - sitemap içinde URL var
     - robots tarafından engellenmiyor
     - mobile responsive
     - schema geçerli
   - En sonunda uygulanan URL listesini, değiştirilen dosyaları ve kalan önerileri raporla.

Başarı ölçütü:
- BreadWarriors public sayfaları SEO dostu HTML döndürmeli.
- Rakip alternative sayfalarının tamamı yayınlanmalı.
- İlk programatik game + product sayfa ağı kurulmalı.
- Blog kümesi yayına alınmalı.
- Sitemap, schema ve indexing akışı çalışmalı.
```

