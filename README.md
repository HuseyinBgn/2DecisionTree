Name des Projekts:	Entscheidungsbaeume

Link zum MyBinder: 	[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HuseyinBgn/2DecisionTree/HEAD)

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem Entscheidungsbaeume.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!

Zum Ausführen der einzelnen Code-Zeilen "STRG" + "Enter" Tasten drücken.
Beachten Sie keine der Zeilen zu überspringen, denn sonst kann es zu Fehlerhaften Ausführung führen.

1. Libraries installieren & importieren: 
- Librairies für die Datenverarbeitung und -visualisierung werden installiert und anschließend importiert.

2. Die Daten:
- Loan_Data.csv Datei wird gelesen.
- Mit head(), info() und describe() Methoden wird auf die Korrektheit und Darstellung der Tabelle überprüft.

3. Explorative Datenanalyse:
- Übereinander liegendes Histogramm der FICO Verteilungen je nach dem "credit.policy" Ergebnis.
- Gleiches Diagramm, bei dem diesmal nach "not.fully.paid" Spalte getrennt wird.
- Ein Countplot mit Hilfe Seaborn Library. Anzahl der Leihgaben nach Zweck sollen angezeigt und nach "not.fully.paid" aufgeteilt werden.
- Jointplot, die FICO Score und Zinsen miteinander Vergleicht.
- Lmplots, die "not.fully.paid" und "credit.policy" unterscheiden.

4. Die Daten Vorbereiten:
- Erstellen und Einfügen der "cat_feats" Spalte in die DataFrame.

5. Train Test Split:
- 30% der Daten werden als Testdaten aufgeteilt.

6. Ein Entscheidungsbaummmodell trainieren:
- "DecisionTreeClassifier" Library wird importiert.
- Anschließend wird das Modell mit Trainingsdaten trainiert. Dies geschieht mit fit() Methode.

7. Vorhersage und Auswertung:
- Das Model soll mit Testdaten durch Nutzung von predict() Methode Vorhersagen. 
- Anschließen werden Ergebnisse Tests und der Konfusionsmatrix von Entscheidungsbaummodell angezeigt.

8. Ein Random Forest Modell trainieren:
- "RamdomForestClassifier" Library wird importiert.
- Anschließend wird das Modell mit Trainingsdaten trainiert. Dies geschieht mit fit() Methode.

9. Vorhersage und Auswertung:
- Das RandomForest-Modell soll mit Testdaten durch Nutzung von predict() Methode Vorhersagen. 
- Anschließen werden Ergebnisse Tests und der Konfusionsmatrix von RandomForest-Modells angezeigt.	