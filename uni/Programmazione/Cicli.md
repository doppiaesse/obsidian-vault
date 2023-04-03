 ```Java
do
  istruzione
while(condizione)
```


Ripetere un blocco di istruzioni fino a quando non viene soddisfatta una [[condizione]].


```Java
import prog.io.ConsoleInputManager;

public class ProvaCicli {
	public static void main(String[] args) {

		ConsoleInputManager in = new ConsoleInputManager();
		int max = 5, somma = 0, tmp;

		do {
			tmp = in.readInt("Inserisci un numero > ");
			somma += tmp;
			max -= 1;
		} while(max == 0);
	
		System.out.println("La somma dei numeri inseriti è " + somma);
	
	}
}

```