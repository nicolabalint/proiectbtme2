# Proiect – Matching și oglinzi de curent CMOS

## Descriere
Acest repository conține proiectarea și verificarea unei structuri CMOS bazate pe **oglinzi de curent**, cu accent pe **matching-ul tranzistoarelor**, realizată în cadrul disciplinei **Bazele tehnologice ale microelectronicii 2**.

Proiectul urmărește etapele complete de realizare:
- planificarea matching-ului
- proiectarea schematicului
- realizarea layout-ului cu tehnici de matching
- verificări DRC și LVS

Documentația completă (scheme, layout-uri și verificări) este inclusă în fișierul PDF al proiectului :contentReference[oaicite:0]{index=0}.

---

##  Structura proiectului
Proiectul este organizat pe etape tehnologice, reflectând fluxul standard de proiectare VLSI:



```text
├── dispozitive
│   ├── layout
│   └── schematic
├── etaj_dif_rezistiv
│   ├── layout
│   └── schematic
├── etaj_dif_rezistiv_R
│   ├── layout
│   └── schematic
├── etaj_dif_rezistiv_T
│   ├── layout
│   └── schematic
├── inv_7x
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── nand2_7x
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── osc
│   ├── layout
│   └── schematic
├── osc_C
│   ├── layout
│   └── schematic
├── proiect
│   ├── layout
│   └── schematic
├── proiect_M1_M2
│   ├── layout
│   └── schematic
├── proiect_M4_M6
│   ├── layout
│   └── schematic
├── proiect_M5_M3
│   ├── layout
│   └── schematic
└── proiect_M7_M8_M9
    ├── layout
    └── schematica

```

##  Tehnologii și unelte utilizate

- **Cadence Virtuoso**
- **Tehnologie CMOS**
- **Layout cu tehnici de matching** (common-centroid, simetrie)
- **DRC & LVS** (Cadence)

---

##  Descrierea etapelor

###  Planificare matching

În această etapă au fost analizate cerințele de matching pentru tranzistoarele din oglinzile de curent.  
Au fost stabilite:

- tranzistoarele care necesită matching strict
- grupările de tip **common-centroid**
- orientarea și simetria layout-ului

---

### Schematic

Au fost realizate schematic-ele pentru:

- oglinda de curent **M5–M3**
- oglinda de curent **M4–M6**
- oglinda de curent **M1–M2**
- gruparea **M7–M8–M9**

Ulterior, toate blocurile au fost integrate într-un **schematic final**.  

---

### Layout

Layout-ul a fost realizat respectând regulile de matching:

- simetrie geometrică
- trasee echilibrate
- distribuție uniformă a paraziților

Pentru fiecare oglindă de curent și pentru gruparea finală a fost realizat layout dedicat.  

---

### DRC & LVS

Pentru toate etapele de layout au fost efectuate:

- verificări **DRC** 
- verificări **LVS** 

Rezultatele confirmă:

- respectarea regulilor tehnologice
- corespondența corectă între schematic și layout

---

## Rezultate

- matching corect al tranzistoarelor
- layout simetric și echilibrat
- **DRC fără erori**
- **LVS corect** pentru toate blocurile și pentru layout-ul final

---

## Documentație

Documentația completă a proiectului este disponibilă în fișierul PDF atașat.

