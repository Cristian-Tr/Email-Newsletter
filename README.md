Readme
# Email-Newsletter
https://cristian-tr.github.io/Email-Newsletter/ 

🥛 Dairies Berries - Premium Newsletter Experience
Concept: Un landing page de tip newsletter, construit pentru a demonstra controlul avansat asupra animațiilor CSS și coerența de brand într-un mediu minimalist.

🚀 Highlights Tehnice
Interactivitate SVG & Canvas Dynamic CTA Header: Am proiectat și implementat un motor de animație custom pentru o dronă SVG care transportă o sticla Dairies Berries peste o imagine idilică de fundal. Această integrare asigura o experiență vizuală fluidă și un Call-to-Action clar și captivant.

Custom CSS Animation Engine: Am implementat un sistem de layering pentru imagini de fundal (background-image multiple) care permite schimbarea scenelor prin fading, fără a afecta elementele interactive din prim-plan.

Asynchronous Animation Flow: Sticla de produs utilizează o animație de tip "sway" (balansare organică) calculată la 5s, fiind decuplată de ciclul de animație al slider-ului din fundal (17s).

Performance First: Proiectul rulează exclusiv pe CSS, eliminând nevoia de biblioteci externe de tip JS (precum Swiper sau Slick), ceea ce garantează un timp de încărcare minim și un scor Lighthouse ridicat.

Responsive Design: Layout-ul se adaptează fluid de la ecrane mobile mici (82% width) la versiuni de desktop (57% width), menținând ierarhia vizuală.

🎨 Decizii de Product Design
Visual Storytelling: Imaginile parcurg drumul produsului: Fermă -> Tradiție -> Producție Tehnologizată -> Livrare Digitală (Dronă).

UX Micro-interactions: Am ales o mișcare de pendul pentru sticlă în detrimentul unei rotații complete pentru a păstra lizibilitatea etichetei și a oferi o senzație de plutire naturală, evitând "motion sickness-ul" digital.

🧠 Interactive Product Discovery & Logic
Orders & Clients Counter (Vanilla JS): Am adaugat un mic contor al numarului de comenzi si al clientilor peste o imagine cu efectul benefic al produselor Dairies Berries.

Dynamic Product Quiz (Vanilla JS): Am dezvoltat un algoritm de recomandare bazat pe un quiz interactiv, care ajută utilizatorul să identifice produsul ideal din gama Dairies Berries. Aceasta demonstrează abilitatea de a manipula DOM-ul și de a gestiona starea aplicației folosind JavaScript pur (fără librării externe).

Smart Product Catalog: Secțiunea de comandă integrează un sistem de afișare a celor 4 produse principale, unde am pus accent pe micro-interacțiuni de tip Hover. Acestea oferă un feedback vizual instantaneu, îmbunătățind experiența de navigare și crescând potențialul de conversie.
