MATHE-OZEAN 4.0 — 3D-Prototyp

GitHub: Die fünf Web-Dateien aus diesem Ordner direkt ins Repository-Hauptverzeichnis hochladen. Alte game.js darf entfernt werden.

WICHTIG: Die 3D-Engine Three.js wird beim ersten Besuch von cdn.jsdelivr.net geladen. Für Offline-Nutzung muss der Service Worker die Engine erfolgreich zwischenspeichern. Zum Prüfen nach dem ersten Laden Flugmodus einschalten, App schließen und erneut öffnen.

Eine vollständig selbst enthaltene Offline-Distribution würde die Three.js-Datei im Repository benötigen. Sie ist in diesem Paket NICHT enthalten, da der Download der Bibliothek hier nicht möglich war. Für eine zuverlässige Offline-App die Datei https://cdn.jsdelivr.net/npm/three@0.170.0/build/three.module.js herunterladen, im Ordner vendor/three.module.js ablegen und in game3d.js sowie sw.js die CDN-Adresse durch ./vendor/three.module.js ersetzen.

Version 4 ist ein nicht auf Android getesteter Prototyp. Die 3D-Modelle sind geometrisch erzeugt, keine professionellen Charaktermodelle. Keine aufgenommenen Stimmen, nur synthetische Signaltöne.
