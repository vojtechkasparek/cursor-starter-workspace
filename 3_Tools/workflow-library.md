# Workflow Library

> Osvědčené postupy zapsané tak, aby se daly opakovat. Přidávej sem cokoliv, co ti fungovalo dvakrát nebo víckrát.
> Spravuje: Systematik (`@1_Agents/agent-modul-4.md`) — pomůže ti zformátovat postup do záznamu.

---

## Jak přidat nový workflow

```markdown
## [Název workflow]

**Kdy použít:** [jedna věta — situace, kdy tento postup nasadíš]

**Vstupy:** [co potřebuješ mít připravené před začátkem]

**Kroky:**
1. [přesná akce]
2. [přesná akce]
3. [přesná akce]
...

**Výstup:** [co dostaneš na konci — jak vypadá hotový výsledek]

**Poznámky:** [co nefunguje, kde pozor, variace]
```

---

## Rozhodovací tabulka: pravidlo vs. workflow vs. agent

| Situace | Vhodné řešení |
|---------|---------------|
| Krátká instrukce, platí vždy, bez variací | `.cursorrules` pravidlo |
| Postup s více kroky, závisí na kontextu | Workflow library |
| Postup je nový, ještě se stabilizuje | Workflow library — zatím |
| Opakující se výstup s pevnou strukturou | Agent |
| Chceš ho sdílet s jinými lidmi | Workflow library jako dokumentace |
| Spouštíš ho jedním `@` příkazem | Agent |

---

## Záznamy

*(Přidej první záznam v Modulu 4 Lekci 3)*

