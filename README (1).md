# Boerschappen B2C ketenflow v0.2

GitHub-ready tabbladpagina met losse Mermaid-diagrammen voor de B2C-keten van Boerschappen.

## Belangrijkste wijzigingen in v0.2

- Boxinhoud & receptbepaling is stap 1 geworden.
- Odoo-orderregels bevatten het daadwerkelijke product, bijvoorbeeld de box als product.
- Boxvariant is niet als harde orderkoppeling opgenomen, omdat dit nog met het team besproken moet worden.
- Leverweek is vervangen door leverdatum/productiedag waar relevant.
- Inkoop draait in eerste instantie vanuit een prognosemodule, niet rechtstreeks vanuit orders.
- Orders slokken uiteindelijk de prognosevoorraad op.
- Er is een aparte stap toegevoegd voor voorraadreservering per productiedag.
- Last mile gebruikt daadwerkelijke orders onder andere voor labelgeneratie.

## Gebruik lokaal

Open `index.html` direct in je browser.

## Gebruik via GitHub Pages

Let op: GitHub Pages met private repos werkt alleen bij bepaalde GitHub-plannen. Public repo werkt standaard.

1. Upload `index.html` en `README.md` in de root van je repository.
2. Ga naar **Settings → Pages**.
3. Kies **Deploy from a branch**.
4. Kies branch `main` en folder `/root`.
5. Sla op en open de Pages URL.

## Diagrammen

Overzicht
1. Odoo — boxinhoud & receptbepaling
2. Shopify + JUO — orderinitiatie
3. Odoo — orderverwerking
4. Odoo — prognosemodule & inkoop
5. Odoo — voorraadreservering per productiedag
6. Odoo — productieplanning
7. IJsVogel — boxen vullen & klaarzetten
8. Odoo — operationele terugkoppeling
9. Last mile & levering
