# Java I — Pasaporta digjitale dhe GitHub

## Çfarë realizova
Krijova faqen e pasaportës digjitale për kandidatin udhërrëfyes të kampusit Arlind Hyseni. Projekti përmban tre faqe HTML (`index.html`, `rreth.html` dhe `kontakt.html`) që lidhen me njëra-tjetrën me lidhje relative, si dhe skedarin `style.css` për stilim.

## Hapat e hapjes
1. Hap folderin `JavaI` në VS Code.
2. Hap skedarin `index.html` me Live Server (ose direkt në shfletues).
3. Kliko linqet për të kaluar nga njëra faqe te tjetra.

## Testet dhe rezultatet
- **Hyrje:** Klikimi te "Rreth Arlindit" nga `index.html`
  - **Rezultat i pritur:** Hapja e faqes `rreth.html`
  - **Rezultat i marrë:** Faqja u hap me sukses.
- **Hyrje:** Klikimi te "Kthehu te pasaporta" nga `rreth.html`
  - **Rezultat i pritur:** Kthimi te `index.html`
  - **Rezultat i marrë:** U kthye te `index.html`.
- **Hyrje:** Klikimi te "Kontakt"
  - **Rezultat i pritur:** Hapja e faqes `kontakt.html`
  - **Rezultat i marrë:** U hap `kontakt.html`.

## DevTools → Network
Gjatë hapjes së `index.html` në serverin lokal:
- **URL:** `http://127.0.0.1:5500/JavaI/index.html`
- **Metoda:** `GET`
- **Statusi:** `200 OK`

## Reflektim individual

**Pyetje:** Cili ndryshim është ruajtur lokalisht por ende nuk shihet në GitHub?
**Përgjigje:** Ndryshimet që kemi ruajtur te skedarët në kompjuter (ose i kemi bërë `git commit` lokalisht), por nuk kemi bërë ende `git push` për t'i dërguar online në GitHub.

**Dallimi mes skedarit lokal, commit-it dhe push-it:**
- **Skedari lokal:** Kodi që ndodhet në kompjuterin tim pasi e ruaj me `Ctrl + S`.
- **Commit:** Ruajtja e një "snapshoti" të kodit në historikun e repozitorit lokal Git.
- **Push:** Dërgimi i commit-eve nga kompjuteri im te repozitori në GitHub.

## Deklarimi i AI dhe burimeve
Gjatë punës kam përdorur udhëzimet e lëndës, kapitujt 1-3 të librit si dhe ndihmë nga AI për të verifikuar sintaksën e saktë të HTML/CSS dhe komandat e Git.