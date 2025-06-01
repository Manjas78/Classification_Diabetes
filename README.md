## Pima Indians Diabetes Klassifikation
Dieses Jupyter Notebook implementiert und vergleicht Machine-Learning-Modelle zur Vorhersage von Diabetes anhand des Pima Indians Diabetes Datensatzes.

### Notebook-Beschreibung
Das Notebook führt durch folgende Kernschritte:

Datenexploration und -vorbereitung: Laden des Pima Indians Diabetes Datensatzes, explorative Datenanalyse (EDA) und Vorverarbeitung. Dies beinhaltet die Behandlung von unplausiblen Nullwerten (als fehlend interpretiert und mit dem Median imputiert), Standardisierung der Merkmale und Aufteilung in Trainings- und Testsets.

Modelltraining und -evaluation: Training und Bewertung von vier Klassifikationsalgorithmen: Logistische Regression, Support Vector Machine (SVM), k-Nearest Neighbors (k-NN) und ein Multilayer Perceptron (MLP). Die Modellevaluation erfolgt anhand von Metriken wie Accuracy, Precision, Recall, F1-Score und Konfusionsmatrizen.

Ergebnisüberblick: Die Modelle zeigen eine moderate Leistung. In einem Beispieldurchlauf erzielte der k-NN-Klassifikator den höchsten F1-Score (ca. 0.635) für die Diabetes-Erkennung. Es besteht Verbesserungspotenzial durch Techniken wie Hyperparameter-Optimierung.

### Nutzung
Anforderungen: Python, pandas, numpy, scikit-learn, matplotlib, seaborn. Ein Anaconda-Environment wird empfohlen.

Ausführung: diabetes.csv Datensatz im Notebook-Verzeichnis platzieren oder Pfad anpassen, dann Notebook ausführen.

Nächste Schritte: Das Notebook legt eine Basis für weitere Optimierungen wie Hyperparameter-Tuning, fortgeschrittene Imputation und Feature Engineering.
