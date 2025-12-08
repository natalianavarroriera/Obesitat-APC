# Obesity Dataset – Classificació i Regressió
## Aprenentatge Computacional

Aquest repositori conté un petit projecte d’anàlisi i modelatge utilitzant el conjunt de dades **ObesityDataSet.csv**, amb dos notebooks principals:

* **`cas_kaggle_classificacio.ipynb`** → models de Classificació per predir la categoria d’obesitat sense distància entre les categories.
* **`cas_kaggle_regressio.ipynb`** → models de regressió per predir arrodonint les categories d'obesitat amb ordre i mateixa distància.

---

## Estructura del repositori

```
.
├── ObesityDataSet.csv
├── cas_kaggle_classificacio.ipynb
├── cas_kaggle_regressio.ipynb
└── README.md
```

---

## Descripció del dataset

El fitxer `ObesityDataSet.csv` conté informació relacionada amb:

* Edat
* Pes i alçada
* Hàbits alimentaris
* Activitat física
* Antecedents familiars
* Transport utilitzat
* Temps d'ús en tecnologies
* Consum d'alcohol i tabac
* Categoria d’obesitat (`NObeyesdad`)

Aquest dataset prové d’un problema de Kaggle --> [Enllaç](https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster/data)

---

## Passos del projecte

### **1. Regressió**

Notebook: `cas_kaggle_regressio.ipynb`

*  Preparació del dataset i tractament de valors categòrics i numèrics.
* Visualitzacions i anàlisi exploratori.
* Entrenament de models (SVM, RandomForestRegressor, XGBoost, LightGBM ,Lineal Regression).
* Mètrica de regressió:
  * RMSE
* Canvi a classificació i comparació amb mètrica de classificació:
  * Accuracy
  * Matriu de confusió


### **2. Classificació**

Notebook: `cas_kaggle_classificacio.ipynb`

* Preparació del dataset i tractament de valors categòrics i numèrics.
* Visualitzacions i anàlisi exploratori.
* Entrenament de diferents models (SVM, RandomForest, XGBoost, LightGBM ,Linear Regression,KNN).
* Comparació de resultats i mètriques:
  * Accuracy
  * Matriu de confusió
 
---

## Requisits

Instal·la les dependències principals:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn spicy time shap
```

---

## Autors

* Anna Mongelos Amill - 1672531
* Natàlia Navarro Riera - 1711044
