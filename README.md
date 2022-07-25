# FiftyShapesOfGrey
Weltkarte, auf der die Grenzen der Länder zu einem eingestellten Zeitpunkt dargestellt werden.

## Beschreibung
Es soll die Animation einer Weltkarte dargestellt werden. 
Hierbei werden die Kontinente und innerhalb der Kontinente die aktuellen Grenzen der Länder dargestellt.
Durch einen Schieberegler soll auf einer Zeitachse verfahren werden können. Nach Verstellen des Reglers soll die zu diesem Zeitpunkt vorhandenen Grenzen dargestellt werden. 
Bei jeder Veränderung einer Grenze soll eine Information erscheinen. Durch Anklicken der Information bekommt man dann Links zu weiterführenden Informationen zu dieser Grenzverschiebeung angezeigt (Wikipedia, YouTube, etc.).

## Entwicklungsumgebung
Aktuell ist in der Planung das Ziel C# mit .NET und Unity zu verwenden.

## Zielplattform
Das Ergebnis soll im Browser ausgeführt werden.

## ToDo
### Geo-Daten
Es wird eine Quelle für Geodaten für die Grenzinformationen benötigt. Hierbei reichen zunächst die Daten zum aktuellen Zeitpunkt, um sich von dort in die Vergangenheit zurückzuarbeiten. Es scheint aber auch schon Kartenmaterial zu geben, welches Grenzdaten aus vorherigen Zeiten beinhaltet.

### Datenstruktur
Klärung, wie die Grenzdaten in der Datenbank gehalten werden sollen. Soll ein bestehendes Format verwendet werden, oder sollen die Daten in ein eigenes Format überführt werden?

### Oberfläche
Es muss ein Weg gefunden werden, die Informationen aus der Datenbank grafisch zu visualisieren.
