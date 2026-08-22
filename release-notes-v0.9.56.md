## Sandbox Vortex v0.9.56

### Neu
Sandbox Vortex verwendet jetzt eine eigene Paketkennung, eine eigene Windows-EXE, einen eigenen Installationsordner und einen eigenen Startmenü-Ordner.

### Behoben
Der Installer nutzt einen festen, nur für Sandbox Vortex bestimmten NSIS-Uninstall-GUID sowie `Sandbox-Vortex-Uninstall.exe`. Dadurch kann die Installation den normalen Vortex Client nicht mehr aktualisieren, ersetzen oder entfernen.

### Installation
1. Falls frühere Installer einen der beiden Launcher entfernt haben, den normalen Vortex Client erneut über dessen aktuellen Release installieren.
2. Anschließend `Sandbox-Vortex-Setup-0.9.56.exe` installieren.
3. Beide Apps bleiben danach getrennt in Windows: **Vortex Client** ohne Cosmetics und **Sandbox Vortex** mit Cosmetics.

### Hinweis
Diese Version ist die korrigierte Sandbox-Installation. Frühere Sandbox-Installer bis einschließlich v0.9.55 nicht erneut verwenden.
