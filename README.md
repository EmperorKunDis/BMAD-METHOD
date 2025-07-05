Zde je kompletní text přeložený do češtiny, s citacemi zdrojů:

# BMad-Method: Univerzální Rámec pro Agenty AI

[![Verze](https://img.shields.io/npm/v/bmad-method?color=blue&label=version)](https://www.npmjs.com/package/bmad-method)
[![Licence: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Verze Node.js](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)](https://nodejs.org)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da?logo=discord&logoColor=white)](https://discord.gg/gk8jAdXWmj)

Základy v Agilním Vývoji Řízeném Agenty, známé jako Průlomová Metoda Agilního Vývoje Řízeného AI, ale je to mnohem víc. Transformujte jakoukoli doménu se specializovanými AI znalostmi: vývoj softwaru, zábava, kreativní psaní, obchodní strategie až po osobní pohodu, abychom jmenovali jen několik.

**[Přihlaste se k odběru BMadCode na YouTube](https://www.youtube.com/@BMadCode?sub_confirmation=1)**

**[Připojte se k naší Discord Komunitě](https://discord.gg/gk8jAdXWmj)** - Rostoucí komunita pro nadšence AI! Získejte pomoc, sdílejte nápady, prozkoumávejte AI agenty a frameworky, spolupracujte na technických projektech, užívejte si koníčky a pomáhejte si navzájem uspět. Ať už jste uvízli s BMad, stavíte si vlastní agenty, nebo si jen chcete popovídat o nejnovějším dění v AI - jsme tu pro vás!

⭐ **Pokud shledáte tento projekt nápomocným nebo užitečným, prosím, dejte mu hvězdičku v pravém horním rohu!** Pomůže to ostatním objevit BMad-Method a budete upozorněni na aktualizace!

## Rychlá navigace

### 🚨 MUSÍTE PŘEČÍST: Pochopení BMad Workflow

**Předtím, než se ponoříte, projděte si tyto kritické diagramy pracovního postupu, které vysvětlují, jak BMad funguje:**

1. **[Workflow plánování (Webové UI)](docs/user-guide.md#the-planning-workflow-web-ui)** - Jak vytvářet dokumenty PRD a Architektury

2. **[Základní vývojový cyklus (IDE)](docs/user-guide.md#the-core-development-cycle-ide)** - Jak agenti SM, Dev a QA spolupracují prostřednictvím souborů příběhů

> ⚠️ **Tyto diagramy vysvětlují 90 % zmatků v agenturním agilním toku BMad Method** - Pochopení tvorby PRD+Architektury a pracovního postupu SM/Dev/QA a toho, jak agenti předávají poznámky prostřednictvím souborů příběhů, je zásadní - a také vysvětluje, proč to NENÍ taskmaster nebo jen jednoduchý spouštěč úkolů!

### Co byste chtěli dělat?

*   **[Tvořit software s plnohodnotným agilním AI týmem](quick-start)** → Rychlý start
*   **[Naučit se používat BMad](docs/user-guide.md)** → Kompletní uživatelská příručka a průvodce
*   **[Zobrazit dostupné AI agenty](#available-agents)** → Specializované role pro váš tým
*   **[Prozkoumat netechnické využití](#-beyond-software-development---expansion-packs)** → Kreativní psaní, byznys, wellness, vzdělávání
*   **[Vytvořit si vlastní AI agenty](#creating-your-own-expansion-pack)** → Vytvořit agenty pro vaši doménu

*   **[Procházet hotové rozšiřující balíčky](expansion-packs/)** → Vývoj her, DevOps, infrastruktura a inspirovat se nápady a příklady
*   **[Pochopit architekturu](docs/core-architecture.md)** → Technický hloubkový ponor
*   **[Připojit se ke komunitě](https://discord.gg/g6ypHytrCB)** → Získat pomoc a sdílet nápady

### Populární případy použití

*   **Vývoj softwaru** - [Rychlý start](quick-start) | [Uživatelská příručka](docs/user-guide.md) | [Průvodci workflow](#documentation--guides)

*   **Vývoj her** - [2D Phaser Pack](expansion-packs/bmad-2d-phaser-game-dev/)

*   **Obchodní strategie** - [Kompletní průvodce](docs/expansion-packs.md#business-strategy-pack)

*   **Kreativní psaní** - [Kompletní průvodce](docs/expansion-packs.md#creative-writing-pack)

*   **DevOps/Infrastruktura** - [Infrastruktura Pack](expansion-packs/bmad-infrastructure-devops/)

### Rychlé odkazy

*   **[Instalace](#installation)** → Začněte za pár minut

*   **[Dokumentace](#documentation--guides)** → Všechny průvodce a reference

*   **[Přispívání](#contributing)** → Pomozte zlepšit BMad

*   **[Podpora](#support)** → Získejte pomoc a připojte se

## Důležité: Udržujte svou instalaci BMad aktuální

**Zůstaňte aktuální bez námahy!** Pokud již máte BMad-Method nainstalovaný ve svém projektu, jednoduše spusťte:

```bash
npx bmad-method install
# NEBO
git pull
npm run install:bmad
```


Toto provede:

*   ✅ Automaticky detekuje vaši existující instalaci v4

*   ✅ Aktualizuje pouze změněné soubory a přidá nové soubory

*   ✅ Vytvoří `.bak` záložní soubory pro jakékoli vlastní úpravy, které jste provedli

*   ✅ Zachová vaše konfigurace specifické pro projekt

Díky tomu je snadné využívat nejnovější vylepšení, opravy chyb a nové agenty, aniž byste ztratili svá přizpůsobení! Pokud z nějakého důvodu selže, můžete přejmenovat nebo odstranit složku .bmad-code a znovu spustit instalaci. Hlavní věc, na kterou si dát pozor, je, pokud jste nastavili vlastní režimy, které nejsou řízeny soubory (Cursor je v tuto chvíli jediný, který není prováděn prostřednictvím souborů projektu a zaostává) - budete chtít zajistit, aby vaše vlastní režimy sm a dev byly udržovány aktuální.

## Rychlý start

### Jeden příkaz pro všechno (instalace IDE)

**Stačí spustit jeden z těchto příkazů:**

```bash
npx bmad-method install
# NEBO pokud už máte BMad nainstalovaný:
git pull
npm run install:bmad
```


Tento jediný příkaz zpracovává:

*   **Nové instalace** - Nastaví BMad ve vašem projektu

*   **Upgrady** - Automaticky aktualizuje stávající instalace

*   **Rozšiřující balíčky** - Nainstaluje jakékoli rozšiřující balíčky, které jste přidali do package.json

> **To je vše!** Ať už instalujete poprvé, upgradujete, nebo přidáváte rozšiřující balíčky - tyto příkazy dělají vše.

**Předpoklady**: [Node.js](https://nodejs.org) v20+ je vyžadován

### Nejrychlejší start: Webové UI (2 minuty)

1.  **Získejte balíček**: Zkopírujte `dist/teams/team-fullstack.txt` (z tohoto repozitáře)

2.  **Vytvořte AI agenta**: Vytvořte nový Gemini Gem nebo CustomGPT

3.  **Nahrajte a nakonfigurujte**: Nahrajte soubor a nastavte instrukce: "Vaše kritické provozní instrukce jsou připojeny, nepřerušujte charakter podle pokynů"

4.  **Začněte s nápadem a plánováním**: Začněte chatovat! Napište `*help` pro zobrazení dostupných příkazů nebo si vyberte agenta jako `*analyst` a začněte hned vytvářet shrnutí.

> **Všechny předpřipravené balíčky jsou ve složce `dist/`** - připravené ke zkopírování a okamžitému použití!

### Alternativa: Klonování a sestavení

```bash
git clone https://github.com/bmadcode/bmad-method.git
npm run install:bmad # sestaví a nainstaluje vše do cílové složky
```


## Přehled

BMad Method (Průlomová Metoda Agilního Vývoje Řízeného Agenty) pozvedá 'Vibe Coding' využitím pokročilých technik prompt engineeringu a kritického řízení kontextu v nejdůležitějších fázích implementace vývoje. Poskytováním specializovaných AI agentů pro každou roli v agilním týmu, každý agent má hluboké znalosti ve své doméně, což vám pomůže skutečně plánovat a realizovat vaši vizi, zatímco udržuje agenty na správné cestě i při složitých aplikačních plánech.

Na rozdíl od systémů jako Task Master nebo vestavěných nástrojů pro úkoly, agilní tok BMad Method dělá mnohem více. U většiny systémů zadáte svůj nápad a systém vygeneruje plán, seznam úkolů, umožní vám ho zkontrolovat a poté začne provádět. Kde se agilní tok BMad liší, je, že si můžete zvolit více předběžného plánování a specifikace architektury, abyste zajistili, že systém bude postaven udržitelným způsobem, nikoli jako chaotický špagetový kód. Při vytváření PRD a architektur (full stack, front end nebo back end) agenti s vámi pracují tam a zpět pomocí pokročilých osvědčených technik LLM prompt engineeringu, aby vytvořili cokoli, co přesahuje to, co průměrné nekvalitní LLM a generátory úkolů vyprodukují samy. Toto je skutečně systém "Human in the Loop" (člověk v procesu), který produkuje znatelně lepší výsledky.

## Instalace

### Metoda 1: CLI instalátor (pro IDE)

**Stačí spustit jeden příkaz:**

```bash
npx bmad-method install
# NEBO pokud už máte BMad nainstalovaný:
npm run install:bmad
```


**Tento jediný příkaz dělá vše:**

*   Instaluje BMad poprvé

*   Aktualizuje stávající instalace

*   Přidává jakékoli rozšiřující balíčky z vašeho package.json

**Předpoklady**: Nejprve nainstalujte [Node.js](https://nodejs.org) v20+

### Metoda 2: Předpřipravené webové balíčky (pro webové UI)

Pro webová rozhraní ChatGPT, Claude nebo Gemini:

1.  Vyberte balíček:

    *   **Doporučeno**: `dist/teams/team-fullstack.txt` (kompletní vývojový tým)

    *   Nebo si vyberte z jednotlivých agentů ve `dist/agents/`

2.  Nahrajte na vaši AI platformu (Gemini Gem, CustomGPT, nebo přímo do chatu)

3.  Nastavte instrukce: "Vaše kritické provozní instrukce jsou připojeny, nepřerušujte charakter podle pokynů"

4.  Napište `/help` pro zobrazení dostupných příkazů

**Podporovaná IDE:**

BMad Method funguje s jakýmkoli IDE, ale má vestavěnou integraci pro:

*   `cursor` - Cursor IDE s manuálními pravidly @agent příkazů

*   `claude-code` - Claude Code s /agent příkazy

*   `cline` - Cline Rules integrace

*   `gemini-cli` - Gemini s @agent příkazy

*   `windsurf` - Windsurf s manuálními pravidly @agent příkazů

*   `roo` - Roo Code s vlastními režimy (viz `.roomodes`)

*   `github-copilot` - Integrace režimu agenta GitHub Copilot

## Dostupné agenty

### Základní vývojový tým

| Agent | Role | Specializace |
| ----------- | ------------------ | -------------------------------------------------------------------------------------------- |
| `analyst` | Business Analytik | analýza trhu, brainstorming, tvorba projektových briefů |
| `pm` | Product Manager | Produktová strategie, rozhodování o MVP, tvorba PRD s Epiky |
| `architect` | Solution Architect | Návrh systému, technická full stack, front end nebo back end architektura |
| `ux-expert` | UX Designer | Uživatelská zkušenost, UI design, prompty pro V0, Lovable a další |
| `po` | Product Owner | Zajistit soulad PRD a Architektury a to, aby změny z architektury skončily v příbězích PRD |
| `sm` | Scrum Master | Epiky a příběhy na vysoké úrovni transformované do detailních vývojových příběhů s úkoly a podúkoly |
| `dev` | Developer | Implementace kódu napříč všemi technologiemi - sleduje detailní příběh vytvořený SM |
| `qa` | QA Specialista | Detailní revize příběhu vývojáře připraveného k revizi, refaktoring a navrhování problémů a změn

### BMad Agenti

| Agent | Role | Specializace |
| ------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `bmad-orchestrator` | Koordinátor týmu | Pomáhá vám a odpovídá na vaše otázky díky své rozsáhlé znalostní bázi a provádí vás pracovními postupy s více agenty |
| `bmad-master` | Univerzální Expert | Všechny možnosti bez přepínání (kromě Dev) |

## Pokročilé funkce

### Dynamické závislosti

Každý agent načítá pouze zdroje, které potřebuje, čímž udržuje kontextová okna štíhlá.

### Systém šablon

Bohaté šablony pro všechny typy dokumentů:

*   Požadavky na produkt (PRD)

*   Architektonické dokumenty

*   Uživatelské příběhy

*   Testovací plány

*   A další...

Šablony jsou jedinečné tím, že jsou v nich zabudovány i instrukce LLM pro další práci s vámi, aby se z vás a vašeho agilního člena týmu vytáhlo to nejlepší – což umožňuje jedinečné možnosti koučování a přizpůsobení. Zatímco existuje jediný úkol `create-doc`, možnosti jsou nekonečné, když rozšíříte šablony na více typů dokumentů nebo je přizpůsobíte vlastními dokumenty s vloženým šablonovacím značkováním a rámcem instrukcí LLM, které jsou jádrem BMad Method.

### Příkazy Slash Star

Zeptejte se agenta, kterého používáte, o pomoc pomocí `/help` (na webu) nebo `*help` v IDE, abyste viděli, jaké příkazy jsou k dispozici!

### Pokročilá elicitace

Mnoho agentů a šablon pro dokumenty a některé úkoly zahrnují pokročilé direktivy pro elicitaci založené na nejnovějších interakcích LLM a pokročilých pokynech pro prompt engineering. S tímto můžete agenty posunout dál než kdykoli předtím. Pokud agent navrhne nápad nebo architekturu – můžete to posunout dál s volitelnými elicitacemi, kde se bude muset skutečně rozšířit, obhájit nebo vytvořit jiné možnosti a prokázat, že jeho návrh byl lepší. Toto je nezbytný krok, pokud chcete absolutně nejlepší výsledky nad rámec přijímání generovaných průměrných odpovědí, které si LLM myslí, že chcete slyšet pro svou první odpověď. Něco z toho je interaktivní a něco je vloženo do základního prompting engine, který pohání postup LLM různými úkoly a toky šablon.

## Použití

BMad Method se řídí strukturovaným agilním pracovním postupem se specializovanými AI agenty. Kompletní pokyny k použití a průvodce naleznete v **[Uživatelské příručce](docs/user-guide.md)**.

### Příklady rychlého startu

#### S integrací IDE

```bash
# V Cursor
@pm Vytvoř PRD pro aplikaci pro správu úkolů

# V Claude Code
/architect Navrhni mikroservisní architekturu

# Ve Windsurf
@dev Implementuj příběh 1.3
```


#### S webovým UI

Po nahrání balíčku zadejte `/help` pro zobrazení dostupných příkazů.

### Klíčové zdroje

*   **[Kompletní uživatelská příručka](docs/user-guide.md)** - Kompletní průvodce od počátku projektu až po jeho dokončení

*   **[Příkazy CLI](docs/user-guide.md#cli-commands)** - Instalace, aktualizace a správa

*   **[Upgrade z V3](docs/user-guide.md#upgrading-from-v3-to-v4)** - Pokyny pro migraci

*   **[Základní konfigurace](docs/user-guide.md#core-configuration)** - Podpora flexibilní projektové struktury V4

*   **[Týmy a pracovní postupy](docs/user-guide.md#team-configurations)** - Předkonfigurované týmy agentů

## Struktura projektu

Viz **[Základní architektura](docs/core-architecture.md)** pro kompletní strom zdrojových souborů a detailní vysvětlení každé komponenty.

### Klíčové adresáře

*   **`.bmad-core/`** - Srdce frameworku (agenti, šablony, workflowy)

*   **`dist/`** - Předpřipravené balíčky připravené pro použití ve webovém UI

*   **`expansion-packs/`** - Rozšíření specifická pro danou doménu

*   **`tools/`** - Nástroje pro sestavení a instalaci

*   **`docs/`** - Vaše projektová dokumentace (PRD, architektura, příběhy)

### 📦 Předpřipravené balíčky (složka dist/)

**Všechny balíčky připravené k použití jsou v adresáři `dist/`!**

*   **Týmy**: `dist/teams/` - Kompletní konfigurace týmů

    *   `team-fullstack.txt` - Full-stack vývojový tým

    *   `team-ide-minimal.txt` - Minimální IDE workflow tým

    *   `team-no-ui.txt` - Tým pouze pro backend

    *   `team-all.txt` - Všichni agenti zahrnuti

*   **Jednotliví agenti**: `dist/agents/` - Soubory jednotlivých agentů

    *   Jeden soubor `.txt` pro každého agenta (analyst, architect, dev atd.)

*   **Rozšiřující balíčky**: `dist/expansion-packs/` - Specializované domény

    *   Vývoj her, DevOps atd.

**Pro použití s webovým UI**: Jednoduše zkopírujte libovolný `.txt` soubor z `dist/` a nahrajte jej na vaši AI platformu!

## Dokumentace a průvodci

### Architektura a technické

*   🏗️ [Základní architektura](docs/core-architecture.md) - Kompletní technická architektura a návrh systému

*   📖 [Uživatelská příručka](docs/user-guide.md) - Komplexní průvodce efektivním používáním BMad-Method

*   🚀 [Průvodce rozšiřujícími balíčky](docs/expansion-packs.md) - Rozšiřte BMad na jakoukoli doménu mimo vývoj softwaru

### Průvodci workflow

*   📚 [Univerzální průvodce BMad Workflow](docs/bmad-workflow-guide.md) - Klíčový pracovní postup, který platí pro všechna IDE

*   🏗️ [Práce v prostředí Brownfield Guide](docs/working-in-the-brownfield.md) - Kompletní průvodce pro vylepšení stávajících projektů

### Průvodci specifickými pro IDE

*   🎯 [Průvodce pro Cursor](docs/agentic-tools/cursor-guide.md) - Nastavení a použití pro Cursor

*   🤖 [Průvodce pro Claude Code](docs/agentic-tools/claude-code-guide.md) - Nastavení a použití pro Claude Code

*   🌊 [Průvodce pro Windsurf](docs/agentic-tools/windsurf-guide.md) - Nastavení a použití pro Windsurf

*   🦘 [Průvodce pro Roo Code](docs/agentic-tools/roo-code-guide.md) - Nastavení a použití pro Roo Code

*   🔧 [Průvodce pro Cline](docs/agentic-tools/cline-guide.md) - Nastavení a použití pro Cline (VS Code)

*   ✨ [Průvodce pro Gemini CLI](docs/agentic-tools/gemini-cli-guide.md) - Nastavení a použití pro Gemini CLI

*   💻 [Průvodce pro Github Copilot](docs/agentic-tools/github-copilot-guide.md) - Nastavení a použití pro VS Code s GitHub Copilot

## 🌟 Mimo vývoj softwaru - Rozšiřující balíčky

Zatímco BMad vyniká ve vývoji softwaru, jeho rámec pro přirozený jazyk dokáže strukturovat odborné znalosti v JAKÉKOLI doméně. Rozšiřující balíčky transformují BMad na univerzální systém AI agentů pro kreativní psaní, obchodní strategii, zdraví a wellness, vzdělávání a mnoho dalšího.

### Dostupné rozšiřující balíčky

#### Technické domény

*   🎮 **[Vývoj her](expansion-packs/bmad-2d-phaser-game-dev/)** - Kompletní tým herního studia s designéry, vývojáři a narativními spisovateli

*   🏗️ **[Infrastruktura/DevOps](expansion-packs/bmad-infrastructure-devops/)** - Cloudoví architekti, bezpečnostní specialisté, SRE experti

*   📱 **Mobilní vývoj** - Specialisté na iOS/Android, mobilní UX designéři

*   🔗 **Blockchain/Web3** - Vývojáři chytrých kontraktů, architekti DeFi

#### Netechnické domény

*   💼 **Obchodní strategie** - Strategičtí plánovači, analytici trhu, obchodní kouči

*   💪 **Zdraví a wellness** - Fitness kouči, výživoví poradci, průvodci meditací

*   🎨 **Kreativní umění** - Spisovatelé příběhů, tvůrci světů, vývojáři postav

*   📚 **Vzdělávání** - Návrháři kurikul, učitelé, kouči učení

*   🧠 **Osobní rozvoj** - Životní kouči, stanovování cílů, budování návyků

*   🏢 **Profesionální služby** - Právní poradci, tvůrci obsahu, výzkumní asistenti

### Vytvoření vlastního rozšiřujícího balíčku

Přeměňte své odborné znalosti na agenty AI:

1.  **Identifikujte svou doménu** - Jaké znalosti chcete sdílet?

2.  **Navrhněte specializované agenty** - Každý s jedinečnými odbornými znalostmi a osobností

3.  **Vytvořte opakovaně použitelné úkoly** - Standardní postupy ve vašem oboru

4.  **Vytvořte profesionální šablony** - Strukturované výstupy pro konzistenci

5.  **Sdílejte s komunitou** - Pomozte ostatním těžit z vašich odborných znalostí

📖 **[Přečtěte si kompletního průvodce rozšiřujícími balíčky](docs/expansion-packs.md)** - Detailní příklady, inspirace a technické detaily

## Podpora

*   💬 [Discord Komunita](https://discord.gg/g6ypHytrCB)

*   📖 [Dokumentace](docs/)

*   🐛 [Sledování chyb](https://github.com/bmadcode/bmad-method/issues)

*   💬 [Diskuze](https://github.com/bmadcode/bmad-method/discussions)

## Licence

MIT Licence - podrobnosti viz [LICENCE](LICENSE).

## Historie verzí

*   **Aktuální**: [v4](https://github.com/bmadcode/bmad-method) - Kompletní přepsání frameworku s CLI instalátorem, dynamickými závislostmi a rozšiřujícími balíčky

*   **Předchozí verze**:

    *   [Verze 3](https://github.com/bmadcode/BMad-Method/tree/V3) - Představila sjednoceného BMad Agenta a optimalizaci Gemini

    *   [Verze 2](https://github.com/bmadcode/BMad-Method/tree/V2) - Přidány weboví agenti a oddělení šablon

    *   [Verze 1](https://github.com/bmadcode/BMad-Method/tree/V1) - Původní 7-souborový důkaz konceptu

Podrobné informace o historii verzí a průvodce migrací naleznete v [versions.md](docs/versions.md).

## Autor

Vytvořil Brian (BMad) Madison

## Přispívání

**Jsme nadšeni z příspěvků a vítáme vaše nápady, vylepšení a rozšiřující balíčky!** 🎉

### Před přispíváním - MUSÍTE PŘEČÍST

Abyste zajistili, že váš příspěvek je v souladu s BMad Method a bude hladce začleněn:

1.  📋 **Přečtěte si [CONTRIBUTING.md](CONTRIBUTING.md)** - Naše směrnice pro přispívání, požadavky na PR a proces

2.  🎯 **Přečtěte si [GUIDING-PRINCIPLES.md](GUIDING-PRINCIPLES.md)** - Klíčové principy, které udržují BMad výkonný díky jednoduchosti

3.  🆕 **Jste noví na GitHubu?** Začněte s naším [Průvodcem pro Pull Requesty](docs/how-to-contribute-with-pull-requests.md)

### Klíčové body k zapamatování

*   Udržujte vývojové agenty štíhlé (šetřete kontext pro kódování!)

*   Používejte malé, cílené soubory namísto velkých rozvětvených

*   Znovu používejte stávající úkoly (jako `create-doc`) namísto vytváření duplikátů

*   Zvažte rozšiřující balíčky pro funkce specifické pro doménu, nikoli vylepšení základního systému (ty patří do základního systému)

*   Všechny příspěvky musí dodržovat náš přístup založený na přirozeném jazyce a markdownu s vloženými instrukcemi LLM a elicitacemi do šablon

Budujeme něco úžasného společně - udržujme to jednoduché, výkonné a zaměřené! 💪

### Vývojové nastavení

Chcete pomoci vylepšit BMad Method. Forkněte a naklonujte repozitář

```bash
git clone https://github.com/bmadcode/bmad-method.git
```


```bash
cd bmad-method

npm run build # znovu sestaví složku dist

npm run install:bmad # sestaví a nainstaluje vše do cílové složky
```


[![Přispěvatelé](https://contrib.rocks/image?repo=bmadcode/bmad-method)](https://github.com/bmadcode/bmad-method/graphs/contributors)

Vybudováno s ❤️ pro komunitu vývoje s podporou AI
