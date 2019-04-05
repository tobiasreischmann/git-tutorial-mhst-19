# Installation

```
 git clone git@github.com/tobiasreischmann/git-tutorial-mhst-19.git git-tutorial
 cd git-tutorial
 git submodule update --init
```
 
# Interessante git Befehle:
 - git rebase -i
 - git merge
 - git reflog
 - git reset (soft/hard)
 - git cherry-pick
 - git push --force-with-lease
 - git commit -v -S
 - git fetch --all
 - git add/checkout -p
 - git log --graph --pretty=format:'%G? %Cred%h %Cgreen[%ai] %Cblue<%an>%Cgreen%C(bold)%d%Creset %s %Creset'
 - git submodule ...
 - git clean

# Aufgaben:

## History eines Branches neu schreiben:
 1. Checkout develop
 2. Ändern der letzten beiden Commits sodass Änderungen an view.php in einem commit und Änderungen an styles.php in anderem commit sind.

## Inconsistenten Patch anwenden.
 1. Der Patch patch-master aus diesem Repo soll auf den master Branch angewendet werden.
 2. Es sind nur die Bugfixed der Lang-Datei relevant. Der neue Lang-String soll nicht übernommen werden.
 3. Bugfix zu eigenem commit machen.

## Mergen mit take theirs
 1. Mergen von feature/view in master.
 2. Es soll NICHT MANUELL nur der Code aus feature/view verwendet werden, falls es zu Konflikten kommt.

## Entfernen aller nicht getrackten Dateien (Tipp: git clean)
 1. Checke den Branch feature/gitignore aus.
 2. Kopiere die Dateien loeschen.txt und ignore.txt in den playground.
 3. Lösche alle nicht getrackten Dateien, die im git status ausgegeben werden.
 4. Lösche auch alle ignorierten Dateien.
