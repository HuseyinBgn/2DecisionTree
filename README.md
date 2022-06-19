Name des Projekts:	Entscheidungsbaeume
Link zum MyBinder: 	https://github.com/HuseyinBgn/2DecisionTree

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem Entscheidungsbaeume.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!


1. Libraries installieren & importieren: 
- Hier werden die Librairies für die Datenverarbeitung und -visualisierung installiert und anschließend importiert

2. Die Daten:
- Loan_Data.csv Datei wird gelesen
- Loan_Data Daten werden überprüft ob sie richtig gelesen wurden, ob die Darstellung korrekt übernommen wurde, usw.

3. Explorative Daten Analyse:
- Übereinander liegendes Histogramm der FICO Verteilungen je nach dem "credit.policy" Ergebnis.
- Gleiches Diagramm, bei dem diesmal nach "not.fully.paid" Spalte getrennt wird.
- Erstellen eines Countplots mit Hilfe Seaborn Library. Anzahl der Leihgaben nach Zweck sollen angezeigt und nach "not.fully.paid" aufgeteilt werden.
- Jointplot, die FICO Score und Zinsen miteinander Vergleicht.
- Lmplots, die "not.fully.paid" und "credit.policy" unterscheiden.

4. Die Daten Vorbereiten:
- Erstellen und Einfügen der "cat_feats" Spalte in die DataFrame.

5. Train Test Split:
- 30% der Daten werden als Testdaten aufgeteilt.

6. Ein Entscheidungsbaummmodell trainieren:
- "DecisionTreeClassifier" Library wird importiert und anschließen werden das Modell mit Trainingsdaten trainiert.

7. Vorhersage und Auswertung:
- Ausgabe der Ergebnisse und der Konfusionsmatrix von Entscheidungsbaummodell.

8. Ein Random Forest Modell trainieren:
- Trainieren des Random Forest Modells.

9. VOrhersage und Auswertung:
- Ausgabe der Ergebnisse und der Konfusionsmatrix von Random Forest Modell.	