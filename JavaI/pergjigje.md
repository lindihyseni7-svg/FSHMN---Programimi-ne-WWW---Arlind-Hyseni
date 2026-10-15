# Pergijgjet — Prova 1

## P1.7

Cfare ben box-sizing: border-box? Jep nje shembull nga faqja jote qe perfshin width, padding dhe border. Pergjigju ne 2–3 fjali.

Pergjigjja ime: Rregulla `box-sizing: border-box` detyron shfletuesin te llogarise gjeresine totale te elementit duke perfshire brenda saj edhe padding-un dhe border-in. Ne faqen time te seksioni `.cards`, kur i vendosim `width: 100%`, `padding: 24px` dhe `border: 2px solid navy`, keto permasa nuk i shtohen gjeresise por merren nga brendesia e saj. Kjo parandalon rritjen e elementit jashte gjeresise se ekranit dhe shmang krijimin e scroll-it horizontal ne ekrane te vogla si 360px.

## P1.8

Pse perdoret a per lidhjen Detaje, ndersa button per nje veprim si “Shfaq/Fshih tekstin”? Referoju nje lidhjeje nga faqja jote. Nuk duhet te implementosh buton ose JavaScript.

Pergjigjja ime: Elementi `<a>` perdoret te lidhja "Detaje" me `href="#info"` sepse qellimi i tij kryesor eshte lundrimi (navigimi) ne nje pozicion ose seksion tjeter te faqes ose ne nje adrese te re. Ndersa `<button>` perdoret per te ekzekutuar nje veprim interaktiv ne faqe (si dorezimi i nje formulari ose shfaqja/fshirja e tekstit me JavaScript) pa ndryshuar pozicionin apo adresen e navigimit ne faqe.