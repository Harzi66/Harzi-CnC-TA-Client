# Harzi-CnC-TA-Client

Offizielle Download- und Updatequelle für den **Harzi-CnC-TA-Client**.

Dieses öffentliche Repository stellt ausschließlich die veröffentlichten Windows-Installationspakete und Release-Informationen bereit. Der vollständige Client-Quellcode wird hier nicht abgelegt.

## Releases veröffentlichen

Für jede stabile Version wird ein GitHub-Release angelegt:

- **Tag:** `v<Version>`, beispielsweise `v0.2.95`
- **Release-Titel:** `Harzi-CnC-TA-Client v<Version>`
- **Release-Asset:** `Harzi-CnC-TA-Client-Setup-<Version>-x64.exe`

Beispiel für Version 0.2.94:

`Harzi-CnC-TA-Client-Setup-0.2.95-x64.exe`

Die Versionsnummer im Tag und im Dateinamen muss exakt übereinstimmen.

Nur reguläre, veröffentlichte Releases werden vom Client berücksichtigt. Entwürfe und Vorabversionen werden ignoriert.

## Integritätsprüfung

Der integrierte Updater liest das neueste stabile Release über die öffentliche GitHub-Releases-API. Vor dem Download muss GitHub für das Installationspaket einen SHA-256-Digest bereitstellen. Der Client vergleicht diesen Wert nach dem Download mit der tatsächlich heruntergeladenen Datei. Fehlt der Digest oder stimmt er nicht überein, wird das Update nicht gestartet.

Die Installationsdatei wird als Release-Asset hochgeladen – nicht als normale Datei in den Repository-Hauptordner.

## Updatequelle

Repository: https://github.com/Harzi66/Harzi-CnC-TA-Client

Release-Übersicht: https://github.com/Harzi66/Harzi-CnC-TA-Client/releases

Automatisch abgefragte API:
`https://api.github.com/repos/Harzi66/Harzi-CnC-TA-Client/releases/latest`

## Kontakt

Harzi / Harzi66  
harzi66@protonmail.com
