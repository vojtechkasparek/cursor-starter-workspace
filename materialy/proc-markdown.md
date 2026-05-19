# Proč Markdown — a proč na tom záleží

> Tento soubor, který právě čteš, je `.md`. A funguje perfektně.

---

## Co je Markdown

Markdown je způsob jak psát formátovaný text pomocí čistých znaků. `#` = nadpis, `**tučně**`, `-` = odrážka. Nic víc. Výsledek je soubor, který vypadá jako čitelný text i bez jakékoliv aplikace — stačí ho otevřít v Poznámkovém bloku.

Vznikl v roce 2004 jako reakce na HTML — lidé chtěli psát strukturovaný obsah bez nutnosti učit se kódování.

---

## Proč je .md lepší než Word nebo PDF pro práci s AI

**Word (.docx)** je binární formát. Uvnitř souboru je XML zabalený do ZIP archivu spolu se styly, metadata, obrázky a dalšími vrstvami. AI sice dokáže Word přečíst, ale musí extrahovat text z té struktury — a občas se ztratí co je nadpis, co je poznámka, co je zápatí.

**PDF** je ještě horší — je to formát pro tisk, ne pro čtení strojem. Text je uložený jako pozice pixelů na stránce. AI z PDF text technicky dostane, ale strukturu (co je odstavec, co je titulek, co patří k čemu) musí rekonstruovat.

**.md** je čistý text. Otevřeš ho v jakémkoliv editoru, uvidíš přesně to, co AI dostane. Žádné skryté vrstvy, žádné hádat strukturu. Co napíšeš, to AI přečte.

Praktický rozdíl: přiložíš Word s 10 stránkami zápisu ze schůzky a AI možná přeskočí zápatí a ztratí strukturu. Přiložíš `.md` se stejným obsahem a AI ho přečte jako člověk.

---

## Jak vytvořit .md soubor

**Způsob 1 — V Cursoru:**
`Cmd+N` (Mac) nebo `Ctrl+N` (Windows) → napiš obsah → `Cmd+S` → pojmenuj soubor s příponou `.md`

**Způsob 2 — V jakémkoliv textovém editoru:**
Poznámkový blok, TextEdit, Notepad++ — stačí uložit soubor jako `.md` místo `.txt`

**Způsob 3 — Dedicated editor:**
[Obsidian](https://obsidian.md) (zdarma) nebo [Typora](https://typora.io) — zobrazí ti živý náhled formátování

---

## Jak konvertovat existující obsah do .md

**Z Google Docs:**
Otevři dokument → File → Download → Plain Text (.txt) → přejmenuj příponu na `.md`. Nebo zkopíruj celý text a vlož do nového `.md` souboru — formátování zmizí, text zůstane.

**Z Wordu:**
File → Save As → Plain Text → ulož jako `.md`. Nebo stejný copy-paste přístup jako u Google Docs.

**Automaticky (pokročilé):**
Nástroj [Pandoc](https://pandoc.org) umí konvertovat `.docx` → `.md` z příkazové řádky jedním příkazem: `pandoc soubor.docx -o soubor.md`

---

## Jak začít pivotovat vlastní obsah směrem k .md

Nemusíš přepisovat vše najednou. Stačí změnit návyk tvorby nových souborů:

- Zápis ze schůzky? Místo Wordu rovnou `.md`.
- Projektový brief? `.md`.
- Poznámky z přednášky? `.md`.

Za půl roku budeš mít zásobárnu vlastního obsahu, který Cursor umí číst perfektně.

---

*Tento soubor je součástí `cursor-starter-workspace` — kurz Cursor pro každého.*