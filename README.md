# klimaogvarme

Automatisk AI-bygning af webshop

## Funktioner

- Automatisk scraping af produkter fra AO.dk
- Data gemmes i CSV-format
- Next.js webshop genereres automatisk fra dataene
- Automatisk deployment til webhotel via GitHub Actions og SFTP

## Sådan bruger du projektet

1. **Klon eller opret et repository på GitHub**
2. **Tilføj dine FTP/SFTP-adgangsoplysninger som secrets i repoet**  
   (Settings → Secrets and variables → Actions)
    - SIMPLY_HOST
    - SIMPLY_USER
    - SIMPLY_PASS
3. **Tilføj eller tilpas produktkategorier i `scraper/ao_scraper.py`**
4. **Push til main**  
   Så kører scraper, webshop genereres og uploades automatisk.

## Projektstruktur

- `scraper/ao_scraper.py` – Python-scraper
- `data/products.csv` – Produktdata (oprettes/overskrives automatisk)
- `web/` – Next.js webshop
- `.github/workflows/deploy.yml` – Automatiseret workflow

## Support

Spørgsmål? Opret et issue – eller få AI-hjælp i chatten!
