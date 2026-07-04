# Voyagers of Nera – Interactive Map

Eine interaktive Karte für **Voyagers of Nera** mit allen wichtigen Ressourcen, Locations und optionaler Live-Spielerposition.

> Erstellt von [OnlyDeko](https://github.com/OnlyDeko) · [Steam](https://steamcommunity.com/profiles/76561198138606543)

---

## Screenshots

![Karte mit Markern](screenshots/map_overview.png)
![Minimap-Overlay](screenshots/minimap.png)

---

## Download

**[Neueste Version herunterladen](../../releases/latest)**

`VoyagersMap.exe` herunterladen und starten — keine Installation nötig, keine weiteren Dateien erforderlich.

---

## Features

- **2.200+ Marker** — Guide Spirits, Schreine (Feuer / Wind / Wasser / Erde), Monolithen, Markierungen, Ruinen, Kisten, Lore, Ressourcen, Zonen …
- **Eigene Marker** — Rechtsklick auf die Karte setzt einen persönlichen Marker (Ort / Achtung / Sterbeort) mit eigenem Namen, ohne Admin-Modus
- **Live-Spielerposition** — Standort + Blickrichtung in Echtzeit via UE4SS-Mod (optional)
- **Minimap-Overlay** — kleines Fenster über dem Spiel, folgt deiner Position (`F10`)
- **Filter-Sidebar** — jede Kategorie einzeln ein-/ausblenden
- **DE / EN** umschaltbar
- **Zonen-Overlay** — Gefahrenbereiche als Flächen auf der Karte
- **Update-Hinweis** — Banner mit Download-Link wenn eine neue Version verfügbar ist

---

## Installation

1. `VoyagersMap.exe` aus den [Releases](../../releases/latest) herunterladen
2. Irgendwo ablegen (Desktop, Downloads, egal) und starten
3. Fertig — die App speichert ihre Daten automatisch unter `%LocalAppData%\VoyagersMap\`

**Voraussetzungen:** Windows 10 / 11 (64-bit) · Microsoft Edge oder WebView2 Runtime (auf Windows 11 vorinstalliert, auf Windows 10 ggf. automatisch installiert)

---

## Live-Position (optional)

Für die Live-Spielerposition wird ein UE4SS-Mod benötigt:

1. **[UE4SS für Voyagers of Nera](https://www.nexusmods.com/voyagersofnera/mods/9)** von Nexus herunterladen und installieren
2. **`VoyagersMapDump_Mod.zip`** aus den [Releases](../../releases/latest) herunterladen und entpacken
3. `install_mod.bat` als Administrator ausführen — installiert den Mod automatisch
4. Spiel neu starten → grüner Punkt auf der Karte zeigt deine Position in Echtzeit

Ohne Mod funktioniert die Karte vollständig — nur ohne Live-Position.

---

## Shortcuts

| Taste / Aktion | Funktion |
|----------------|----------|
| `F10` | Minimap-Modus umschalten (globaler Hotkey, auch wenn das Spiel fokussiert ist) |
| Rechtsklick auf Karte | Eigenen Marker setzen (Name + Icon wählen) |
| `Esc` | Marker-Dialog schließen |

Spiel im **Randlos-Fenster-Modus (Borderless Windowed)** starten, damit das Minimap-Overlay sichtbar bleibt.

---

## Rechtliches / Legal

Dieses Tool ist ein inoffizielles Fan-Projekt ohne Verbindung zu den Entwicklern von Voyagers of Nera.
Alle Spielinhalte und Assets sind Eigentum der jeweiligen Rechteinhaber.

Siehe [DISCLAIMER.md](DISCLAIMER.md) für den vollständigen rechtlichen Hinweis.

---

## Credits

- [RE-UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) — Lua-Modding-Framework (MIT)
- UE4SS-Paket für VoN von Ogato ([Nexus Mod #9](https://www.nexusmods.com/voyagersofnera/mods/9))
- Kartendaten & Icons aus dem Spiel gehören Treehouse Games — Fan-Tool, keine offizielle Software
