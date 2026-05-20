# Cursor Starter Workspace

Vítej, nováčku. Právě jsi vstoupil do světa omezeného jen tvou fantazií.

Tohle není prázdný editor. Je to připravená základna: máš tu agenty, materiály, místo pro výstupy, deník a mapu plnou neprozkoumaných míst. Jako v každé dobré hře — nejdřív se naučíš ovládání, pak tě pošleme do akce.

---

## Tutorial: naučíš se ovládat

Cursor má jedno základní gesto, bez kterého nic nefunguje: **tagování souborů přes `@`**.

Není to stejné jako vložit `@soubor` jako plain text. Musíš nejprve napsat @ až pak soubor vybrat z nabídky — jen tehdy Cursor soubor opravdu přečte a předá agentovi. Bez tohoto kroku agent mluví naslepo.

**Krok 1 — Probuzení agenta:**

Otevři chat (`Cmd+L` na Macu, `Ctrl+L` na Windows). Ujisti se, že je vybraný **Ask** mód.

Napiš do chatu `@`, začni psát `agent` a z nabídky vyber **agent-pomocnik.md**. Pak mezerou přidej:

> `Zdravím. Hlásím se na výcvik!`

Výsledek: místo holého textu uvidíš v chatu "tag" (barevný štítek se jménem agenta). To je správně — Cursor teď opravdu roli daného agenta.

> **Proč na tom záleží:** Zkopírovaný `@agent-pomocnik.md` z code blocku je plain text. Agent vidí jen název, ne obsah. Tagování přes picker = agent má v ruce celý soubor.

---

## Mise 1: První průzkum

Teď když umíš tagovat, tady je první mise.

Otevři chat a postav zprávu takhle:

- Napiš `@`, vyber **1_Agents/agent-pomocnik.md**
- Mezerou přidej: `Přečti`
- Napiš další `@`, vyber **materialy/ukazka-dokumentu.md**
- Přidej: `a řekni mi, co je hlavní myšlenka.`

Výsledek: agent přečetl konkrétní soubor z tvého workspace — ne internet, ne vymyšlená data. Tohle je základ všeho, co v kurzu přijde.

**Bonusová mise:** Přetáhni vlastní soubor do složky `materialy/` a zopakuj totéž. Výsledek bude jiný — a relevantnější.

---

## Mise 2: Tvoje palivo

Cursor nepracuje s cloudem ani internetem. Čte soubory přímo z tvého počítače — z té složky, kterou máš otevřenou. Přidáš soubor do `materialy/` a Cursor ho hned vidí. Tak jednoduché.

Ale ne každý formát funguje stejně dobře. **Word a PDF jsou pro AI špatné palivo** — jejich obsah je schovaný ve složité struktuře, AI musí hádat co je nadpis, co je text, co je poznámka pod čarou.

`.md` (Markdown) je čistý text. Co napíšeš, to AI dostane — bez přebytečného balastu. Je to formát, který Cursor spaluje nejlépe. Čím víc vlastního obsahu budeš mít v `.md`, tím silnější nástroj budeš mít k dispozici.

**Jak vytvořit .md soubor:** V Cursoru stiskni `Cmd+N` (Mac) nebo `Ctrl+N` (Windows), napiš obsah a ulož s příponou `.md`. Nebo zkopíruj text z Wordu / Google Docs do nového souboru — formátování zmizí, zůstane čistý obsah. To je přesně to, co chceš.

E-maily píšeš každý den — a každý z nich obsahuje kousek toho, jak přemýšlíš a jak komunikuješ. To je přesně to, čím začneme Cursor trénovat na tebe.

**Mise:** Vytvoř nový soubor `materialy/muj-email.md` a zkopíruj do něj jeden svůj reálný odchozí e-mail. Jakýkoliv — pracovní, klientský, kolegyni.

Jak vytvořit `.md` soubor? V Cursoru `Cmd+N` (Mac) nebo `Ctrl+N` (Windows) → vlož obsah → ulož jako `muj-email.md` do složky `materialy/`. Pokud si nevíš rady, zeptej se Google nebo AI — tohle je základní dovednost, která se ti bude hodit.

Až soubor máš, otaguj agenta i soubor v jedné zprávě a napiš: *Jak píšu? Popiš můj komunikační styl.*

Chceš víc o tom proč `.md` a jak konvertovat? Otaguj `@materialy/proc-markdown.md`.

---

## Mise 3: Tvůj kontext

Zatím jsi Cursoru ukazoval soubory. Teď mu řekneš co má udělat — a on to udělá.

Cursor má tři módy a každý dělá něco jiného:

- **Ask** — ptáš se a čteš. Cursor nic nemění.
- **Plan** — říkáš co chceš. Cursor ukáže co chystá, ale ještě nic nedělá. Máš čas zkontrolovat a schválit.
- **Agent** — Cursor to opravdu udělá. Zapisuje do souborů, vyplňuje obsah, mění workspace.

Kaskáda, která to spojuje: **Plan → Agent**. Nejdřív plán, pak akce.

V levém panelu najdeš připravenou složku `2_Context/`. Je tam struktura a šablony čekající na vyplnění — čtyři soubory s placeholdery `[DOPLNIT]`. Tvůj úkol: naplnit je s pomocí Cursoru.

**Mise — část A: tone of voice**

1. Přepni do **Plan mode** — přepínač vlevo dole v chatu.
2. Otaguj tyto soubory a napiš instrukci:

   Otaguj `@2_Context/identity/jak-komunikuju.md` + `@materialy/muj-email.md` a napiš:
   *Na základě mého e-mailu vyplň šablonu jak-komunikuju.md — nahraď všechny [DOPLNIT] konkrétními poznatky z mého psaní.*

3. Cursor ukáže plán — zkontroluj co chystá.
4. Schváliš → přepni do **Agent mode** → soubor se vyplní.

**Mise — část B: kdo jsem**

Po části A otaguj `@2_Context/identity/o-mne.md` a napiš:
*Přečti šablonu a polož mi 3–5 otázek, abych ji mohl vyplnit.*

Cursor se zeptá. Ty odpovíš. Pak přepni do Agent mode a Cursor šablonu vyplní podle tvých odpovědí.

Výsledek: složka `2_Context/` s tvými reálnými daty. Příště stačí otagovat `@2_Context/` a Cursor ví kdo jsi, jak komunikuješ a co řešíš — aniž bys to musel pokaždé vysvětlovat znovu.

---

## Co je uvnitř

- `.cursorrules` — základní pravidla pro Cursor v tomto workspace.
- `workspace-mapa.md` — mapa celého workspace: co kde je a proč.
- `1_Agents/` — agenti: průvodci, kronikáři, specialisté. Jejich seznam najdeš v `1_Agents/AGENT-REGISTRY.md`.
- `2_Context/` — tvoje paměť: kdo jsi, jak komunikuješ, jaké máš cíle.
- `0_Projects/` — tvoje projekty a výstupy. Deník průchodu kurzem je v `0_Projects/pruchod-kurzem/`.
- `3_Tools/` — nástroje a skripty pro opakované úkoly.
- `materialy/` — ukázkové dokumenty pro cvičení v Lekci 0.

---

## Důležité pravidlo

Otevírej v Cursoru přímo složku `cursor-starter-workspace/`, ne její nadřazenou složku.

Cursor pracuje s tím, co vidí ve workspace. Když otevřeš špatnou složku, agent nebude mít správný kontext.

---

## Kurz

Tento workspace je určený pro kurz **Cursor pro každého**. V každé lekci budeš pracovat s jedním konkrétním souborem nebo složkou odsud.