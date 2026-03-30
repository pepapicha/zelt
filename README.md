### 1. Magnetická indukce ($B$) a Intenzita ($H$)
Tady se nejčastěji chybuje. Rozdíl je v tom, **kde** se nacházíme:
* **Intenzita ($H$):** Vyjadřuje "sílu" magnetického pole, kterou vytváří proud ve vodiči. Nezávisí na prostředí (je jí jedno, jestli je tam vzduch nebo železo). Jednotka: **A/m**.
* **Magnetická indukce ($B$):** Vyjadřuje skutečný silový účinek pole v konkrétním materiálu. Jednotka: **T (Tesla)**.

**Vztah mezi nimi:**
$$B = \mu \cdot H$$
*(Kde μ je permeabilita – viz níže).*

---

### 2. Magnetomotorické napětí ($F_m$ nebo $U_m$)
V elektrickém obvodu tlačí proud baterka (napětí $U$). V magnetickém obvodu "tlačí" magnetický tok cívka.
* **Vzorec:** $F_m = I \cdot N$
* $I$ = proud, $N$ = počet závitů. Jednotka: **A (Ampér)**, někdy se uvádí "ampérzávit".
* **Rozdíl od magnetického napětí:** Magnetomotorické napětí je "zdroj" (celá cívka). Magnetické napětí ($U_m$) je úbytek na určité části obvodu (jako úbytek napětí na odporu).

---

### 3. Jeden vodič vs. Více vodičů (Cívka)
Magnetické pole tvoří kolem vodiče soustředné kružnice.
* **1 přímý vodič:** $H = \frac{I}{2\pi r}$ (kde $r$ je vzdálenost od vodiče).
* **Cívka (dutina):** Uvnitř dlouhé cívky (solenoidu) je pole homogenní (všude stejné).
    * **Vzorec:** $H = \frac{I \cdot N}{l}$
    * $l$ = délka cívky.



---

### 4. Permeabilita ($\mu$) – "Magnetická vodivost"
Říká, jak dobře materiál "vede" magnetické pole.
* **$\mu_0$ (vakua):** Konstanta ($4\pi \cdot 10^{-7} \, \text{H/m}$).
* **$\mu_r$ (relativní):** Číslo, které říká, kolikrát lépe vede materiál pole než vakuum.
* **Celková:** $\mu = \mu_0 \cdot \mu_r$

---

### 5. Druhy látek (Dělení podle $\mu_r$)
Látky dělíme podle toho, jak reagují na vnější magnetické pole:

| Typ látky | Relativní permeabilita ($\mu_r$) | Chování | Příklad |
| :--- | :--- | :--- | :--- |
| **Diamagnetické** | $\mu_r < 1$ (nepatrně) | Mírně pole oslabují (vypuzují). | Měď, zlato, voda |
| **Paramagnetické** | $\mu_r > 1$ (nepatrně) | Mírně pole zesilují. | Hliník, vzduch, platina |
| **Feromagnetické** | $\mu_r \gg 1$ (stovky až tisíce) | Extrémně zesilují pole, dají se zmagnetovat. | Železo, kobalt, nikl |

**Zásadní vlastnost feromagnetik:** Jsou nelineární (mají **hysterézní smyčku**) – při určité síle pole se "nasytí" a už víc nezesilují.

---

### Shrnutí vzorců pro zítřek:
1.  **Zdroj pole:** $F_m = I \cdot N$
2.  **Intenzita v cívce:** $H = \frac{F_m}{l}$
3.  **Indukce (síla):** $B = \mu_0 \cdot \mu_r \cdot H$
4.  **Magnetický tok:** $\Phi = B \cdot S$ (jednotka **Wb - Weber**) – to je to, co reálně "teče" jádrem.
