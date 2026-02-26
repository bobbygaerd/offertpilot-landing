# Landing framework (OffertPilot)

## Mål
Skapa seriösa B2B-landningssidor snabbt, med hög trovärdighet och tydlig CTA.

## Stack (snabb + stabil)
- **Astro + Tailwind CSS** för framtida versioner (modulärt, snabbt, lätt att hosta)
- **Nuvarande drift:** statisk HTML på GitHub Pages
- **Designprincip:** clean SaaS/B2B (mycket whitespace, tydlig hierarki, få färger)

## Struktur (alltid denna ordning)
1. Hero: problem + löfte + CTA
2. Social proof: vem tjänsten passar för
3. Hur det fungerar (3-4 steg)
4. ROI i SEK (konkret exempel)
5. Pris & pilot
6. FAQ (invändningar)
7. CTA igen

## Copy-regler
- Skriv för upptagen företagsägare
- Inga flufford ("banbrytande", "revolution")
- Alltid konkret nytta i tid, kronor eller risk
- Max 1 huvud-CTA

## Promptmall (för AI-generering)

```text
Du är senior B2B conversion copywriter och web designer.
Skapa en svensk landningssida för [TJÄNST] mot [MÅLGRUPP].

Krav:
- Trovärdig svensk B2B-ton (ingen hype)
- Struktur:
  1) Hero med tydligt problem + värdelöfte + CTA
  2) Problemsektion
  3) Så fungerar det (4 steg)
  4) ROI-exempel i SEK
  5) Pris (pilot + månadsplaner)
  6) FAQ med 6 invändningar
  7) CTA-sektion
- Skriv i korta stycken, tydliga bullets
- CTA-text: "Boka 20 min demo"
- Lägg till mikrocopy: "Ingen bindning i pilot"
- Returnera färdig HTML (semantisk, responsiv)
```

## QA-check innan publicering
- [ ] Förklarar sidan vad tjänsten gör på 5 sek?
- [ ] Finns ett tydligt nästa steg?
- [ ] Finns minst ett ROI-exempel i SEK?
- [ ] Låter tonen seriös nog för svensk SME?
- [ ] Mobil-läsbarhet OK?
