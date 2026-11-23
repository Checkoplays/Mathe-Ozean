MATHE-OZEAN WUNDERWELT V5

UPLOAD: Alle Dateien aus diesem Ordner direkt in das Hauptverzeichnis des bestehenden GitHub-Repositories hochladen (nicht den Ordner selbst).

ENTHALTEN: 12 verschiedene prozedurale echte 3D-Figuren (max. 12 gleichzeitig), animierte Riffwelt, berührbare Charaktere, 5 Rechenmodi, Fortschritt, Belohnung alle 5 richtigen Aufgaben, lokal gespeicherter Fortschritt, Synthesizer-Sounds.

EHRLICHE GRENZEN:
- Three.js wird über CDN geladen. Die Engine-Datei ist nicht im ZIP enthalten, weil in der Erstellungsumgebung kein Netzwerkzugriff auf das CDN möglich war. Die Web-App benötigt daher beim ersten Start Internet. Vollständige, garantierte Offlinefähigkeit kann mit diesem Paket nicht zugesichert werden. Für echtes Offline-Bundling muss three.module.js lokal als Datei eingebunden und im Service Worker gecacht werden.
- Die Sounds sind synthetisch, keine professionell aufgenommenen Stimmen/Lacher.
- Die Figuren sind geometrisch erzeugte 3D-Modelle, keine extern produzierten, geriggten Filmcharaktere.
- Browser-/Android-Tests waren in der Erstellungsumgebung nicht möglich.

Zum späteren Offline-Bundling: Lade https://cdn.jsdelivr.net/npm/three@0.170.0/build/three.module.js herunter, speichere sie im selben Ordner und ersetze in game3d.js den Import-URL durch './three.module.js'. Füge './three.module.js' der FILES-Liste in sw.js hinzu, erhöhe den CACHE-Namen und lade alles erneut hoch.
