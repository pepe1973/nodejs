# <ins>node.js<ins>

Lépcsőzetesen felépülő oktatóanyag a ==node.js==-ről.

---

## <ins>Első Lecke: Alapok</ins>

1. A node.js letöltése és telepítése: [nodejs.org](https://nodejs.org/en/)
2. Verzió(szám) ellenőrzés parancssorban: `node --version`
3. Az **npm** használata parancssorban:
    - _node package manager_ rövidítése
    - a ==node.js==-szel együtt települ
    - verzió(szám) ellenőrzés parancssorban: `npm --version`
4. A **REPL** használata parancssorban:
    - _Read-Eval-Print-Loop_ rövidítése
    - kilépés a parancssorból: `.exit`
5. Futtatás parancssorból: `node server.js`, vagy `node server`
6. Fontosabb **Globals**-ok megismerése (==**NINCS WINDOW OBJEKTUM!**==):
    - _\_\_dirname_ = elérési út az aktuális könyvtárhoz
    - _\_\_filename_ = a használatban lévő állomány (_file_) neve
    - _require_ = függvény modulok használatához
    - _module_ = információk az adott modulról
    - _process_ = információk a környezetről, ahol az alkalmazás fut
