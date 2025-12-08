# Decision Tree Model — Macroeconomic & Housing Market Indicators

Ovaj projekat prikazuje izgradnju **Decision Tree modela** korišćenjem makroekonomskih i finansijskih indikatora koji utiču na tržište nekretnina.  
Model i analiza su urađeni u Python-u, u Jupyter Notebook okruženju.

## 📌 Cilj projekta

- Demonstrirati primenu Decision Tree modela na realnim ekonomskim podacima  
- Ilustrovati proces pripreme podataka (čišćenje, transformacija, konverzije tipova)  
- Podeliti podatke na trening i test skup  
- Trenirati Decision Tree model i vizualizovati rezultate  
- Prikazati *feature importance* — koji indikatori najviše utiču na target promenljivu  

Ovaj projekat predstavlja osnovu za šire mašinsko učenje u oblasti finansijske stabilnosti i kvantitativne analize.

---

## 📊 Sadržaj notebook-a

Notebook `decision_tree.ipynb` uključuje:

1. **Učitavanje podataka iz CSV fajla**
2. **Čišćenje podataka**
   - zamena nedostajućih vrednosti  
   - konverzija string vrednosti u numeričke  
3. **Analiza deskriptivnih statistika**
4. **Train-test split (npr. 95% / 5%)**
5. **Trening Decision Tree modela**  
   Parametri poput:
   - `max_depth`
   - `min_samples_leaf`
   - `random_state`
6. **Vizualizacija stabla i grafa strukture**
7. **Feature Importance**
8. **Tumačenje rezultata**

---

## 🛠 Tehnologije i biblioteke

Projekat koristi:

- **Python 3**
- **pandas**
- **numpy**
- **scikit-learn**
- **matplotlib**
- **Jupyter Notebook / VS Code**

---

## 🚀 Kako pokrenuti projekat

1. Klonirajte repozitorijum:

```bash
git clone https://github.com/MiMica-wow/decision_tree_project.git

