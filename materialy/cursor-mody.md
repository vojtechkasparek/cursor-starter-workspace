# Tři módy Cursoru — kdy který použít

> Přečti si při prvním spuštění workspace. Pak se k tomuto souboru vracet nemusíš — ale je tu, kdykoliv budeš chtít.

---

## Základ: tři módy, tři záměry

| Mód | Co dělá | Kdy ho použít |
|-----|---------|---------------|
| **Ask** | Čte a odpovídá. Do souborů nic nezapisuje. | Chceš se zeptat, pochopit, prozkoumat. |
| **Plan** | Ukáže ti co chystá udělat — ale ještě to neudělá. Čeká na tvé schválení. | Chceš vidět záměr před akcí. Pojistka před každou změnou. |
| **Agent** | Jedná. Zapisuje do souborů, vytváří, mění, maže. | Máš schválený plán nebo jasné zadání a chceš výsledek. |

---

## Tři situace, jeden mód

**"Nevím, co v tomto souboru je."**
→ **Ask**: Otaguj soubor a zeptej se. Agent ti přečte a shrne obsah. Nic se nezmění.

**"Chci vyplnit šablonu, ale nevím co přesně agent chystá."**
→ **Plan**: Agent ukáže každý krok. Ty ho projdeš, schválíš (nebo upravíš), a teprve pak to provede.

**"Vím co chci, plan byl schválený, jdem na to."**
→ **Agent**: Jedná. Soubory se změní. Diff ti ukáže co.

---

## Typická kaskáda v průběhu kurzu

```
Ask  →  Plan  →  Agent
(ptám se)  (vidím záměr)  (schvaluji akci)
```

**Příklad:**
1. `Ask`: "Co je v tomto souboru?"
2. `Plan`: "Vyplň sekci [DOPLNIT] na základě mých odpovědí."
3. `Agent`: soubor se vyplní.

---

## Kde přepínáš

Přepínač módů je **vlevo dole v chatovém panelu** — malá rozbalovací nabídka. Výchozí mód je Ask.

---

## Kde se módy probírají v kurzu

- **Setup (README.md)** — první setkání s kaskádou Ask → Plan → Agent.
- **Modul 1** — Plan mode poprvé v praxi (vyplňování README projektu).
- **Modul 3** — záměrné odmítání a schvalování plánu, čtení diffu.
- **Modul 5** — Plan → Agent jako základ vibe codingu.

---

*Soubor je součástí `cursor-starter-workspace` — kurz Cursor pro každého.*
