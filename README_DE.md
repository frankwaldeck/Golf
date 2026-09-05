# Waldeck Golf – WebApp für waldeck.cc

## Inhalt
- `index.html` – komplette mobile Golf-App
- `manifest.webmanifest` – Installierbarkeit als Web-App
- `service-worker.js` – Offline-Cache
- `CNAME` – benutzerdefinierte Domain `waldeck.cc`

## Veröffentlichung mit GitHub Pages

1. Auf GitHub ein neues Repository anlegen.
2. Die vier Dateien aus diesem Ordner in das Repository laden.
3. In GitHub: **Settings → Pages**.
4. Als Quelle den Branch `main` und den Ordner `/ (root)` wählen.
5. Unter **Custom domain** `waldeck.cc` eintragen und speichern.
6. Beim DNS-Anbieter die Domain auf GitHub Pages zeigen lassen.
7. Danach in GitHub Pages **Enforce HTTPS** aktivieren, sobald verfügbar.

GitHub Pages erwartet `index.html` als Einstiegsdatei. Für eine Apex-Domain wie `waldeck.cc` werden die DNS-Einstellungen beim Domainanbieter benötigt. DNS-Änderungen können bis zu 24 Stunden benötigen.

## Wichtig
Die App speichert ihre lokalen Daten im Browser des jeweiligen Geräts. Eine serverseitige Synchronisation zwischen mehreren Geräten ist in dieser Version nicht enthalten.

Die Anzeige „HCP-Verlauf“ ist eine Runden-/Punktehistorie und keine offizielle DGV/WHS-Handicapberechnung. Für ein offizielles Handicap müssen die vollständigen WHS-Regeln einschließlich Score Differential, Adjusted Gross Score, PCC und weiterer Vorgaben berücksichtigt werden.
