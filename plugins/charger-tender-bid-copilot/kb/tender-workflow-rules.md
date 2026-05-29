# Tender Workflow Pravidla

## Zakladne Pravidlo

Tento plugin pracuje s tendrami na nabijacie stanice a suvisiace sluzby. Nepouzivaj ho na portalovy vyvoj myAgeVolt, uctovnictvo, SuperFakturu, vyrobu alebo vseobecne pravne review bez suvisu s ponukou nabijaciek.

## Zdroj Pravdy

Pri kazdom tasku najprv urci, z coho agent vychadza:

- zadavacia dokumentacia tendra,
- zmluva alebo navrh obchodnych podmienok,
- technicka specifikacia,
- interny produktovy/cennikovy podklad,
- predchadzajuca AgeVolt ponuka alebo referencny text,
- pouzivatelsky brief.

Ak zdroj chyba, nepokracuj odhadom. Vrat kratky access gap a vypytaj si dokument alebo potvrdenie, ze ma ist iba o sablonu.

## Citlivost

Tender dokumenty, cenniky, rozpocty, zakaznicke data, interne marze a rozhodnutia bid/no-bid su private. Nedavaj ich do public Gitu ani do public-safe KB. Vo vystupe pouzi iba nevyhnutne fakty a nesir plne znenia dokumentov.

## Spolocne Vystupne Pravidla

- Vystup pis po slovensky alebo v jazyku zadania, ak pouzivatel poziada inak.
- Oddel fakty zo zadania od interpretacie alebo odporucania.
- Pri neistote oznac `istota: low/medium/high`.
- Pri rizikach uved dopad a navrhovany dalsi krok.
- Pri deadline alebo poziadavke udrz zdrojovu vetu alebo miesto v dokumente, ak je dostupne.
- Pri cenach a produktoch pouzi private produktovu/cennikovu KB; ak chyba, nahlas access gap.

## Stop Pravidla

- Nevymyslaj parametre nabijaciek, ceny, dodacie lehoty ani certifikacie.
- Nerob zavazne pravne stanovisko; priprav iba pracovnu analyzu a rizika na kontrolu zodpovednou osobou.
- Nepodavaj ponuku, neposielaj email ani nevykonavaj externu akciu bez explicitneho potvrdenia pouzivatela.
- Nevyhlasuj tender za vyhratelny iba na zaklade dojmu; pouzi scoring alebo zretelne oznac, ze ide o odhad.
