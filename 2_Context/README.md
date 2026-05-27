# Kontext

> Tvůj osobní kontext pro AI. Zdroj pravdy o tom, kdo jsi, jak komunikuješ a kam směřuješ.

---

## Struktura

| Složka | Obsah |
|--------|-------|
| `identity/` | Kdo jsi — `o-mne.md`, `jak-komunikuju.md` |
| `cile/` | Kam směřuješ — `aktualni-cile.md` |
| `prace/` | Jak pracuješ — `jak-pracuju.md` |

---

## Jak to používají agenti

Když chceš, aby agent znal tvůj kontext, otaguj příslušný soubor ve zprávě:

```
@2_Context/identity/o-mne.md
@2_Context/identity/jak-komunikuju.md
@2_Context/cile/aktualni-cile.md
```

Nebo odkaz na celou složku, pokud chceš předat vše najednou:

```
@2_Context/
```

---

## Pravidlo

- Toto NENÍ projekt — nemá výstupy ani deadline.
- Toto JE reference — zdroj pravdy pro konzistentní výsledky.
- Průběžně aktualizuj. Čím přesnější kontext, tím přesnější výstupy.

---

*Struktura vychází z PACT metodiky — personal AI context layer.*
