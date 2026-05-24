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
| Stavitel | `1_Agents/agent-modul-2.md` | Průvodce tvorbou agentů od identifikace případu po funkční soubor | Modul 2 — chceš postavit nového agenta. Trigger: *"Začínám Modul 2."* nebo *"Chci postavit agenta pro [X]."* |

---

## Jak přidat nového agenta

1. Vytvoř soubor `1_Agents/agent-[funkční-název].md` — název podle role agenta, ne čísla modulu (např. `agent-kronikar-workspace.md`, ne `agent-modul-1.md`).
2. Přidej řádek do tabulky výše.
3. Pokud agent pracuje s konkrétní částí workspace, aktualizuj i `workspace-mapa.md`.

**Trigger pro aktualizaci:** Zavolej `@1_Agents/agent-kronikar-workspace.md` a řekni: *"Přidal jsem nového agenta [název]. Pomož mi ho zapsat do registru."*
