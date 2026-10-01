# Detyra Java II 

Ky projekt eshte ushtrim i thjeshte ne HTML dhe CSS per lenden Programimi ne WWW. Qellimi eshte me ndertu faqen "Muzeu i Sendeve" fiks si ne foton e kerkuar.

---

## Analiza para kodimit

Sipas udhezimeve te ushtrimit, kjo eshte analiza e meparshme:

- **Hyrjet (Inputs):** Skedaret e imazheve SVG (`celesi.svg`, `filxhani.svg`, `bileta.svg`) dhe tekstet e secilit send.
- **Daljet (Outputs):** Faqja ne browser me kokën e faqes, linqet, daten, 3 kartelat e rreshtuara dhe footer-in.
- **Rast Normal:** Faqja hapet ne laptop/desktop dhe 3 kartelat rrijne ne nje rresht horizontalisht.
- **Rast Kufitar 1 (Ekrane te vogla / Telefon):** Dritarja zvogelohet, prandaj kartelat kalojne automatikisht njera nen tjetren me `flex-wrap` ose grid responsive.
- **Rast Kufitar 2 (Klikimi te historia e fshehur):** Perdorimi i tagut native `<details>` lejon hapjen e tekstit shtese pa pas nevoje me shkru fare JavaScript.

---

## Struktura e skedareve

- **`index.html`** : Permban skeletin semantik me tagat `header`, `main`, `nav`, `article`, `<details>` dhe `footer`.
- **`style.css`** : Permban stilin vizual (ngjyren e gjelber te vijes, kornizat e kartelave, hapesirat dhe radhitjen).
- **`celesi.svg` / `filxhani.svg` / `bileta.svg`** : Imazhet vektoriale te sendeve.

---

## Si eshte realizuar kodi?

1. **Struktura semantike:** Eshte ruajtur kodi bazë i dhene ne pikenisje duke zevendesuar pjesen kryesore te `<main>`.
2. **Kornizat e imazheve:** Cdo imazh eshte futur ne nje div me prapavije gri ku eshte qenderzu ne mes.
3. **Interaktiviteti:** Eshte perdorur `<summary>` me simbolin `►` per me simulu hapjen e historise se fshehur.