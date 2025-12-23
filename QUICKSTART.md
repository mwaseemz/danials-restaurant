# 🚀 Quick Start Guide - Danials Website

## Snabbstart (5 minuter)

### Steg 1: Öppna webbplatsen lokalt

**Alternativ A: Direkt i webbläsaren**
1. Navigera till projektmappen
2. Dubbelklicka på `index.html`
3. Webbplatsen öppnas i din standardwebbläsare

**Alternativ B: Med lokal server (Rekommenderat)**

Med Python:
```bash
cd /Users/waseemzaheer/Desktop/Specials/Danials
python3 -m http.server 8000
```

Öppna sedan: `http://localhost:8000`

### Steg 2: Testa funktionerna

1. **Navigation**: Klicka på menyalternativen i headern
2. **Meny-filter**: Testa att växla mellan Indiska rätter, Pizza, Vegetariskt, och Drycker
3. **Lägg till**: Klicka på + knappen vid någon maträtt
4. **Beställ**: Testa beställningsknapparna
5. **Mobilvy**: Ändra fönsterstorlek för att se responsiv design

### Steg 3: Anpassa innehållet

#### Uppdatera kontaktinformation
Redigera `index.html` och sök efter:
- `040-612 00 40` (telefonnummer)
- `info@danials.nu` (email)
- Adressinformation i contact-sektionen

#### Ändra färger
Redigera `styles.css` längst upp:
```css
:root {
    --primary-color: #D97706;  /* Din färg här */
    --secondary-color: #DC2626; /* Din färg här */
}
```

#### Lägg till/ta bort menyobjekt
I `index.html`, hitta `.menu-grid` sektionen och kopiera/redigera menu-items.

### Steg 4: Publicera online

#### Gratis hosting alternativ:

**1. GitHub Pages**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/dittanvändare/danials.git
git push -u origin main
```
Aktivera GitHub Pages i repository settings.

**2. Netlify**
- Dra och släpp projektmappen på netlify.com/drop
- Din webbplats är live på sekunder!

**3. Vercel**
```bash
npm i -g vercel
vercel
```

## 📋 Checklista innan publicering

- [ ] Uppdatera kontaktinformation (telefon, email, adress)
- [ ] Lägg till riktiga matbilder istället för placeholders
- [ ] Lägg till Google Maps integration
- [ ] Uppdatera öppettider om de skiljer sig
- [ ] Testa alla länkar
- [ ] Testa på mobil, tablet, och desktop
- [ ] Lägg till din Google Analytics-kod (om du vill)
- [ ] Verifiera att alla priser är korrekta
- [ ] Lägg till riktiga sociala media-länkar
- [ ] Testa beställningsfunktionen

## 🎨 Snabba anpassningar

### Byta hero-text
Leta upp i `index.html`:
```html
<h1 class="hero-title">
    Välkommen till <span class="highlight">Danials</span>
</h1>
```

### Ändra logotyp
Leta upp i `index.html`:
```html
<span class="logo-text">Danials</span>
<span class="logo-subtitle">Indian Kitchen & Pizza</span>
```

### Lägg till Google Maps
Ersätt `.map-placeholder` i contact-sektionen med:
```html
<iframe 
    src="https://www.google.com/maps/embed?pb=YOUR_EMBED_URL"
    width="100%" 
    height="450" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy">
</iframe>
```

## 🔧 Felsökning

### Problem: Menyn visar inte rätt objekt när jag byter kategori
**Lösning**: Kontrollera att JavaScript är aktiverat och att `script.js` är korrekt länkad.

### Problem: Mobilmenyn öppnas inte
**Lösning**: 
1. Öppna Developer Console (F12)
2. Kolla efter JavaScript-fel
3. Verifiera att alla filer är korrekt länkade

### Problem: Fonts laddas inte
**Lösning**: Kontrollera internetanslutning. Google Fonts kräver internet.

### Problem: Styling ser fel ut
**Lösning**: 
1. Hårduppdatera sidan (Cmd+Shift+R på Mac, Ctrl+Shift+R på Windows)
2. Kontrollera att `styles.css` är korrekt länkad
3. Öppna Developer Console för CSS-fel

## 📞 Support & Hjälp

### Vanliga frågor

**Q: Kan jag använda detta kommersiellt?**
A: Ja! Webbplatsen är skapad för Danials restaurant och kan användas fritt.

**Q: Behöver jag kunna programmera för att ändra innehåll?**
A: Nej, grundläggande ändringar (text, färger, bilder) kan göras utan programmeringskunskap.

**Q: Hur lägger jag till riktiga matbilder?**
A: 
1. Placera bilder i en mapp `images/`
2. Ersätt `.image-placeholder` div med:
```html
<img src="images/dinbild.jpg" alt="Rätt namn">
```

**Q: Hur kopplar jag till ett beställningssystem?**
A: Du kan integrera med:
- Deliveroo API
- Uber Eats API
- Eller bygga egen backend med Node.js/Python

**Q: Är webbplatsen GDPR-kompatibel?**
A: Ja, webbplatsen samlar ingen data. Om du lägger till Analytics eller cookies, behöver du cookie-banner.

## 🎯 Nästa steg

1. ✅ Webbplatsen är klar och fungerar lokalt
2. 📝 Anpassa innehåll och information
3. 🖼️ Lägg till riktiga bilder
4. 🌍 Publicera online
5. 📊 Lägg till analytics
6. 🛒 Integrera beställningssystem (Fas 2)

## 📚 Dokumentation

- `README.md` - Fullständig dokumentation
- `FEATURES.md` - Lista över alla funktioner och jämförelse
- `QUICKSTART.md` - Denna fil
- Kod är välkommenterad för lätt förståelse

---

**Lycka till med din nya webbplats!** 🎉

För teknisk support, kontakta din webbutvecklare eller skapa en issue på GitHub.

