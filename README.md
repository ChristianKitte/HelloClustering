# EA 12 - Clustering Exercise
### Data Science SS 21
### Christian Kitte 

### Aufgabe ###

Es sollen vorgegebene  [**Daten**](https://github.com/ChristianKitte/HelloClustering/blob/main/edlich-kmeans-A0.csv) einer Clusteranalyse unterzogen werden. Als Ziel soll eine sinnvolle Anzahl Cluster (k) ermittelt werden, sowie der daraus resultierende Clustervektor erstellt werden.

Die Löung mit einer ausführlichen Erklärung befindet sich in dem hier vorliegenden [**Notebook**](https://github.com/ChristianKitte/HelloClustering/blob/main/Clustering.ipynb). Es gliedert sich in die Datenbeschaffung, dem Anlegen einiger Methoden sowie darauf basierend der Bestimmung von k mithilfe des "Ellenbogen Effektes". 

Als Maß wird hier die auftretende Differenz der Distanzen zu dem vorhergehenden k verwendet. Ist diese sehr klein, so ist eine weitere Clusterung eher weniger sinnvoll. Letztlich kommt es natürlich auch immer auf den Kontext der Daten an.

Die angelegten Methoden selbst wurden allgemeiner programmiert und können auch außerhalb dieses Kontextes eingesetzt werden, um Arbeiten zu erleichtern.
