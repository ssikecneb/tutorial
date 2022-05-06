Github Segédlet
1. VSC - terminal - git bash (ha nincs ilyen akkor git scm telepítése)
2. mkdir  tutorial - make directory tutorial nevű mappa
3. cd tutorial
4. echo "github segédlet" >> readme.md - readme.md fájl létrehozása és a szöveg beszúrása
5. git init - mappa inicializálása
6. git config --global --list - globális beállítások ellenőrzése/listázása
7. git remote -v - távoli repo címének lekérdezése
8. git remote add origin- távoli repo hozzáadása origin néven / ha elrontjuk: git remote remove origin - origin nevű távoli repo eltávolítása
9. git add  readme.md - változtatások mentése (staging)
10. git commit -m "first commit" - first commit hozzáadása
11. git branch -m main - az ág átnevezésa main-re