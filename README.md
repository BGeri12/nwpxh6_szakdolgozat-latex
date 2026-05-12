# Szakdolgozat: Kátyú detektálás, autóra rögzített monokuláris kamera felvétel alapján, és az úton betöltött oldalirányú pozíciójának metrikus meghatározása, valós időben

Ez a repository tartalmazza a szakdolgozatom teljes LaTeX forráskódját.
* **Szerző:** [Bertalan Gergő] ([nwpxh6])
* **Konzulens:** [Prof. Dr. Vámossy Zoltán Imre]
* **Intézmény:** [Obudai egyetem, Neumann János Informatikai Kar]

---

## 📌 Útmutató a repohoz

### 1. A kész dolgozat megtekintése (A leggyorsabb mód)
A dolgozat legfrissebb, lefordított verziója mindig megtalálható a repository-ban. 
👉 **Kattintson ide a main.pdf letöltéséhez: https://github.com/BGeri12/nwpxh6_szakdolgozat-latex/blob/main/main.pdf vagy keresse a főkönyvtárban a `main.pdf` fájlt.)**

### 2. A forráskód letöltése és megnyitása
Ha meg szeretné tekinteni a LaTeX forráskódot, a legegyszerűbb módon így teheti meg:
1. Kattintson a jobb felső sarokban található zöld **`<> Code`** gombra.
2. Válassza a **`Download ZIP`** opciót.
3. Csomagolja ki a letöltött fájlt a gépén.
4. Nyissa meg a **`main.tex`** fájlt egy tetszőleges LaTeX szerkesztőben (pl. *TeXstudio*).

### 3. A projekt felépítése
A könnyebb navigáció érdekében a dokumentum modulárisan épül fel:
* `main.tex`: A fő dokumentum, ez húzza be a többi fájlt (ezt kell lefordítani).
* `chapters/`: Ebben a mappában találhatók a fejezetek külön `.tex` fájlokra bontva (pl. 1_Bevezetés, 2_Hasonlo_Fejlesztesek_Vizsgalata....).
* `img/`: A dolgozatban szereplő összes ábra és kép.
* `references.bib`: A Zotero által generált, frissített irodalomjegyzék fájl.

### 4. Fordítás (Build) információk
Ha lokálisan szeretné lefordítani a projektet (pl. TeXstudio-ban), a hivatkozások megfelelő generálásához a következő lépések szükségesek:
1. Alapértelmezett fordító: `pdflatex` (F5)
2. Bibliográfia fordító: `biber` (F8)
3. Újra `pdflatex` (F5) kétszer a hivatkozások frissítéséhez.

*(A rendszer a Better BibTeX formátumot használja az irodalomjegyzékhez.)*