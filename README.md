# Interneto Technologijos ND1

Šis projektas yra pirmasis namų darbas modulyje **Interneto technologijos**.  
Svetainė sukurta naudojant **HTML5 ir CSS3**, be papildomų karkasų.

Projekto tema – astronomija ir kosmoso reiškiniai.  
Svetainė „ASTRAEUS“ ateityje pateiks informaciją apie:
- dangaus įvykius,
- NASA nuotraukas,
- planetariumo funkcijas,
- naudotojų pasiūlymus.

Šiuo metu naudojami pavyzdiniai elementai (placeholders).

Antrame namų darbe (ND2), svetainė bus papildyta JavaScript funkcionalumu, pavyzdiniai elementai 
(placeholders) bus pakeisti tikrais paveikslėliais, duomenimis.

---

## Projekto struktūra

```text
interneto_technologijos_nd1/
│
├── index.html
├── sky_events_calendar_page.html
├── suggestion_box_page.html
│
├── css/
│   ├── styles.css
│   ├── base.css
│   └── theme.css
│
├── images/
│   └── logo.svg
    └── main_background.png
    └── placeholder.png
│
├── README.md
├── NOTES.md
└── .gitignore
```

---

## Svetainės puslapiai

### Pagrindinis puslapis (`index.html`)
- Hero sekcija
- Naujausių kosmoso naujienų sąrašas
- Funkcijų kortelės (Moon Phase, VirtualSky, NASA APOD)

### Kalendoriaus puslapis (`sky_events_calendar_page.html`)
- Mėnesio kalendorius su įvykių žymekliais (hardcoded)
- Artėjančių įvykių lentelė (table)

### Pasiūlymų puslapis (`suggestion_box_page.html`)
- Forma su:
    - vardu
    - el. paštu
    - kategorija
    - žinute
    - įvertinimu
- Submit mygtukas

---

## Dizainas ir technologijos

### Naudotos technologijos
- HTML5
- CSS3
- Google Fonts (Space Grotesk)

### Dizaino sprendimai
- Stiklo stilius
- Tamsi tema
- Responsive dizainas
- CSS custom properties

## Responsyvumas

Svetainė pritaikyta įvairiems ekranų dydžiams:

- Desktop
- Tablet
- Mobile

Naudojami `@media` breakpointai:
- 900px
- 700px

---

## Testavimas

Projektas buvo tikrintas naudojant:

### HTML validacija
https://validator.w3.org/

### CSS validacija
https://jigsaw.w3.org/css-validator/

Validatoriuose gauti tik informaciniai perspėjimai apie:
- vendor prefix (`-webkit-`)
- CSS variables

Kritinių klaidų nėra.

---
## Versijų kontrolė

Projektas valdomas naudojant **Git** ir talpinamas **GitHub** platformoje.

Naudojamas `.gitignore` failas, kuriame ignoruojami:
- `.idea/`
---
## Paleidimas

Projektą galima paleisti lokaliai:

1. Atsisiųsti repozitoriją:
   ```bash
   git clone https://github.com/deer-in-haze/interneto_technologijos_nd1.git
   ```

2. Atidaryti `index.html` naršyklėje.

Papildoma serverio konfigūracija nereikalinga.

---

## Ateities patobulinimai

Planuojami patobulinimai:

- JavaScript integracija realiems duomenims
- Hamburger meniu mobiliesiems
- Accessibility (ARIA atributai)
- Realios NASA API integracijos

## Autorius
Vilnius Tech DIPf-23 grupės studentė Miglė Lukoševičiūtė