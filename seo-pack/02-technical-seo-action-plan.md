# BreadWarriors Teknik SEO Uygulama Planı

## Hemen Yapılacaklar

1. Ana sayfayı SSR/prerender yap.
   - Botlar `title`, `meta description`, H1, kategori linkleri, oyun linkleri ve güven metinlerini ham HTML içinde görmeli.
   - Önerilen title: `Buy & Sell Game Items, Accounts, Gold and Skins | BreadWarriors`
   - Önerilen meta description: `BreadWarriors is a low-fee gaming marketplace to buy and sell game accounts, gold, items, skins, boosting services and gift cards with escrow protection.`

2. Sitemap'i parçalara ayır.
   - `/sitemap.xml`
   - `/sitemaps/static.xml`
   - `/sitemaps/games.xml`
   - `/sitemaps/game-products.xml`
   - `/sitemaps/alternatives.xml`
   - `/sitemaps/blog.xml`

3. URL mimarisini büyüt.
   - `/game/world-of-warcraft`
   - `/game/world-of-warcraft/gold`
   - `/buy/world-of-warcraft-gold`
   - `/sell/world-of-warcraft-gold`
   - `/blog/how-to-buy-world-of-warcraft-gold-safely`

4. Her ticari sayfaya benzersiz içerik ekle.
   - 150-250 kelime açıklama
   - Güvenli alışveriş adımları
   - Satıcı kalite kriterleri
   - Oyun/ürün özel FAQ
   - İlgili kategori linkleri

5. Structured data ekle.
   - Homepage: Organization + WebSite + SearchAction
   - Game hub: BreadcrumbList + ItemList
   - Product pages: Product + Offer + FAQPage
   - Blog: Article + FAQPage

## 30 Günlük Yayın Planı

Hafta 1:
- 14 rakip alternative sayfası
- 20 en önemli oyun hub sayfası
- Escrow, refund, buyer protection, seller rules sayfalarının güçlendirilmesi

Hafta 2:
- 100 ürün tipi sayfası: game + gold/account/items/top-up/boosting
- 20 güven rehberi blogu
- Türkçe ilk 20 sayfa

Hafta 3:
- Rusça ilk 20 sayfa
- Programatik FAQ schema
- İç linkleme blokları

Hafta 4:
- Search Console/Bing Webmaster/Yandex Webmaster kontrolü
- IndexNow entegrasyonu
- Log analizi: Googlebot/Bingbot tarama derinliği
- Düşük performanslı sayfalarda title/H1 testleri

## IndexNow

Bing ve Yandex için IndexNow kullan:

```txt
POST https://api.indexnow.org/indexnow
{
  "host": "breadwarriors.com",
  "key": "YOUR_INDEXNOW_KEY",
  "keyLocation": "https://breadwarriors.com/YOUR_INDEXNOW_KEY.txt",
  "urlList": [
    "https://breadwarriors.com/alternatives/g2g-alternative",
    "https://breadwarriors.com/game/world-of-warcraft/gold"
  ]
}
```

## Page Template Zorunluları

Her landing page şu blokları içermeli:

- H1: ana arama niyetini tam karşılayan başlık
- Above the fold: ürün/kategori linkleri ve search
- 1% fee vaadi
- TradeShield/escrow açıklaması
- Popüler oyunlar veya popüler ürünler
- Sık sorulan sorular
- İç linkler
- Canonical URL
- Hreflang: en, tr, ru

