# SEO Improvement Plan for ismailov.uz Portfolio

## Objective
Optimize the portfolio website for Uzbek business owners searching for web development and Telegram bot services in Google search results.

## Target Keywords (Uzbek)
### Primary Keywords
- sayt yaratish
- sayt kerak
- veb sayt buyurtma
- telegram bot yaratish
- telegram bot kerak
- dasturchi xizmati
- veb dasturlash

### Secondary Keywords
- arzon sayt
- biznes uchun sayt
- onlayn do'kon yaratish
- landing page yaratish
- bot buyurtma berish
- professional sayt
- sayt narxi
- telegram bot narxi
- o'zbekistonda sayt yaratish
- toshkent dasturchi

### Long-tail Keywords
- telegram bot buyurtma berish uzbekistan
- veb sayt yaratish xizmati toshkent
- arzon telegram bot yaratish
- biznes uchun telegram bot
- professional veb sayt yaratish

## Technical SEO Tasks

### 1. Language Attribute
- Change `lang="en"` to `lang="uz"`

### 2. Structured Data (JSON-LD)
Add Person and LocalBusiness schema:
```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Diyorbek Ismoilov",
  "jobTitle": "Backend Developer",
  "url": "https://ismailov.uz",
  "sameAs": [
    "https://linkedin.com/in/diyorbekismoilov",
    "https://github.com/deeorbeck",
    "https://t.me/diyorbek_ismailov"
  ]
}
```

### 3. Create robots.txt
```
User-agent: *
Allow: /
Sitemap: https://ismailov.uz/sitemap.xml
```

### 4. Create sitemap.xml
Include main page and any additional pages.

### 5. Fix Open Graph Images
Change relative paths to absolute URLs:
- `./older/images/logo.png` → `https://ismailov.uz/older/images/logo.png`

### 6. Improve H1 Tag
Current: "Portfolio"
New: "Sayt va Telegram Bot Yaratish | Diyorbek Ismoilov"

### 7. Fix Alt Texts
Replace generic "Images" with descriptive Uzbek text for each portfolio item.

## Content Translation Tasks

### Meta Tags
- Title: Include primary keywords
- Description: Compelling Uzbek description with keywords
- Keywords: Comprehensive list of Uzbek search terms

### Page Sections to Translate
1. Navigation menu
2. Hero section
3. Portfolio section (titles, descriptions)
4. About section
5. Services section
6. Skills section
7. Contact section
8. Footer

## Expected Results
- Improved visibility for Uzbek search queries
- Better click-through rates from search results
- Enhanced local SEO for Uzbekistan market
- Professional appearance for Uzbek-speaking clients
