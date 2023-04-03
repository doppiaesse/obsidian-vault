Un tipo è caratterizzato dai suoi valori e dalle operazioni che si possono compiere su di essi.

Il [[Tipi primitivi e di riferimento|tipo primitivo]] **boolean** dispone di:
- `&&` - and
- `||` - or
- `!` - not

L'operatore `!` ha la **massima** precedenza e `||` la **minima**.

Esempio:
- `a && b || a && b`  equivalente a  `(a && b) || (a && b)`
- compl