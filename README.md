# myE010 - Linux Essentials Exam 010

Beispiel für einen Aufbau einer Dokumention des Lern- und Entwicklungsprozesses mit Ausgesuchten Unterkapiteln aus einem oder beiden LPI Examen

## Einrichtung forken dieses GitHub Repository für Dokumentation

Als erster Schritt muss ein GitHub-Account eingerichtet werden. Dieser dient uns später als "Cloud-Speicher" unserer Dokumentation und weiteren Dateien.

Folgende Arbeiten müssen gemacht werden:

**Account erstellen**

1. Auf www.github.com ein Benutzerkonto erstellen (Angabe von Username, E-Mail und Passwort)
2. E-Mail zur Verifizierung des Kontos bestätigen und anschliessend auf GitHub anmelden

**Forken dieses Repositories**

1. Auf Repository [myE010](https://github.com/w901-fr19-mi/myE010) wechseln.
2. Klicken Sie oben rechts auf der Seite auf `Fork` .

![](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Das ist es! Jetzt haben Sie einen `Fork` (Kopie) des Original myE010 Repository und können dessen Inhalte verändern.

Weitere Möglichkeiten siehe [Modul M300 - 10 Toolumgebung](https://github.com/mc-b/M300/tree/master/10-Toolumgebung)

## Dokumentation

Die Dokumentation erfolgt im Markdownformat, dem Standard Wiki Format von github. Dies geht am Einfachsten direkt auf github.com.

Eine Markdown Übersicht / Syntax etc. finden Sie auf:
* [Markdown Syntax inkl. Online Demo](http://markdown-syntax.de/Was-ist-Markdown/)
* [Dokumentation aus dem Modul M300](https://github.com/mc-b/M300/blob/master/80-Ergaenzungen/vcs/03-Markdown.md) 

## Installation

Es kann entweder Manuell eine Linux VM erstellt werden, wie in [E010](../E010/blob/master/md/10-Linux-System/10-Installation.md) beschrieben oder Sie verwenden Vagrant und holen sich gleichzeitig die 4 Punkte von [E701 - 703.1 Virtual Machine Deployment](../../../E701#topic-703-machine-deployment).

**Vagrant Installation**

Zuerst muss folgende SW Installiert werden:
* [Git/Bash](https://git-scm.com/downloads)
* [Vagrant](https://www.vagrantup.com/) 
* [VirtualBox](https://www.virtualbox.org/)

Wechseln Sie auf die Kommandozeile (*bash* oder *PowerShell*), Erstellen Sie ein neues Verzeichnis und Erzeugen eine VM

	mkdir myVM
	cd myVM
	vagrant init centos/7
	vagrant up
	
Das ist es! Jetzt haben Sie eine VM. 

Um darin zu Arbeiten geben Sie `vagrant ssh` ein und wechseln ins Verzeichnis `vagrant`. Dieses Verzeichnis mountet die VM automatisch und zeigt auf `myVM` auf Ihrem Notebook.

	vagrant ssh
	cd /vagrant
	ls -l 
	
`ls -l` gibt alle Dateien aus. Als einzige Datei sollte die Konfigurationsdatei von vagrant `Vagrantfile` angezeigt werden.

Weitere Informationen siehe [Modul M300 - 20 Infrastruktur-Automatisierung](https://github.com/mc-b/M300/tree/master/20-Infrastruktur).

**Weitere nützliche Programme**

* [Windows SSH Client, putty](https://putty.org)
* [Grafischer Windows SFTP Client, Bitvise SSH Client](https://www.bitvise.com/ssh-client-download)
* [Visual Studio Code](https://code.visualstudio.com/)

## Fahrplan
***


| Datum | behandelte Unterrichtsinhalte: | Gewichtung |
| -------- | ------ | -------- |
| 15.05.19 | 1.1 Linux Evolution and Popular Operating Systems<br>1.3 Open Source Software and Licensing | 2 + 2 |
| 22.05.19 | 2.1 Command Line Basics<br>2.3 Using Directories and Listing Files<br>2.4 Creating, Moving and Deleting Files  | 2 + 3 + 2 |
| 29.05.19 | 3.2 Searching and Extracting Data from Files<br>3.3 Turning Commands into a Script | 3 + 4 | 
| 05.06.19 | 4.4 Your Computer on the Network | 2 |
| 12.06.19 | 702.1 Container Usage - Studium | - |
| 19.06.19 | 702.1 Container Usage - Umsetzung | 7 (14) |
| 26.06.19 | LB1 Theoretische Prüfung und Abschluss LB2 | - |
| 03.07.19 | Sommersporttage | - |
|          | Total Punkte | 24 (31) !

Kapitel aus E010 sind einzeln erarbeitet worden. Kapitel aus E701 in der Gruppe mit ....

## Dokumention des Lern- und Entwicklungsprozesses
***

### Kapitel: 2.1 Command Line Basics (Status: In Arbeit)

**Weight**: 3 (Wert aus Exam 010)

**Beschreibung** des Unterkapitels, z.B. Basiswissen um mit der Kommandozeile von Linux zu arbeiten.

**Tagesziele**, z.B. Aufbau des Wissen über die Shell. 

**Vorgehen**, z.B. Installation einer Ubuntu Linux Umgebung. Durcharbeiten ...., Dokumentation der einzelnen Befehle in ...

**Beispiele und Arbeitsergebnisse**

* Starten der Shell: bash bzw. Einloggen.
* Einfache 'mein Befehl' lösen Variablen nicht auf.
* Doppelte " lösen Variablen auf.

**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir einen Einblick in die Shell. Das nächste Mal will ich diese im Kapitel ... vertiefen.

