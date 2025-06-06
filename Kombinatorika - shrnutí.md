
| Typ úlohy                | Označení           | Vzorec                                                           | Poznámka                                          |
|--------------------------|--------------------|-------------------------------------------------------------------|---------------------------------------------------|
| Variace bez opakování    | $$ V(n, k) $$       | $$ V(n, k) = \frac{n!}{(n - k)!} $$                              | Záleží na pořadí, bez opakování                   |
| Variace s opakováním     | $$ V'(n, k) $$      | $$ V'(n, k) = n^k $$                                             | Záleží na pořadí, s opakováním                    |
| Permutace                | $$ P(n) $$          | $$ P(n) = n! $$                                                  | Pořadí důležité, všech $$ n $$ prvků              |
| Permutace s opakováním   | $$ P(n; n_1, \dots, n_k) $$ | $$ P = \frac{n!}{n_1! \cdot n_2! \cdots n_k!} $$        | Některé prvky se opakují                           |
| Kombinace bez opakování  | $$ C(n, k) $$       | $$ C(n, k) = \binom{n}{k} = \frac{n!}{k!(n - k)!} $$             | Na pořadí nezáleží, bez opakování                 |
| Kombinace s opakováním   | $$ C'(n, k) $$      | $$ C'(n, k) = \binom{n + k - 1}{k} $$                            | Na pořadí nezáleží, s opakováním                  |

---

### **1. Permutace (uspořádaný výběr všech prvků, bez opakování)**

**Úloha:**  
Kolika způsoby lze seřadit 6 různých knih do jedné police?

**Řešení:**  
Jedná se o permutace 6 prvků, protože uspořádáváme všech 6 knih a žádná se neopakuje.  
Počet možností: 
$$
P(6) = 6! = 720
$$
---

### **2. Variace bez opakování (uspořádaný výběr k prvků z n, bez opakování)**

**Úloha:**  
Kolika způsoby může učitel vybrat 3 různé žáky ze třídy 20 studentů a seřadit je do pořadí na prezentaci?

**Řešení:**  
Záleží na pořadí (např. kdo bude 1., 2., 3.) a nevybíráme všechny. Bez opakování.  
Počet možností:  

$$ V(20, 3) = \frac{20!}{(20-3)!} = 6840 $$

---

### **3. Variace s opakováním (uspořádaný výběr k prvků z n, s opakováním)**

**Úloha:**  
Kolik různých tříciferných kódů lze vytvořit z číslic 0–9, když se číslice mohou opakovat?

**Řešení:**  
Záleží na pořadí a číslice se mohou opakovat.  
Počet možností: 
$$ 
10^3 = 1000
$$
---

### **4. Kombinace bez opakování (neuspořádaný výběr k prvků z n, bez opakování)**

**Úloha:**  
Kolika způsoby lze vybrat 5 studentů z 18členné třídy, kteří pojedou na soutěž?

**Řešení:**  
Nezáleží na pořadí (všichni jedou jako tým) a neopakují se.  
Počet možností:  
$$
\binom{18}{5} = 8568
$$
---

### **5. Kombinace s opakováním (neuspořádaný výběr k prvků z n, s opakováním)**

**Úloha:**  
V cukrárně mají 4 druhy zákusků. Kolika způsoby si můžeš vybrat 6 zákusků, když na druhu nezáleží a můžeš si vzít i více stejných?

**Řešení:**  
Nezáleží na pořadí, zákusky se mohou opakovat.  
Počet možností:  
$$
\binom{4 + 6 - 1}{6} = \binom{9}{6} = 84
$$
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

