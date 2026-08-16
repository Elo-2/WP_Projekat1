# IPI Akademija - Web projekat

Web projekat izrađen u okviru predmeta **Web programiranje** na Internacionalnoj poslovno-informacionoj akademiji Tuzla.

Projekat predstavlja web stranicu IPI Akademije sa informacijama o kursevima, rasporedom, kontakt formom i posebnom sekcijom **Student Fun Zone** koja sadrži interaktivne igre i web aplikacije.

---

## 📌 Sadržaj projekta

Projekat se sastoji od nekoliko glavnih stranica:

- Početna stranica - O kursevima
- Popis kurseva
- Raspored kurseva
- Kontakt
- Student Fun Zone

U okviru Student Fun Zone nalaze se:

- 🎱 Bingo
- 🧠 Kviz
- 🖊️ Interaktivni Whiteboard
- 🎨 Visual Board
- 📋 Kanban Board

---

## 🎮 Student Fun Zone

Student Fun Zone predstavlja interaktivni dio projekta u kojem korisnik može pokrenuti različite aplikacije.

Sadržaj se prikazuje pomoću **iframe** elementa, tako da se igre i boardovi mogu koristiti unutar glavne stranice bez otvaranja novih tabova.

### Bingo

Bingo omogućava:

- generisanje Bingo kartice
- izvlačenje nasumičnih brojeva
- označavanje izvučenih brojeva
- provjeru Bingo kombinacije
- igranje prema standardnim Bingo pravilima

### Kviz

Kviz omogućava korisniku da odgovara na pitanja i dobije rezultat nakon završetka kviza.

### Interaktivni Whiteboard

Whiteboard omogućava:

- crtanje po digitalnoj ploči
- izbor boje
- promjenu veličine četke
- brisanje
- čišćenje cijele ploče
- spremanje crteža kao PNG slike
- spremanje crteža kao PDF dokumenta
- slanje crteža putem e-maila

### Visual Board

Visual Board omogućava korisniku organizovanje različitih elemenata na digitalnoj ploči, njihovo pomjeranje i spremanje sadržaja.

### Kanban Board

Kanban Board omogućava organizovanje zadataka pomoću različitih kolona i kartica.

---

## 🛠️ Korištene tehnologije

Projekat je izrađen korištenjem:

- **HTML5** - struktura web stranica
- **CSS3** - dizajn i stilizacija
- **JavaScript** - interaktivnost i funkcionalnosti
- **Canvas API** - crtanje na Whiteboardu
- **jsPDF** - generisanje PDF dokumenta
- **LocalStorage** - spremanje podataka u browseru
- **iframe** - prikaz interaktivnih sadržaja unutar Student Fun Zone

---

## 📁 Struktura projekta

```text
projekat/
│
├── index.html
├── popis.html
├── raspored.html
├── studentfunzone.html
├── kontakt.html
├── bingo.html
├── kviz.html
├── izgled.css
│
├── slike/
│   ├── logo-ipi.png
│   ├── tecajevi1.png
│   ├── tecajevi2.jpg
│   ├── tecajevi3.jpg
│   └── srce.jpg
│
├── whiteboard/
│   ├── whiteboard.html
│   ├── style.css
│   ├── javascript.js
│   └── marker.png
│
├── visionboard/
│   ├── visionboard.html
│   ├── style.css
│   └── javascript.js
│
└── kanbanboard/
    ├── kanbanboard.html
    ├── style.css
    └── javascript.js
