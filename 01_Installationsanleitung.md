<!--Start Anleitung-->
# VSCode Installationsanleitung

Dies ist eine Anleitung (von Studenten für Studenten) zur Installation von <b>VSCode</b> und der hilfreichen Erweiterung <b>HSH_AddOn4VSC</b>.<br />

Bei Problemen kann hier dann einer Lösung geschaut werden: [03_Fehlerbehebung](https://github.com/hshf1/VorlesungC/blob/main/VSCode/03_Fehlerbehebung.md).<br />

### <p align="center">Download und Installation</p>
Die neueste Version von VSCode kann hier runtergeladen und installiert werden: [https://code.visualstudio.com](https://code.visualstudio.com).<br />

Nach der Installation ist VSCode zu öffnen. Es erscheint die folgende Benutzeroberfläche (Stand: 21.09.2023):

Auf der linken Seite kann auf den Marktplatz zugegriffen werden. Dort können Erweiterungen für VSCode installiert werden. Mit der Suche nach <b>HSH_AddOn4VSC</b> taucht die folgende Erweiterung auf (Stand: 21.09.2023):

Mit einem Klick auf Installieren wird die Erweiterung heruntergeladen und installiert. Sobald die Installation abgeschlossen ist, führt VSCode die Erweiterung sofort aus. Ab da werden alle weiteren benötigten Erweiterungen und zusetzende Einstellungen von der Erweiterung automatisch ausgeführt.

<!--Start MacOS-Anleitung-->
## <p align="center">MacOS</p>

<details>
<summary>VSCode auf MacOS installieren.</summary>
<br />
Für die Installation von VSCode auf dem MacOS ist das Terminal zu starten.<br /><br />
  
<img width="392" alt="Bildschirmfoto 2022-10-23 um 02 47 45" src="https://user-images.githubusercontent.com/100713757/197367855-42cb8849-0f3f-48de-88da-cea064dcccfe.png">

Nun wird folgender Code kopiert, im Terminal eingefügt und mit der ENTER-Taste ausgeführt:
  
```sh
curl -sL https://raw.githubusercontent.com/hshf1/HSH_AddOn4VSC/master/script/vsclinuxosx.sh | bash 
```
<!--Passwort wird zurzeit nicht abgefragt: sudo wurde entfernt
Nun werdet ihr nach eurem Passwort gefragt. <br />

<img width="561" alt="Bildschirmfoto 2022-04-17 um 05 38 59" src="https://user-images.githubusercontent.com/100713757/163699305-1b6cf156-158f-4c7c-880f-c51858000e5e.png">
  
Gebt das Passwort ein, dass ihr auch für die Anmeldung am Laptop nutzt und drückt auf Enter auf der Tastatur. -->

Am Ende sollte dann Installation beendet erscheinen. <br />
<img width="750" alt="Bildschirmfoto 2022-04-17 um 05 33 50" src="https://user-images.githubusercontent.com/100713757/163699227-a2bf91bd-3c4f-42d6-a16b-a7946f22f5c9.png">
  
Das Terminal kann nun beendet werden.

Hiermit wäre die Installation auch schon fertig und wir können mit [Erste Schritte](https://github.com/hshf1/VorlesungC/blob/main/VSCode/02_Erste_Schritte.md) weiter machen.
  
</details>

<details>
<summary>VSCode ist bereits installiert.</summary>
  
Das ist kein Problem, führe die oben beschriebene Installationsanleitung einfach ganz normal durch.
Bereits installierte Programme bleiben erhalten und nur fehlende dazu installiert.

</details>

<details>
<summary>VSCode auf MacOS deinstallieren.</summary>
<br />
Falls trotz erneuter Installation nach der obigen Anleitung Fehler auftreten und sich nicht beheben, besteht die Möglichkeit, alles komplett zu deinstallieren und zu löschen. <br /><br />
<b>ACHTUNG: Bei der Deinstallation werden auch manuell installierte Erweiterungen und manuell gesetzte Einstellungen gelöscht! Diese müssen nach der erneuten Installation wieder manuell hinzugefügt werden!</b><br /><br />
Danach kann man erneut die oben beschriebene Installation durchführen.
<br />
Für die Deinstallation von VSCode auf dem MacOS ist das Terminal zu starten.<br /><br />
  
<img width="392" alt="Bildschirmfoto 2022-10-23 um 02 47 45" src="https://user-images.githubusercontent.com/100713757/197367855-42cb8849-0f3f-48de-88da-cea064dcccfe.png">

Nun wird folgender Code kopiert, im Terminal eingefügt und mit der ENTER-Taste ausgeführt:
  
```sh
curl -sL https://raw.githubusercontent.com/hshf1/HSH_AddOn4VSC/master/script/vsclinuxosx.sh | uninstall=true bash 
```
  
Am Ende sollte dann für 5 Sekunden Installation beendet erscheinen. <br />
<img width="750" alt="Bildschirmfoto 2022-04-17 um 05 33 50" src="https://user-images.githubusercontent.com/100713757/163699227-a2bf91bd-3c4f-42d6-a16b-a7946f22f5c9.png">
  
Das Terminal beendet sich selbst und öffnet eine auf eurem Schreibtisch (Desktop) befindende Logfile. Ist kein Fehler aufgetreten könnt ihr die Logfile auch wieder löschen. Sollten Probleme oder Fehler auftauchen, stehen diese da drin. Zur Problembehandlung könnt ihr im Logfile sehen, was nicht geklappt hat. Solltet ihr das Problem nicht beheben können, schickt bitte die Logfile mit als Anhang.
    
Nun ist alles deinstalliert und gelöscht und es kann mit der Installation wieder von vorne begonnen werden.
  
</details>

<details>
<summary>Fehleranalyse am MacOS.</summary>

Für die Fehleranalyse von VSCode auf dem MacOS ist das Terminal zu starten.<br /><br />
  
<img width="392" alt="Bildschirmfoto 2022-10-23 um 02 47 45" src="https://user-images.githubusercontent.com/100713757/197367855-42cb8849-0f3f-48de-88da-cea064dcccfe.png">

Nun wird folgender Code kopiert, im Terminal eingefügt und mit der ENTER-Taste ausgeführt:
  
```sh
curl -sL https://raw.githubusercontent.com/hshf1/VorlesungC/main/VSCode/Quellcodes/Fehleranalyselinuxosx.sh | bash 
```

Die in der LogFile angezeigten Fehler enthalten Fehlercodes, die in der [Fehlerbehebung](https://github.com/hshf1/VorlesungC/blob/main/VSCode/03_Fehlerbehebung.md) nachgesehen werden können. Dort wird erklärt, wie vorzugehen ist.
  
</details>

<!--Ende MacOS-Anleitung-->

<!--Start Windows-Anleitung-->
## <p align="center">Windows</p>
<!--Neue Windows-Anleitung ohne Download-->
<details>
<summary>VSCode auf Windows installieren.</summary>

Für die Installation ist die Windows Eingabeaufforderung (Windows Terminal) als <b>Administrator</b> zu starten.<br /><br />
  
![Screenshot (29)_LI](https://user-images.githubusercontent.com/100713757/197366401-965de1cc-424d-459d-beeb-154240fe5653.jpg)

Nun wird der folgende Code kopiert und im Terminal eingefügt und mit der ENTER-Taste ausgeführt:

```cmd
curl -o %temp%\vsc.cmd https://raw.githubusercontent.com/hshf1/HSH_AddOn4VSC/master/script/vscwindows.cmd && %temp%\vsc.cmd install
```

Nun läuft die Installation von alleine und meldet euch, wenn es fertig ist. <br /><br />
  
![Screenshot (22)](https://user-images.githubusercontent.com/100713757/166149376-7700c166-11da-442f-a8ab-68e2da784fe9.png)

Bei der Meldung klicken wir auf <b>OK</b>, dass Terminal schließt nun automatisch und es erscheint ein Logfile, welches sich auf eurem Desktop befindet. <br /><br />
  
![Screenshot (23)](https://user-images.githubusercontent.com/100713757/166149506-b4171410-2132-45ac-af4d-1284638c1e3d.png)
  
Ist kein Fehler aufgetreten könnt ihr die Logfile auch wieder löschen. Sollten Probleme oder Fehler auftauchen, stehen diese da drin.
Zur Problembehandlung könnt ihr im Logfile sehen, was nicht geklappt hat. Solltet ihr das Problem nicht beheben können, schickt bitte die Logfile mit als Anhang.
  
Hiermit wäre die Installation auch schon fertig und wir können mit [Erste Schritte](https://github.com/hshf1/VorlesungC/blob/main/VSCode/02_Erste_Schritte.md) weiter machen.
  
</details>  
<!--Ende neue Windows-Anleitung ohne Download-->
    
<details>
<summary>VSCode ist bereits installiert.</summary>
  
Das ist kein Problem, führe die oben beschriebene Installationsanleitung einfach ganz normal durch.<br />
Bereits installierte Programme bleiben erhalten und nur fehlende dazu installiert.

</details>

<details>
<summary>VSCode auf Windows deinstallieren.</summary>
<br />
Falls trotz erneuter Installation nach der obigen Anleitung Fehler auftreten und sich nicht beheben lassen, besteht die Möglichkeit, alles komplett zu deinstallieren und zu löschen. <br /><br />
<b>ACHTUNG: Bei der Deinstallation werden auch manuell installierte Erweiterungen und manuell gesetzte Einstellungen gelöscht! Diese müssen nach der erneuten Installation wieder manuell hinzugefügt werden!</b><br /><br />
Danach kann man erneut die oben beschriebene Installation durchführen.
<br />
Für die Deinstallation ist die Windows Eingabeaufforderung (Windows Terminal) als Administrator zu starten.<br /><br />
  
![Screenshot (29)_LI](https://user-images.githubusercontent.com/100713757/197366401-965de1cc-424d-459d-beeb-154240fe5653.jpg)

Nun wird der folgende Code kopiert und im Terminal eingefügt und mit der ENTER-Taste ausgeführt:

```cmd
curl -o %temp%\vsc.cmd https://raw.githubusercontent.com/hshf1/HSH_AddOn4VSC/master/script/vscwindows.cmd && %temp%\vsc.cmd uninstall
```

Nun läuft die Deinstallation von alleine und meldet euch, wenn es fertig ist.
![Screenshot (22)](https://user-images.githubusercontent.com/100713757/166149376-7700c166-11da-442f-a8ab-68e2da784fe9.png)

Bei der Meldung klicken wir auf <b>OK</b>, dass Terminal schließt nun automatisch und es erscheint ein Logfile, welches sich auf eurem Desktop befindet.
![Screenshot (23)](https://user-images.githubusercontent.com/100713757/166149506-b4171410-2132-45ac-af4d-1284638c1e3d.png)
  
Ist kein Fehler aufgetreten könnt ihr die Logfile auch wieder löschen. Sollten Probleme oder Fehler auftauchen, stehen diese da drin.
Zur Problembehandlung könnt ihr im Logfile sehen, was nicht geklappt hat. Solltet ihr das Problem nicht beheben können, schickt bitte die Logfile mit als Anhang.
    
Nun ist alles deinstalliert und gelöscht und es kann mit der Installation wieder von vorne begonnen werden.
  
</details>

<details>
<summary>Fehleranalyse am Windows.</summary>

Für die Fehleranalyse ist die Windows Eingabeaufforderung (Windows Terminal) zu starten.<br /><br />
  
![Screenshot (29)_LI](https://user-images.githubusercontent.com/100713757/197366401-965de1cc-424d-459d-beeb-154240fe5653.jpg)

Nun wird der folgende Code kopiert und im Terminal eingefügt und mit der ENTER-Taste ausgeführt:

```cmd
curl https://raw.githubusercontent.com/hshf1/VorlesungC/main/VSCode/Quellcodes/Fehleranalysewindows.cmd | cmd>nul 2>&1
```

Die in der LogFile angezeigten Fehler enthalten Fehlercodes, die in der [Fehlerbehebung](https://github.com/hshf1/VorlesungC/blob/main/VSCode/03_Fehlerbehebung.md) nachgesehen werden können. Dort wird erklärt, wie vorzugehen ist.

</details>

<!--Ende Windows-Anleitung-->

<!--Start Linux-Anleitung-->

## <p align="center">Linux</p>

<!--Neue Linux-Anleiung-->
<details>
<summary>VSCode auf Linux installieren.</summary>
<br />
Bisher getestet für: Ubuntu / Zorin 15.3<br /><br />
Für die Installation ist das Terminal zu öffnen.<br />

<img width="566" alt="Bildschirmfoto 2022-04-17 um 05 31 43" src="https://user-images.githubusercontent.com/100713757/163699216-b1eb7dd1-ffce-4bcd-be21-1691adaf0c6b.png">
  
Der folgende Code wird kopiert, im Terminal eingefügt und mit der ENTER-Taste ausgeführt:
```sh
sudo snap install curl && curl -sL https://raw.githubusercontent.com/hshf1/HSH_AddOn4VSC/master/script/vsclinuxosx.sh | bash
```

Das Terminal beendet sich selbst und öffnet eine auf eurem Schreibtisch (Desktop) befindende Logfile, die ihr nach erfolgreicher Installation löschen könnt. Bei anhaltenden Problemen bitte diesen Logfile im Anhang per Mail abschicken.

Hiermit wäre die Installation auch schon fertig und wir können mit [Erste Schritte](https://github.com/hshf1/VorlesungC/blob/main/VSCode/02_Erste_Schritte.md) weiter machen.

</details>

<details>
<summary>VSCode ist bereits installiert.</summary>
  
Das ist kein Problem, führe die oben beschriebene Installationsanleitung einfach ganz normal durch.
Bereits installierte Programme bleiben erhalten und nur fehlende dazu installiert.

</details>

<details>
<summary>VSCode auf Linux deinstallieren.</summary>
<br />
Falls trotz erneuter Installation nach der obigen Anleitung Fehler auftreten und sich nicht beheben lassen, besteht die Möglichkeit, alles komplett zu deinstallieren und zu löschen. <br /><br />
<b>ACHTUNG: Bei der Deinstallation werden auch manuell installierte Erweiterungen und manuell gesetzte Einstellungen gelöscht! Diese müssen nach der erneuten Installation wieder manuell hinzugefügt werden!</b><br /><br />
Danach kann man erneut die oben beschriebene Installation durchführen.
<br />

Bisher getestet für: Ubuntu / Zorin 15.3<br /><br />
Für die Deinstallation ist das Terminal zu öffnen.<br />

<img width="566" alt="Bildschirmfoto 2022-04-17 um 05 31 43" src="https://user-images.githubusercontent.com/100713757/163699216-b1eb7dd1-ffce-4bcd-be21-1691adaf0c6b.png">
  
Der folgende Code wird kopiert, im Terminal eingefügt und mit der ENTER-Taste ausgeführt:
```sh
sudo snap install curl && curl -sL https://raw.githubusercontent.com/hshf1/HSH_AddOn4VSC/master/script/vsclinuxosx.sh | uninstall=true bash 
```

</details>

<details>
<summary>Fehleranalyse am Linux.</summary>
  
Bisher getestet für: Ubuntu / Zorin 15.3<br /><br />
Für die Fehleranalyse ist das Terminal zu öffnen.<br />

<img width="566" alt="Bildschirmfoto 2022-04-17 um 05 31 43" src="https://user-images.githubusercontent.com/100713757/163699216-b1eb7dd1-ffce-4bcd-be21-1691adaf0c6b.png">
  
Der folgende Code wird kopiert, im Terminal eingefügt und mit der ENTER-Taste ausgeführt:
```sh
sudo snap install curl && curl -sL https://raw.githubusercontent.com/hshf1/VorlesungC/main/VSCode/Quellcodes/Fehleranalyselinuxosx.sh | bash
```

Die in der LogFile angezeigten Fehler enthalten Fehlercodes, die in der [Fehlerbehebung](https://github.com/hshf1/VorlesungC/blob/main/VSCode/03_Fehlerbehebung.md) nachgesehen werden können. Dort wird erklärt, wie vorzugehen ist.

</details>
<!--Ende Linux-Anleitung-->

<!--Start Computerraum-Anleitung-->
## <p align="center">Computerraum an der Hochschule</p>

<details>
<summary>VSCode auf Rechner im CR installieren.</summary>
<br />
<p align="center">:warning:<b>Hinweis</b>:warning:</p>
Nach der Installation erscheint eine Datei auf dem Desktop mit dem Namen "C_Uebung.cmd". Die Datei kann nach belieben verschoben werden. Mit einem Doppelklick auf diese Datei öffnet sich VSCode automatisch mit dem Ordner, der bei der Installation miterstellt wurde (in U:/C_Uebung). Dort können Programme erstellt und gespeichert werden. Der Debugger und der Runner funktionieren nur richtig, wenn ein Ordner geöffnet wurde. So hilft die Verknüpfung, dies nicht zu vergessen.
<br />
<b>Anmerkung: Um im Computerraum richtig debuggen zu können, muss Schritt 2 befolgt werden. Andernfalls erhält man eine Fehlermeldung beim Ausführen des Debuggers.</b>
<br /><br />
Für die Installation ist die Windows Eingabeaufforderung (Windows Terminal) ganz normal zu starten. (Wenn Terminal nicht gefunden wird, nach "cmd" suchen.<br /><br />
  
![cr_terminal](https://user-images.githubusercontent.com/100713757/197754867-00515001-4d1d-49ce-a25e-7a02ed615506.png)

Nun wird der folgende Code kopiert und im Terminal eingefügt und mit der ENTER-Taste ausgeführt:

```cmd
curl https://raw.githubusercontent.com/hshf1/VorlesungC/main/VSCode/Quellcodes/VSCodeCR.cmd -o %temp%\VSCodeCR.cmd && %temp%\VSCodeCR.cmd && del %temp%\VSCodeCR.cmd && EXIT /B
```
  
Nun läuft die Installation von alleine und meldet euch, wenn es fertig ist.
![Screenshot (22)](https://user-images.githubusercontent.com/100713757/166149376-7700c166-11da-442f-a8ab-68e2da784fe9.png)

Bei der Meldung klicken wir auf <b>OK</b>, dass Terminal schließt nun automatisch und es erscheint ein Logfile, welches sich auf eurem Desktop befindet.
![Screenshot (23)](https://user-images.githubusercontent.com/100713757/166149506-b4171410-2132-45ac-af4d-1284638c1e3d.png)
  
Ist kein Fehler aufgetreten könnt ihr die Logfile auch wieder löschen. Sollten Probleme oder Fehler auftauchen, stehen diese da drin.
Zur Problembehandlung könnt ihr im Logfile sehen, was nicht geklappt hat. Solltet ihr das Problem nicht beheben können, schickt bitte die Logfile mit als Anhang.
  
### Schritt 2
Um im Computerraum debuggen zu können, ist es erforderlich, den Ordner direkt über den Netzlaufwerkverzeichnis zu öffnen.
Nach dem Start von VSCode klicken wir auf Open Folder.
  
![Screenshot (1)](https://user-images.githubusercontent.com/100713757/168243894-209938d6-c5b7-44e6-afa0-bb3072cfe8f6.png)

Dann gehen wir auf Dieser PC.
  
![Screenshot (2)](https://user-images.githubusercontent.com/100713757/168244010-46a3c191-c587-4af2-a8ac-e7da979685f2.png)

Und dort klicken wir auf den Netzlaufwerk mit dem Namen der eigenen Benutzerkennung.
  
![Screenshot (3)](https://user-images.githubusercontent.com/100713757/168244174-d539e84b-cf00-4eda-b1eb-8e517865720d.png)

Nun gehen wir noch auf Systemordner.
  
![Screenshot (4)](https://user-images.githubusercontent.com/100713757/168244323-6e0ecd94-6db6-4493-8fbc-8c06571460b2.png)
  
![Screenshot (6)](https://user-images.githubusercontent.com/100713757/168244473-e47306cd-3c71-4a78-a36d-3ad6ede3cdee.png)
  
Von hier aus können wir unseren Ordner dann auswählen und debuggen können.
  
Hiermit wäre die Installation auch schon fertig und VSCode ist nun im Computerraum nutzbar.

</details>
<!--Ende Computerraum-Anleitung-->

<!--Ende Anleitung-->
