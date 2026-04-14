## **Pracovní list 4: Oddělení komunikací (LOS)**
**Cíl:** Určit dobu trvání výpadku komunikace.

### **1. Modelování dráhy: Aproximace kružnicí a nekonečnem**
Výpočet hyperbolické dráhy je obtížný. Abychom si to zjednodušili, vytvoříme dva předpoklady:

1.  **Dráha:** Předpokládáme, že dráha za Měsícem je kruhový oblouk o poloměru $r = r_{p,moon}$.
2.  **Signál:** Předpokládáme, že Země je tak daleko, že rádiové vlny přicházejí jako **rovnoběžné přímky** (jako by z nekonečna).

* **Úkol 1: Kružnice vs. hyperbola:** Požádejte Skupinu 3, aby vám v GeoGebře ukázala svou hyperbolu. Zkuste proložit kružnici přes tu část dráhy, která je za Měsícem. Jak si tato kružnice vede ve srovnání s jejich skutečnou dráhou?

---

### **2. Matematické úkoly**
* **Úkol 2: Geometrie trojúhelníku:** Protože signály přicházejí jako rovnoběžné přímky, „stínová zóna“ je rovnoběžný válec za Měsícem. Vizualizujte si pravúhlý trojúhelník tvořený:
    1.  Středem Měsíce (ohnisko).
    2.  Bodem na středové ose ve vzdálenosti lunárního perigea.
    3.  Bodem, kde kosmická loď vstupuje do stínu (ve vzdálenosti $r_{p,moon}$ od středu).
    * *Poznámka: V tomto trojúhelníku je jednou odvěsnou poloměr Měsíce ($R_M$) — to je „poloviční tětiva“ stínu.*
* **Úkol 3: Výpočet úhlu:** Použijte $R_M$ a $r_{p,moon}$ k nalezení úhlu $\alpha$ ve středu Měsíce. Který poměr (sin, cos nebo tan) pro tento trojúhelník funguje?
* **Úkol 4: Načasování:**
    1.  Najděte celkový oblouk výpadku $\theta = 2\alpha$.
    2.  Vypočítejte vzdálenost uraženou v tichu: $s = r_{p,moon} \cdot \theta_{rad}$.
    3.  Použijte $v_{arrival}$ (od Skupiny 2) k nalezení celkové doby výpadku v minutách.
* **Úkol 5: Validace:** Zeptejte se Skupiny 3 na excentricitu ($e$). Proč musí být $e$ větší než 1, aby tato mise fungovala?

---

### **3. Digitální úkoly**
* **GeoGebra:** Zmapujte Měsíc a dráhu letu od Skupiny 3. Nakreslete **rovnoběžné přímky** tečné k povrchu Měsíce, abyste našli „stínovou zónu“. Odpovídá vizuální bod vstupu vašemu vypočítanému úhlu $\alpha$?
* **Excel:** Prozkoumejte bezpečnost. Pokud poletíte blíže (menší $r_p$), prodlouží se výpadek, nebo zkrátí? **Co zde pozorujete?**
