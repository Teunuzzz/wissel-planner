# ⚽ Wissel Planner O9 – ZVV De Esch (v2.3.3)

Een webapp (PWA) om **wissels en keepers eerlijk te verdelen** tijdens wedstrijden van O9-teams.  
De app werkt op **telefoon, tablet en laptop**, ook **offline** via het beginscherm.  

---

## 🌟 Belangrijkste functies
- **Eerlijke speeltijdverdeling:** alle spelers krijgen zo gelijk mogelijk minuten.  
- **Strikte eerlijkheid-modus:** garandeert dat het verschil maximaal één wissel-slot (5 minuten) is.  
- **Keeper-rotatie:** automatisch per wedstrijd, per helft of per kwart (1 / 2 / 4 keepers).  
- **Positie-bewust:** houdt rekening met linies (DEF, MID, ATT) en kwaliteitsbalans.  
- **Bank rouleert automatisch:** niemand blijft te lang wissel.  
- **Live timer:** trilsignaal bij elke wissel (iPhone / Android).  
- **Touch-drag-&-drop:** rangschik spelers eenvoudig met het ≡-handvat.  
- **ZVV De Esch-thema:** blauw-geel kleuren schema.  
- **PWA:** installeerbaar op je telefoon, werkt offline.

---

## 📱 Gebruik

### 1 – Startpagina (👥 Spelers & Setup)
- Voeg spelers toe of **reset** naar de vaste 8 (Wouter, Sydney, Twan, Milan, Ryan, Dani, Finn, Diede).  
- Versleep met ≡ om de **kwaliteitsvolgorde** te bepalen (beste bovenaan).  
- Vink **Aanw.** = aanwezig en **K.** = keeper-kandidaat aan.  
- Stel wedstrijd-instellingen in: kwartieren, minuten, formatie, keepers, enz.  
- Vink eventueel **⚖️ Strikte eerlijkheid** aan.  
- Klik **Voorstel genereren** → het schema wordt gemaakt.

### 2 – Live-pagina (⏱️)
- Start de wedstrijd met ▶️.  
- De app trilt bij elke wissel / nieuw slot.  
- Bekijk in de tabel: Keeper, Veld en Bank per 5 minuten.  
- Pauzeer ⏸️ of reset 🔄 per kwart.

### 3 – Wijzigingen (🛠️)
- Gebruik bij blessures of wijzigingen.  
- “Speler stopt” → herbereken vanaf nu.  
- Wissel veld/bank-spelers handmatig indien nodig.

---

## 🔧 Installatie / Hosting via GitHub Pages
1. **Download** de laatste release (v2.3.3):  
   [wissel_planner_o9_mobile_team_v2_3_3.zip](./wissel_planner_o9_mobile_team_v2_3_3.zip)
2. **Upload** de bestanden (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`)  
   in de **root** van je GitHub-repo `teunuzzz/wissel-planner`.
3. Ga in GitHub naar:  
   **Settings → Pages → Build and deployment → Branch: `main` / `(root)`**
4. Open → [`https://teunuzzz.github.io/wissel-planner/`](https://teunuzzz.github.io/wissel-planner/)
5. **Hard refresh** op telefoon (PWA-cache v2_3_3) of herinstalleer op het beginscherm.

---

## 💡 Tips
- Gebruik geen **privé-modus** in Safari → dan kan de app niet opslaan.  
- Je kunt meerdere teams aanmaken door de site te dupliceren met een eigen naam.  
- De data wordt lokaal opgeslagen (geen internet nodig).  
- De app werkt het best in **staande oriëntatie** op mobiel.

---

© 2025 Teun Segerink – Wissel Planner O9 voor ZVV De Esch  
Laatste versie: **v2.3.3** (7 november 2025)
