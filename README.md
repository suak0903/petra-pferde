# Petra-Pferde-Demonstrator

Unverbindlicher Redesign-Entwurf für [traumasensitive-transformation-mit-pferden.de](https://www.traumasensitive-transformation-mit-pferden.de/) (Petra Ladenburger, Berglesranch, Berglen-Oppelsbohm). Kein offizieller Auftritt; alle Inhalte und Fotos stammen aus dem bestehenden Auftritt (Bildrechte: pt-arts / chewiegraphie). `noindex` auf allen Seiten.

## Stack

Vanilla HTML/CSS/JS nach dem Web-Starter-Kit. Design-System „Sanfte Erde": Waldgrün `#2c3a31`, Mauve `#8d5b68`, Salbei `#8fa695`, Elfenbein `#faf9f4`; Schriften Lora + Nunito Sans (self-hosted, latin-subset).

## Bauen

Gemeinsame Chrome-Partials (`partials/header|demobar|footer.html`) werden per Marker in die Seiten gespiegelt:

```
node build-site.mjs
```

## Seiten

- `index.html` — One-Pager: Hero, Kennst-du-das, Pferde als Katalysator, sicherer Raum, 7 Schritte, Zitat, Team, Angebote/Preise, Galerie, Kontakt
- `hinweise.html` — Über diesen Entwurf (Skala, Design, Vergleich, Referenzen)
- `impressum.html` / `datenschutz.html` / `404.html`
