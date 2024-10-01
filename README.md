# Cheat Sheets für Ubuntu-Terminal
 1. **Navigation im Dateisystem**
     - pwd - zeigt aktuellen Arbeitsverzeichnis-pfad an
     - ls - listet Dateien und Verzeichnisse im aktuellen Verzeichnis auf
         - **Optionen**:
             - ls -l- langformat
             - ls -a- zeigt auch verstecken Dateien
      - cd - wechselt das Verzeichnis
           - cd home/user (wechselt in home/user)
           - cd .. wecshelt ein Verzeichnis nach Oben
           - cd ~ wechselt in das Heimatverzeichnis des Users
 2. **Dateiverwaltung**
       - cp - kopiert Dateien
            - bsp: cp file.txt file2.txt (kopiert file.txt zufile2.txt)
     - mv - verschiebt dateien oder benennt sie um
       - Verschieben --> bsp: mv file.txt /home/user/ (verschiebt datei in das Verzeichnis User
        - Umbenennen --> bsp: mv file.txt neuername (benennt Datei um in: neuername)
      - rm - löscht eine Dateie
          - **Optionen**
          - rmdir - löscht leere Ordner
          - rm -r - löscht Ordner und alle Inhalte
          - rm -rf - löscht Ordner, alle Inhalte und auch das was "rm -r" nicht löschen kann
 3. **Dateiinhalte anzeigen und bearbeiten**
     - cat - zeigt Inhalt einer Datei im Terminal an
     - nano - einfache Textbearbeitung direkt im Terminal
     - touch - erstellt eine neue Datei
 4. **Systeminformationen**
     - uname -a - Zeigt Informationen über das System (Kernel-Version, Architektur etc.)
     - top - Zeigt eine Echtzeitansicht der laufenden Prozesse und Systemressourcen
 5. **Benutzer- und Berechtigungsbefehle**
     - sudo [Befehl] - Führt einen Befehl mit Administratorrechten aus
     - chmod [Berechtigungen] [Dateiname] - Ändert Berechtigungen einer Datei oder eines Verzeichnisses
     - whoami - zeigt den aktuellen User
 6. **Paketmanagement**
     - sudo apt update - Aktualisiert die Liste der verfügbaren Pakete
     - sudo apt upgrade - Installiert die neueste Version der installierten Pakete
     - sudo apt install [Paketname] - Installiert ein Paket
     - sudo apt remove [Paketname]- Entfernt ein installiertes Paket
     - sudo apt autoremove [Paketname] - Entfernt nicht mehr nötige Pakete
 7. **Hilfe und Manpages**
     - man [Befehl] - Zeigt das Handbuch (Manual) zu einem bestimmten command
     - [Befehl] --help - Zeigt eine kurze Hilfe oder Übersicht zu einem bestimmten command
 8. **Sonstiges**
     - history - zeigt eine Liste der zuvor ausgeführten Befehle
     - clear - löscht den Inhalt des Terminals und zeigt eine leere Eingabeaufforderung
         
    
