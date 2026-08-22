## Sandbox Vortex v0.9.59

### Behoben
Minecraft 1.21.11 konnte beim Start abstürzen, weil die neue Sandbox-Titelmenü-Anpassung zwei geerbte Minecraft-Felder als direkte Mixin-Felder angesprochen hat. Der Fehler ist korrigiert: Die Menüanpassung liest die öffentlichen Bildschirmmaße jetzt direkt über die Screen-API.

### Prüfung
Das Sandbox-Addon wurde nach dem Fix erfolgreich gegen Minecraft 1.21.11 und Fabric gebaut. Der normale Vortex Client bleibt unverändert.

### Installation
1. Sandbox Vortex schließen.
2. `Sandbox-Vortex-Setup-0.9.59.exe` installieren.
3. Minecraft 1.21.11 über Sandbox Vortex starten; das korrigierte Addon wird automatisch in die Instanz kopiert.
