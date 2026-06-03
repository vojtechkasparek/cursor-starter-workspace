# Modely a kredity v Cursoru — co potřebuješ vědět

> Přečti si před Modulem 3. Pochopíš proč (a kdy) přepínat modely.

---

## Co je token

Token je základní jednotka textu, se kterou AI pracuje. Přibližně:
- 1 token ≈ 0,75 slova v angličtině (v češtině trochu více, záleží na délce slov).
- Věta "Začínám Modul 3" = přibližně 5–8 tokenů.
- Stránka textu ≈ 500–800 tokenů.

Každý model má limit na to, kolik tokenů zvládne v jedné konverzaci (kontextové okno) — a každý token stojí kredit.

---

## Co je kredit

Cursor funguje na systému kreditů (nebo měsíčního předplatného s limitem požadavků). Každá zpráva, kterou odešleš, spotřebuje určitý počet kreditů — v závislosti na:
- Délce tvého vstupu (kolik @souborů jsi přidal)
- Délce odpovědi agenta
- Modelu, který zprávu zpracovává

---

## Přehled modelů dostupných v Cursoru

V Cursoru přepínáš model v rozbalovací nabídce nahoře v chatovém panelu.

| Model | Síla | Rychlost | Kdy použít |
|-------|------|---------|------------|
| **Claude Sonnet** | Vysoce schopný | Rychlý | Dobrý výchozí pro většinu práce |
| **Claude Opus** | Nejschopnější | Pomalejší | Komplexní plánování, důležitá rozhodnutí |
| **GPT-4o** | Silný, dobře zaoblený | Rychlý | Alternativa Sonnet, výborný na kód |
| **o3 / o4-mini** | Analytický, hluboké uvažování | Pomalejší | Řeší složité problémy krok za krokem |
| **Claude Haiku / gemini-flash** | Lehký | Velmi rychlý | Jednoduché úkoly, opravy, formátování |

---

## Kdy přepínat modely — praktická pravidla

**Plánování (Plan mode):** Použij silnější model (Sonnet, Opus, GPT-4o).
- Přemýšlí o záměru, navrhuje strukturu, zvažuje možnosti.
- Chyba v plánu = chyba v provedení. Vyplatí se investovat do kvalitnějšího modelu.

**Provedení (Agent mode):** Lehčí model může stačit.
- Pokud je plán jasný a výstup strukturovaný, levnější model ho spolehlivě provede.
- Například vyplňování šablony, formátování, doplnění dat do hotové struktury.

**Jednoduché dotazy (Ask mode):** Klidně Haiku nebo flash.
- "Co je v tomto souboru?" nevyžaduje nejsilnější model na světě.

---

## Jak přepnout model v Cursoru

1. Klikni na název modelu v horní části chatovacího panelu.
2. Z nabídky vyber požadovaný model.
3. Model platí pro celou tuto konverzaci (nebo ji v průběhu změnit).

---

## Proč na tom záleží

Používat nejsilnější model na všechno je jako jezdit do obchodu za rohem Ferrari — funguje, ale je to zbytečně drahé a pomalé. Uvědomělý výběr modelu = rychlejší práce + nižší spotřeba kreditů.

---

*Soubor je součástí `cursor-starter-workspace` — kurz Cursor pro každého.*
