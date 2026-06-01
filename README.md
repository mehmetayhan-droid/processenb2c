# Boerschappen B2C ketenflow

GitHub-ready tabbladpagina met losse Mermaid-diagrammen voor de B2C-keten van Boerschappen.

## Inhoud

- `index.html` — volledige pagina met tabbladen en diagrammen
- Mermaid wordt geladen via CDN
- Geen build tool nodig
- Werkt direct met GitHub Pages

## Gebruik lokaal

Open `index.html` direct in je browser.

## Gebruik via GitHub Pages

1. Maak een nieuwe repository aan, bijvoorbeeld `boerschappen-b2c-flowcharts`.
2. Upload `index.html` naar de root van de repository.
3. Ga naar **Settings → Pages**.
4. Kies bij **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Sla op.
6. Open de GitHub Pages URL zodra deze beschikbaar is.

## Diagrammen aanpassen

In `index.html` staat per tabblad een blok:

```html
<pre class="mermaid-source">
flowchart TD
  ...
</pre>
```

Pas de Mermaid-code binnen zo'n blok aan om het diagram te wijzigen.

## Huidige diagrammen

0. Overzicht
1. Shopify + JUO — orderinitiatie
2. Odoo — orderverwerking
3. Odoo — boxinhoud & receptbepaling
4. Odoo — inkoop
5. Odoo — productieplanning
6. IJsVogel — boxen vullen & klaarzetten
7. Odoo — operationele terugkoppeling
8. Last mile & levering
