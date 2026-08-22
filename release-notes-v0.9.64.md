# Sandbox Vortex v0.9.64

## Mod Installer repariert und erweitert

| Bereich | Verbesserung |
|---|---|
| **Kompatible Suche** | Der Installer sucht wieder über Modrinth nach Fabric-Mods für die aktuell ausgewählte Minecraft-Version. |
| **Sichere Installation** | Jeder Download wird als JAR-Archiv geprüft, per SHA-512 gegen den Modrinth-Hash validiert und erst danach atomar in den Mod-Ordner verschoben. |
| **Fehleranzeigen** | Netzwerk-, API-, Größen-, Archiv- und Prüfsummenfehler werden klar angezeigt, ohne fehlerhafte Dateien im Mod-Ordner zu hinterlassen. |
| **Mehr Auswahl** | Schnellsuchen für Performance, Minimap, Voice Chat, Shader und Inventar sowie Sortierung nach Relevanz, Downloads, Aktualität oder Neuheit. |
| **Mehr Ergebnisse** | Weitere kompatible Ergebnisse können schrittweise nachgeladen werden. |
| **Mod Health** | Ein lesender Gesundheitscheck zeigt aktive, deaktivierte und geschützte Mod-Dateien sowie fehlende erforderliche Vortex-Dateien oder auffällige JAR-Signaturen. |

## Zusätzliche Verbesserungen

Beim Wechsel der Minecraft-Version werden alte Suchresultate bewusst entfernt. Dadurch kann kein Mod-Ergebnis einer vorherigen Version versehentlich für die neue Instanz installiert werden.

## Hinweis

Diese Veröffentlichung betrifft ausschließlich **Sandbox Vortex**. Der normale Vortex Client bleibt unverändert. Eigene Mods, Welten und Resource Packs werden durch den Mod-Health-Check nicht verändert oder gelöscht.

## Installation

Installiere `Sandbox-Vortex-Setup-0.9.64.exe` über die bestehende Sandbox Vortex oder lade das Update über **Check for updates** im Launcher.
