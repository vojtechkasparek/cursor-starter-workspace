# Kurz: Cursor pro každého

> Tvoje mapa kurzu. Pomocník čte tento soubor na začátku každé session — aby věděl nejen kde jsi byl (deník), ale i kam jdeš (tady).

---

## Jak kurz funguje

Každý modul má jednoho průvodce (agenta), jednu věc, kterou vytvoříš, a jeden konkrétní důkaz, že jsi modul dokončil. Pomocník čte tento soubor a deník, porovná je a řekne ti přesně co je dalším krokem. Ty nepotřebuješ vědět co přijde — stačí říct "Začínám".

---

## Příprava — Setup workspace

- **Co se naučíš:** Základní ovládání Cursoru — tagování souborů přes `@`, rozdíl mezi Ask / Plan / Agent módem. Nastavíš svůj kontext, aby tě Cursor "znal".
- **Co vytvoříš:** `materialy/muj-email.md` + vyplněné soubory v `2_Context/identity/` (jak-komunikuju.md, o-mne.md)
- **Agent:** `@1_Agents/agent-pomocnik.md` → *"Zdravím. Hlásím se na výcvik!"*
- **Důkaz dokončení:** `2_Context/identity/jak-komunikuju.md` neobsahuje žádné `[DOPLNIT]` placeholdery

---

## Modul 1 — Workspace jako systém

- **Co se naučíš:** PACT framework — čtyři zóny workspace a proč existují. Mapa a registr agentů jako infrastruktura, která se čte sama.
- **Co vytvoříš:** Vyplněné `0_Projects/pruchod-kurzem/README.md` + Kronikář workspace registrovaný v `1_Agents/AGENT-REGISTRY.md`
- **Agent:** `@1_Agents/agent-kronikar-workspace.md` → *"Začínám Modul 1."*
- **Důkaz dokončení:** `AGENT-REGISTRY.md` obsahuje řádek pro Kronikáře workspace

---

## Modul 2 — Postav si nástroj

- **Co se naučíš:** Jak vytvořit vlastního agenta od identifikace případu po funkční soubor. Plan mode jako quality gate před vznikem souboru — ne jen pojistka nad existujícím.
- **Co vytvoříš:** Vlastní agent v `1_Agents/agent-[tvoje-tema].md` registrovaný v AGENT-REGISTRY.md
- **Agent:** `@1_Agents/agent-modul-2.md` → *"Začínám Modul 2."*
- **Důkaz dokončení:** `AGENT-REGISTRY.md` obsahuje tvůj vlastní agent s funkčním názvem (ne agent-modul-2.md)

---

## Modul 3 — Vidíš záměr dřív než čin

- **Co se naučíš:** Plan mode jako pojistka před každou změnou workspace. Jak záměrně odmítnout nebo upravit plán agenta. Jak číst diff a co v něm hledat.
- **Co vytvoříš:** Reálnou úpravu existujícího dokumentu provedenou přes Plan → odmítnutí/úprava → schválení → Agent
- **Agent:** `@1_Agents/agent-modul-3.md` → *"Začínám Modul 3."*
- **Důkaz dokončení:** Máš v deníku záznam o záměrném odmítnutí plánu a jeho úpravě

---

## Modul 4 — Naučíš ho jednou, pamatuje si navždy

- **Co se naučíš:** `.cursorrules` — pravidla platná pro celý workspace. Workflow library jako recept sešit osvědčených postupů. Kdy z workflow udělat agenta.
- **Co vytvoříš:** Aspoň 3 vlastní pravidla v `.cursorrules` + jedno zapsané workflow v `3_Tools/workflow-library.md`
- **Agent:** `@1_Agents/agent-modul-4.md` → *"Začínám Modul 4."*
- **Důkaz dokončení:** Agent dodržuje tvoje pravidla bez opakování v každém promptu + workflow library obsahuje jeden funkční záznam

---

## Modul 5 — Tvůj první nástroj

- **Co se naučíš:** Vibe coding — popis výsledku místo psaní kódu. Celý cyklus: zadání → plán → realizace → test → úprava → README.
- **Co vytvoříš:** Funkční HTML nástroj v `3_Tools/[nazev-nastroje]/` s README pro předání
- **Agent:** `@1_Agents/agent-modul-5.md` → *"Začínám Modul 5."*
- **Důkaz dokončení:** Nástroj funguje a jiný člověk ho umí použít podle README

---

## Závěrečný projekt

- **Co uděláš:** Vezmeš reálnou situaci ze svého života nebo práce — a postavíš pro ni řešení v Cursoru (workflow, agenta nebo nástroj).
- **Žádný návod.** Tento projekt je důkazem, že jsi přenesl dovednosti z kurzu do reálného kontextu.
- **Podklady:** `0_Projects/zaverecny-projekt/README.md` — zadání, kritéria a příklady scénářů
- **Důkaz dokončení:** Funkční workflow nebo nástroj + krátký zápis "co fungovalo, co jsem se naučil" v `0_Projects/zaverecny-projekt/denik-projektu.md`

---

## Jak Pomocník tento soubor čte

Při "Začínám" porovná tento soubor s `muj-denik.md`:
- Najde poslední dokončený modul (podle důkazů dokončení)
- Identifikuje první nedokončený modul
- Řekne ti přesně: kterého agenta zavolat a co mu napsat

Při "Uzavři session" zkontroluje, zda session dokončila nějaký milestone — a pokud ano, zapíše to do deníku konkrétně.
