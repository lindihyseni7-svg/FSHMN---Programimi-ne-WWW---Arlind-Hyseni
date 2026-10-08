# Java III - Fillimi i CSS

Kjo eshte detyra per rregullimin e afishes te klubit te debatit.

## Analiza e gabimeve ne gabime.css

1. **Konflikti ne kaskade (Specificity):**
   Ne kodin fillestar selektori me ID `#poster` kishte `color: white;` mbi sfond te bardhe. Meqenese ID selector ka specifikueshmeri me te larte se sa klasa `.poster`, ngjyra e tekstit mbeteshte e bardhe dhe nuk shihej fare. E kam rregulluar duke vendosur ngjyren e erret `#17263c` te `#poster` pa perdorur `!important`.

2. **Problemi me gjeresi (Overflow):**
   Afisha kishte `width: 700px` fikse dhe `padding: 80px`, gje qe e bente panelin te dilte jashte ekranit ne telefona mobil (360px). E kam rregulluar duke vendosur `width: 100%` dhe `max-width: 650px`.

## Box Model dhe Accessibility

- **Box Sizing:** Kam perdorur `box-sizing: border-box` qe padding dhe border te hyjne brenda gjeresise se panelit, qe te mos dale jashte ekranit.
- **Etiketat:** Per te mos u bazuar vetem ne ngjyre, etiketa e dyte ka kufi me viza te nderprera (`dashed`), ndersa tjerat me vije te plote (`solid`).
- **Focus:** Eshte shtuar `:focus-visible` me ngjyre te verdhe per te pare qarte levizjen me tastiere (Tab).