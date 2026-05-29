# Charger Tender Bid Copilot

Plugin pre AgeVolt tender workflowy k nabijacim staniciam. Slúzi na predajnu a administrativnu pripravu ponuk do verejnych a sukromnych tendrov: rychle vyhodnotenie zadania, extrakciu poziadaviek, rizik, kvalifikacii, otazok, sprievodnej komunikacie, cenovo-administrativnu kontrolu a spatnu evaluaciu.

## Povod

Vychadza z GPT3/GPT6 tender chatov:

- GPT6 `Tendre`: 46 chatov, najcastejsi cisty tender workflow.
- GPT6 `tender-review`: 25 chatov, najpouzivanejsi tender skill kandidat.
- GPT6 `Business Info: AgeVolt`: 52 chatov, ale ide hlavne o podpornu business/product KB a obchodne texty.
- GPT3 `Tendre`: 20 chatov.
- GPT3 `Granty`: 20 chatov.
- GPT3 `Grant AC/DC`: 9 chatov.

## Skilly

- `tender-review` - hlavny workflow pre review zadavacej dokumentacie.
- `tender-summary-brief` - kratky interny brief bez strategickeho rozhodovania.
- `tender-business-email` - obchodne a tender emaily, follow-upy, LoI a sprievodne texty.
- `tender-clarification-objection` - otazky, vysvetlenia, namietky a reakcie na vylucenie.
- `tender-pricing-admin-check` - administrativna kontrola nacenenia, dodacich podmienok a priloh.
- `tender-evaluation-retrospective` - vyhodnotenie uspesnosti, scoringu a bid/no-bid poucenia.

## KB

Plugin obsahuje iba public-safe pravidla a mapu private zdrojov. Konkretne tender dokumenty, zmluvy, cenniky, zakaznicke data, rozpocty a podacie materialy patria do private SharePoint KB alebo lokalneho stagingu.

Ak agent nema private KB alebo dokumenty tendra, nesmie si doplnit fakty. Ma vratit access gap a poziadat o upload, odkaz alebo potvrdenie zdroja.
