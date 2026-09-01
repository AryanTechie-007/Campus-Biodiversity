# 🌿🐾 Campus Biodiversity Inventory Repository
### Shiv Nadar University Chennai (SNU Chennai)
**Course:** Environmental Science and Engineering (EVS)  
**Assignment 3:** Collective Biodiversity Repository (Weightage: 30%)  
**Faculty / Evaluator:** Dr. K. Uthradevi  
**Submission Deadline:** 16 September 2026  
**Repository Link:** [https://github.com/AryanTechie-007/Campus-Biodiversity](https://github.com/AryanTechie-007/Campus-Biodiversity)

---

## 📌 Executive Summary

This repository serves as the official, systematically organized **Collective Campus Biodiversity Inventory** for **Shiv Nadar University Chennai**. It compiles, categorizes, and analyzes the species documented during the field surveys and submitted assignments across the university campus ecosystem.

### Key Inventory Highlights
- 🏛️ **Institution**: Shiv Nadar University Chennai, Rajiv Gandhi Salai (OMR), Kalavakkam, Tamil Nadu.
- 🔬 **Total Unique Documented Species**: **26 Species** (Zero duplicate taxa).
- 🌿 **Flora (Botanical Diversity)**: **11 Unique Species** (Trees, Palms, Shrubs, Climbing Vines, and Wetland Herbs).
- 🐾 **Fauna (Zoological Diversity)**: **15 Unique Species** across 6 distinct taxonomic guilds (Insects, Myriapods, Molluscs, Crustaceans, Reptiles, Birds, and Mammals).
- 🛡️ **Conservation Highlight**: Documented presence of the **Crimson Rose Butterfly (*Pachliopta hector*)**, a **Schedule I Protected Species** under the Indian Wildlife (Protection) Act, and the **Indian Peafowl (*Pavo cristatus*)**, the **National Bird of India**.
- 🔄 **Deduplication Policy**: In strict compliance with guidelines (*"Do not include duplicate/repeated species. Each species should be listed only once"*), redundant entries such as *Hibiscus rosa-sinensis* (observed as both Tropical Peach and Crimson Red cultivars) have been unified into a single comprehensive taxon entry (`FL-02`) with both original field survey photographs documented.

---

## 🗂️ Repository Architecture

```
Campus-Biodiversity/
│
├── README.md                          # Master inventory, summary tables, methodology, & trophic web
├── index.html                         # Interactive Campus Biodiversity Explorer Web App & Atlas
│
├── Flora/                             # Botanical Division
│   ├── README.md                      # Flora master catalog & classification overview
│   ├── images/                        # Original field survey photographs of all floral species
│   └── species/                       # Dedicated Markdown profiles for each unique plant species
│       ├── fl-01_plumeria_obtusa.md
│       ├── fl-02_hibiscus_rosa_sinensis.md
│       └── ...
│
├── Fauna/                             # Zoological Division
│   ├── README.md                      # Fauna master catalog & taxonomic guild breakdown
│   ├── images/                        # Original field survey photographs of all faunal species
│   └── species/                       # Dedicated Markdown profiles for each unique animal species
│       ├── fa-01_spilostethus_hospes.md
│       ├── fa-02_pachliopta_hector.md
│       └── ...
│
├── Ecological-Analysis/               # Trophic Dynamics & Energy Flow
│   ├── README.md                      # In-depth food chains, ecological roles, and trophic pyramid
│   └── campus_food_web.png            # High-resolution Campus Food Web Architecture Diagram
│
└── data/                              # Open Machine-Readable Datasets
    ├── biodiversity_inventory.json    # Complete structured JSON database with metadata
    └── biodiversity_inventory.csv     # Master tabular CSV dataset for ecological computation
```

---

## 📋 Master Campus Species Inventory

### 🌿 Division I: Campus Flora (11 Unique Species)

| Sl. | Catalog ID | Common Name | Scientific Name | Botanical Family | Campus Location | Observation Photo | Profile Link |
| :-: | :--- | :--- | :--- | :--- | :--- | :-: | :-: |
| 01 | `FL-01` | **White Champa / Frangipani** | *Plumeria obtusa* | `Apocynaceae` | Pathway behind Dhanyas | [📷 View](Flora/images/plumeria_obtusa.png) | [📄 Profile](Flora/species/fl-01_plumeria_obtusa.md) |
| 02 | `FL-02` | **Tropical Hibiscus / China Rose & Red Hibiscus / Shoeblack Plant** | *Hibiscus rosa-sinensis* | `Malvaceae` | Pathway behind Dhanyas | [📷 View](Flora/images/hibiscus_rosa_sinensis.png) | [📄 Profile](Flora/species/fl-02_hibiscus_rosa-sinensis.md) |
| 03 | `FL-03` | **Peppervine** | *Nekemias arborea (syn. Ampelopsis arborea)* | `Vitaceae` | Pathway behind Dhanyas | [📷 View](Flora/images/nekemias_arborea.png) | [📄 Profile](Flora/species/fl-03_nekemias_arborea.md) |
| 04 | `FL-04` | **Bismarck Palm** | *Bismarckia nobilis* | `Arecaceae` | Campus entrance | [📷 View](Flora/images/bismarckia_nobilis.png) | [📄 Profile](Flora/species/fl-04_bismarckia_nobilis.md) |
| 05 | `FL-05` | **Bamboo Palm / Lady Palm** | *Rhapis excelsa* | `Arecaceae` | AB3 open space | [📷 View](Flora/images/rhapis_excelsa.png) | [📄 Profile](Flora/species/fl-05_rhapis_excelsa.md) |
| 06 | `FL-06` | **Sugar Date Palm / Wild Date Palm** | *Phoenix sylvestris* | `Arecaceae` | AB3 | [📷 View](Flora/images/phoenix_sylvestris.png) | [📄 Profile](Flora/species/fl-06_phoenix_sylvestris.md) |
| 07 | `FL-07` | **Golden Trumpet / Yellow Allamanda** | *Allamanda cathartica* | `Apocynaceae` | AB2 | [📷 View](Flora/images/allamanda_cathartica.png) | [📄 Profile](Flora/species/fl-07_allamanda_cathartica.md) |
| 08 | `FL-08` | **Yellow Alder / Yellow Buttercup (Ramgovam)** | *Turnera ulmifolia* | `Passifloraceae` | Pathway behind Dhanyas | [📷 View](Flora/images/turnera_ulmifolia.png) | [📄 Profile](Flora/species/fl-08_turnera_ulmifolia.md) |
| 09 | `FL-09` | **White Frangipani / Singapore Graveyard Flower** | *Plumeria alba* | `Apocynaceae` | AB1 | [📷 View](Flora/images/plumeria_alba.png) | [📄 Profile](Flora/species/fl-09_plumeria_alba.md) |
| 10 | `FL-10` | **Red Frangipani / Pink Temple Tree** | *Plumeria rubra* | `Apocynaceae` | AB3 | [📷 View](Flora/images/plumeria_rubra.png) | [📄 Profile](Flora/species/fl-10_plumeria_rubra.md) |
| 11 | `FL-11` | **Beach Spider Lily** | *Hymenocallis littoralis (syn. Hymenocallis speciosa)* | `Amaryllidaceae` | Pathway behind Dhanyas | [📷 View](Flora/images/hymenocallis_littoralis.png) | [📄 Profile](Flora/species/fl-11_hymenocallis_littoralis.md) |

### 🐾 Division II: Campus Fauna (15 Unique Species)

| Sl. | Catalog ID | Common Name | Scientific Name | Taxonomic Guild | Campus Location | Observation Photo | Profile Link |
| :-: | :--- | :--- | :--- | :--- | :--- | :-: | :-: |
| 01 | `FA-01` | **Dolic Bug / Ground Bug (Milkweed Bug)** | *Spilostethus hospes* | `Insects / Arthropods` | Pathway behind Dhanyas | [📷 View](Fauna/images/spilostethus_hospes.png) | [📄 Profile](Fauna/species/fa-01_spilostethus_hospes.md) |
| 02 | `FA-02` | **Crimson Rose Butterfly** | *Pachliopta hector* | `Insects / Arthropods` | Ladies Hostel | [📷 View](Fauna/images/pachliopta_hector.png) | [📄 Profile](Fauna/species/fa-02_pachliopta_hector.md) |
| 03 | `FA-03` | **Indian Paper Wasp / Yellow Paper Wasp** | *Ropalidia marginata* | `Insects / Arthropods` | AB3 | [📷 View](Fauna/images/ropalidia_marginata.png) | [📄 Profile](Fauna/species/fa-03_ropalidia_marginata.md) |
| 04 | `FA-04` | **Giant African Snail** | *Lissachatina fulica (syn. Achatina fulica)* | `Molluscs` | Pathway behind Dhanyas | [📷 View](Fauna/images/lissachatina_fulica.png) | [📄 Profile](Fauna/species/fa-04_lissachatina_fulica.md) |
| 05 | `FA-05` | **Indian Freshwater / Field Crab** | *Oziotelphusa senex* | `Crustaceans` | Pathway behind Dhanyas | [📷 View](Fauna/images/oziotelphusa_senex.png) | [📄 Profile](Fauna/species/fa-05_oziotelphusa_senex.md) |
| 06 | `FA-06` | **Red Cotton Stainer** | *Dysdercus cingulatus* | `Insects / Arthropods` | Pathway behind Dhanyas | [📷 View](Fauna/images/dysdercus_cingulatus.png) | [📄 Profile](Fauna/species/fa-06_dysdercus_cingulatus.md) |
| 07 | `FA-07` | **Red-Headed / Banded Millipede** | *Xenobolus carnifex* | `Myriapods / Arthropods` | Pathway to Rishabhs | [📷 View](Fauna/images/xenobolus_carnifex.png) | [📄 Profile](Fauna/species/fa-07_xenobolus_carnifex.md) |
| 08 | `FA-08` | **Yellow-billed Babbler (Seven Sisters)** | *Argya affinis (syn. Turdoides affinis)* | `Birds (Avifauna)` | Pathway behind Dhanyas | [📷 View](Fauna/images/argya_affinis.png) | [📄 Profile](Fauna/species/fa-08_argya_affinis.md) |
| 09 | `FA-09` | **Black Drongo (King Crow)** | *Dicrurus macrocercus* | `Birds (Avifauna)` | Metro Cafe | [📷 View](Fauna/images/dicrurus_macrocercus.png) | [📄 Profile](Fauna/species/fa-09_dicrurus_macrocercus.md) |
| 10 | `FA-10` | **House Crow** | *Corvus splendens* | `Birds (Avifauna)` | Campus-wide / Academic & Dining vicinity | [📷 View](Fauna/images/corvus_splendens.png) | [📄 Profile](Fauna/species/fa-10_corvus_splendens.md) |
| 11 | `FA-11` | **Bonnet Macaque** | *Macaca radiata* | `Mammals` | Gents Hostel | [📷 View](Fauna/images/macaca_radiata.png) | [📄 Profile](Fauna/species/fa-11_macaca_radiata.md) |
| 12 | `FA-12` | **Indian Pariah Dog (Desi Dog / INDog)** | *Canis lupus familiaris* | `Mammals` | Backside of AB3 | [📷 View](Fauna/images/canis_lupus_familiaris.png) | [📄 Profile](Fauna/species/fa-12_canis_lupus.md) |
| 13 | `FA-13` | **Indian Peafowl (Peacock - National Bird of India)** | *Pavo cristatus* | `Birds (Avifauna)` | Pathway behind Dhanyas | [📷 View](Fauna/images/pavo_cristatus.png) | [📄 Profile](Fauna/species/fa-13_pavo_cristatus.md) |
| 14 | `FA-14` | **Oriental Garden Lizard (Changeable Lizard)** | *Calotes versicolor* | `Reptiles` | Pathway behind Dhanyas | [📷 View](Fauna/images/calotes_versicolor.png) | [📄 Profile](Fauna/species/fa-14_calotes_versicolor.md) |
| 15 | `FA-15` | **Domestic Cat (Campus Tabby / Feral Cat)** | *Felis catus* | `Mammals` | Gents Hostel | [📷 View](Fauna/images/felis_catus.png) | [📄 Profile](Fauna/species/fa-15_felis_catus.md) |

---

## 🕸️ Campus Ecosystem Food Chains & Trophic Architecture

The biodiversity documented on campus interacts dynamically across four major trophic levels:

```
[ Trophic Level 4: Apex Predators & Scavengers ]
   - Felis catus (Feral Cat)
   - Canis lupus familiaris (Indian Pariah Dog)
   - Corvus splendens (House Crow)
   - Pavo cristatus (Indian Peafowl - reptile predation)
                           ▲
                           │ Energy Transfer
[ Trophic Level 3: Secondary Consumers & Insectivores ]
   - Calotes versicolor (Oriental Garden Lizard)
   - Ropalidia marginata (Indian Paper Wasp)
   - Dicrurus macrocercus (Black Drongo)
   - Argya affinis (Yellow-billed Babbler)
                           ▲
                           │ Energy Transfer
[ Trophic Level 2: Primary Consumers & Detritivores ]
   - Herbivores: Dysdercus cingulatus, Spilostethus hospes, Pachliopta hector larvae
   - Decomposers/Detritivores: Xenobolus carnifex (Millipede), Lissachatina fulica (Snail), Oziotelphusa senex (Crab)
   - Frugivores: Macaca radiata (Bonnet Macaque)
                           ▲
                           │ Solar Energy & Nutrient Uptake
[ Trophic Level 1: Primary Producers (Flora) ]
   - Flowering Shrubs, Palms, Canopy Trees, Vines & Wetland Flora
```

### Documented Linear Food Chains
1. **Terrestrial Grazing & Predator Chain:**  
   *Hibiscus rosa-sinensis* (Red Hibiscus) $\rightarrow$ *Dysdercus cingulatus* (Cotton Stainer) $\rightarrow$ *Calotes versicolor* (Garden Lizard) $\rightarrow$ *Pavo cristatus* (Indian Peafowl)
2. **Nectar-Pollinator & Aerial Hawking Chain:**  
   *Plumeria alba* / *Turnera ulmifolia* (Nectar) $\rightarrow$ *Pachliopta hector* (Crimson Rose) $\rightarrow$ *Dicrurus macrocercus* (Black Drongo) $\rightarrow$ *Corvus splendens* (House Crow)
3. **Detrital & Soil Decomposition Chain:**  
   Leaf Litter (*Bismarckia* / *Plumeria*) $\rightarrow$ *Xenobolus carnifex* & *Lissachatina fulica* $\rightarrow$ *Argya affinis* (Babbler) $\rightarrow$ *Felis catus* (Domestic Cat)
4. **Wetland / Moist Margin Chain:**  
   *Hymenocallis littoralis* (Detritus) $\rightarrow$ *Oziotelphusa senex* (Field Crab) $\rightarrow$ *Pavo cristatus* $\rightarrow$ *Canis lupus familiaris*
5. **Frugivore-Primate Canopy Chain:**  
   *Phoenix sylvestris* & *Nekemias arborea* (Fruits/Berries) $\rightarrow$ *Macaca radiata* (Bonnet Macaque) $\rightarrow$ *Corvus splendens* & *Canis lupus familiaris*
6. **Biological Pest Control Chain:**  
   *Turnera ulmifolia* (Seeds/Weeds) $\rightarrow$ *Spilostethus hospes* (Dolic Bug) $\rightarrow$ *Ropalidia marginata* (Paper Wasp) $\rightarrow$ *Dicrurus macrocercus* (Black Drongo)

👉 **For complete visual diagrams and detailed trophic analysis, visit [`Ecological-Analysis/README.md`](Ecological-Analysis/README.md).**

---

## 📍 Key Campus Observation Hotspots

| Hotspot Zone | Habitat Type | Key Documented Species |
| :--- | :--- | :--- |
| **Pathway behind Dhanyas** | Garden border, moist drainage soil & shrubbery | *Plumeria obtusa*, *Hibiscus rosa-sinensis*, *Nekemias arborea*, *Turnera ulmifolia*, *Hymenocallis littoralis*, *Spilostethus hospes*, *Lissachatina fulica*, *Oziotelphusa senex*, *Dysdercus cingulatus*, *Argya affinis*, *Pavo cristatus*, *Calotes versicolor* |
| **Academic Block 3 (AB3 & Courtyard)** | Open space, landscaped beds, shaded understory | *Rhapis excelsa*, *Phoenix sylvestris*, *Plumeria rubra*, *Ropalidia marginata*, *Canis lupus familiaris* (backside) |
| **Academic Block 2 (AB2)** | Ornamental trellis & facade landscaping | *Allamanda cathartica* (Golden Trumpet) |
| **Academic Block 1 (AB1)** | Open quadrangle | *Plumeria alba* (White Frangipani) |
| **Campus Main Entrance** | Architectural landscape | *Bismarckia nobilis* (Bismarck Palm) |
| **Ladies Hostel Garden** | Flowering flora & nectar sources | *Pachliopta hector* (Crimson Rose Butterfly) |
| **Gents Hostel Vicinity** | High canopy trees & residential zones | *Macaca radiata* (Bonnet Macaque), *Felis catus* (Campus Cat) |
| **Metro Cafe & Open Wires** | Elevated utility cables & open aerial vantage | *Dicrurus macrocercus* (Black Drongo) |
| **Pathway to Rishabhs** | Shaded leaf mulch & moist soil | *Xenobolus carnifex* (Red-Headed Millipede) |

---

## 🛠️ Contribution, Methodology & Survey Protocol

1. **Survey Methodology**: Direct visual encounter surveys, photographic documentation, and GPS/landmark hotspot logging conducted across daytime and crepuscular hours.
2. **Identification & Taxonomy**: Taxonomic nomenclature cross-verified with IPNI / Plants of the World Online (POWO) for Flora and Catalogue of Life / GBIF for Fauna.
3. **Data Integrity & Deduplication**: To maintain repository standards as a research-grade collective inventory, all student contributions are checked for redundant taxonomic synonyms prior to integration.

---

## 👥 Course & Assignment Information
- **Course**: Environmental Science and Engineering (EVS)
- **Institution**: Shiv Nadar University Chennai (SNU Chennai)
- **Coordinator**: Dr. K. Uthradevi
- **Semester**: Monsoon 2026
- **Repository Maintainer / Lead**: [AryanTechie-007](https://github.com/AryanTechie-007)

---

<p align="center">
  <b>Shiv Nadar University Chennai — Campus Biodiversity Inventory Repository</b><br>
  <i>Conserving and documenting our living campus heritage.</i>
</p>
