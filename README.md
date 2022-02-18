# WICHTIG
Die Verbindungsstärke ist komplett zufällig. Dieses Repo ist nur ein Proof of principle für die technische Seite. KEINE ECHTEN DATEN.

# Ziel der Behörden-Karte
Dieses Netzwerk soll grafisch die Zusammenarbeit zwischen den Berliner Behörden darstellen. Die Abbildung soll quantitativ sein, das heißt sie soll die echte Situation darstellen unabhängig von der gewollten Darstellung. 

# Methoden
Das Netzwerk ist mit R erstellt. Die Daten sind in den .csv-Dateien enthalten. Die Berechnung ist in der Datei behoerden_network.Rmd.

## Sammlung der Player
Hier könnte die folgenden Player stehen mit einer Subdomain im Berliner Netz registrierte Behörde. Beispiel: sengpg.berlin.de oder reinickendorf.berlin.de. Vorläufig sind es alle auf https://service.berlin.de/behoerden/ gelisteten Behörden.

## Bewertung der Größe der Nodes
Hier könnte die Anzahl an allen mit der Domain registrierten E-Mail-Adressen stehen 

## Bewertung der Links
Hier könnte die Anzahl an allen von einer Domain zu einer anderen Domain gesendeten E-Mail stehen.
