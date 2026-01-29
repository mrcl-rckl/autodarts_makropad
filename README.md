<div align="center">
  <h1>🎯 Autodarts Macropad</h1>
  <p><b>✨ The ultimate DIY wireless companion for your Autodarts setup ✨</b></p>
  <p><i>A custom 12-key controller designed for seamless darts tracking.</i></p>

  <p>
    <img src="https://img.shields.io/badge/Difficulty-Experienced_Makers-orange.svg?style=for-the-badge&logo=buildkite" alt="Difficulty" />
    <img src="https://img.shields.io/badge/Hardware-nRF52840-lightgrey.svg?style=for-the-badge&logo=nordicsemiconductor" alt="Hardware" />
    <img src="https://img.shields.io/badge/Firmware-ZMK-blue.svg?style=for-the-badge&logo=github" alt="Firmware" />
  </p>

  <p>
    <a href="#manual-en">📖 Manual</a> •
    <a href="#diagrams-en">🗺️ Wiring & Pinout</a> •
    <a href="#keymap-en">🎹 Keymap</a> •
    <a href="#bom-en">📦 BOM</a> •
    <a href="#support-en">☕ Support</a>
  </p>
</div>

<hr />

<h2 id="manual-en">📖 Comprehensive Manual</h2>
<blockquote>
  This repository includes a <b>detailed 33-page PDF instruction manual</b>. It covers the entire process: from optimized 3D printing settings and complex matrix soldering to flashing the ZMK firmware and customized key mapping.
</blockquote>

<hr />

<h2 id="bom-en">📦 Bill of Materials (BOM)</h2>
<p>This project is designed for experienced makers and involves 3D printing, component assembly, and precision soldering.</p>
<table>
  <thead>
    <tr>
      <th>Quantity</th>
      <th>Component 🛒</th>
      <th>Source 🔗</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>12x</td>
      <td><b>Gateron G Pro 3.0 Switches</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007052507996.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>nRF52840 Developer Board (SuperMini)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005008664621573.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>500mAh LiPo Battery (503030)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005009836119485.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>12x</td>
      <td><b>1N4148 Diodes</b></td>
      <td><a href="https://de.aliexpress.com/item/1005006208000285.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>16x</td>
      <td><b>Jumper Wires Female (20-30cm)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007046465880.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>Toggle Switch (MTS-101)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005005942183255.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>ASUS USB-BT500 Bluetooth Dongle</b></td>
      <td><a href="https://www.cyberport.de/pc-und-zubehoer/netzwerk/bluetooth/asus/pdp/4e18-007/asus-usb-bt500-bluetooth-5-0-usb-adapter.html">Cyberport</a></td>
    </tr>
  </tbody>
</table>

<h3>🛠️ Required Tools & Additional Materials</h3>
<ul>
  <li>USB-C charging cable</li>
  <li>Soldering iron & Solder wire</li>
  <li>Hot air gun or lighter (for insulation)</li>
  <li>Heat shrinks & side cutters</li>
  <li>Pliers & wire stripping tool</li>
  <li>Super glue (for mounting logos)</li>
  <li>Filament (PLA or PETG - 2 different colors recommended for contrast)</li>
</ul>

<hr />

<h2 id="diagrams-en">🗺️ Wiring Diagram & Pinout</h2>
<div align="center">
  <h3>🛠️ Wiring Diagram</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Wiring_Diagram.png?raw=true" alt="Wiring Diagram" width="800">
  <br><br>
  <h3>🔌 Controller Pinout</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Pin_Diagram.png?raw=true" alt="Pin Diagram" width="800">
</div>

<hr />

<h2 id="keymap-en">🎹 Default Key Assignment</h2>
<p>The layout is fully optimized for the Autodarts web interface, allowing focus on the game without reaching for a mouse.</p>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Key_Assignment.png?raw=true" alt="Keymap Assignment" width="800">
</div>

<br>

<table>
  <thead>
    <tr>
      <th>Row</th>
      <th>Left ⬅️</th>
      <th>Middle ⬆️</th>
      <th>Right ➡️</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Row 1</b></td>
      <td>Start/Stop Board (S)</td>
      <td>Reset Board (R)</td>
      <td>Reload Webpage (F5)</td>
    </tr>
    <tr>
      <td><b>Row 2</b></td>
      <td>Undo Throw (Backspace)</td>
      <td>Call AI Referee (A)</td>
      <td>Next Throw (Enter)</td>
    </tr>
    <tr>
      <td><b>Row 3</b></td>
      <td><i>Free for Updates</i></td>
      <td>Cancel "Removing Darts" (Click)</td>
      <td>Toggle Fullscreen (F11)</td>
    </tr>
    <tr>
      <td><b>Row 4</b></td>
      <td>Switch Camera 1 (Key 1)</td>
      <td>Switch Camera 2 (Key 2)</td>
      <td>Switch Camera 3 (Key 3)</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="support-en">☕ Support</h2>
<p align="left">
  If this project helped you hit the bullseye, consider supporting my work! Every coffee helps fund new prototypes and open-source tools. 🎯☕
  <br><br>
  <a href="https://www.buymeacoffee.com/mrcl_rckl">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="Buy Me A Coffee" />
  </a>
</p>

<br><br>
<div style="height: 15px; background: linear-gradient(90deg, #444 0%, #888 50%, #444 100%); border-radius: 8px; margin: 50px 0;"></div>
<br><br>

<div align="center">
  <h1>🎯 Autodarts Zusatztastatur</h1>
  <p><b>✨ Der ultimative kabellose Begleiter für dein Autodarts-Setup – Marke Eigenbau ✨</b></p>
  <p><i>Ein maßgeschneidertes 12-Tasten-Steuergerät für die professionelle Wurferfassung am Oche.</i></p>
</div>

<hr />

<h2>📖 Umfangreiche Anleitung</h2>
<blockquote>
  In diesem Repository findest du eine <b>detaillierte 33-seitige PDF-Anleitung</b>. Diese führt dich Schritt für Schritt durch den gesamten Prozess: von den optimalen Einstellungen für den 3D-Druck über das präzise Verlöten der Tastatur-Matrix bis hin zur Installation der Steuersoftware und der persönlichen Tastenbelegung.
</blockquote>

<hr />

<h2>🚀 Hauptmerkmale</h2>
<ul>
  <li><b>📶 Vollkommen Kabellos:</b> Dank Bluetooth 5.0 und dem nRF52840-Steuermodul bleibt dein Abwurfbereich frei von Kabeln. 🎯</li>
  <li><b>🔋 Enorme Akkulaufzeit:</b> Eine einzige Ladung hält bei normaler Nutzung bis zu <b>6 Wochen</b>. Der integrierte Tiefschlafmodus schont die Batterie zusätzlich. ⚡</li>
  <li><b>⌨️ Hochwertiger Druckpunkt:</b> 12 mechanische Gateron G Pro 3.0 Schalter bieten ein erstklassiges haptisches Feedback und garantieren eine zuverlässige Bedienung. ⌨️</li>
  <li><b>☁️ Cloud-Konfiguration:</b> Die Tastenbelegung kann direkt im Browser über GitHub-Automatisierungen angepasst werden – es ist keine lokale Programmierumgebung erforderlich. ☁️</li>
  <li><b>🖥️ System-Integration:</b> Der Akkustand wird direkt in den Einstellungen von Windows oder Linux angezeigt. 🖥️</li>
</ul>

<hr />

<h2>📦 Stückliste</h2>
<p>Dieses Projekt wird für erfahrene Bastler empfohlen, da es fundierte Kenntnisse im 3D-Druck und im Weichlöten voraussetzt. 🛠️</p>
<table>
  <thead>
    <tr>
      <th>Menge</th>
      <th>Bauteil 🛒</th>
      <th>Bezugsquelle 🔗</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>12x</td>
      <td><b>Gateron G Pro 3.0 Tastenschalter</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007052507996.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>nRF52840 Entwickler-Platine (SuperMini)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005008664621573.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>500mAh LiPo Akku (Bauform 503030)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005009836119485.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>12x</td>
      <td><b>1N4148 Dioden</b></td>
      <td><a href="https://de.aliexpress.com/item/1005006208000285.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>16x</td>
      <td><b>Steckbrückenkabel (weiblich, 20-30cm)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007046465880.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>Kippschalter (MTS-101)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005005942183255.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>ASUS USB-BT500 Bluetooth-Adapter</b></td>
      <td><a href="https://www.cyberport.de/pc-und-zubehoer/netzwerk/bluetooth/asus/pdp/4e18-007/asus-usb-bt500-bluetooth-5-0-usb-adapter.html">Cyberport</a></td>
    </tr>
  </tbody>
</table>

<h3>🛠️ Erforderliche Werkzeuge & Materialien</h3>
<ul>
  <li>USB-C Ladekabel</li>
  <li>Lötkolben & Lötzinn</li>
  <li>Heißluftfön oder Feuerzeug (für die Isolierung der Kontakte)</li>
  <li>Schrumpfschläuche & Seitenschneider</li>
  <li>Zange & Abisolierwerkzeug</li>
  <li>Sekundenkleber (zum Fixieren der Logos)</li>
  <li>Filament (PLA oder PETG - 2 verschiedene Farben für einen kontrastreichen Look empfohlen)</li>
</ul>

<hr />

<h2>🗺️ Stromlaufplan & Anschlussbelegung</h2>
<div align="center">
  <h3>🛠️ Schaltplan der Tastatur-Matrix</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Wiring_Diagram.png?raw=true" alt="Stromlaufplan" width="800">
  <br><br>
  <h3>🔌 Anschlussbelegung des Steuerungsmoduls</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Pin_Diagram.png?raw=true" alt="Anschlussbelegung" width="800">
</div>

<hr />

<h2>🎹 Standard-Tastenbelegung</h2>
<p>Die Tasten sind für die Autodarts-Weboberfläche optimiert, damit du dich voll auf deine Würfe konzentrieren kannst. 🎯</p>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Key_Assignment.png?raw=true" alt="Tastenbelegung" width="800">
</div>

<br>

<table>
  <thead>
    <tr>
      <th>Reihe</th>
      <th>Links ⬅️</th>
      <th>Mitte ⬆️</th>
      <th>Rechts ➡️</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Reihe 1</b></td>
      <td>Board Start/Stop (S)</td>
      <td>Board zurücksetzen (R)</td>
      <td>Webseite neu laden (F5)</td>
    </tr>
    <tr>
      <td><b>Reihe 2</b></td>
      <td>Wurf rückgängig (Rücktaste)</td>
      <td>KI-Schiedsrichter rufen (A)</td>
      <td>Nächster Wurf (Eingabe)</td>
    </tr>
    <tr>
      <td><b>Reihe 3</b></td>
      <td><i>Frei für Erweiterungen</i></td>
      <td>"Darts entfernen" Abbruch (Linksklick)</td>
      <td>Vollbild umschalten (F11)</td>
    </tr>
    <tr>
      <td><b>Reihe 4</b></td>
      <td>Kamera 1 (Taste 1)</td>
      <td>Kamera 2 (Taste 2)</td>
      <td>Kamera 3 (Taste 3)</td>
    </tr>
  </tbody>
</table>

<hr />

<h2>💡 Bedienung & Fehlerbehebung</h2>
<ul>
  <li><b>Ladevorgang:</b> Der physische Kippschalter <b>MUSS auf ON</b> stehen, damit der Akku über USB-C geladen werden kann. Steht er auf OFF, ist der Ladestromkreis unterbrochen. 🔌</li>
  <li><b>Verbindung zurücksetzen:</b> Um die Bluetooth-Kopplung zu löschen, halte die Tasten <b>[Pfeil Links] + [Pfeil Rechts]</b> gleichzeitig für 5 Sekunden gedrückt. 🔄</li>
  <li><b>Bootloader-Modus:</b> Falls die Platine nicht als Laufwerk erkannt wird, überbrücke kurz die Kontakte <b>GND</b> und <b>RST</b>. 💾</li>
</ul>

<hr />

<h2>☕ Unterstützung</h2>
<p align="left">
  Hat dieses Projekt bei dir ins Schwarze getroffen? Wenn du meine Arbeit unterstützen möchtest, freue ich mich über einen digitalen Kaffee! Jeder Beitrag fließt direkt in die Entwicklung neuer Prototypen und quelloffener Werkzeuge für die Community. 🎯☕
  <br><br>
  <a href="https://www.buymeacoffee.com/mrcl_rckl">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="Spende mir einen Kaffee" />
  </a>
</p>
