# Installation and Usage / Installation und Bedienung

> [!IMPORTANT]
> The user interface of the HK Rollband Editor is currently available in German only.  
> Die Benutzeroberfläche des HK Rollband Editors ist derzeit ausschließlich auf Deutsch verfügbar.

---

# 🇬🇧 English

## Requirements

- A working installation of **SubwaySim 2**
- The **HK vehicle**
- The latest version of the **HK Rollband Editor**

> [!NOTE]
> The editor itself is currently available in German only. This guide explains the German controls in English.

> [!IMPORTANT]
> The mod is currently designed exclusively for the HK. Other vehicles are not officially supported.

---

## Installation

1. Download the latest `.pak` file from the [Releases](../../releases) page.
2. Close SubwaySim 2 if it is currently running.
3. Open the following directory:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods
```

The complete path usually looks like this:

```text
C:\Users\YourName\Documents\My Games\SubwaySim2\Mods
```

4. Copy the downloaded `.pak` file directly into the `Mods` folder.
5. Start SubwaySim 2.

The installed file should look similar to this:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods\HK_Rollband_Mod_v1.pak
```

> [!NOTE]
> If the `Mods` folder does not exist, create it manually.

> [!WARNING]
> Do not extract or modify the `.pak` file.

---

## Opening the Editor

1. Start SubwaySim 2.
2. Load a scenario or timetable using the HK.
3. Wait until the vehicle has completely loaded.
4. Press **Ctrl + P**.
5. The **HK Rollband Editor** should now appear.

Click the **X button** in the upper-right corner to close the editor.

---

## Changing a Destination

1. Open the editor with **Ctrl + P**.
2. Under **„Station auswählen“**, select the station you want to modify.
3. Enter the new destination name under **„Neuer Anzeigename“**.
4. Click **„Ziel übernehmen“**.
5. The new destination will be transferred to the supported displays.

### Translation of the controls

| German interface | English meaning |
|---|---|
| Stationen umbenennen | Rename stations |
| Station auswählen | Select station |
| Neuer Anzeigename | New display name |
| Ziel übernehmen | Apply destination |

### Example

```text
Station auswählen: Wittenbergplatz
Neuer Anzeigename: Ruhleben
```

The selected station is the original destination that should be replaced.

---

## Changing a Line

1. Open the editor with **Ctrl + P**.
2. Under **„Bestehende Linie“**, select the line currently used by the train.
3. Under **„Neue Linie“**, select the line that should be displayed instead.
4. Click **„Linie übernehmen“**.
5. The selected line logo and colour will be transferred to the supported displays.

### Translation of the controls

| German interface | English meaning |
|---|---|
| Linienanzeige ändern | Change line display |
| Bestehende Linie | Existing line |
| Neue Linie | New line |
| Linie übernehmen | Apply line |

### Example

```text
Bestehende Linie: U1
Neue Linie: U12
```

> [!IMPORTANT]
> **„Bestehende Linie“** must match the line originally selected in the game. Otherwise, the replacement may not be applied correctly.

---

## Supported Displays

The mod can update the following displays:

- Front destination display
- HK interior passenger information displays
- Compatible station information displays
- Compatible DAISY displays

Some displays are refreshed regularly by the game. The mod may therefore reapply the selected line and destination automatically.

---

## Updating the Mod

1. Close SubwaySim 2.
2. Open the following directory:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods
```

3. Remove the old `HK_Rollband_Mod_v1.pak` file.
4. Download the latest version from the [Releases](../../releases) page.
5. Copy the new `.pak` file into the `Mods` folder.
6. Start SubwaySim 2.

> [!IMPORTANT]
> Do not keep multiple versions of the mod in the `Mods` folder at the same time.

---

## Uninstallation

1. Close SubwaySim 2.
2. Open the following directory:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods
```

3. Delete the `HK_Rollband_Mod_v1.pak` file.
4. Start SubwaySim 2 again.

No original game files are replaced during installation.

---

## Troubleshooting

### The editor does not open

- Make sure you are pressing **Ctrl + P**.
- Make sure an HK has been loaded.
- Check whether the `.pak` file is located directly inside the `Mods` folder.
- Make sure the file is not still inside a ZIP archive.
- Restart the game after installing the mod.

### The line does not change

- Make sure **„Bestehende Linie“** matches the line currently selected in the game.
- Click **„Linie übernehmen“** again.
- Wait a few seconds for all displays to refresh.

### The destination does not change

- Make sure a station has been selected.
- Make sure **„Neuer Anzeigename“** is not empty.
- Avoid extremely long destination names.
- Click **„Ziel übernehmen“** again.

### A display briefly shows the original value

SubwaySim 2 refreshes some displays automatically. The mod should reapply the custom line or destination shortly afterwards.

---

## Important Information

- The editor interface is currently available in German only.
- Custom lines only change the visual displays.
- The mod does not create new routes, tracks, timetables or announcements.
- Changes may be reset when the game or scenario is restarted.
- Game updates may temporarily break compatibility.
- The additional line numbers do not necessarily represent real BVG services.
- Other vehicles are currently not officially supported.

---

# 🇩🇪 Deutsch

## Voraussetzungen

- Eine funktionierende Installation von **SubwaySim 2**
- Das Fahrzeug **HK**
- Die aktuelle Version des **HK Rollband Editors**

> [!IMPORTANT]
> Die Mod wurde aktuell ausschließlich für den HK entwickelt. Andere Fahrzeuge werden nicht offiziell unterstützt.

---

## Installation

1. Lade die aktuelle `.pak`-Datei unter [Releases](../../releases) herunter.
2. Schließe SubwaySim 2, falls das Spiel gerade geöffnet ist.
3. Öffne folgendes Verzeichnis:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods
```

Der vollständige Pfad sieht normalerweise so aus:

```text
C:\Users\DeinName\Documents\My Games\SubwaySim2\Mods
```

4. Kopiere die heruntergeladene `.pak`-Datei direkt in den Ordner `Mods`.
5. Starte SubwaySim 2.

Die Datei sollte anschließend ungefähr hier liegen:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods\HK_Rollband_Mod_v1.pak
```

> [!NOTE]
> Falls der Ordner `Mods` nicht existiert, kannst du ihn manuell erstellen.

> [!WARNING]
> Die `.pak`-Datei darf nicht entpackt oder verändert werden.

---

## Editor öffnen

1. Starte SubwaySim 2.
2. Lade ein Szenario oder einen Fahrplan mit dem HK.
3. Warte, bis das Fahrzeug vollständig geladen wurde.
4. Drücke **Strg + P**.
5. Der **HK Rollband Editor** sollte nun erscheinen.

Über die Schaltfläche **X** oben rechts kannst du den Editor wieder schließen.

---

## Zielnamen ändern

1. Öffne den Editor mit **Strg + P**.
2. Wähle unter **Station auswählen** die Station aus, deren Anzeigename verändert werden soll.
3. Trage unter **Neuer Anzeigename** das gewünschte Ziel ein.
4. Klicke auf **Ziel übernehmen**.
5. Der neue Zielname wird auf die unterstützten Anzeigen übertragen.

### Beispiel

```text
Station auswählen: Wittenbergplatz
Neuer Anzeigename: Ruhleben
```

Die ausgewählte Station ist das ursprüngliche Ziel, das ersetzt werden soll.

---

## Linie ändern

1. Öffne den Editor mit **Strg + P**.
2. Wähle unter **Bestehende Linie** die aktuell vom Zug verwendete Linie aus.
3. Wähle unter **Neue Linie** die Linie aus, die stattdessen angezeigt werden soll.
4. Klicke auf **Linie übernehmen**.
5. Linienlogo und Linienfarbe werden auf die unterstützten Anzeigen übertragen.

### Beispiel

```text
Bestehende Linie: U1
Neue Linie: U12
```

> [!IMPORTANT]
> Unter **Bestehende Linie** muss die Linie ausgewählt werden, die ursprünglich im Spiel eingestellt wurde. Andernfalls kann die Ersetzung möglicherweise nicht korrekt angewendet werden.

---

## Unterstützte Anzeigen

Die Mod kann folgende Anzeigen aktualisieren:

- Zugzielanzeige an der Fahrzeugfront
- Fahrgastinformationsanzeigen im HK
- Kompatible Informationsanzeigen an Stationen
- Kompatible DAISY-Anzeigen

Einige Anzeigen werden vom Spiel regelmäßig aktualisiert. Die Mod kann die ausgewählte Linie und das eigene Ziel deshalb automatisch erneut anwenden.

---

## Mod aktualisieren

1. Schließe SubwaySim 2.
2. Öffne folgendes Verzeichnis:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods
```

3. Lösche die alte Datei `HK_Rollband_Mod_v1.pak`.
4. Lade die aktuelle Version unter [Releases](../../releases) herunter.
5. Kopiere die neue `.pak`-Datei in den Ordner `Mods`.
6. Starte SubwaySim 2.

> [!IMPORTANT]
> Es sollten sich nicht mehrere Versionen der Mod gleichzeitig im Ordner `Mods` befinden.

---

## Deinstallation

1. Schließe SubwaySim 2.
2. Öffne folgendes Verzeichnis:

```text
%USERPROFILE%\Documents\My Games\SubwaySim2\Mods
```

3. Lösche die Datei `HK_Rollband_Mod_v1.pak`.
4. Starte SubwaySim 2 erneut.

Bei der Installation werden keine originalen Spieldateien ersetzt.

---

## Fehlerbehebung

### Der Editor öffnet sich nicht

- Prüfe, ob du **Strg + P** drückst.
- Stelle sicher, dass ein HK geladen wurde.
- Prüfe, ob sich die `.pak`-Datei direkt im Ordner `Mods` befindet.
- Stelle sicher, dass die Datei nicht mehr in einem ZIP-Archiv liegt.
- Starte das Spiel nach der Installation vollständig neu.

### Die Linie wird nicht geändert

- Prüfe, ob **Bestehende Linie** mit der aktuell im Spiel eingestellten Linie übereinstimmt.
- Klicke erneut auf **Linie übernehmen**.
- Warte einige Sekunden, bis alle Anzeigen aktualisiert wurden.

### Der Zielname wird nicht geändert

- Stelle sicher, dass eine Station ausgewählt wurde.
- Das Feld **Neuer Anzeigename** darf nicht leer sein.
- Vermeide extrem lange Zielnamen.
- Klicke erneut auf **Ziel übernehmen**.

### Eine Anzeige zeigt kurzzeitig wieder den ursprünglichen Wert

SubwaySim 2 aktualisiert einige Anzeigen automatisch. Die Mod sollte die eigene Linie oder den eigenen Zielnamen kurz darauf erneut anwenden.

---

## Wichtige Hinweise

- Die Mod ist derzeit nur auf Deutsch verfügbar.
- Eigene Linien verändern ausschließlich die Darstellung auf den Anzeigen.
- Die Mod erstellt keine neuen Strecken, Gleise, Fahrpläne oder Ansagen.
- Änderungen können beim Neustart des Spiels oder Szenarios zurückgesetzt werden.
- Spielupdates können die Kompatibilität vorübergehend beeinträchtigen.
- Die zusätzlichen Liniennummern entsprechen nicht zwangsläufig realen Angeboten der BVG.
- Andere Fahrzeuge werden derzeit nicht offiziell unterstützt.
