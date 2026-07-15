# Workspace mapa

> Master mapa tohoto PACT workspace. Tento soubor čte každý agent při první orientaci — bez něj by musel hádat co kde je.

---

## Struktura workspace

Tento workspace je postaven na PACT frameworku — čtyři zóny, každá s jasnou rolí.

```
cursor-starter-workspace/
├── workspace-mapa.md       ← tento soubor (první zastávka pro každého agenta)
├── .cursorrules            ← pravidla platná pro celý workspace
├── README.md               ← vstupní bod pro nového studenta
│
├── 0_Projects/             ← P: aktivní projekty a jejich výstupy
│   ├── sablona-projektu/   ← šablona pro nový projekt ([DOPLNIT])
│   ├── pruchod-kurzem/     ← první projekt: průchod kurzem
│   │   ├── README.md       ← cíl, status, materiály projektu
│   │   ├── kurz.md         ← mapa celého kurzu (agenti čtou pro navigaci)
│   │   └── muj-denik.md    ← session log průchodu kurzem
│   └── zaverecny-projekt/  ← závěrečný projekt studenta (Modul 5+)
│       ├── README.md       ← zadání, kritéria, příklady scénářů
│       ├── denik-projektu.md ← deník průchodu závěrečným projektem
│       └── vystupy/        ← sem student ukládá výstupy projektu
│
├── 1_Agents/               ← A: agenti — průvodci, specialisté, kronikáři
│   ├── AGENT-REGISTRY.md   ← seznam všech agentů a kdy je volat
│   ├── agent-pomocnik.md   ← session manager a tutorial NPC
│   ├── agent-kronikar-workspace.md ← správce PACT architektury (Modul 1)
│   ├── agent-tvurce-agentu.md ← Tvůrce agentů — průvodce tvorbou agentů, OHIO filtr (Modul 2)
│   ├── agent-modul-3.md    ← Revizor — průvodce záměrnou kontrolou (Modul 3)
│   ├── agent-modul-4.md    ← Systematik — průvodce systematizací (Modul 4)
│   └── agent-modul-5.md    ← Stavitel nástrojů — průvodce vibe codingem (Modul 5)
│       (... další agenti se přidávají průběžně a přejmenovávají na roli)
│
├── 2_Context/              ← C: kontext — paměť workspace o uživateli
│   ├── identity/
│   │   ├── o-mne.md        ← kdo jsem, co dělám, v jakém oboru
│   │   └── jak-komunikuju.md ← styl komunikace a tone of voice
│   ├── cile/
│   │   └── aktualni-cile.md ← aktuální cíle a priority
│   └── prace/
│       └── jak-pracuju.md  ← pracovní styl, nástroje, rutiny
│
├── 3_Tools/                ← T: nástroje — skripty a opakované utility
│   ├── priklad-nastroje/   ← ukázkový HTML nástroj (prohlédnout v Modulu 4)
│   │   ├── index.html      ← spustitelný nástroj v prohlížeči
│   │   └── README.md       ← jak nástroj použít
│   ├── muj-cursor-manifest/ ← osobní Cursor manifest (vytváří se v Modulu 5)
│   │   ├── index.html      ← manifest stránka (otevřít v prohlížeči)
│   │   └── README.md       ← jak manifest otevřít a aktualizovat
│   └── workflow-library.md ← zápisy fungujících postupů (Modul 4+)
│
└── materialy/              ← cvičební dokumenty + teoretické podklady (mimo PACT)
    ├── cursor-mody.md          ← referenční přehled Ask / Plan / Agent módů
    ├── kontextove-okno.md      ← co je kontextové okno, proč fresh chat per modul
    ├── ohio-framework.md       ← filtr pro rozhodnutí "má tohle smysl agentovat?"
    ├── cursor-modely-a-kredity.md ← přehled modelů, tokeny, kredity, kdy přepínat
    ├── human-in-the-loop.md    ← princip AI navrhuje / člověk rozhoduje + cvičební dokument Modulu 3
    ├── proc-markdown.md        ← proč .md soubory pro AI éru
    ├── muj-email.md            ← sem student vloží svůj e-mail (tone of voice analýza)
    ├── ukazka-dokumentu.md
    ├── ukazka-hodnoceni.md
    ├── ukazka-sablony.md
    └── sablona-zpravy.md   ← vícesekcový dokument pro cvičení diffu
```

---

## PACT — co každá zóna znamená

| Zóna | Složka | Účel |
|------|--------|------|
| **P** — Projects | `0_Projects/` | Kde žijí projekty a jejich výstupy. Každý projekt = vlastní podsložka s README. |
| **A** — Agents | `1_Agents/` | Průvodci, specialisté, kronikáři. Každý agent = `.md` soubor s instrukcemi. |
| **C** — Context | `2_Context/` | Paměť workspace: kdo jsi, jak komunikuješ, co chceš. Agenti ho čtou pro personalizaci. |
| **T** — Tools | `3_Tools/` | Nástroje pro opakované úkoly — skripty, HTML nástroje, workflow library. |

---

## Klíčové soubory pro agenty

Při orientaci ve workspace přečti tyto soubory:

1. `workspace-mapa.md` — tento soubor (struktura a logika)
2. `1_Agents/AGENT-REGISTRY.md` — kdo je k dispozici a na co ho zavolat
3. `2_Context/` — kdo je uživatel a jak s ním pracovat

---

## Pravidlo pro rozšiřování workspace

- Nový projekt → nová podsložka v `0_Projects/` s `README.md`
- Nový agent → nový `.md` soubor v `1_Agents/` + záznam v `AGENT-REGISTRY.md`
- Nový kontext → nový soubor v příslušné podsložce `2_Context/`
- Nový nástroj → nová podsložka v `3_Tools/` s `README.md`
- Workflow zápis → přidat do `3_Tools/workflow-library.md`
