
# 🚲 Green Mobility – Data Analysis with Python

**Autore:** Mikael Mbiada Nganou  
**Repository:** [green-mobility-python](https://github.com/mikael-10/green-mobility-python)  
**Data:** Giugno 2025  
**Tecnologie:** Python, pandas, matplotlib, seaborn, Jupyter Notebook  

---

## 📌 Obiettivo del progetto

Analizzare le abitudini e le percezioni della popolazione piemontese in merito alla mobilità sostenibile.  
Attraverso un questionario composto da 12 domande, l’obiettivo è quello di trarre insight utili per enti pubblici, startup, aziende green e policy makers.

---

## 📊 Dataset

Il dataset è stato raccolto tramite Google Forms e contiene 55 risposte.  
Include 12 colonne, ciascuna corrispondente a una domanda del questionario (es. Età, Genere, Mezzo usato, Interesse per la green mobility, ecc.).

📁 File: `questionario_greenmobility.csv`

---

## ⚙️ Librerie utilizzate

- `pandas` – per la manipolazione dei dati
- `matplotlib` – per i grafici base
- `seaborn` – per visualizzazioni avanzate (heatmap, countplot)
- `numpy` – per supporto numerico
- `Jupyter Notebook` – ambiente di lavoro

---

## 🔍 Metodologia

1. **Caricamento e ispezione iniziale del dataset**
2. **Analisi descrittiva** con `.describe()` e `.value_counts(normalize=True)`
3. **Visualizzazioni univariate** (distribuzioni di età, genere, mezzi)
4. **Analisi incrociata** tra genere e mezzi usati (`pd.crosstab`)
5. **Visualizzazioni bivariate**: heatmap, grafici percentuali
6. **Storytelling e insight pratici**

---

## 📈 Visualizzazioni

- Bar chart su **Genere**, **Età** e **Mezzo usato settimanalmente**
- Heatmap che incrocia **Genere × Mezzo usato**
- Grafici trasposti per confronti percentuali tra gruppi
- Normalizzazione in percentuali con visualizzazioni leggibili

---

## 💡 Insight principali

- Il 60% del campione usa ancora l’**auto** come mezzo principale
- Il 70% è **interessato** alla mobilità sostenibile, ma solo il 40% **pagherebbe di più**
- La **fatica** è il principale svantaggio percepito della bicicletta
- Il 91% crede che la **bicicletta riduca l’inquinamento**
- Le donne mostrano maggiore apertura all’adozione di mezzi alternativi rispetto agli uomini

---

## 📎 Storytelling e riflessioni

La mobilità sostenibile è una priorità per il futuro delle città, ma emergono ostacoli culturali, fisici ed economici.  
Il dataset mostra che, seppur motivati, i cittadini necessitano di supporti pratici: incentivi, infrastrutture sicure, campagne educative.  
Questa analisi può aiutare a definire azioni mirate e orientate all’impatto.

---

## 📁 Struttura del repository

```
green-mobility-python/
├── data/
│   ├── questionario_greenmobility.csv
│   └── domande_Form_mob_sost.csv
├── notebooks/
│   └── greenMobility_analysis.ipynb
├── .gitignore
└── README.md
```

---

## ▶️ Come eseguire il progetto

Apri il notebook direttamente in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mikael-10/green-mobility-python/blob/main/notebooks/greenMobility_analysis.ipynb)

---

## 👨‍💻 Autore

Mikael Mbiada Nganou  
[Portfolio](https://github.com/mikael-10) – [LinkedIn](https://www.linkedin.com/in/mikaelmbiada/) – [Website](https://mikaelmbiada.dev)

---

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT – libero utilizzo con attribuzione.
