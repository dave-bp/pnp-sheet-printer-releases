# PnP Sheet Printer – Releases

Foundry-VTT-Modul (v14, dnd5e 6.0.x), das Charaktere live aus Foundry in ausfüllbare **PDF-Charakterbögen** druckt – für das analoge Spiel am Tisch. Mitgeliefert wird der Bogen **Heldenbogen 5E** (Pergament und tintensparende Druckversion); die offiziellen Bögen DE/EN lassen sich als eigene PDFs einbinden.

Dieses Repository enthält nur die installierbaren Pakete.

## Installation

Foundry-Setup → **Add-on-Module** → **Modul installieren** → bei **Manifest-URL** eintragen:

```
https://raw.githubusercontent.com/dave-bp/pnp-sheet-printer-releases/main/module.json
```

Danach in der Welt unter **Einstellungen → Module verwalten** aktivieren. Gedruckt wird über das Fenstermenü des Charakterbogens oder per Rechtsklick auf den Charakter in der Akteure-Liste → **Bogen drucken**.

### Offizielle Bögen

Die offiziellen ausfüllbaren Charakterbögen sind aus Urheberrechtsgründen nicht enthalten. Lege sie als `official-de.pdf` / `official-en.pdf` in einen Ordner deines Foundry-Datenverzeichnisses und wähle ihn in den Moduleinstellungen unter **Ordner für offizielle Bögen** aus.

## Versionen

Siehe [CHANGELOG.md](CHANGELOG.md). Ältere Pakete liegen unter `releases/v<Version>/module.zip`.
