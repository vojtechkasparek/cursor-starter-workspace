# Human-in-the-loop — principy spolupráce člověka a AI

> Tento dokument je cvičební materiál pro Modul 3. Shrň ho do 5 bullet pointů — a zároveň si přečti co ti říká o způsobu práce, který právě trénuješ.

---

## Co je human-in-the-loop

Human-in-the-loop (česky: člověk v smyčce) je přístup k práci s AI, kdy člověk pravidelně vstupuje do procesu, hodnotí výsledky a rozhoduje o dalším směru. AI nevyřeší problém jedním průchodem — člověk ji usměrňuje v každém kroku.

Opakem je "fire and forget" — zadáš AI úkol a čekáš na výsledek bez jakékoliv průběžné kontroly. To funguje jen u triviálních, jasně definovaných úkolů.

---

## Proč je human-in-the-loop důležitý

AI dělá chyby. Ne vždy záměrně nebo nápadně — výstup může vypadat přesvědčivě a přitom obsahovat faktickou chybu, chybějící sekci nebo špatný tón. Bez průběžné lidské kontroly se tyto chyby hromadí.

Zároveň: AI nezná tvůj záměr s jistotou. I precizní prompt může AI interpretovat trochu jinak, než jsi myslel. Teprve když vidíš výstup, víš jestli sedí.

---

## Jak human-in-the-loop vypadá v Cursoru

1. **Zadáš instrukci** v Plan mode — AI navrhne plán.
2. **Přečteš plán** — ne letmo, celý. Odpovídá tomu, co jsi chtěl?
3. **Schválíš, nebo odmítneš a upřesníš** — to je tvůj vstup do smyčky.
4. **AI provede schválený plán** — Agent mode.
5. **Přečteš diff** — co se opravdu změnilo? Nic navíc, nic chybí?
6. **Přijmeš nebo vrátíš** — poslední kontrolní bod.

Každý krok 2, 3 a 5 je "human-in-the-loop" moment. Bez nich AI pracuje slepě.

---

## Kdy human-in-the-loop selhává

- Schvaluješ plán bez čtení — klikáš "OK" reflexivně.
- Nepřečteš diff — přijmeš změny bez kontroly.
- Zadáváš příliš vágní instrukce a doufáš, že AI "pochopí" — pak se divíš výsledku.

---

## Praktické pravidlo

> AI navrhuje. Ty rozhoduješ. Nikdy naopak.

Kvalita tvé práce s Cursorem závisí na kvalitě tvých rozhodovacích vstupů — ne na tom, jak chytrý je model.

---

## Kde se human-in-the-loop v kurzu trénuje

- **Modul 3** — záměrné odmítnutí plánu, čtení diffu. Toto cvičení je o tom principu.
- **Každý modul** — Plan → schválení → Agent je human-in-the-loop v praxi od začátku.

---

*Soubor je součástí `cursor-starter-workspace` — kurz Cursor pro každého.*
