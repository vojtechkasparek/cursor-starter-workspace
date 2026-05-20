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

---

## Jak přidat nového agenta

1. Vytvoř soubor `1_Agents/agent-[název].md` s instrukcemi agenta.
2. Přidej řádek do tabulky výše.
3. Pokud agent pracuje s konkrétní částí workspace, aktualizuj i `workspace-mapa.md`.

**Trigger pro aktualizaci:** Zavolej `@1_Agents/agent-modul-1.md` a řekni: *"Přidal jsem nového agenta [název]. Pomož mi ho zapsat do registru."*
