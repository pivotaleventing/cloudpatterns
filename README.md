# cloudpatterns
Eine Sammlung von Architekturmustern und Lösungsstrategien im Kontext Cloud

## Katalog der Architekturmustern

### Valet Key (Dienerschlüssel)
#### Problembeschreibung
Ihre Applikation bietet die Möglichkeit langlaufende Aktionen wie den Upload großer Dateien an. Das Ziel dieser Aktionen liegt allerdings außerhalb ihrer Anwendung, sodass die Applikation währenddessen beteiligt bleibt, was den Verbrauch an Ressourcen unnötig erhöht. Das eigentliche Ziel der Aktion wäre für den anfragenden Client theoretisch auch direkt erreichbar, allerdings ist die Frage wie dies sicher abgebildet werden kann.

### Circuit Breaker	(Schutzschalter)
