# Danials Indian Kitchen & Pizza - Website Revamp

En modern och responsiv webbplats för Danials restaurang i Malmö.

## 🎨 Features

- **Modern Design**: Vackert och intuitivt användargränssnitt med gradient-färger och smooth animationer
- **Fully Responsive**: Perfekt anpassad för alla enheter (mobil, tablet, desktop)
- **Interactive Menu**: Dynamiska menyflikar med olika kategorier (Indiska rätter, Pizza, Vegetariskt, Drycker)
- **Smooth Animations**: Scroll-animationer och övergångar för en premium användarupplevelse
- **Contact Integration**: Enkel kontakt via telefon och e-post
- **Fast Loading**: Optimerad för snabb laddning och bra prestanda

## 🚀 Teknologier

- **HTML5**: Semantisk och tillgänglig markup
- **CSS3**: Modern styling med CSS Variables, Flexbox, och Grid
- **Vanilla JavaScript**: Ingen externa beroenden för optimal prestanda
- **Font Awesome**: Ikoner för bättre visuell kommunikation
- **Google Fonts**: Playfair Display & Inter för elegant typografi

## 📁 Filstruktur

```
Danials/
├── index.html          # Huvudsida med all innehåll
├── styles.css          # All styling och responsiv design
├── script.js           # Interaktivitet och animationer
└── README.md           # Dokumentation
```

## 🎯 Sektioner

1. **Hero Section**: Välkomstsida med call-to-action knappar
2. **About Section**: Information om restaurangen med tre nyckelpoäng
3. **Menu Preview**: Interaktiv meny med olika kategorier
4. **Opening Hours**: Öppettider och kontaktinformation
5. **Order Section**: Beställningsalternativ (avhämtning/hemleverans)
6. **Contact**: Kontaktuppgifter och platsinformation
7. **Footer**: Snabblänkar och ytterligare information

## 🎨 Färgschema

- **Primary Color**: `#D97706` (Varm orange - perfekt för en restaurang)
- **Secondary Color**: `#DC2626` (Röd - för accenter)
- **Dark**: `#1F2937` (Mörkgrå - text)
- **Accent Green**: `#10B981` (Grön - för positiva element)
- **Background**: Ljusa nyanser för god läsbarhet

## 📱 Responsiv Design

- **Desktop**: Full width layout med multi-column grids
- **Tablet**: Anpassad layout för medium-storlekar (768px - 1024px)
- **Mobile**: Single column layout med hamburger-meny (<768px)

## ⚙️ Installation & Användning

### Lokal utveckling

1. Klona eller ladda ner filerna
2. Öppna `index.html` i din webbläsare
3. Det är allt! Ingen build-process krävs.

### Live Server (Rekommenderat)

För bästa utvecklingsupplevelse, använd en live server:

```bash
# Med Python 3
python -m http.server 8000

# Med Node.js (installera live-server först)
npm install -g live-server
live-server
```

Öppna sedan `http://localhost:8000` i din webbläsare.

## 🔧 Anpassning

### Uppdatera färger

Redigera CSS-variablerna i `styles.css`:

```css
:root {
    --primary-color: #D97706;
    --secondary-color: #DC2626;
    /* ... */
}
```

### Lägg till menyobjekt

I `index.html`, hitta `.menu-grid` sektionen och lägg till:

```html
<div class="menu-item" data-category="indian">
    <div class="menu-item-image">
        <div class="image-placeholder" style="background: linear-gradient(135deg, #FF6B6B 0%, #C92A2A 100%);">
            <i class="fas fa-pepper-hot"></i>
        </div>
    </div>
    <div class="menu-item-content">
        <h3>Rätt Namn</h3>
        <p>Beskrivning av rätten</p>
        <div class="menu-item-footer">
            <span class="price">145 kr</span>
            <button class="btn btn-sm btn-add">
                <i class="fas fa-plus"></i>
            </button>
        </div>
    </div>
</div>
```

### Uppdatera kontaktinformation

Sök efter följande i `index.html` och uppdatera:

- Telefonnummer: `040-612 00 40`
- E-post: `info@danials.nu`
- Adress: I contact-sektionen

## 🎯 Nästa steg / Förbättringar

### Rekommenderade tillägg:

1. **Backend Integration**:
   - Koppla till ett beställningssystem (t.ex. Deliveroo, Uber Eats API)
   - Skapa egen beställningsfunktionalitet med databas

2. **Google Maps Integration**:
   - Lägg till riktig Google Maps embed i contact-sektionen
   - Ersätt map-placeholder med: `<iframe>` från Google Maps

3. **Bilder**:
   - Lägg till riktiga matbilder istället för gradient placeholders
   - Optimera bilder för snabb laddning (WebP format)

4. **Analytics**:
   - Lägg till Google Analytics för att spåra besökare
   - Implementera conversion tracking för beställningar

5. **SEO Optimering**:
   - Lägg till meta-tags för sociala medier (Open Graph)
   - Skapa sitemap.xml
   - Implementera structured data för restauranger

6. **Multi-språk Support**:
   - Lägg till engelska versionen
   - Implementera språkväxlare

7. **Online Beställning**:
   - Integrera med beställningssystem
   - Skapa kundvagn och checkout
   - Betalningsintegration (Swish, Kort)

8. **Reservationssystem**:
   - Bordsbokningsfunktion
   - Kalenderintegration

## 📊 Prestanda

Webbplatsen är optimerad för:
- **Snabb laddning**: Minimal användning av externa resurser
- **Lighthouse Score**: Siktar på 90+ i alla kategorier
- **Accessibility**: WCAG 2.1 AA standard
- **Mobile-First**: Optimerad för mobila enheter först

## 🐛 Felsökning

### Menyn visar inga objekt
- Kontrollera att JavaScript är aktiverat i webbläsaren
- Öppna Developer Console (F12) för felmeddelanden

### Mobilmenyn öppnas inte
- Kontrollera att `script.js` är korrekt länkad
- Verifiera att hamburger-elementet har rätt ID

### Animationer fungerar inte
- Kontrollera browser-kompatibilitet (behöver modern browser)
- Verifiera att CSS-filen är korrekt länkad

## 📄 Licens

© 2025 Danials Indian Kitchen & Pizza Malmö. Alla rättigheter förbehållna.

## 👨‍💻 Support

För frågor eller support:
- 📞 Telefon: 040-612 00 40
- 📧 E-post: info@danials.nu
- 🌐 Webbplats: https://danials.nu

---

**Skapad med ❤️ för Danials Restaurant**

