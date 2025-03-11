# KANID UG Website - Version 2

Dies ist das Repository für die offizielle Website der KANID UG, spezialisiert auf Konstruktionsberatung, Prozessoptimierung und 3D-Druck in Stuttgart und Umgebung.

## Überblick

Die Website bietet Informationen über die Dienstleistungen, Unternehmensphilosophie und Kontaktmöglichkeiten der KANID UG. Sie ist für eine optimale Darstellung auf verschiedenen Geräten (Desktop, Tablet, Smartphone) optimiert.

## Technologien

Die Website verwendet:
- HTML5 für Struktur
- CSS3 für Styling
- JavaScript für Interaktivität
- Resend API für das Kontaktformular (über separate Netlify-Funktion)

## Projektstruktur

```
KANID-Website-v2/
│
├── css/                # Stylesheets
│   └── styles.css      # Hauptstylesheet
│
├── html/               # HTML-Dateien
│   ├── index.html      # Startseite
│   ├── impressum.html  # Impressum
│   ├── agb.html        # AGB
│   ├── datenschutz.html # Datenschutzerklärung
│   └── danke.html      # Dankeseite für Kontaktformular
│
├── img/                # Bilder und Grafiken
│   ├── LOGO.png        # KANID Logo
│   ├── icons/          # Icon-Sammlung
│   └── ...
│
└── js/                 # JavaScript-Dateien
    └── scripts.js      # Hauptskriptdatei
```

## Kontaktformular

Das Kontaktformular verwendet die Resend API, die als Serverless-Funktion in einem separaten Repository bereitgestellt wird: [KANID-Kontaktformular-API](https://github.com/KANIDv/KANID-Kontaktformular-API)

## Deployment

Die Website wird von einem Standard-Webhosting-Provider gehostet, während das API-Backend auf Netlify bereitgestellt wird.

## Entwicklungsumgebung

Um lokal an diesem Projekt zu arbeiten:

1. Repository klonen:
   ```
   git clone https://github.com/KANIDv/KANID-Website-v2.git
   ```

2. Einen lokalen Server starten (z.B. mit [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code)

## Lizenz

Copyright © 2024 KANID UG. Alle Rechte vorbehalten.