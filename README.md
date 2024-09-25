# project2

**Cheat Sheets für Ubuntu-Terminal**
---
- 1. **Navigation im Dateisystem**
     - pwd - zeigt aktuellen Arbeitsverzeichnis-pfad an
     - ls - listet Dateien und Verzeichnisse im aktuellen Verzeichnis auf
         - **Optionen**:
             - ls -l- langformat
             - ls -a- zeigt auch verstecken Dateien
      - cd - wechselt das Verzeichnis
           - cd home/user (wechselt in home/user)
           - cd .. wecshelt ein Verzeichnis nach Oben
           - cd ~ wechselt in das Heimatverzeichnis des Users
- 2. **Dateiverwaltung**
       - cp - kopiert Dateien
            - bsp: cp file.txt file2.txt (kopiert file.txt zufile2.txt)
     - mv - verschiebt dateien oder benennt sie um
       - Verschieben --> bsp: mv file.txt /home/user/ (verschiebt datei in das Verzeichnis User
        - Umbenennen --> bsp: mv file.txt neuername (benennt Datei um in: neuername)
      - rm - löscht Dateien
          - **Optionen**
          - rmdir - löscht leere Ordner
          - rm -r - löscht Ordner und alle Inhalte
          - rm -rf - löscht Ordner, alle Inhalte und auch das was "rm -r" nicht löschen kann
- 3. **Dateiinhalte anzeigen und bearbeiten**
     - cat - zeigt Inhalt einer Datei im Terminal an
     - nano - einfache Textbearbeitung direkt im Terminal
     - touch - erstellt eine neue Datei
  - 4. **Sonstiges**
       - history - zeigt eine Liste der zuvor ausgeführten Befehle
       - clear - löscht den Inhalt des Terminals und zeigt eine leere Eingabeaufforderung
         
    
