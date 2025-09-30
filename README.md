SAP Journal Entry Automation

Dieses Projekt demonstriert, wie sich Buchungsbelege für SAP mithilfe von Python automatisiert erzeugen lassen.
Ausgangsbasis sind Excel- oder CSV-Dateien (z. B. aus dem Controlling).
Das Skript übernimmt die Zuordnungen (z. B. Sachkonten, Kostenstellen, Partner) und erstellt automatisch eine fertige Datei im SAP Journal Entry Upload Format (S/4HANA Fiori App „Upload Journal Entries“).

__________________________________________________________________________________________________________________________________________________


🚀 Projektziele
Vereinfachung manueller Arbeiten in der Buchhaltung
Reduktion von Fehlerquellen bei Massendaten
Aufbau eines nachvollziehbaren Python-Portfolios (Transition von VBA → moderne Automatisierung)

__________________________________________________________________________________________________________________________________________________


⚙️ Geplanter Funktionsumfang
Input: Einlesen von Excel/CSV-Dateien mit Rohdaten
Transformation:
Mapping von Feldern (z. B. Kostenstelle → Sachkonto)
Validierung (Soll = Haben, Pflichtfelder vorhanden)
Output: Erstellung einer SAP-konformen Upload-Datei (Excel)
Optional:
Kleine Weboberfläche mit Streamlit (Dateiupload → Download fertige SAP-Datei)
Logging & Fehlerreport

__________________________________________________________________________________________________________________________________________________


📂 Projektstruktur (geplant)
sap-journal-entry-automation/
│
├── notebooks/         # Jupyter/Colab Notebooks für Entwicklung & Tests
├── src/               # Python-Skripte mit der Kernlogik
├── examples/          # Beispiel-Input- und Output-Dateien
├── README.md          # Projektdokumentation
└── requirements.txt   # Python-Abhängigkeiten

__________________________________________________________________________________________________________________________________________________


🔧 Technologien
Python 3
pandas (Datenbearbeitung)
openpyxl (Excel-Handling)
Streamlit (optional: Weboberfläche)

__________________________________________________________________________________________________________________________________________________


📅 Roadmap (2 Monate)
Woche 1–2: Python-Basics & pandas kennenlernen
Woche 3–4: Input einlesen & Transformationen implementieren
Woche 5: Output im SAP-Uploadformat erzeugen
Woche 6: Fehlerhandling & Validierungen
Woche 7–8: Optionales Streamlit-Frontend + Dokumentation

__________________________________________________________________________________________________________________________________________________


📜 Lizenz

Dieses Projekt steht unter der MIT License – freie Nutzung erlaubt, Verweis auf den Autor erwünscht.

__________________________________________________________________________________________________________________________________________________


✨ Hinweis

Dieses Projekt ist kein offizielles SAP-Produkt, sondern ein Lern- und Portfolio-Projekt, das zeigen soll, wie Finance-Workflows mit Python automatisiert werden können.
