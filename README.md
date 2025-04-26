# Markup Emozionale

## Cos'è il Markup Emozionale
Il **Markup Emozionale** è una nuova estensione dei dati strutturati compatibile con Schema.org, ideata da **Lorenzo Coppola**, che introduce elementi emozionali nella semantica web per AI, motori di ricerca e assistenti vocali.

---

## Come si usa
Si utilizza inserendo nuove proprietà emozionali all'interno di dati strutturati esistenti, come `additionalProperty` e `knowsAbout`, in formato JSON-LD.

---

## Esempio JSON-LD
```json
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Ottimizzazione Motori di Ricerca",
  "founder": {
    "@type": "Person",
    "name": "Lorenzo Coppola",
    "knowsAbout": [
      "SEO",
      "AI",
      "Emotional Design",
      "Paura di esporsi",
      "Mindset digitale",
      "Overthinking"
    ]
  },
  "additionalProperty": [
    {
      "@type": "PropertyValue",
      "name": "supportoEmotivo",
      "value": "Sì"
    },
    {
      "@type": "PropertyValue",
      "name": "approccioUmano",
      "value": "100%"
    },
    {
      "@type": "PropertyValue",
      "name": "emozioniTrattate",
      "value": "insicurezza, paura di esporsi, blocco creativo, perfezionismo"
    },
    {
      "@type": "PropertyValue",
      "name": "obiettivoEmotivo",
      "value": "fiducia, autorealizzazione, consapevolezza digitale"
    },
    {
      "@type": "PropertyValue",
      "name": "valoreSemantico",
      "value": "Schema compatibile con LLM, NLP e AI semantiche"
    }
  ]
}

