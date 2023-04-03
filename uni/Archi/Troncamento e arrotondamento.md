I numeri frazionari possono avere un numero infinito di cifre.
Ne scriveremo solo un numero finito k.

- **Troncamento**: ignoro tutte le cifre dopo k (quindi, arrotondo sempre per difetto)

- **Arrotondamento**: idem, ma prima arrotondo per eccesso o per difetto, per minimizzare l'errore
	- dipende dalla **prima cifra che scarto**
		- in base 10:     0, 1, 2, 3, 4  -->  difetto        5, 6, 7, 8, 9  -->  eccesso
		- in base 2:       0  -->  difetto         1  -->  eccesso