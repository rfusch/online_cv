# Online CV - Minimalistischer Lebenslauf

Ein moderner, minimalistischer Online-Lebenslauf als GitHub Page. Einfach zu personalisieren und professionell im Design.

## 🎨 Features

- **Modernes Design**: Klares, minimalistisches Layout mit sanften Farbverläufen
- **Responsive**: Perfekt auf Desktop, Tablet und Mobile
- **Einfach anpassbar**: Alle Inhalte in einer HTML-Datei
- **Print-optimiert**: Sieht auch gedruckt professionell aus
- **Keine Abhängigkeiten**: Nur HTML und CSS (außer Google Fonts)

## 🚀 Schnellstart

### GitHub Pages aktivieren

1. Gehen Sie zu Ihren Repository-Einstellungen
2. Navigieren Sie zu **Pages** (unter "Code and automation")
3. Wählen Sie unter **Source** den Branch aus (z.B. `main`)
4. Klicken Sie auf **Save**
5. Ihre Seite wird unter `https://[ihr-username].github.io/online_cv/` verfügbar sein

## ✏️ Personalisierung

### 1. Grundlegende Informationen ändern

Öffnen Sie `index.html` und passen Sie folgende Bereiche an:

#### Header-Bereich (Zeile 18-63)
```html
<h1 class="name">Max Mustermann</h1>
<p class="title">Full-Stack Entwickler</p>
```

Ändern Sie:
- Ihren Namen
- Ihre Berufsbezeichnung
- E-Mail-Adresse
- GitHub-Profil-URL
- LinkedIn-Profil-URL
- Standort

#### Profilbild (optional)
Ersetzen Sie das Avatar-Placeholder (Zeile 21-27) mit einem echten Bild:
```html
<div class="profile-image">
    <img src="ihr-foto.jpg" alt="Ihr Name" class="profile-photo">
</div>
```

Fügen Sie dann dieses CSS zu `style.css` hinzu:
```css
.profile-photo {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 4px solid rgba(255, 255, 255, 0.3);
    object-fit: cover;
}
```

### 2. Über mich-Sektion (Zeile 67-74)

Schreiben Sie eine kurze Zusammenfassung über sich, Ihre Erfahrung und Spezialisierung.

### 3. Berufserfahrung (Zeile 77-125)

Für jeden Job passen Sie an:
```html
<div class="experience-item">
    <div class="experience-header">
        <h3 class="job-title">Ihre Position</h3>
        <span class="job-date">Von - Bis</span>
    </div>
    <p class="company-name">Firmenname · Standort</p>
    <ul class="job-description">
        <li>Aufgabe 1</li>
        <li>Aufgabe 2</li>
        <!-- Fügen Sie mehr Punkte hinzu oder entfernen Sie welche -->
    </ul>
</div>
```

### 4. Ausbildung (Zeile 128-140)

Aktualisieren Sie Ihre akademische Ausbildung:
```html
<h3 class="job-title">Ihr Abschluss</h3>
<span class="job-date">Jahr - Jahr</span>
<p class="company-name">Universität/Hochschule</p>
```

### 5. Fähigkeiten (Zeile 143-182)

Passen Sie die Skill-Tags an Ihre Fähigkeiten an:
```html
<span class="skill-tag">React</span>
<span class="skill-tag">Vue.js</span>
<!-- Fügen Sie eigene Skills hinzu -->
```

### 6. Projekte (Zeile 185-213)

Fügen Sie Ihre eigenen Projekte hinzu oder entfernen Sie diese Sektion komplett, falls nicht benötigt.

### 7. Footer (Zeile 216-220)

Aktualisieren Sie das Copyright und Jahr:
```html
<p>© 2024 Ihr Name. Alle Rechte vorbehalten.</p>
```

## 🎨 Farbschema anpassen

Öffnen Sie `style.css` und ändern Sie die CSS-Variablen (Zeile 7-17):

```css
:root {
    --primary-color: #2563eb;  /* Hauptfarbe */
    --accent-color: #3b82f6;   /* Akzentfarbe */
    --text-primary: #1f2937;   /* Haupttextfarbe */
    /* ... weitere Farben */
}
```

## 📱 Struktur

```
online_cv/
├── index.html      # Hauptdatei mit allen Inhalten
├── style.css       # Styling und Design
└── README.md       # Diese Anleitung
```

## 💡 Tipps

- **SEO**: Ändern Sie den `<title>` und `<meta description>` Tag in `index.html`
- **Favicon**: Fügen Sie ein Favicon hinzu für ein professionelleres Aussehen
- **Analytics**: Integrieren Sie Google Analytics oder eine andere Tracking-Lösung
- **Eigene Domain**: Verbinden Sie eine eigene Domain mit GitHub Pages

## 🖨️ Drucken

Die Seite ist für den Druck optimiert. Verwenden Sie einfach `Strg+P` (oder `Cmd+P` auf Mac) in Ihrem Browser.

## 📄 Lizenz

Frei verwendbar für persönliche und kommerzielle Zwecke.

## 🤝 Beitragen

Vorschläge und Verbesserungen sind willkommen! Erstellen Sie einfach ein Issue oder Pull Request.

---

**Viel Erfolg mit Ihrem Online-Lebenslauf!** 🎉
