# LB259

## Datensatz
Kaggle-Link: https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling

Ich verwende den Datensatz **Churn Modelling**, weil er mit 10'000 Einträgen eine passende Grösse für das Modul hat und trotzdem gut überschaubar bleibt. Die Zielvariable `Exited` ist binär (Kunde bleibt oder kündigt), wodurch sich Klassifikationsmodelle leicht umsetzen lassen. Felder wie `CreditScore`, `Age`, `Balance`, `Geography` und `NumOfProducts` sind einfach interpretierbar und eignen sich sehr gut für Statistik, Visualisierungen, Feature-Auswahl und eine saubere Modell-Evaluation.

## Datenschutz
Der Datensatz enthält keine direkt sensiblen Daten wie echte Passwörter, Kreditkartennummern oder vollständige Bankdaten. Trotzdem gibt es Angaben wie `Surname`, `CustomerId`, `Geography`, `Gender`, `Age` und `EstimatedSalary`. Damit muss man vorsichtig umgehen, weil Namen und geografische Angaben Personen eher erkennbar machen könnten. Ich verwende die Daten deshalb nur für diese Schulaufgabe und verbinde sie nicht mit echten Personen.

## Dateien im Ordner
- `churn_modelling.xlsx` (Excel-Datei für die Abgabe)
- `churn_modelling.csv` (gleiches Dataset als CSV)
