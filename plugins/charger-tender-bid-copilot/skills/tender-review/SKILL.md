---
name: tender-review
description: "Pouzi pri review tendra na nabijacie stanice: citanie zadavacej dokumentacie, extrakcia predmetu, kvalifikacii, technickych poziadaviek, terminov, rizik, priloh a bid/no-bid odporucania. Nepouzivaj na kratky sumar, email, namietku, pricing-only kontrolu ani retrospektivu."
---

# Review Tendru

Tento skill je hlavny workflow pre tender dokumentaciu k nabijacim staniciam.

## Kontext

Najprv precitaj:

- `../../kb/tender-workflow-rules.md`
- `../../kb/tender-private-kb-map.md`
- `../../kb/tender-output-templates.md`

Potom identifikuj dostupne zdroje: zadavacia dokumentacia, zmluva, technicka specifikacia, rozpoctovy formular, prilohy, interny produktovy/cennikovy podklad alebo iba pouzivatelsky brief.

Ak dokumenty alebo private KB chybaju, nehadz fakty. Vrat access gap a poziadaj o upload alebo potvrdenie, ze ma ist iba o sablonu.

## Postup

1. Vypis zdroje, ktore si realne pouzil.
2. Vytiahni predmet obstarania a ciel zakazky.
3. Vytiahni formu, termin, miesto a sposob podania.
4. Rozdel poziadavky na kvalifikacne, technicke, obchodne/zmluvne a administrativne.
5. Pri technickych poziadavkach oznac, ci vyzaduju private produktovu KB alebo kontrolu technikom.
6. Identifikuj povinne prilohy a podklady od AgeVolt.
7. Vytiahni rizika: vylucovacie, cenove, technicke, zmluvne, kapacitne, termínove.
8. Priprav otazky na vyjasnenie, ak zadanie nie je jednoznacne.
9. Daj pracovny bid/no-bid navrh iba ako odporucanie na kontrolu clovekom.
10. Skonci checklistom dalsich krokov.

## Vystup

Pouzi sablonu `Review Tendru` z `tender-output-templates.md`.

Ku kazdemu riziku uveď:

- zavaznost: `high`, `medium`, `low`,
- dopad,
- navrhovany dalsi krok,
- istotu.

## Hranice

- Neposudzuj pravnu zavaznost definitivne; oznac pravne rizika na kontrolu.
- Nevymyslaj technicke parametre, ceny ani dodacie lehoty.
- Nepodavaj tender ani neposielaj dokumenty.
- Ak pouzivatel chce len kratke zhrnutie, pouzi `tender-summary-brief`.
- Ak pouzivatel chce email alebo sprievodny text, pouzi `tender-business-email`.
