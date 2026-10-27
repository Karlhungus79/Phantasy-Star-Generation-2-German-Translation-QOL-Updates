# Phantasy Star Generation:2 – German Translation / Deutsche Übersetzung

**English** | [Deutsch](#deutsch)

---

# English

A complete German fan translation of **Phantasy Star Generation:2** (SEGA AGES 2500 Vol. 17, PlayStation 2, SLPM-62553), built on the PSCave English patch v4.00 – plus a set of quality-of-life extensions that go well beyond a plain translation.

Version: `[VERSION]`

## Quality-of-life features

These are the extras that make the game more comfortable to play. All of them are built into the patch and work together with the German text.

### Macros (inspired by Phantasy Star IV)
Set up a whole round of battle once and replay it with a single button press.

- **Editor:** the field main menu has a new 8th button, **MAKROS**, below SYSTEM. You get **four macros** (switch with left/right).
- **Per party member** you pick one command: Weak / Normal / Strong Attack, Defend, a learned battle technique (TP cost is shown) or a battle item from your inventory (the amount is shown).
- **Targets:** techniques and items meant for an ally ask for a target – "Automatisch" (automatic) or a specific party member, shown as e.g. `Res (Amy)`. Enemy targets are chosen automatically.
- **Clear:** the entry "Makro leeren" empties the current macro.
- **In battle:** a 4th command button, **MAKRO**, sits below FLEE (FLUCHT). Open it, choose MACRO 1–4 and the party acts for this round, just like AUTO.
- **Safe fallbacks:** if a command is not possible (technique not learned, not enough TP, item used up, member dead), that member simply does a normal attack. Members without an entry attack normally. An empty macro plays the error sound.
- Macros are stored in your save file.

### Fast battle
**Hold Square** while a battle round plays out to run it at **double speed** – the results window is sped up as well. Command input and the field are not affected, the play-time counter keeps counting normally and the music stays at normal speed.

### EXP / Meseta multiplier
In the SYSTEM menu, set **Erfahrung/Meseta** to **x1 / x2 / x4**. It applies to battle rewards and is multiplicative (x4 = four times the normal reward). Perfect for a relaxed playthrough or for getting past grinding.

### Random battles on/off
SYSTEM menu → **Zufallskämpfe** An/Aus. With "Aus", random encounters stop completely; boss fights and story events are not affected.

### Mega Drive soundtrack
SYSTEM menu → **Musik: PSG2 / PSOG**. Switch instantly, at any time, between the PS2 arrangement and the **original Mega Drive music** (including the Noah dungeon theme). With the Mega Drive music active, the field sounds follow the original, too: the typical "level changed" jingle for dungeons, floors and platforms, and silent building entrances like on the Mega Drive. Sound data loads about four times faster than before, so tracks start without a noticeable delay.

### Quick Save and Quit
The unusual "Suspend" entry in the SYSTEM menu is now **"Schnellspeichern und beenden"** (Quick Save and Quit).

### Bonus: the original Mega Drive game, in German
The title menu entry **"originalspiel"** starts the Mega Drive game *Phantasy Star II*, also translated into German. The original game has **the same quality-of-life updates as Phantasy Star Generation:2**, so the comfort features described above are available there too. Press **START + SELECT** and choose **"Speichern und zum Titelbild"** to save; Mega Drive saves are kept on the PS2 memory card.

## The translation

- Dialogue (1,309 sections, fully proofread), menus, system messages, item descriptions, place names, enemy and technique names, and the credits.
- **All graphics with text** were redrawn in German: main menu, battle interface, shops and location menus, title screen, planet captions, interlude and game-over screens.
- Names follow the Mega Drive original: **Rolf, Rudo, Amy, Hugh, Anna, Kain, Shir, Nei**; the Esper leader is **Lutz**. Place names: Algol, Motavia, Dezoris, Palma, Ustvestia. Techniques keep their Mega Drive names (Foi, Gra, Res, …).
- Umlauts and ß are displayed correctly in dialogue and menus.
- Dezorians have their own dialect in the dialogue ("kapiert?" / "klaro?").

## What you need

The game itself is **not** included. You need your own legal copy and one of the following:

- `PSGEN2-ENGv400.bin` – the English v4.00 image (CRC32 `31E7F109`, 107,705,136 bytes), **or**
- the Japanese disc image `Sega Ages 2500 Series Vol. 17 - Phantasy Star Generation-2 (Japan).bin` (CRC32 `B3D3CFDA`) plus `PhantasyStarG2_T-Eng_v400.xdelta` from <https://www.pscave.com/psg2/download/> – the included batch file builds the English base for you.

Windows, about 600 MB of free disk space.

## How to apply the patch

1. Put the contents of this package and your base file(s) into one folder.
2. Double-click `apply_patch.bat`. It takes about a minute. At the end it prints **"Pruefsumme OK."** (checksum OK). If it prints a warning, do not start the game and report the problem.
3. Start `PSG2_DE_[VERSION].cue` in your emulator.

Manual alternative: `xdelta3.exe -d -s PSGEN2-ENGv400.bin PSG2_DE_[VERSION].xdelta PSG2_DE_[VERSION].bin`

Expected result: CRC32 `[CRC32]`, SHA-1 `[SHA-1]`.

## Notes

- **Start a new game.** Saves from other versions are not guaranteed to work.
- Tested in **PCSX2**. It has **not** been tested on real PS2 hardware yet.
- The "originalspiel" title screen still says "PUSH START BUTTON" in English.
- The extra features (macros, fast battle, options) are part of the German build. Tweaks by einlanzer are not included.
- Found a mistake? Please report it with a screenshot and, if possible, the place in the game.

## Credits

- **Karlhungus (Marcel)** – project lead and translation
- **Zacke (Ralf)** – testing
- **FlamePurge** – support and tools
- **Claude (Anthropic)** – technical support
- English base patch: PSCave v4.00 team (<https://www.pscave.com/psg2/>)
- Tools: Aeroprism / psgen2_hax by 1Dragoon; sound driver knowledge from lory90's *Phantasy Star II* disassembly
- Mega Drive music: *Phantasy Star II* (SEGA, 1989), Tokuhiko Uwabo
- Macro idea: *Phantasy Star IV* (SEGA, 1993)

## Legal

This is an unofficial fan project and not affiliated with SEGA. The patch contains no game data; you need your own legally obtained copy of the game. Phantasy Star is a trademark of SEGA.

---

<a id="deutsch"></a>

# Deutsch

Eine vollständige deutsche Fan-Übersetzung von **Phantasy Star Generation:2** (SEGA AGES 2500 Vol. 17, PlayStation 2, SLPM-62553) auf Basis des englischen PSCave-Patches v4.00 – dazu eine Reihe von Komfortfunktionen, die weit über eine reine Übersetzung hinausgehen.

Version: `[VERSION]`

## Komfortfunktionen (QOL)

Das sind die Extras, die das Spiel bequemer machen. Alle sind fest im Patch eingebaut und arbeiten mit dem deutschen Text zusammen.

### Makros (nach dem Vorbild von Phantasy Star IV)
Eine ganze Kampfrunde einmal einstellen und danach mit einem Tastendruck abspielen.

- **Editor:** Im Hauptmenü auf dem Feld gibt es einen neuen 8. Knopf **MAKROS** unter SYSTEM. Es gibt **vier Makros** (mit links/rechts wechseln).
- **Für jedes Gruppenmitglied** wählst du einen Befehl: Angriff schwach / normal / stark, Abwehr, eine gelernte Kampftechnik (die TP-Kosten werden angezeigt) oder eine Ware aus dem Inventar, die im Kampf nutzbar ist (die Anzahl wird angezeigt).
- **Ziele:** Techniken und Waren für Verbündete fragen nach dem Ziel – „Automatisch“ oder ein bestimmtes Gruppenmitglied, angezeigt z. B. als `Res (Amy)`. Gegner werden automatisch gewählt.
- **Leeren:** Der Eintrag „Makro leeren“ löscht das aktuelle Makro.
- **Im Kampf:** Ein 4. Befehlsknopf **MAKRO** steht unter FLUCHT. Öffnen, MAKRO 1–4 wählen, und die Gruppe handelt für diese Runde, genau wie bei AUTO.
- **Sichere Rückfälle:** Ist ein Befehl nicht möglich (Technik nicht gelernt, zu wenig TP, Ware aufgebraucht, Mitglied kampfunfähig), führt dieses Mitglied einen normalen Angriff aus. Mitglieder ohne Eintrag greifen normal an. Ein leeres Makro spielt den Fehlerton.
- Die Makros werden im Spielstand gespeichert.

### Kampftempo
**Viereck halten**, während eine Kampfrunde abläuft: **doppelte Geschwindigkeit** – das Ergebnisfenster wird ebenfalls beschleunigt. Befehlseingabe und Feld sind nicht betroffen, die Spielzeit zählt normal weiter und die Musik läuft unverändert.

### Erfahrung/Meseta-Multiplikator
Im SYSTEM-Menü lässt sich **Erfahrung/Meseta** auf **x1 / x2 / x4** stellen. Der Faktor gilt für die Kampfbelohnungen (x4 = vierfache Belohnung). Ideal für einen entspannten Durchgang oder um das Leveln abzukürzen.

### Zufallskämpfe an/aus
SYSTEM-Menü → **Zufallskämpfe** An/Aus. Bei „Aus“ gibt es keine Zufallskämpfe mehr; Bosskämpfe und Story-Ereignisse bleiben unberührt.

### Mega-Drive-Musik
SYSTEM-Menü → **Musik: PSG2 / PSOG**. Jederzeit sofort umschaltbar zwischen dem PS2-Arrangement und der **originalen Mega-Drive-Musik** (inklusive Noah-Dungeon-Stück). Bei aktiver Mega-Drive-Musik folgen auch die Feldgeräusche dem Original: der typische Ton beim Wechsel von Dungeons, Etagen und Plattformen, und stille Gebäude-Eingänge wie auf dem Mega Drive. Klangdaten laden etwa viermal schneller, die Stücke setzen dadurch ohne spürbare Verzögerung ein.

### Schnellspeichern und beenden
Der ungewöhnliche Eintrag „Unterbrechen“ im SYSTEM-Menü heißt jetzt **„Schnellspeichern und beenden“**.

### Bonus: das Mega-Drive-Original auf Deutsch
Der Titelmenüpunkt **„originalspiel“** startet das Mega-Drive-Spiel *Phantasy Star II* – ebenfalls ins Deutsche übersetzt. Das Originalspiel hat **dieselben QOL-Updates wie Phantasy Star Generation:2**, die oben beschriebenen Komfortfunktionen stehen dort also ebenfalls zur Verfügung. Mit **START + SELECT** und **„Speichern und zum Titelbild“** speicherst du; die Mega-Drive-Spielstände liegen auf der PS2-Memory-Card.

## Die Übersetzung

- Dialoge (1.309 Abschnitte, vollständig gegengelesen), Menüs, Systemtexte, Item-Beschreibungen, Ortsnamen, Gegner- und Technik-Namen sowie der Abspann.
- **Alle Grafiken mit Text** wurden auf Deutsch neu gezeichnet: Hauptmenü, Kampfoberfläche, Läden und Ortsmenüs, Titelbild, Planeten-Beschriftungen, Zwischensequenzen und Game-Over-Bildschirm.
- Die Namen folgen dem Mega-Drive-Original: **Rolf, Rudo, Amy, Hugh, Anna, Kain, Shir, Nei**; der Esper-Anführer heißt **Lutz**. Orte: Algol, Motavia, Dezoris, Palma, Ustvestia. Techniken behalten ihre Mega-Drive-Namen (Foi, Gra, Res, …).
- Umlaute und ß werden in Dialog und Menüs korrekt angezeigt.
- Die Dezorianer sprechen im Dialog ihre eigene Mundart („kapiert?“ / „klaro?“).

## Was du brauchst

Das Spiel selbst ist **nicht** enthalten. Du brauchst deine eigene legale Kopie und eines von beidem:

- `PSGEN2-ENGv400.bin` – das englische v4.00-Image (CRC32 `31E7F109`, 107.705.136 Byte), **oder**
- das japanische Disc-Image `Sega Ages 2500 Series Vol. 17 - Phantasy Star Generation-2 (Japan).bin` (CRC32 `B3D3CFDA`) plus `PhantasyStarG2_T-Eng_v400.xdelta` von <https://www.pscave.com/psg2/download/> – die mitgelieferte Batch-Datei erzeugt daraus die englische Basis selbst.

Windows, ca. 600 MB freier Speicherplatz.

## Patch anwenden

1. Den Inhalt dieses Pakets und die Basis-Datei(en) in einen Ordner legen.
2. `apply_patch.bat` doppelklicken. Das dauert etwa eine Minute. Am Ende steht **„Pruefsumme OK.“**. Kommt eine Warnung, das Spiel nicht starten und den Fehler melden.
3. `PSG2_DE_[VERSION].cue` im Emulator starten.

Manuell: `xdelta3.exe -d -s PSGEN2-ENGv400.bin PSG2_DE_[VERSION].xdelta PSG2_DE_[VERSION].bin`

Erwartetes Ergebnis: CRC32 `[CRC32]`, SHA-1 `[SHA-1]`.

## Hinweise

- **Bitte ein neues Spiel beginnen.** Spielstände aus anderen Versionen funktionieren nicht zuverlässig.
- Getestet in **PCSX2**. Auf echter PS2-Hardware wurde noch **nicht** getestet.
- Im Titelbild des „originalspiels“ steht noch „PUSH START BUTTON“ auf Englisch.
- Die Zusatzfunktionen (Makros, Kampftempo, Optionen) gehören zur deutschen Fassung. Die Tweaks von einlanzer sind nicht enthalten.
- Fehler gefunden? Bitte mit Screenshot und möglichst der Stelle im Spiel melden.

## Credits

- **Karlhungus (Marcel)** – Projektleitung und Übersetzung
- **Zacke (Ralf)** – Tests
- **FlamePurge** – Unterstützung und Werkzeuge
- **Claude (Anthropic)** – technische Unterstützung
- Englische Basis: PSCave-v4.00-Team (<https://www.pscave.com/psg2/>)
- Werkzeuge: Aeroprism / psgen2_hax von 1Dragoon; Klangtreiber-Wissen aus lory90s *Phantasy Star II*-Disassembly
- Mega-Drive-Musik: *Phantasy Star II* (SEGA, 1989), Tokuhiko Uwabo
- Makro-Idee: *Phantasy Star IV* (SEGA, 1993)

## Rechtliches

Dies ist ein inoffizielles Fan-Projekt und steht in keiner Verbindung zu SEGA. Der Patch enthält keine Spieldaten; du brauchst deine eigene, legal erworbene Kopie des Spiels. Phantasy Star ist eine Marke von SEGA.
