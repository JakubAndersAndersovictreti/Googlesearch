# Citace a zdroje projektu Andems Search

**Předmět:** Programování a vývoj aplikací (PVA)  
**Autor:** Jakub Anders  
**Repozitář GitHub:** [https://github.com/JakubAndersAndersovictreti/Googlesearch](https://github.com/JakubAndersAndersovictreti/Googlesearch)  
**Živý web (GitHub Pages):** [https://jakubandersandersovictreti.github.io/Googlesearch/](https://jakubandersandersovictreti.github.io/Googlesearch/)  
**Osobní portfolio:** [https://jakubandersandersovictreti.github.io/andersovicportfolio/](https://jakubandersandersovictreti.github.io/andersovicportfolio/)

---

## 1. Použité prompty pro AI (Generování a úprava kódu)

Projekt vznikl s asistencí AI asistenta (Google DeepMind Antigravity). Zde jsou uvedeny přesné prompty a zadání:

### Prompt 1: Základní zadání a specifikace projektu
> *"https://martinekpavel.github.io/vyuka/web_html/09search.html Vypracuj googlesearch podle zadani v odkazu je tam aji odkaz na video od harvardu a je tam všechno potřebné jak to má vypadat ale zase moc nepřehaněj ať to nevypadá jak kdyby to dělal někdo kdo koduje 3000 let"*

### Prompt 2: Úprava vzhledu, rebrandingu a oprava odkazu na portfolio
> *"Nefunguje tam ten proklik na moje portfolio odkaz na něho je https://jakubandersandersovictreti.github.io/andersovicportfolio/ ale změn vzhled ať to neni čisty google dej misto google třeba Andems search a změn vzhled"*

### Asistovaný výstup a požadavky:
- Vytvořit čistý, srozumitelný a standardní kód v HTML5 a CSS3 bez obřích externích frameworků.
- Vlastní moderní design **Andems Search** s gradientním logem, moderním zaobleným panelem vyhledávání a stylovými tlačítky.
- Implementace tří stránek dle CS50 s napojením na funkční vyhledávání Google:
  1. Hlavní vyhledávání Andems (`index.html`) s tlačítky "Andems Search" a "I'm Feeling Lucky" (`btnI`).
  2. Vyhledávání obrázků (`images.html`) s parametrem `tbm=isch`.
  3. Pokročilé vyhledávání (`advanced.html`) se 4 povinnými poli (`as_q`, `as_epq`, `as_oq`, `as_eq`) a akcentním tlačítkem.
- Splnění dodatečných požadavků zadání PVA:
  - Vytvoření demonstrační stránky se všemi typy formulářových prvků (`forms.html`).
  - Odkazy na W3C HTML a CSS validátory na všech stránkách.
  - Odkazy na citace (`citace.md`) a opravený funkční odkaz na portfolio (`andersovicportfolio`).

---

## 2. Použité odborné zdroje a specifikace

1. **Harvard University – CS50’s Web Programming with Python and JavaScript**
   - *Project 0: Search*
   - URL: [https://cs50.harvard.edu/web/projects/0/search/](https://cs50.harvard.edu/web/projects/0/search/)
   - Specifikace fungování formulářů a parametrů vyhledávače Google (`q`, `btnI`, `tbm=isch`, `as_q`, `as_epq`, `as_oq`, `as_eq`).
   - Ukázkové video CS50: [https://www.youtube.com/watch?v=24Kf3v7kZyE](https://www.youtube.com/watch?v=24Kf3v7kZyE)

2. **Ing. Pavel Martínek – Výuka PVA (Web HTML)**
   - *Projekt Google Search (09search)*
   - URL: [https://martinekpavel.github.io/vyuka/web_html/09search.html](https://martinekpavel.github.io/vyuka/web_html/09search.html)
   - Zadání práce, doplňující požadavky na formuláře, validátory, citace a portfolio.

3. **MDN Web Docs (Mozilla Developer Network)**
   - *HTML forms guide & `<input>` types reference*
   - URL: [https://developer.mozilla.org/en-US/docs/Learn/Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
   - Dokumentace všech typů formulářových prvků (text, email, password, select, radio, checkbox, range, color, datalist, atd.).

4. **W3C – World Wide Web Consortium**
   - *W3C Markup Validation Service*
   - URL: [https://validator.w3.org/](https://validator.w3.org/)
   - *W3C CSS Validation Service*
   - URL: [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)
   - Nástroje pro ověření syntaktické správnosti a standardu HTML5 a CSS3.

---

## 3. Použité technologie a nástroje

- **HTML5 & moderní CSS3** – flexbox, CSS grid, gradienty, přechody a moderní stíny bez frameworků
- **Visual Studio Code** – editor kódu
- **Git & GitHub** – verzovací systém
- **GitHub Pages** – statický hosting pro web
