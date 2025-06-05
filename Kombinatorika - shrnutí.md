
---

### **1. Permutace (uspořádaný výběr všech prvků, bez opakování)**

**Úloha:**  
Kolika způsoby lze seřadit 6 různých knih do jedné police?

**Řešení:**  
Jedná se o permutace 6 prvků, protože uspořádáváme všech 6 knih a žádná se neopakuje.  
Počet možností: P(6)=6!=720P(6) = 6! = 720

---

### **2. Variace bez opakování (uspořádaný výběr k prvků z n, bez opakování)**

**Úloha:**  
Kolika způsoby může učitel vybrat 3 různé žáky ze třídy 20 studentů a seřadit je do pořadí na prezentaci?

**Řešení:**  
Záleží na pořadí (např. kdo bude 1., 2., 3.) a nevybíráme všechny. Bez opakování.  
Počet možností:  
V(20,3)=20!(20−3)!=6840V(20, 3) = \frac{20!}{(20-3)!} = 6840

---

### **3. Variace s opakováním (uspořádaný výběr k prvků z n, s opakováním)**

**Úloha:**  
Kolik různých tříciferných kódů lze vytvořit z číslic 0–9, když se číslice mohou opakovat?

**Řešení:**  
Záleží na pořadí a číslice se mohou opakovat.  
Počet možností: 103=100010^3 = 1000

---

### **4. Kombinace bez opakování (neuspořádaný výběr k prvků z n, bez opakování)**

**Úloha:**  
Kolika způsoby lze vybrat 5 studentů z 18členné třídy, kteří pojedou na soutěž?

**Řešení:**  
Nezáleží na pořadí (všichni jedou jako tým) a neopakují se.  
Počet možností:  
(185)=8568\binom{18}{5} = 8568

---

### **5. Kombinace s opakováním (neuspořádaný výběr k prvků z n, s opakováním)**

**Úloha:**  
V cukrárně mají 4 druhy zákusků. Kolika způsoby si můžeš vybrat 6 zákusků, když na druhu nezáleží a můžeš si vzít i více stejných?

**Řešení:**  
Nezáleží na pořadí, zákusky se mohou opakovat.  
Počet možností:  
(4+6−16)=(96)=84\binom{4 + 6 - 1}{6} = \binom{9}{6} = 84

---

### Shrnutí přehledně:

|Typ úlohy|Počet prvků|Záleží na pořadí?|Opakování?|Příklad|
|---|---|---|---|---|
|**Permutace**|n|Ano|Ne|Seřazení knih|
|**Variace bez opak.**|n, k|Ano|Ne|Výběr a pořadí prezentujících|
|**Variace s opak.**|n, k|Ano|Ano|Kód z číslic|
|**Kombinace bez opak.**|n, k|Ne|Ne|Výběr týmu|
|**Kombinace s opak.**|n, k|Ne|Ano|Výběr zákusků|

---

