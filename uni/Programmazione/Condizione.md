```Java
if (condizione)
	istruzione1
else
	istruzione2
```

È una qualunque espressione di tipo **boolean**, scritta obbligatoriamente tra parentesi tonde.

Valuto la condizione:
- se restituisce **true**, eseguo **istruzione1**
- altrimenti, se è **false**, eseguo **istruzione2**

È possibile utilizzare solo if, senza else, ma non else senza if.

```Java
public class ProvaIfElse {
	public static void main(String[] args) {
		int x = 0;
		int y = 2;
		int z;

		if (x >= 0)
			z = x + y;
		else
			z = x - y;

		System.out.println("z = " + z);
	}
}
```