Il calcolatore può essere descritto e costruito come una gerarchia di [[Astrazione|macchine astratte]] (o virtuali), in cui ogni livello maschera i dettagli dei livelli sottostanti.

1. Costruiamo una prima macchina (l’elaboratore) in grado di eseguire istruzioni elementari.

3. Utilizziamo queste istruzioni elementari per scrivere un programma (il Sistema Operativo) in grado di eseguire comandi più complessi

	*Il programmatore del S.O. non conosce i dettagli relativi alla tecnologia realizzativa del microprocessore*

3. Scriviamo programmi che si basano sulle funzioni del S.O.

	*Il programmatore del programma non conosce i dettagli costruttivi del S.O.*


Un esecutore è definito in base a tre elementi:
- l’insieme delle [[Istruzioni e operazioni|operazioni]] elementari che è capace di compiere
- l’insieme delle [[Istruzioni e operazioni|istruzioni]] che capisce (sintassi)
- quali operazioni associa ad ogni istruzione che riconosce (semantica)