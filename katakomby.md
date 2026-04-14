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


## **Průvodce laboratorní připraveností k letu: Mise Artemis II**

**Stav:** Fáze HEO (vysoká oběžná dráha Země) dokončena. Přechod na TLI (trans-lunární injekce).

**Cíl:** Ověřit fyzikální parametry setkání s Měsícem a návratové trajektorie.

---

### **1. Globální brífink mise: Konstanty**
Pro všechny výpočty používejte tyto hodnoty.

**Fyzikální konstanty**
* **Gravitační konstanta ($G$):** $6,674 \times 10^{-11} \text{ m}^3\text{kg}^{-1}\text{s}^{-2}$
* **Hmotnost Země ($M_E$):** $5,972 \times 10^{24} \text{ kg}$
* **Hmotnost Měsíce ($M_M$):** $7,342 \times 10^{22} \text{ kg}$
* **Poloměr Země ($R_E$):** $6\,371 \text{ km}$
* **Poloměr Měsíce ($R_M$):** $1\,737 \text{ km}$

**Údaje o trajektorii**
* **Výška perigea HEO ($h$):** $185 \text{ km}$
* **Výška apogea HEO ($h_a$):** $74\,000 \text{ km}$
* **Vzdálenost k Měsíci ($r_{moon}$):** $384\,400 \text{ km}$
* **Poloměr periluny ($r_{p,moon}$):** $7\,400 \text{ km}$ (vzdálenost ke středu Měsíce)

---

### **2. Fyzikální dodatek: Energie a Kepler**

**Zákon zachování energie**
Celková energie ($\epsilon$) je součtem kinetické (rychlost) a potenciální (gravitace) energie. Energie je konstantní:
$$\epsilon = \frac{1}{2}v^2 - \frac{\mu}{r} = \text{Konstanta}$$

**Úkol: Kepler a Vis-viva**
1. Keplerův zákon: Oběžné dráhy jsou elipsy. Velikost elipsy ($a$) určuje energii:
$$\epsilon = -\frac{\mu}{2a}$$
**Cíl:** Porovnejte tyto dva vzorce pro energii. Vyjádřete $v^2$ ve vzdálenosti $r$.
**Výsledek:** $v^2 = \dots\dots\dots$

**Tvary drah: Excentricita ($e$) a ohnisko**
* **Ohnisko (Focus):** Všechny orbity mají dvě ohniska. Planeta (Země nebo Měsíc) se vždy nachází v jednom z nich.
* **Elipsa ($e < 1$):** Uzavřená, kruhová smyčka. Plavidlo je "vázáno" k planetě.
* **Hyperbola ($e > 1$):** Otevřená křivka. Plavidlo má dostatek energie k "úniku" a už se nikdy nevrátí.

**Úkol: Úniková rychlost ($v_{esc}$)**
K úniku potřebujete dostatek celkové energie ($\epsilon \ge 0$).
**Cíl:** Pro dosažení dostatečné energie nastavte $\epsilon = 0$ a vypočítejte $v$.
**Výsledek:** $v_{esc} = \dots\dots\dots$

---

### **3. Inženýrský dodatek: Ciolkovskij a raketová věda**

**Zákon zachování hybnosti**
Konstantin Ciolkovskij zjistil, že rakety se pohybují vpřed díky vyvrhování hmoty směrem dozadu. Toto je **Zákon zachování hybnosti**.

**Raketová rovnice**
Palivo má svou hmotnost. Abyste letěli rychleji, potřebujete více paliva. Jde o exponenciální vztah:
$$\Delta v = v_e \ln \left( \frac{m_i}{m_f} \right)$$

**Co je co?**
* $\Delta v$: Změna rychlosti ("kopanec").
* $v_e$: Výtoková rychlost (účinnost motoru).
* $m_i$: Počáteční hmotnost (loď + palivo).
* $m_f$: Konečná hmotnost (pouze loď).
