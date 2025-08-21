<div align="center">

**Corso di Laurea in Mathematical Engineering**

### Business Intelligence per Big Data

# Glass Type Classification

<img src="logo_università/logo_Politecnico_Torino.jpg" alt="logo" width="200">

<br>

<span style="font-size:20px"><b>Andrea Terenziani</b> — s349167</span>  


**Anno Accademico 2024–2025**

</div>

## Struttura del lavoro

### 1. Report scientifico
- File: `Multiclasse_s349167.pdf`  
- Documento che presenta:
  - Introduzione e motivazioni del problema
  - Analisi del dataset (sbilanciamento classi, valori mancanti, outlier, correlazioni)
  - Preprocessing dei dati (scaling, imputazione, riduzione di dimensionalità, PCA)
  - Descrizione dei modelli utilizzati:
    - Decision Tree
    - K-Nearest Neighbors
    - Support Vector Machine
    - Multi-Layer Perceptron
  - Metodologia di validazione (Grid Search, cross-validation, metriche)
  - Risultati sperimentali (confusion matrix, F1-macro, ROC/AUC, learning curve)
  - Conclusioni e confronto dei modelli

### 2. Codice
- File: `main_glass_BI.ipynb`  
- Notebook Jupyter che contiene:
  - Analisi esplorativa del dataset
  - Implementazione delle pipeline di preprocessing
  - Addestramento e valutazione dei modelli
  - Generazione di grafici e metriche
  - Riproducibilità completa degli esperimenti

### 3. Sorgenti LaTeX
- Cartella Overleaf contenente i file `.tex` per la generazione del report PDF.

### 4. Repository GitHub
Tutto il materiale è disponibile anche su GitHub:  
[Glass Classification BIXBD](https://github.com/terenziani/Glass_Classification_BIXBD)

---

## Tecniche utilizzate
- **KNN Imputer** per la gestione dei valori mancanti.  
- **StandardScaler** per normalizzare le feature.  
- **Analisi di correlazione** ed eliminazione di variabili ridondanti.  
- **PCA** (Principal Component Analysis) per la riduzione della dimensionalità.  
- **Grid Search + Cross-Validation** per l’ottimizzazione degli iperparametri.  
- Confronto tramite **F1-macro**, **Confusion Matrix**, **ROC/AUC**, **Learning Curve**.  

---

## Risultati principali
- Tutti i modelli hanno ottenuto buone prestazioni.  
- Il **Multi-Layer Perceptron (MLP)** è risultato il più performante, con valori superiori in tutte le metriche.  
- Il preprocessing (scaling, imputazione, feature selection) ha avuto un impatto positivo significativo.  
- Modelli diversi risultano preferibili in base alle esigenze (es. Decision Tree/KNN per basso FPR, SVM per recall perfetta su alcune classi).  

---

## Requisiti
- Python 3.9+  
- Librerie principali: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`  
---

## Autore
Andrea Terenziani  
Matricola: **s349167**  
Politecnico di Torino




















