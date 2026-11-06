# Milutin & Milica · sajt

Igraonica i čuvaonica za decu · TC Roda, Kragujevac.

## Stranice
- `index.html` – početna
- `igraonica.html`, `cuvaonica.html`
- `blog.html` + 3 blog teksta
- `mm-sub.css` – stilovi za podstranice
- `uploads/` – slike, logo i video
- `sitemap.xml`, `robots.txt`, `og-image.jpg`, `.nojekyll`

## Objavljivanje na GitHub Pages
1. Otpremite **ceo sadržaj** ovog foldera u koren repozitorijuma (uključujući skriveni fajl `.nojekyll`).
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. Sajt je za minut na `https://<korisnik>.github.io/<repozitorijum>/`.

## Važno za SEO
Adrese u `<link rel="canonical">`, `og:url`, strukturiranim podacima i u `sitemap.xml`
podešene su na `https://misicv89-ops.github.io/Milutin-i-Milica/`.
Ako sajt objavite na drugoj adresi ili domenu, zamenite tu adresu u svim `.html` fajlovima i u `sitemap.xml`
(Find & Replace u VS Code-u).
Posle objave dodajte sajt u Google Search Console i pošaljite `sitemap.xml`.
