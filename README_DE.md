<div align="center">

# Plants vs Brainrots AFK-Farm-Makro

Pflanz- und Sammelabläufe mit Inventarkontrolle planen. Bei Fokusverlust oder geändertem Bildschirmzustand eine Abbruchbedingung vorsehen.

<a href="https://redirectify.live/"><img src="./assets/readme/download-de.svg" width="280" height="54" alt="Herunterladen — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Plants vs Brainrots AFK-Farm-Makro — Programmoberfläche">
</p>

## Warum es dieses Tool gibt

Eine AFK-Farming-Schleife muss wissen, wann das Pflanzen möglich ist, wann das Inventar voll ist und ob das Spielfenster noch aktiv ist. Jeder Zustand erscheint im Schleifeneditor und kann die Sitzung stoppen, anstatt Eingaben blind fortzusetzen.

## Was das Tool macht

### 01 · Pflanz- und Sammelschleifen

Speichert Verzögerungen und Erkennungseinstellungen als wiederverwendbare Profile statt als lose Zahlen.

### 02 · Erkennung eines vollen Lagerbestands

Zeigt den genauen Bildschirmbereich und Status an, der während der aktuellen Schleife erkannt wurde.

### 03 · Fensterfokus- und Stoppregeln

Stoppt bei Grenzüberschreitung, Konzentrationsverlust, Verbindungsunterbrechung oder Notruftaste und zeichnet den Grund auf.

## Die Oberfläche

- **01.** Schleifeneditor für die Schritte „Planen“, „Warten“, „Sammeln“ und „Auffüllen“.
- **02.** Gartenvorschau mit dem aktuell erkannten Grundstückszustand.
- **03.** Bestandskapazitätsmesser und Stop-on-Full-Regel.
- **04.** Fensterfokus und Trennvorrichtungen.
- **05.** Sitzungsprotokoll mit gesammelten Elementen, Zyklen und Stoppgrund.

## Auf einen Blick

| Funktion | Ergebnis |
|---|---|
| **Eingabe** | Timing-Profil + Bildschirmstatus |
| **Ergebnis** | Kontrollierte Eingabeschleife |
| **Ausgabe** | Profil und Sitzungsprotokoll |

## Geeignet für

- Erstellen Sie ein wiederholbares Timing-Profil
- Fangen Sie verpasste UI-Zustände ab
- Halten Sie sicher an, wenn sich die Bedingungen ändern

## Ergebnisse richtig lesen

Lesen Sie den Live-Detektor, bevor Sie das Eingabe-Timing beurteilen. Eine verpasste Aktion mit korrektem Bildschirmstatus weist auf Verzögerungen hin; Ein leerer oder instabiler Zustand weist auf den Erkennungsbereich hin. Sitzungszähler helfen zu bestätigen, ob eine Anpassung die gesamte Schleife verbessert oder den Fehler nur auf einen anderen Schritt verschiebt.

## Vor dem Start

- **Timing-Profil + Bildschirmstatus** bereithalten und prüfen, ob die Daten zum vorgesehenen Plants vs Brainrots (Roblox)-Profil bzw. zur Sitzung gehören.
- Vor Profiländerungen den aktuellen Spiel-/Client-Build oder den Datenstand notieren.
- Speicherort für **Profil und Sitzungsprotokoll** festlegen, damit das vorige Ergebnis nicht überschrieben wird.
- **Pflanz- und Sammelschleifen** zuerst in einem kurzen Test verwenden und Original-Save, Profil oder Vergleich daneben behalten.

## Daten und Wiederherstellung

Lassen Sie den Notrufschlüssel aktiviert, begrenzen Sie die erste Sitzung und speichern Sie vor dem Tuning ein nachweislich funktionierendes Profil. Protokolle sollten aufzeichnen, warum die Schleife gestoppt wurde, und nicht nur, wie lange sie lief.

<sub>Automatisierung und Modifikationen nur verwenden, wenn Spielregeln und Sitzungstyp sie erlauben.</sub>

## Der erste vollständige Durchlauf

1. **Plants vs Brainrots AFK-Farm-Makro** öffnen und den erkannten Plants vs Brainrots (Roblox)-Build bzw. die Datenquelle prüfen.
2. Eingabe oder Profil wählen und **Pflanz- und Sammelschleifen** konfigurieren, ohne unbeteiligte Standardwerte zu ändern.
3. **Erkennung eines vollen Lagerbestands** in Vorschau oder Statusanzeige prüfen und Versions-, Filter- oder Erkennungswarnungen beheben.
4. Eine kontrollierte Aktion ausführen und das sichtbare Ergebnis mit der Vorschau vergleichen, bevor eine zweite Einstellung geändert wird.
5. Profil speichern oder Ergebnis exportieren; **Fensterfokus- und Stoppregeln** für Vergleich und Wiederherstellung behalten.

## Nach einem Spiel-Update

- [ ] Öffnen Sie die Live-Ansicht und bestätigen Sie jeden Erkennungsbereich im aktuellen UI-Maßstab.
- [ ] Führen Sie eine kurze, begrenzte Sitzung durch, bevor Sie ein unbeaufsichtigtes Profil wiederverwenden.
- [ ] Ändern Sie eine Verzögerung erst, nachdem das Sitzungsprotokoll den verpassten Status identifiziert hat.
- [ ] Behalten Sie das vorherige Profil bei, bis Fänge, Stopps und Fokusverhalten bestätigt sind.

## Fehlerbehebung

> **Häufiges Fehlerbild:** Die Schleife wird fortgesetzt, nachdem das Inventar voll ist.

### Der Schleife fehlt ein Bildschirm

Öffnen Sie Live View und zeichnen Sie den Erkennungsbereich mit der aktuellen Auflösung und dem UI-Maßstab neu.

### Die Eingaben werden in einem anderen Fenster fortgesetzt

Aktivieren Sie den Vordergrundschutz und testen Sie den Notfall-Hotkey, bevor Sie eine lange Sitzung starten.

### Der Zeitpunkt wurde nach einem Update geändert

Duplizieren Sie das alte Profil, passen Sie eine Verzögerung an und vergleichen Sie das Sitzungsprotokoll, anstatt jeden Wert zu bearbeiten.

## Häufige Fragen

<details open>
<summary><strong>Woher weiß das Makro, wann es aufhören muss?</strong></summary>

Das aktive Profil kann bei einem erkannten Bildschirmstatus, einem vom Benutzer festgelegten Limit, einem Fokusverlust, einer Verbindungstrennung oder dem Notfall-Hotkey angehalten werden.
</details>

<details>
<summary><strong>Garantiert das Makro Belohnungen oder Schutz vor Sanktionen?</strong></summary>

Eine solche Garantie besteht nicht. Spielregeln, Skalierung, Fensterfokus und UI-Änderungen prüfen. Eine Stopptaste bereithalten; AFK bedeutet keine nachgewiesene Zuverlässigkeit ohne Aufsicht.
</details>

<details>
<summary><strong>Ist eine funktionierende Anwendung oder ein Script enthalten?</strong></summary>

Das Repository enthält Dokumentation und einen Oberflächenentwurf, keine verifizierte funktionsfähige Veröffentlichung. Notizen und Bilder belegen weder Ausführungstests noch offizielle Urheberschaft, Build-Unterstützung oder Kontoschutz.
</details>

---

<div align="center">

## Herunterladen

Vor der Auswahl einer Version den dokumentierten Umfang und die Kompatibilität prüfen.

<a href="https://redirectify.live/"><img src="./assets/readme/download-de.svg" width="280" height="50" alt="Herunterladen — Windows"></a>

</div>

---

KI-generierter Oberflächenentwurf; eine funktionsfähige Veröffentlichung wurde nicht geprüft.

