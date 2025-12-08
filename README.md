# Mini Decision Tree Primer — Basic Classification Logic

Ovaj mini projekat prikazuje kako funkcioniše **Decision Tree classifier** na malom, ručno definisanom datasetu iz oblasti makroprudencijalne analize.  
Cilj je da se jasno razume *kako drvo bira splitove*, *šta je Gini impurity*, i *kako nastaje putanja odluke*.

---

## 🎯 Cilj projekta

- Razumeti osnovnu logiku stabala odlučivanja (Decision Tree)
- Pratiti kako model bira najbolje pitanje (split)
- Videti kako se računa Gini impurity
- Naučiti interpretaciju grana i listova
- Primeniti sve to na malom, jednostavnom datasetu pre prelaska na veće i realne podatke

Ovaj primer služi kao **intuitivni uvod** pre rada sa pravim makro-ekonomskim podacima.

---

## 🧠 Šta se uči na ovom primeru?

- Kako Decision Tree razdvaja podatke po pitanjima (`feature > threshold`)
- Kako funkcioniše Gini impurity:  
  - čisto čvor → Gini = 0  
  - mešan čvor → Gini se povećava  
- Kako drvo bira *najkorisnije prvo pitanje*
- Kako izgleda stablo kada ga nacrtamo (`plot_tree`)
- Kako svaki „put“ kroz stablo vodi do odluke (klase 0 ili 1)

---

## 🛠 Tehnologije

- Python 3  
- pandas  
- scikit-learn  
- matplotlib  
- Jupyter Notebook / VS Code  

Notebook: **`decision_tree.ipynb`**

---

## 🚀 Kako pokrenuti projekat

1. Klonirajte repozitorijum:

```bash
git clone https://github.com/MiMica-wow/decision_tree_project.git
cd decision_tree_project


