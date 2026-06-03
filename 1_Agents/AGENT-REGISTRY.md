# Agent Registry

> Seznam všech agentů v tomto workspace. Aktualizuj tento soubor pokaždé, když přidáš nebo odstraníš agenta.

---

## Jak používat registr

Před voláním agenta se sem podívej — vyber toho, jehož role odpovídá tvému úkolu. Agenta aktivuješ tím, že ho v chatu otaguješ přes `@` picker.

---

## Registr agentů

| Agent | Soubor | Role | Kdy ho volat |
|-------|--------|------|--------------|
| Pomocník | `1_Agents/agent-pomocnik.md` | Tutorial NPC a session manager | První spuštění workspace, začátek nebo konec každé session ("Začínám" / "Uzavři session") |
| Kronikář workspace | `1_Agents/agent-kronikar-workspace.md` | Správce PACT architektury | Modul 1 — odhalení struktury workspace. Kdykoliv přidáváš nový projekt, agenta nebo složku a chceš aktualizovat registr a mapu |
| Tvůrce agentů | `1_Agents/agent-tvurce-agentu.md` | Průvodce tvorbou agentů — OHIO filtr, specifikace přes 4 otázky, Plan gate, test, registrace | Modul 2 — chceš postavit nového agenta. Trigger: *"Začínám Modul 2."* nebo *"Chci postavit agenta pro [X]."* |
| Revizor | `1_Agents/agent-modul-3.md` | Průvodce záměrnou kontrolou: Plan mode, odmítnutí plánu, čtení diffu | Modul 3 — záměrná kontrola před každou větší změnou. Trigger: *"Začínám Modul 3."* nebo *"Projdi se mnou plán."* |
| Systematik | `1_Agents/agent-modul-4.md` | Zaznamenávač vzorců — pravidla, workflow library, rozhodnutí pravidlo vs. agent | Modul 4 — systematizace opakovaných postupů. Trigger: *"Začínám Modul 4."* nebo *"Opakuji tuto instrukci: [instrukce]."* |
| Stavitel nástrojů | `1_Agents/agent-modul-5.md` | Průvodce vibe codingem: tvorba Cursor manifestu (Modul 5) a libovolných HTML nástrojů | Modul 5 — tvorba Cursor manifestu. Trigger: *"Začínám Modul 5."* nebo *"Chci postavit nástroj pro [X]."* |

---

## Jak přidat nového agenta

1. Vytvoř soubor `1_Agents/agent-[funkční-název].md` — název podle role agenta, ne čísla modulu (např. `agent-kronikar-workspace.md`, ne `agent-modul-1.md`).
2. Přidej řádek do tabulky výše.
3. Pokud agent pracuje s konkrétní částí workspace, aktualizuj i `workspace-mapa.md`.

**Trigger pro aktualizaci:** Zavolej `@1_Agents/agent-kronikar-workspace.md` a řekni: *"Přidal jsem nového agenta [název]. Pomož mi ho zapsat do registru."*
