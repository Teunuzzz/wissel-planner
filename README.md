# ⚽ Wisselplanner – mobiele webapp voor voetbalwissels

De **Wisselplanner** is een volledig mobiele webapp voor jeugdvoetbalteams (zoals O9) waarmee je eenvoudig
eerlijk verdeelde speelminuten en automatische wisselmomenten kunt beheren.

De app werkt **offline**, is **PWA-ready** (toe te voegen aan het beginscherm),
en past zich automatisch aan elk telefoonscherm aan.

---

## 📱 Functies

### 🔹 1. Setup & Spelers
- Drag & drop spelers 
- Voeg spelers toe of verwijder ze
- Per speler:
  - Naam (klikbaar om te wijzigen)
  - Positie: **Aanvaller**, **Middenvelder**, **Verdediger**
  - Aanwezig / Afwezig-toggle
- Instellingen:
  - Formatie (aantal veldspelers, standaard 5)
  - Keepers per wedstrijd:  
    - 1 = hele wedstrijd  
    - 2 = per helft  
    - 4 = per kwart  
  - Keeper-toewijzing per kwart of helft
- Alles wordt automatisch opgeslagen in `localStorage`

### 🔹 2. Live
- Een wedstrijd bestaat uit **4 kwarten van 10 minuten**
- Iedere **5 minuten** komt er een **wisselmoment**
- Bij het wisselmoment:
  - De telefoon **trilt**
  - Een **overlay-scherm** verschijnt met alleen de namen van de spelers **die in en uit gaan**
  - Klik op **“Gewisseld”** → terug naar het live-scherm  
    (de kwart-timer loopt door, er volgen geen nieuwe wissels in dit kwart)
- De app houdt rekening met:
  - 2-gaten-regel (speler pas weer wisselbaar na 2 beurten)
  - Keeper nooit tegelijk veldspeler of wissel
  - Positie-evenwicht (geen twee van dezelfde positie tegelijk op de bank)
  - Evenwichtige speeltijd voor iedereen

### 🔹 3. Snelle wijzigingen
- Gebruik dit tijdens de wedstrijd:
  - Spelers **actief / afwezig** zetten
  - **Keeper wijzigen**
  - **Formatie aanpassen**
- Klik op **Herberekenen** om de planning direct te vernieuwen
- **Naar Live** brengt je terug naar de wedstrijdweergave

---

## 🧭 Installatie (PWA)

1. Zet de volgende bestanden in één map op je server of op je telefoon:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
2. Open `index.html` in je mobiele browser.
3. In Safari (iOS) of Chrome (Android):  
   **Deel → Zet op beginscherm**  
   → De app verschijnt als een zelfstandige webapp.
4. De app werkt **offline** dankzij de ingebouwde service-worker.

---

## 🧩 Bestandsstructuur

