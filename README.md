<div align="center">

  # 🚀 G2ModManager

  **Mod Manager zum verwalten/installieren von Mods für Gothic 2 und Gothic 2: Die Nacht des Raben.**

   [![VirusTotal](https://img.shields.io/badge/VirusTotal-Scan_Result-brightgreen?style=for-the-badge&logo=virustotal)](https://www.virustotal.com/gui/file/4ddd2712eea989d5f0ae130295a7e5177f710c59f87c9bb9d40299c0cedbedb7?nocache=1)

  <br />

  <img width="1600" height="980" alt="g2mmprofil" src="https://github.com/user-attachments/assets/cba271f5-1a5e-4a8f-89c2-025444711862" />




  </a>

</div>

---

## 📦 Installation

1. Unter Releases/Assets die letzte Version herunterladen.
2. ZIP Datei auf den Computer entpacken.
3. Rechtsklick auf G2ModManager.exe und Senden an Desktop zum erstellen einer Verknüpfung.
4. Erneut Rechtsklick auf die Verknüpfung, und unter Kompatibilität , Als Administrator ausführen wählen, übernehmen und ok klicken.

🖥️ **<u>Microsoft .Net Framework 10 Runtime benötigt zum starten</u>** [Download](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)<br>
<img width="412" height="570" alt="g2mm-admin" src="https://github.com/user-attachments/assets/f9367a8b-b971-42d3-bf5f-fbbb1c98fa9b" />


---

## 🎮 Benutzung/Beschreibung

Der Mod Manager selbst versucht beim start bereits installierte Mods zu erkennen, optimalerweise sollten alte Mods entfernt werden
und dann alles direkt im Manager über dem Mods Tab, installiert werden mit dem "Mod installieren" Button, damit alles zuverlässig erkannt wird.
Erkannt werden Mods direkt als .vdf Datei, innerhalb einer ZIP Datei und auch große installationen per .exe Datei können, über den Manager
über den selbigen Button installiert werden um somit als ein Mod erkannt zu werden.

Erkannt werden 3 Arten von Mods derzeit, der normale Mod selbst, ein Feature-Patch und Union-Plugin.
Feature-Patches sind Mods die Ninja benötigen, und Union-Plugins Union.

Für Mod-Creator kann eine textdatei beigelegt werden Namens "mod.txt"
Die folgende Argumente beinhalten kann
```
name=
type=
requirement=
compatible=
notcompatible=
```
Als Name kann dort der Modname angegeben werden, worunter er gelistet sein soll im Mod Manager.
Type kann die Werte: Mod, Feature-Patch oder Union-Plugin enthalten, dessen funktion oben beschrieben.
Requirement kann zb eingetragen werden wenn Ninja benötigt wird mit ninja, oder union für Union.
Compatible/notcompatible können Mod Namen eingetragen werden von anderen Mods die kompatibel oder nicht kompatibel sind,
wodurch im Manager eine Nachricht kommt falls etwas davon aktiviert ist,
Also hat zb ein anderer Mod den Namen Test1234 eingetragen als Modname in der mod.txt dann, kann man den Namen zb in notcompatible eintragen

Momentan können noch Fehler auftreten, welche ich bitte im Issues Tab so detailliert wie möglich auf meinem Github hier zu berichten.
UI ist derzeit Platzhalter und wird noch im laufe überarbeitet wenn dass ganze Programm stabil läuft.
Der Datenbank Tab wird an einem späteren Zeitpunkt aktiviert, um von dort direkt Mods herunterzuladen.
Dateien wie dass Systempack, Ninja etc werden von den offiziellen Github Seiten und oder von worldofgothic.de geladen, Credits weiter unten.

---

## ⚖️ Rechtliches/Info

(Coding mit KI Hilfe vorgenommen)<br>
Mein Programm ist in keiner Art und Weise mit Piranha Bytes, Gothic 2 oder deren Entwickler/Publisher verknüpft.<br>
Es werden keine Daten gesammelt und oder gespeichert.<br>
Der Mod Manager enthält keine bösartige Software/Viren oder sonstige Arten von exploits, oder schädlicher Software.<br>
Die Installation von Fixes/Patches/Tools oder Mods erfolgt auf eigene Gefahr, ich hafte für keine schäden an der Gothic 2 installation.<br>

## ©️ Credits

G2-Fix: https://www.worldofgothic.de/dl/download_278.htm<br>
Playerkit/Systempack: https://github.com/GothicFixTeam/GothicFix/releases<br>
GD3D11 Renderer: https://github.com/SaiyansKing/GD3D11/releases<br>
Ninja: https://github.com/szapp/Ninja/releases<br>
Toolkit: https://github.com/szapp/Toolkit<br>
Union: https://www.worldofgothic.de/dl/download_651.htm<br>
GRawInput: https://github.com/SaiyansKing/GRawInput/releases<br>

---
