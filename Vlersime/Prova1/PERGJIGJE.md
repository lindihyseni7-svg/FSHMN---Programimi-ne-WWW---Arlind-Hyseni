# Përgjigjet — Varianti B

## P1.7

Shpjego box-sizing: border-box me width, padding dhe border nga kodi yt.

Pergjigjja ime: Rregulla box-sizing: border-box detyron shfletuesin me llogarit gjeresine totale te elementit duke perfshire brenda saj edhe padding dhe kufriin apo borderin ne faqen time te seksioni kurset kur i vendosim width: 100% padding: 24px dhe border: 2px solid navy keto permasa nuk i shtohen gjeresise por merren nga brendesia e saj kjo parandalon rritjen e elementit jashte gjeresise se ekranit dhe shmang krijimin e scrollit ne ekrane me te vogla po te ishte content box do ishte problem do dalin jasht kornizes pra content box eshte default e browserit.

## P1.8

Pse “Më shumë” është lidhje dhe jo button? Kur do të përdorje button? Nuk kërkohet implementim butoni ose JS.

Përgjigjja ime: …Elementi `<a>` perdoret te lidhja "Detaje" me `href="#info"` sepse qellimi i tij kryesor eshte lundrimi (navigimi) ne nje pozicion ose seksion tjeter te faqes ose ne nje adrese te re. Ndersa `<button>` perdoret per te ekzekutuar nje veprim interaktiv ne faqe (si dorezimi i nje formulari ose shfaqja fshirja e tekstit me JavaScript) pa ndryshuar pozicionin apo adresen e navigimit ne faqe.
