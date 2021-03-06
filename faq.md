# Häufig gestellte Fragen und Hinweise (Q&A)

*Q: Wie komme ich an die Notebooks?*<br/>
A: Clonen Sie das Repository des Kurses.
Unter dem `jupyter` Verzeichnis finden Sie die Notebooks der Vorlesungen.

*Q: Wie kann ich das Kurs-Repository clonen?*<br/>
A: Mit der Konsole (git muss installiert sein):
```bash
git clone https://github.com/cis-kb21/cis-kb21.github.io.git
```

*Q: Wie kann ich das Kurs-Repository ohne einen Konsolen-Client clonen?*<br/>
A: Verwenden Sie einen der unten angegebenen graphischen Git-Clients und clonen Sie das Repository
unter https://github.com/cis-kb21/cis-kb21.github.io.git
* [GitKraken](https://www.gitkraken.com/)
* [TortoiseGit](https://tortoisegit.org/)
* [SourceTree](https://www.sourcetreeapp.com/)

*Q: Ich habe das Git-Repository.  Wie kann ich das aktuelle Notebook erhalten?*<br/>
A: Verwenden Sie den graphischen Git-Client und aktuallisieren Sie das Repository
oder führen Sie (innerhalb des Git-Verzeichnisses) folgenden Befehl aus:
```bash
git pull origin main
```

*Q: Ich habe das Git-Repository.  Wie kann ich das aktuelle Notebook erhalten?*<br/>
A: Verwenden Sie den graphischen Git-Client und aktuallisieren Sie das Repository
oder führen Sie (innerhalb des Git-Verzeichnisses) folgenden Befehl aus:
```bash
git pull origin main
```

*Q: Wie kann ich ein Notebook starten?*<br/>
A: Wechseln Sie in das entsprechende Verzeichnis (`jupyter/..`) und
starten Sie das Notebook (jupyter muss installiert sein) mit folgenden Befehl:
```bash
jupyter notebook
```

*Q: Wie kann ich jupyter installieren?*<br/>
A: Global (benötigt pip und python):
```bash
sudo pip install jupyter
```
oder lokal (benötigt python):
```bash
python -m venv venv
source venv/bin/activate
pip install jupyter
...
deactivate
```

*Q: Wie wird die Klausur durchgeführt?*<br/>
A: Die Verteilung und die Abgabe der Klausur finden über Moodle statt.
Näheres dazu finden Sie in den [Folien vom 15.07.2021](https://github.com/cis-kb21/cis-kb21.github.io/blob/main/11_summary.pdf).
