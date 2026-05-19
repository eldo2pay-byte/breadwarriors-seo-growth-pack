# JSON-LD Schema Şablonları

## Homepage: Organization + WebSite

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "BreadWarriors",
  "url": "https://breadwarriors.com/",
  "logo": "https://breadwarriors.com/logo.png",
  "sameAs": []
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "BreadWarriors",
  "url": "https://breadwarriors.com/",
  "potentialAction": {
    "@type": "SearchAction",
    "target": "https://breadwarriors.com/browse?q={search_term_string}",
    "query-input": "required name=search_term_string"
  }
}
</script>
```

## Game Product Page: Breadcrumb + FAQ

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://breadwarriors.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Games",
      "item": "https://breadwarriors.com/games"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "[Game]",
      "item": "https://breadwarriors.com/game/[game-slug]"
    },
    {
      "@type": "ListItem",
      "position": 4,
      "name": "[Product]",
      "item": "https://breadwarriors.com/game/[game-slug]/[product-type]"
    }
  ]
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Can I buy [Game] [Product] on BreadWarriors?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. BreadWarriors lets players browse [Game] [Product] listings from marketplace sellers when available."
      }
    },
    {
      "@type": "Question",
      "name": "How do I trade safely?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Use BreadWarriors checkout, keep communication on the platform, review seller details and save delivery proof."
      }
    }
  ]
}
</script>
```

## Blog Article

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "[Article Title]",
  "description": "[Meta Description]",
  "author": {
    "@type": "Organization",
    "name": "BreadWarriors"
  },
  "publisher": {
    "@type": "Organization",
    "name": "BreadWarriors",
    "logo": {
      "@type": "ImageObject",
      "url": "https://breadwarriors.com/logo.png"
    }
  },
  "mainEntityOfPage": "https://breadwarriors.com/blog/[slug]",
  "datePublished": "2026-05-20",
  "dateModified": "2026-05-20"
}
</script>
```

