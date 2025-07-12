
# 🎓 Studiengangs-Matching Tool

Ein interaktives Persönlichkeits-basiertes Matching-Tool zur Studienberatung. Es kombiniert das RIASEC-Modell mit den Big Five Persönlichkeitsdimensionen, um passende Studiengänge zu identifizieren.

## 🚀 Funktionen

- 40 Fragen (Likert-Skala)
- Persönlichkeitsprofil mit 11 Dimensionen (RIASEC + Big Five)
- Zusatzfragen zu Motivation & Arbeitsumgebung
- Matching mit 30+ Studiengängen inkl. NC, Berufsfelder und Gehalt
- Intuitive Web-Oberfläche mit Streamlit

## 🧠 Verwendete Dimensionen

- **RIASEC:** Realistic, Investigative, Artistic, Social, Enterprising, Conventional  
- **Big Five:** Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism

## 📁 Dateistruktur

```
studiengangs-matching/
├── app_neu.py                        # Hauptanwendung
├── fragebogen_kurzversion.csv       # Persönlichkeitsfragebogen (40 Items)
├── studiengaenge_bewertung_komplett.csv  # Studiengangs-Bewertungen
├── README.md                         # Diese Datei
```

## ▶️ Ausführen

Installiere die Abhängigkeiten (optional in venv):

```bash
pip install streamlit pandas numpy
```

Starte das Tool mit:

```bash
streamlit run app_neu.py
```

## ⚠️ Voraussetzungen

- Python 3.8+
- UTF-8-codierte CSV-Dateien mit `;` als Trennzeichen

## 📬 Kontakt

Bei Fragen oder Erweiterungswünschen: max.mustermann@example.com
