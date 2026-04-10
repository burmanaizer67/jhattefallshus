# Implementering i Smartproduktion

## Vad filen gör
Använd [smartproduktion-patch.html](smartproduktion-patch.html) som en drop-in patch i er befintliga sida.
Den:
- uppdaterar hero-copy och CTA till tydligare offertfokus
- lägger till trust badges och förtroenderad under hero
- lägger in sektionen "Därför väljer kunder JH Attefallshus"
- förstärker modellkort med storlek, användning och "Pris från"
- lägger in process-sektion i 5 steg
- förstärker FAQ-rubriker för köpfrågor
- lägger in avslutande CTA över footer
- lägger sticky mobil-CTA

## Hur du lägger in patchen
1. Öppna er startsida i Smartproduktion custom code editorn.
2. Klistra in hela innehållet i [smartproduktion-patch.html](smartproduktion-patch.html) i custom HTML/JS/CSS-blocket för startsidan.
3. Publicera och hard-reloada sidan.
4. Kontrollera mobil och desktop.

## Snabb QA-checklista
1. Hero-rubrik: "Nyckelfärdiga Attefallshus med fast pris och trygg process"
2. Hero-knapp: "Få kostnadsfri offert"
3. Sekundär knapp syns: "Se våra husmodeller"
4. Trust-rad under hero syns med 5 punkter
5. "Därför väljer kunder..." sektionen syns före modellkort
6. Modellkort visar badges + "Pris från"
7. Process i 5 steg syns före recensioner
8. Stark botten-CTA syns före footer
9. Mobil sticky CTA syns i botten på små skärmar

## Kända antaganden
- Patchen riktar sig mot selectors i er nuvarande HTML (t.ex. VideoHeader-video_header_8894, ServicesInline-services_inline_5282, SmartReviews-reviews_8874, SmartFaqs-faqs_9241).
- Om ID/klassnamn ändras i plattformen måste patchen uppdateras.

## Rekommenderat nästa steg
- A/B-test av hero:
  - Variant A: "Nyckelfärdiga Attefallshus med fast pris..."
  - Variant B: "Bygg ditt Attefallshus tryggt med fast pris..."
- Matning:
  - klick på /offertförfrågan
  - scroll till formuläret
  - formulärinskick
