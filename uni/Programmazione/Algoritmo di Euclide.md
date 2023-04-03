### Algoritmo di Euclide
[[Algoritmo]] per trovare il massimo comune divisore (**MCD**) tra due numeri interi.

1. Calcola il resto della divisione di $x$ per $y$
2. Se il resto è diverso da zero
		ricominciamo dal passo 1 utilizzando come $x$ il valore attuale di $y$ e come $y$ il valore del resto
	Altrimenti
		prosegui con il passo successivo
3. MCD = valore attuale di $y$