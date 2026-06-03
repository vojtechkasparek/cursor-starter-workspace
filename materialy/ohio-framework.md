# OHIO Framework — filtr pro tvorbu agentů

> Only Handle It Once. Přečti si před Modulem 2.

---

## Proč OHIO

Před tím, než postavíš agenta, je dobré se zastavit a zeptat se: *Má tohle smysl automatizovat?*

Ne všechno, co opakuješ, potřebuje agenta. Někdy stačí jednoduchý postup v hlavě. Jindy je agent zbytečný luxus tam, kde by stačilo pravidlo v `.cursorrules`.

OHIO — **Only Handle It Once** — je tříotázkový filtr, který ti pomůže rychle rozhodnout, zda je tvůj případ kandidátem na agenta.

---

## Tři otázky

**1. Opakuje se to?**
Děláš tento úkol pravidelně — každý týden, měsíc, nebo pokaždé v konkrétní situaci? Pokud je to jednorázová věc, agent nepotřebuješ.

**2. Trvá to déle než minutu?**
Pokud úkol zvládneš za 30 sekund v hlavě, agent je zbytečný overhead. Pokud tě stojí 5–20 minut opakovaného vysvětlování "tohle chci, takhle to má vypadat" — tam agent ušetří čas.

**3. Je to standardizovatelné?**
Existuje vzor výstupu, který chceš pokaždé? Agent funguje nejlépe, když existuje jasná struktura — sekce, formát, tón. Pokud je každý výstup jiný a závisí na nepředvídatelném kontextu, agent bude frustrující.

---

## Jak s tím pracovat

Vzpomeň si na úkol, který možná chceš agentovat. Projdi tři otázky:

| Otázka | Ano | Ne |
|--------|-----|-----|
| Opakuje se? | Pokračuj dál | Stop — agent nepotřebuješ |
| Trvá > 1 minutu? | Pokračuj dál | Možná stačí poznámka nebo pravidlo |
| Jde standardizovat? | Silný kandidát na agenta | Možná workflow library místo agenta |

Pokud jsi odpověděl třikrát "Ano" — máš dobrý případ pro Modul 2.

---

## Kde se OHIO v kurzu použije

- **Modul 2** — Tvůrce agentů ho použije v Kroku 1 jako rozcestník před identifikací případu.
- **Modul 4** — Systematik ho nepřímo aplikuje při rozhodování: pravidlo vs. workflow vs. agent.

---

## Příklad

**Situace:** Každý týden píšu zprávu o stavu projektu pro klienta. Vždy má stejnou strukturu: shrnutí týdne, co bylo hotovo, co přijde příště, rizika.

- Opakuje se? ✓ Každý týden.
- Trvá > 1 minutu? ✓ Asi 20–30 minut psaní.
- Jde standardizovat? ✓ Struktura je vždy stejná.

→ Silný kandidát. Jdi na Modul 2.

---

*Soubor je součástí `cursor-starter-workspace` — kurz Cursor pro každého.*
