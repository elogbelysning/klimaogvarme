# Webshop (Next.js)

Dette er frontend-delen til din automatiske AO.dk-webshop bygget med Next.js.

## Sådan kører du projektet lokalt

1. Gå ind i mappen:

   ```
   cd web
   ```

2. Installer afhængigheder:

   ```
   npm install
   ```

3. Start udviklingsserveren:

   ```
   npm run dev
   ```

4. Åbn browseren på [http://localhost:3000](http://localhost:3000)

## Byg og eksportér statiske filer

Når du er klar til at bygge:

```
npm run build
```

De statiske filer bliver eksporteret til mappen `out/`.

## Struktur

- `pages/` — Next.js-sider
- `next.config.js` — Next.js-konfiguration
- `package.json` — NPM scripts og afhængigheder
- `out/` — Byggede statiske filer (auto-genereret)
