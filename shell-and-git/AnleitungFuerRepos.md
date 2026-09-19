Git Repository erstellen

meine GitHub Seite öffnen / repo erstellen ohne README.md
Git Bash / VS Code Terminal öffnen und Sicherstellen dass ich im richtigen Ordner bin
git init
git add . (für den ersten Commit vorgemerkt)
git commit -m "Initial commit"
GitHub Repo verbinden, wird angezeigt sobald neues Repo erstellt wird (persönliche SSH URL) kopieren
git remote add origin SSH URL aus dem Repo einfügen
git branch -m main
git push -u origin main

index.html auf GitHub (Repo) updaten

1. GitBash öffnen richtigen Ordner öffnen
2. git status
3. git add index.html
4. git commit -m "datei die geändert wurde"
5. git push ODER git push -u origin main

Git Branch Commands

git remote -v Zeigt die Remote repository mit der er Lokal verbunden ist, zeig die Qulle an
git branch Liste meiner Branches
git branch <branchname> Erzeugt einen neuen Branch
git branch -a Liste aller Branches (lokal und remote)
git branch -d <branchnamen> Löscht einen Lokeln Git-Branch
git switch -c <branchname> Erstellt einen neune Branch und wechselt zu dem
git switch <branchname> Zweige wechseln
