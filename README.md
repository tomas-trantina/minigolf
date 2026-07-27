# ⛳ Mini Golf 3D — Infinite Procedural

[![Single File HTML](https://img.shields.io/badge/Single--File-HTML-orange?style=for-the-badge&logo=html5)](./minigolf.html)
[![Three.js](https://img.shields.io/badge/Engine-Three.js-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![Mobile Ready](https://img.shields.io/badge/Mobile-Touch%20Ready-brightgreen?style=for-the-badge&logo=android)](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

> Moderní, vizuálně působivá **3D minigolfová hra** v jediném `.html` souboru, navržená a optimalizovaná primárně pro **mobilní telefony** i desktopové prohlížeče.

---

## ✨ Hlavní Funkce

- 📱 **Mobilní optimalizace a dotykové ovládání**  
  Plně přizpůsobené pro dotykové obrazovky smartphonů. Jednoduché zaměřování a nastavení síly odpalu potažením prstu (drag & release), vyhnuté systémovým gestům (`viewport-fit=cover`, safe-area insets).
- 📦 **Single-file architektonický zázrak (`minigolf.html`)**  
  Žádný Node.js, žádný build proces, žádné `npm install`. Vše (HTML, CSS glassmorphism UI, JS logika, 3D fyzika a zvukový syntetizér) je v jediném souboru [minigolf.html](./minigolf.html).
- ⛳ **Nekonečné procedurální levely & Boss Fights**  
  Každý level je unikátní díky procedural generation. Každých 25 levelů vás čeká **Boss Level** s vysokou náročností a unikátními hazardními prvky.
- 🧊 **Dynamické povrchy a překážky**  
  - **Tráva**: Klasické tření a stabilní odraz.
  - **Led (Ice)**: Vysoká klouzavost a dlouhé dojezdy.
  - **Písek (Sand)**: Značný odpor a rychlé zastavení míčku.
  - **Portály (Portals)**: Teleportace míčku mezi spárovanými branami.
  - **Větrné zóny (Wind Zones)**: Proudy vzduchu ovlivňující dráhu míčku.
  - **Násobiče (2× Multipliers)**: Časově omezené násobení získaných coinů.
- 🛍️ **Obchod & Trvalá Vylepšení**  
  Sbírejte **Mince (Coins)** a **Diamanty (Diamonds)** během hraní:
  - **Jednorázové Powerupy**: Extra pokus, Magnet na mince, Sílový Boost, Duch míček (procházení překážkami), Zamrznutí času.
  - **Trvalá Vylepšení (Upgrades)**: Více startovních pokusů, nižší tření, silnější odpal, delší trajektorie zaměřování, vyšší šance na bonusy.
- 🏆 **Úspěchy (Achievements) & Denní Výzva (Daily Challenge)**  
  - 18 unikátních achievementů ke získání.
  - Denní výzva generovaná ze seedu aktuálního data – porovnejte své nejlepší skóre každý den.
- 🔊 **Procedurální Zvuky (Web Audio API)**  
  Všechny zvukové efekty (odpaly, cinkání coinů, spadnutí do jamky, výhra) jsou generovány synteticky v reálném čase bez nutnosti stahovat audio soubory.
- 💾 **Automatické Ukládání**  
  Veškerý postup, zakoupená vylepšení, diamanty a odemčené achievementy se ukládají lokálně do `localStorage`.

---

## 🎮 Jak Hrát / Ovládání

### 📱 Na mobilu (Touch)
1. **Zamíření a síla**: Stiskněte míček a **potáhněte směrem od cíle** (jako pračkem). Čím dále potáhnete, tím větší sílu odpalu získáte.
2. **Kamera**: Otáčejte kamerou tahem mimo míček pro lepší přehled o dráze.
3. **Pustit**: Uvolněním prstu odpálíte míček.

### 💻 Na počítači (Myš)
1. **Stiskněte a táhněte levým tlačítkem** od míčku pro nastavení směru a síly.
2. Uvolněním tlačítka myši provedete odpal.

---

## 🚀 Jak Spustit

Jelikož je aplikace v jediném HTML souboru, spuštění nemůže být snazší:

### Otevření lokálně
Stačí otevřít soubor `minigolf.html` v libovolném moderním webovém prohlížeči (Chrome, Safari, Edge, Firefox).

### 🌐 Nasazení na GitHub Pages (Zdarmo)
1. Nahrajte tento repozitář na **GitHub**.
2. V repozitáři přejděte do **Settings** -> **Pages**.
3. Jako **Source** vyberte větev `main` (nebo `master`) a složku `/ (root)`.
4. Klikněte na **Save**.
5. Vaše hra bude během minuty dostupná na adrese `https://<vaše-jméno>.github.io/<název-repozitáře>/minigolf.html`.

> 💡 **Tip:** Pokud přejmenujete `minigolf.html` na `index.html`, hra se načte ihned na hlavní adrese bez nutnosti psát koncovku `/minigolf.html`!

---

## 🛠️ Použité Technologie

| Technologie | Popis |
| :--- | :--- |
| **HTML5 Canvas** | Zobrazovací plocha pro 3D grafiku a rozhraní |
| **[Three.js (r128)](https://threejs.org/)** | 3D rendering engine (světla, stíny, částice, materiály) |
| **Vanilla JavaScript (ES6+)** | Fyzikální engine, generování tratí a herní logika |
| **CSS3 (Glassmorphic UI)** | Moderní temný design s rozostřeným pozadím a plynulými animacemi |
| **Web Audio API** | Syntéza zvukových efektů v reálném čase |
| **HTML5 Web Storage** | Trvalá persistence herního stavu (`localStorage`) |

---

## 📜 Licencování

Tento projekt je poskytován pod licencí [MIT](LICENSE). Můžete jej volně upravovat, šířit a používat.

---

<p center align="center">
  Vytvořeno s 💚 pro mobilní i desktopové hráče minigolfu.
</p>
