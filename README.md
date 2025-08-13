# ARE-SD-2025_Tree-Health-Classification

The dataset includes information on the location, species, dimensions, specific features, and state of health of the trees in **Saint-Germain-en-Laye**.  
The main objective of this project is to build **machine learning models** which, given categorical and numerical variables describing the trees, will be able to predict a **diagnosis** (C1–C5).  

---

## 📂 Dataset Description

### Files
- **`train.csv`** – Training data  
- **`prev.csv`** – Data to predict  
- **`benchmark.csv`** – Example submission file  

---

### Variables & Codes

#### `type_sol` – Ground type
| Code | Meaning |
|------|---------|
| P    | Mulch (*paillage*) |
| G    | Lawn (*gazon*) |
| S    | Stabilised surface (*stabilisé*) |
| Gr   | Grating (*grille*) |
| GR   | Gravel (*grave*) |
| MA   | Flower beds (*massifs*) |
| E    | Asphalt (*enrobé*) |
| CS   | Ground cover (*couvre-sol*) |

#### `classe_age` – Age class
| Code | Meaning |
|------|---------|
| A    | Adult, 20–40 years |
| JA   | Young adult, 10–20 years |
| J    | Young, < 10 years |
| AM   | Mature adult, 50–70 years |

#### `classe_hauteur` – Height class
| Code | Height |
|------|--------|
| H1   | 0–5 m |
| H2   | 5–10 m |
| H3   | 10–15 m |
| H4   | 15–20 m |
| H5   | 20–25 m |

#### `classe_circonference` – Circumference class
| Code | Circumference |
|------|---------------|
| C1   | 0–0.5 m |
| C2   | 0.51–1 m |
| C3   | 1.01–1.5 m |
| C4   | 1.51–2 m |
| C5   | 2.01–2.5 m |
| C6   | 2.51–3 m |
| C7   | 3.01–3.5 m |

#### `port_arbre` – Tree form
| Code | Meaning |
|------|---------|
| SL   | Semi-free |
| L    | Free |
| R5   | 5-sided screen |
| RR   | Reduced relaxed |
| A    | Architectured |

#### `vigueur_pousse` – Growth vigour
| Code | Meaning |
|------|---------|
| P    | Vigorous growth |
| PP   | Low growth |
| MP   | Medium growth |
| D    | Declining |

#### `plaie_collet` – Collar wound
| Code | Meaning |
|------|---------|
| RCPPL | No wound |
| RCPLS | Healthy wound |
| RCPLNS | Necrotic wound with oozing |
| RCPLNC | Necrotic wound with cavity |
| RCPLC | Healed wound |

#### `fissure_tronc` – Trunk crack
| Code | Meaning |
|------|---------|
| TPF  | No crack |
| TFO  | Open crack |
| TFF  | Closed crack |

#### `plaie_tronc` – Trunk wound
| Code | Meaning |
|------|---------|
| TPLS  | Healthy wound |
| TPLCF | Closed cavity |
| TPLNC | Necrotic wound with cavity |
| TPLC  | Healed wound |
| TPPL  | No wound |

#### `fissure_houppier` – Crown crack
| Code | Meaning |
|------|---------|
| HPF  | No crack |
| HFO  | Open crack |

#### `bois_mort_houppier` – Dead wood in crown
| Code | Meaning |
|------|---------|
| HBMI | Isolated dead wood |
| HPBM | No dead wood |
| HBMU | Uniform dead wood |

#### `plaie_houppier` – Crown wound
| Code | Meaning |
|------|---------|
| HPLC  | Healed wound |
| HPLS  | Healthy wound |
| HPPL  | No wound |
| HPLNC | Necrotic wound with cavity |

#### `esperance_maintien` – Remaining lifespan
| Code | Meaning |
|------|---------|
| 1 | > 15 years |
| 2 | 10–15 years |
| 3 | 5–10 years |
| 4 | < 5 years |
