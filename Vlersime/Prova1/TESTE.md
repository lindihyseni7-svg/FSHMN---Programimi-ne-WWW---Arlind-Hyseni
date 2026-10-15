# Testet — Varianti B

Plotëso pasi ta testosh faqen.

| Testi | Pritja | Rezultati real |
|---|---|---|
| 360 px | Tri oferta njëra poshtë tjetrës; çdo ofertë ka titullin, nivelin dhe lidhjen në rreshta të veçantë. Pa scroll horizontal. | Ofertat shfaqen ne 1 kolone vertikale pa asnje scroll horizontal ne 360px. |
| 1000 px | Dy oferta në rreshtin e parë; oferta e tretë shtrihet në të gjithë rreshtin e dytë. | Kartat shfaqen ne 3 kolona te barabarta me media query ne ekrane mbi 800px/1000px. |
| Menuja dhe Më shumë | ID-të ekzistojnë dhe lidhjet arrijnë te seksioni përkatës | Lidhja #info dergon te seksioni i ofertave dhe #regjistrimi dergon te seksioni i informatave. |
| Tab / Enter | Fokusi shihet, lidhja aktivizohet | Fokusi shfaqet i qarte me outline 3px navy dhe teppeli Enter aktivizon lidhjet. |
| Tekst i gjatë te paragrafi i parë | Teksti thyhet brenda kutisë, pa scroll horizontal në 360 px | Teksti i gjate pa hapesira thyhet automatikisht fale overflow-wrap: break-word pa dale jashte |

