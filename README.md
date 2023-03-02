# odd23-workshop
Workshop "Mit Open Data zur KI" am Open Data Day 2023 im München

Im folgenden sind alle Ressourcen und Informationen zum Workshop gesammelt:

## Installation Python & JupyterLab
Zuerst benötigt ihr eine aktuelle Python-Version für euer OS.
Danach installiert ihr JupyterLab, eine auf Python laufende Browser IDE, welche zur Data Science benutzt wird.

### Windows & Mac
Download des Python-Installers auf https://www.python.org/downloads/.
Führt den Installer aus und geht sicher, dass ihr Python zu eurem Pfad hinzufügt.

Öffnet CMD und führt folgende Kommandos nacheinander aus:
```cmd
python -m venv jupyter-venv :: Im aktuellen Ordner wird ein Unterordner mit allen Dateien des virtuellen Environments erstellt, somit "müllt" ihr nicht eure System-Version von Python voll.
jupyter-venv\Scripts\activate.bat :: venv aktivieren

pip install -U wheel :: Zuerst sichergehen dass wheel installiert ist
pip install -U jupyterlab :: Anschließend Jupyter Lab installieren
```

Danach kann JuypterLab mit dem Aufruf `jupyter lab` gestartet werden.

Alle anderen benötigten Pakete werden zu Anfang der Skripte installiert.


### Linux / Unix
Python sollte normalerweise bereits auf eurem System installiert sein, prüft dies mit dem Aufruf von `python3 --version` in eurer Kommandozeile.
Zusätzlich benötigt ihr noch das Paket "python3.x-venv" im ein virtuelles Environment zu erstellen, bitte recherchiert hier selbständig nach dem richtigen Paket für eure Distritution.

Öffnet die Bash und führt folgende Kommandos nacheinander aus:
```bash
python3 -m venv jupyter-venv # Im aktuellen Ordner wird ein Unterordner mit allen Dateien des virtuellen Environments erstellt, somit "müllt" ihr nicht eure System-Version von Python voll.
source jupyter-venv/bin/activate # venv aktivieren

pip install -U wheel # Zuerst sichergehen dass wheel installiert ist
pip install -U jupyterlab # Anschließend Jupyter Lab installieren
```

Danach kann JuypterLab mit dem Aufruf `jupyter lab` gestartet werden.

Alle anderen benötigten Pakete werden zu Anfang der Skripte installiert.