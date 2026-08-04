# Produktanbieter-Darlehensdaten API

API zur Abfrage von Darlehensdaten für Produktanbieter

Diese API kann von Produktanbietern als Service-Provider angebunden werden, um EUROPACE in die Lage zu versetzen, automatisiert Darlehensdaten bei ihnen
auszulesen. Die Darlehensdaten werden dann in [BaufiSmart](https://github.com/europace/baufismart) im Rahmen einer Umschuldung oder Prolongation
weiterverarbeitet.

# Dokumentation

Die API ist nach *OpenAPI Spec 2.0* (https://openapis.org/) spezifiziert.

* Spezifikation: https://github.com/OAI/OpenAPI-Specification
* Swagger: http://editor.swagger.io/#/?import=https://raw.githubusercontent.com/europace/baufismart-darlehensdaten-api/master/swagger.yaml

# Release

Bei Anpassungen der API-Spezifikation in [`swagger.yaml`](https://github.com/europace/baufismart-darlehensdaten-api/blob/master/swagger.yaml) muss die
Versionsnummer erhöht und ein neues [GitHub-Release](https://github.com/europace/baufismart-darlehensdaten-api/releases) mit einem passenden Git-Tag angelegt
werden. Der Tag soll der Versionsnummer entsprechen und mit `v` beginnen, zum Beispiel `v0.0.7`. Die Release-Beschreibung sollte die wesentlichen Änderungen der
neuen Version zusammenfassen.
