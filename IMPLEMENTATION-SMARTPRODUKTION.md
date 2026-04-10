# Implementering i Smartproduktion

## Vad filen gor
Anvand [smartproduktion-patch.html](smartproduktion-patch.html) som en drop-in patch i er befintliga sida.
Den:
- uppdaterar hero-copy och CTA till tydligare offertfokus
- lagger till trust badges och fortroenderad under hero
- lagger in sektionen "Darfor valjer kunder JH Attefallshus"
- forstarker modellkort med storlek, anvandning och "Pris fran"
- lagger in process-sektion i 5 steg
- forstarker FAQ rubriker for kopfragor
- lagger in avslutande CTA over footer
- lagger sticky mobil-CTA

## Hur du lagger in patchen
1. Oppna er startsida i Smartproduktion custom code editorn.
2. Klistra in hela innehallet i [smartproduktion-patch.html](smartproduktion-patch.html) i custom HTML/JS/CSS-blocket for startsidan.
3. Publicera och hard-reloada sidan.
4. Kontrollera mobil och desktop.

## Snabb QA-checklista
1. Hero-rubrik: "Nyckelfardiga Attefallshus med fast pris och trygg process"
2. Hero-knapp: "Fa kostnadsfri offert"
3. Sekundar knapp syns: "Se vara husmodeller"
4. Trust-rad under hero syns med 5 punkter
5. "Darfor valjer kunder..." sektionen syns fore modellkort
6. Modellkort visar badges + "Pris fran"
7. Process i 5 steg syns fore recensioner
8. Stark botten-CTA syns fore footer
9. Mobil sticky CTA syns i botten pa sma skarmar

## Kanda antaganden
- Patchen riktar sig mot selectors i er nuvarande HTML (t.ex. VideoHeader-video_header_8894, ServicesInline-services_inline_5282, SmartReviews-reviews_8874, SmartFaqs-faqs_9241).
- Om ID/klassnamn andras i plattformen maste patchen uppdateras.

## Rekommenderat nasta steg
- A/B-test av hero:
  - Variant A: "Nyckelfardiga Attefallshus med fast pris..."
  - Variant B: "Bygg ditt Attefallshus tryggt med fast pris..."
- Matning:
  - klick pa /offertforfragan
  - scroll till formularet
  - formularyinskick
