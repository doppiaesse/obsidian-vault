Il **bit più significativo** di una stringa di n bit ha peso **$-2^{n-1}$** anziché $2^{n-1}$, mentre gli altri bit **mantengono** il peso corrispondente alla loro posizione, come in binario puro.

- **MSB** $= 0$ --> numero positivo
	(stesso valore che si avrebbe in binario puro, il diverso peso del MSB non ha influenza)
	
- **MSB** $= 1$ --> numero negativo
	(il valore si ottiene sommando il contributo negativo del MSB con i contributi positivi degli altri bit)

- **$127$** = valore massimo rappresentabile con $8$ bit
- **$-128$** = valore minimo

**Esempi:**
- $11010111$ --> $-2^7 + 2^6 + 2^4 + 2^2 + 2^1 + 2^0 = -128 + 87 = -41$
- **$00110011$** --> $2^5 + 2^4 + 2^1 + 2^0 = 51$
- **$10000000$** --> $-2^7 = -128$
- $11111111$ --> $-1$
- **$00000000$** --> $0$
- $01111111$ --> $2^0 + 2^1 + 2^2 + 2^3 + 2^4 + 2^5 + 2^6 = 2^7 - 1 = 127$

Valori opposti, come $17$ e $-17$, hanno rappresentazioni diverse:
- $17$ --> $00010001$
- $-17$ --> $11101111$

Rappresentazioni identiche a meno del MSB denotano valori interi completamente diversi
- $01010101$ --> $85$
- $11010101$ --> $-43$

L'intervallo di valori rappresentabili complessivamente è $[-2^{k-1} ; +2^{k-1} - 1]$
 - MSB $= 0$ --> $k-1$ bit usabili come in binario puro --> intervallo da $0$ a $2^{k-1}-1$
 - MSB $= 1$ --> stesso intervallo traslato da $-2^k-1$ --> intervallo da $-2^{k-1}$ a $-1$

**Esempio:**
- $k = 8$ bit --> $2^8 = 256$ combinazioni --> intervallo da $-2^7$ a $2^7 -1$ cioè $-128..127$

Massimo intero positivo di **uno inferiore** al valore assoluto del minimo negativo, perchè lo **$0$** viene considerato **positivo**.

La rappresentazione in complemento a 2 permette di utilizzare direttamente gli **algoritmi dei numeri naturali**.
- Verificata $X + (-X) = 0$

Notazione in complemento a 2: algoritmo pratico
Rappresentazione di $-25$ su ($k = 8$ bit)

- $25$ --> $00011001$
- complemento a 1 --> $11100110$
- incremento di 1 --> $11100111$

Verifica: $-2^7 + 2^6 + 2^5 + 2^2 + 2^1 + 2^0 = -25$

**Overflow**
Sommando due valori che danno come risultato un valore esterno all'intervallo rappresentabile $[-2^n-1; 2^{n-1}-1]$ si provoca l'invasione del bit di segno da parte del risultato.

In questo caso si ha un overflow: il bit non è sufficiente per la rappresentazione del numero.
