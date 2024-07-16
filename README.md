# Backmarket Preis Tracker in Node-Red

Dieser Node-Red-Flow ermöglicht es, die Preise verschiedener Produkte auf Backmarket zu verfolgen und zu speichern. 
Es werden keine Datenbanken benötigt, lediglich Node-Red und das Dashboard-Plugin.

## Anleitung

1. Importiere die JSON-Datei in Node-Red
2. Passe die URL im Node "Preis abfragen" an
3. Passe den Dateinamen und den Pfad im Speichern- und Lesen-Node an
4. Führe eine Preisabfrage mit dem Inject-Node durch
5. Öffne die automatisch erstellte Datei und füge diese Beschriftungen hinzu:
   
   ![grafik](https://github.com/Spb2005/Backmarket-Preis-Tracker-in-Node-Red/assets/92474938/84af6b62-3081-40a6-a063-60c10421cd5e)
6. Führe die Preisabfrage erneut durch
7. Passe den Variablen Namen in den Nodes "Reset Min Price + Reset Chart" und "Min Price" an. (in V1.1)
8. Passe ggf. die Namen der Grafiken an
9. Passe ggf. das Dashboard-Layout an
10. Ändere ggf. die tägliche Abfragezeit (Da das Abfragen ca. 15s dauert, empfehle ich, nicht alle Tracker gleichzeitig abzufragen)

## Bilder
![grafik](https://github.com/user-attachments/assets/606b7651-d6f8-41c5-bdab-ef9974fe5f51)
![grafik](https://github.com/user-attachments/assets/b5e40127-02fa-4408-88ff-3fe9e7538587) (Preis Tracker V1.1)
![grafik](https://github.com/user-attachments/assets/63301406-3933-4dfa-a41a-05e4839d44df) (Beispiel Tracker V1.1)




