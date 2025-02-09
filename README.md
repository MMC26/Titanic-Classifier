# Titanic-Classifier
Projecte de Machine Learning dissenyat per predir la supervivència d'una persona al Titanic.

## CARACTERÍSTIQUES
- **Tipus de classificació:** binària (*Sobreviu* [1] o *NO sobreviu* [0]).
- **EDA (exploratory data analysis)**
  - Comprensió de la base de dades
- **PREPROCESSING**
  - Tractament de Nans
  - Encoding de categòriques
  - Normalització
  - PCA
- **METRIC SELECTION**
  - Mètriques considerades: Accuracy, Precision, Recall, F1-Score
  - Ajust del threshold
  - Corbes ROC i PR
- **MODEL SELECTION amb CROSSVALIDATION**
  - Models seleccionats: Regressió logística, Random Forest, KNN, SVM
  - Búsqueda d'hiperparàmetres
- **Anàl·lisi final**
- **Cas d'ús:**
  - Aprofundir en el comportament del model de classificació respecte a la supervivència en funció del sexe.

## INSTAL·LACIÓ 

1. **Clona el repositori:**
   ```bash
   git clone https://github.com/MMC26/Titanic-Classifier.git
   cd Titanic-Classifier

2. **Llibreries:**
    Aquest projecte utilitza diverses llibreries de Python que cal instal·lar abans d’executar-lo. Pots fer-ho creant un entorn virtual i instal·lant-les amb pip:

    ```bash
    pip install pandas
    pip install numpy
    pip install matplotlib
    pip install seaborn
    pip install scikit-learn
    pip install category-encoders
    pip install kaggle

    ```

## RESULTATS
- Mètriques escollides: F1-Score i PR curve
- Random Forest model més efectiu, amb un accuracy del 83% i un F1-Score de 0.75.
- Les dones van tenir una taxa de supervivència molt més alta (69.15%) que els homes (18.39%)

## AUTORES
- Maria Muñoz Cabestany 
- Blanca Pinyol Chacon 

