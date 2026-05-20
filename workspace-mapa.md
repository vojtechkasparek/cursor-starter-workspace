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
│   └── pruchod-kurzem/     ← první projekt: průchod kurzem
│       ├── README.md       ← cíl, status, materiály projektu
│       └── muj-denik.md    ← session log průchodu kurzem
│
├── 1_Agents/               ← A: agenti — průvodci, specialisté, kronikáři
│   ├── AGENT-REGISTRY.md   ← seznam všech agentů a kdy je volat
│   ├── agent-pomocnik.md   ← první průvodce a NPC session manageru
│   └── agent-modul-1.md    ← kronikář workspace a správce architektury (Modul 1)
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
│   └── priklad-nastroje/   ← ukázkový HTML nástroj
│
└── materialy/              ← pomocná složka pro cvičení (mimo PACT)
    ├── ukazka-dokumentu.md
    ├── ukazka-hodnoceni.md
    └── ukazka-sablony.md
```

---

## PACT — co každá zóna znamená

| Zóna | Složka | Účel |
|------|--------|------|
| **P** — Projects | `0_Projects/` | Kde žijí projekty a jejich výstupy. Každý projekt = vlastní podsložka s README. |
| **A** — Agents | `1_Agents/` | Průvodci, specialisté, kronikáři. Každý agent = `.md` soubor s instrukcemi. |
| **C** — Context | `2_Context/` | Paměť workspace: kdo jsi, jak komunikuješ, co chceš. Agenti ho čtou pro personalizaci. |
| **T** — Tools | `3_Tools/` | Nástroje pro opakované úkoly — skripty, HTML nástroje, šablony. |

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
