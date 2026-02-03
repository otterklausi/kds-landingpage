# KDS – Keller & Dach Spezialisten

**Moderne Landing Page für eine Handwerksfirma**

Eine hochwertige, animierte Landing Page mit modernem Dark-Theme Design.

## ✨ Features

- 🎨 **Modernes Design** – Dark Theme mit Gradienten & Glassmorphism
- ⚡ **GSAP Animationen** – Smooth Scroll, Parallax-Effekte
- 📱 **Voll Responsive** – Mobile-First Ansatz
- 🎯 **Conversion-optimiert** – Sticky CTAs, Notdienst-Highlight
- 🔗 **SEO-ready** – Semantisches HTML, Meta-Tags
- 📄 **Rechtssicher** – Impressum & Datenschutz inklusive

## 📁 Dateistruktur

```
kds-modern/
├── index.html          # Hauptseite
├── impressum.html      # Impressum
├── datenschutz.html    # Datenschutz
└── README.md          # Dokumentation
```

## 🚀 Technologien

- **Tailwind CSS** – Utility-First CSS Framework
- **GSAP** – Professionelle Animationen
- **Lucide Icons** – Moderne Icons
- **Google Fonts** – Space Grotesk & Inter

## 🎨 Design-Features

### Sektionen
1. **Hero** – Eye-catching mit Stats & Floating Cards
2. **Services** – 8 Dienstleistungen im Grid
3. **About** – Über uns mit Trust Badges
4. **Work** – Portfolio/Referenzen
5. **CTA** – Kontakt mit Notdienst-Banner
6. **Footer** – Navigation & Rechtliches

### Besonderheiten
- Grain Texture Overlay
- Magnetic Buttons
- Glass Cards mit Glow-Effekt
- Infinite Marquee
- Scroll-Triggered Animations
- Mobile Navigation

## 🔧 Anpassungen

### Kontaktdaten
In allen HTML-Dateien suchen und ersetzen:
- `+49 123 456 7890` → Telefonnummer
- `info@kds-handwerk.de` → E-Mail
- `Musterstraße 123` → Adresse

### Farben
In `index.html` Tailwind Config anpassen:
```javascript
colors: {
  'brand': { ... },      // Hauptfarbe (Blau)
  'accent': { ... },     // Akzentfarbe (Gold/Gelb)
}
```

### Texte
Einfach im HTML editieren – alle Texte sind gut strukturiert.

## 📤 Deployment

### Option 1: Direkter Upload
```bash
# Alle Dateien auf Webserver kopieren
scp -r kds-modern/* user@server:/var/www/html/
```

### Option 2: Netlify/Vercel
1. Ordner als Git Repo pushen
2. Mit Netlify oder Vercel verbinden
3. Automatisches Deployment

## 📱 Preview

Lokal öffnen:
```bash
cd kds-modern
# Einfacher Server
python3 -m http.server 8000
# oder
npx serve
```

Dann `http://localhost:8000` öffnen.

## 🎯 Nächste Schritte

- [ ] Echte Bilder einfügen (Portfolio)
- [ ] Kontaktdaten aktualisieren
- [ ] Google Analytics hinzufügen
- [ ] Kontaktformular bauen (PHP/Formspree)
- [ ] SEO-Texte optimieren
- [ ] Google My Business verknüpfen

## 📝 Hinweise

- **Kein Build-Prozess** nötig – alles ist statisches HTML
- **CDN-Links** – Tailwind, GSAP, Icons werden extern geladen
- **Keine Cookies** – Datenschutzfreundlich
- **Schnell** – ~100KB Gesamtgröße

## 🏆 Credits

Design & Entwicklung: Klausi 🤖

---

**Gute Handwerker – Gute Arbeit**
