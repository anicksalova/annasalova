# annasalova.cz — rozcestník projektů Anny Sálové

Osobní rozcestník na doméně `annasalova.cz`. Jednoduchý one-pager (inline HTML/CSS, žádné závislosti kromě Google Fonts), který odkazuje na všechny Anniny projekty.

## Projekt

- **URL:** `https://annasalova.cz`
- **Git repo:** `https://github.com/anicksalova/annasalova`, větev **`main`**
- **Deploy:** GitHub → Netlify (auto-deploy), Netlify přesměrovává `www` → bez www
- **Soubory webu:** složka `annasalova/` v tomto repozitáři (`index.html`, `images/`, `favicon.svg`, `robots.txt`, `sitemap.xml`)

## Analytika a SEO

- **GA4 Measurement ID:** `G-XE14YHF5XG` — v `<head>` `index.html`
- **Google Search Console:** ověřeno; property nastavena jako **URL-prefix** `https://annasalova.cz` (bez www — Netlify přesměrovává www → non-www, proto GSC property musí být bez www). Ověření proběhlo přes Google Analytics.
- **robots.txt** a **sitemap.xml** přidány (2026-08-22), sitemap odkazuje na `https://annasalova.cz/sitemap.xml`
- **Title:** `Anna Sálová | Expertka na obsahový marketing od roku 2012`
- **Meta description:** `Seznamte se s mými projekty ze světa content marketingu, copywritingu, historie a politiky. Začtěte se do blogu annacopy.cz nebo poptejte agenturu Content Wizards.`

## Projekty na rozcestníku (pořadí karet)

1. **Content Wizards** → `https://contentwizards.cz`
2. **annacopy.cz** → `https://annacopy.cz`
3. **ChatLab** → `https://info.chatlab.app`
4. **e-politics.cz** → `https://e-politics.cz`
5. **Legionář Jaroslav Janda** → `https://legionarjaroslavjanda.cz`
6. **Desklicious** → `https://desklicious.app`
7. **U Starejch hadrů** → `https://ustarejchhadru.cz`

## Dev server

Projekt nemá Python ani Node.js — statický server běží přes PowerShell skript `serve.ps1` (v kořeni repozitáře, port 3456, slouží složku `annasalova/`). Konfigurace v `.claude/launch.json`.
