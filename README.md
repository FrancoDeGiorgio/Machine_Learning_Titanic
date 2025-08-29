# Machine_Learning_Titanic

## Progetto ML: Predizione della Sopravvivenza sul Titanic

Questo progetto mira a sviluppare un modello di machine learning capace di stimare la probabilità di sopravvivenza dei passeggeri del Titanic, basandosi sulle loro caratteristiche personali.

---

#### 1. Analisi dei dati
Il primo passo è stato esplorare il dataset per comprenderne struttura, tipi di variabili e valori mancanti, e visualizzazione dei dati così da identificare eventuali anomalie o informazioni rilevanti per il modello.
- **Statistiche di base**
- **Sopravvivenza per genere e classe**
- **Sopravvivenza e distribuzione per porto d'imbarco**
- **Distribuzione dell'età per categorie Socio-Demografiche**
- **Distribuzione erà passeggeri SOpravvisuti e Non Sopravviauti**
- **Heat Map correlazioni**

#### 2. Suddivisione del dataset
Per ottenere una valutazione affidabile, i dati sono stati divisi in più segmenti:
- **Identificazione della variabile target:**
  
#### 3. Grid Search CV
Questa fase ha incluso:
- **Gestione dei valori mancanti nella variabile "Age"**
- **Sostituzione valori mancanti in 'Age' con media**
- **Sostituzione valori mancanti in 'Age' con mediana**
- **Sostituzione valori mancanti in 'Age' con mediana dell'età per genere raggruppata per classe**
- **Risultati analisi comparativa su Grid Search**

#### ## 4. Sostituzione valori Mancanti
Sostituizione valori mancanti:
- **Gestione dei valori mancanti nella variabile "Embarked"**
- **Sostituzione valori mancanti in 'Age' con mediana dell'età per genere raggruppata per classe**

#### 5. Encoding Variabili Categoriche con One-Hot
Encoding con One-Hot:
- **Codifica delle variabili categoriche**
- **Sostituzione valori mancanti in 'Age' con mediana dell'età per genere raggruppata per classe**

#### 6. Implementazione Decision Tree Classifer
Addestramento e previsione:
- **Validazione della profondità dell'albero di decisione e valutazione sul Test Set**
- **Conclusioni**
