# IPA/PA Checkliste Kanton Zug

Dieses Latex Template kann gebraucht werden für die Checkliste zur Durchführung einer PA (Praktische Abschlussarbeit) für Informatiker EFZ im Kanton Zug und basiert auf dem bisherigen Template der Checkliste. Wichtig: Diese Checkliste ist nicht verbindlich und dient nur zur Unterstützung der Experten. 

## Dokument bearbeiten

 1. Repository klonen
 1. In Visual Studio Code öffen, die Extension [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) sollte vorher installiert werden, ebenso wie Docker.
 1. DEV Container starten, Output-PDF-Dokument wird automatisch via on-save aktualisert.


## Dokument builden ohne Entwicklungsumgebung

Das Dokument kann mit LaTeX gebaut werden, die besten Resultate gibt es mit der Tectonic Latex Umgebung. Wenn Tectonic installiert ist, kann folgender Befehl ausgeführt werden:

```
tectonic -X build
```

Das fertige Dokument befindet sich dann unter build/default/default.pdf.


## Credits

Dieses Dokument basiert auf der IPA Checkliste von Open ICT: https://github.com/ictorg/ipa-experts-checklist
