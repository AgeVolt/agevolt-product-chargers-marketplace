---
name: tender-pricing-admin-check
description: "Pouzi pri administrativnej a obchodnej kontrole nacenenia tender ponuky na nabijacie stanice: polozky, prilohy, platobne podmienky, dodacie lehoty, rozpoctove riadky a chybajuce podklady. Nepouzivaj na samotne vypocitanie ceny bez private cennika ani na plny review dokumentacie."
---

# Tender Pricing A Administrativna Kontrola

Tento skill kontroluje, ci je tender ponuka obchodne a administrativne pripravena. Nepocita ceny bez private cennika.

## Kontext

Najprv precitaj:

- `../../kb/tender-workflow-rules.md`
- `../../kb/tender-private-kb-map.md`

Over, ci su dostupne cenniky, rozpoctovy formular, produktovy vyber, dodacie podmienky a zoznam povinnych priloh. Ak chyba private cennik alebo rozpoctovy podklad, nahlas access gap.

## Postup

1. Vypis kontrolovane zdroje.
2. Skontroluj, ci ponuka pokryva vsetky polozky zo zadania.
3. Skontroluj, ci su ceny a rozpoctove riadky naviazane na zdroj alebo private KB.
4. Skontroluj dodacie lehoty, platobne podmienky, zaruky, servis a opakujucu sa prevadzku.
5. Skontroluj povinne prilohy a podpisove poziadavky.
6. Oznac chybajuce podklady, konflikty a body na schvalenie.
7. Vrat checklist pred odoslanim.

## Hranice

- Nevymyslaj ceny, marze ani zlavy.
- Neprepisuj zmluvne podmienky ako pravnik.
- Neposkytuj finalne schvalenie ponuky; daj pracovny check na review.
