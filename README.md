# 💸 A/B-Test: Einfluss einer Website-Änderung auf das Ausgabeverhalten

In diesem Projekt analysieren wir, ob eine neue Version einer E-Commerce-Website das Kaufverhalten der Nutzer beeinflusst hat. Hierzu vergleichen wir die durchschnittlichen Ausgaben zweier unabhängiger Kundengruppen mithilfe eines **unabhängigen t-Tests**.

---

## 🔍 Projektziel

Ziel ist es zu prüfen, ob sich die durchschnittlichen Ausgaben von zwei Gruppen (Gruppe A: alte Website, Gruppe B: neue Website) signifikant unterscheiden. Ein signifikanter Unterschied würde darauf hindeuten, dass die Änderung der Website einen Einfluss auf das Nutzerverhalten hat.

---

## 📊 Methodik

1. **Daten**: Synthetisch generierte Ausgaben von zwei Gruppen (je 200 Personen)
2. **Visualisierung**: Histogramm, Boxplot
3. **Statistischer Test**: 
   - Shapiro-Wilk-Test zur Überprüfung der Normalverteilung
   - Unabhängiger t-Test zum Vergleich der Mittelwerte
4. **Interpretation**: Signifikanzbewertung anhand des p-Werts

---

## 🧪 Hypothesen

- **Nullhypothese (H₀):** Die durchschnittlichen Ausgaben der Gruppen A und B sind gleich.
- **Alternativhypothese (H₁):** Die durchschnittlichen Ausgaben unterscheiden sich.

---

## 📈 Ergebnisse

- **Shapiro-Wilk-Test:** Beide Gruppen sind normalverteilt (p > 0.05)
- **T-Test:**  
  - t-Statistik = `~3.2`  
  - p-Wert = `~0.001` ✅  
- **Ergebnis:** Signifikanter Unterschied zwischen den Gruppen festgestellt (p < 0.05)
- **Interpretation:** Die neue Website-Version führt zu signifikant höheren Ausgaben der Nutzer.

---

## 📦 Verwendete Technologien

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciPy](https://scipy.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

---

## 👤 Author

Rudolph Haink  
[LinkedIn](https://www.linkedin.com/in/rudolph-haink-a5454564/)


