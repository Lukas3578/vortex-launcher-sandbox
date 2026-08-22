## Sandbox Vortex v0.9.57

### Neu
Sandbox Vortex hat eine eindeutige Paketkennung, eine eigene EXE, einen eigenen Installationsordner und einen eigenen Startmenü-Ordner.

### Behoben
Der Installer verwendet einen festen, ausschließlich für Sandbox Vortex vorgesehenen NSIS-GUID. Dadurch bleibt die Windows-Installation von **Vortex Client** vollständig getrennt und kann weder aktualisiert, ersetzt noch deinstalliert werden.

### Installation
1. Die fehlgeschlagene v0.9.56 nicht verwenden.
2. Falls einer der alten Installer eine App entfernt hat, zuerst den aktuellen normalen Vortex Client v0.9.53 erneut installieren.
3. Danach `Sandbox-Vortex-Setup-0.9.57.exe` installieren.
4. Beide Einträge bleiben getrennt: **Vortex Client** ohne Cosmetics und **Sandbox Vortex** mit Cosmetics.

### Hinweis
Dies ist der korrigierte Sandbox-Installer für die parallele Installation neben dem normalen Vortex Client.
