Servizi forniti dalle [[Classe|classi]] anzichè dai singoli oggetti.

Esempio:
- `public static String valueOf(int i)`
- `public static int parseInt(String s)`

Usati per:
- Costruire oggetti della classe stessa a partire da oggetti o valori di altro tipo.
- Fornire operazioni utili su oggetti o su [[Tipi primitivi e di riferimento|tipi primitivi]].

La classe [[Math]] del package **java.lang** mette a disposizione metodi statici per realizzare alcune funzioni matematiche.


```Java
public class ProvaStatic {
	public static void main(String[] args) {
			int x = 5;
			String s = String.valueOf(x);
			String i = "5";
			x = Integer.parseInt(i);

			System.out.println(x);
	}
}
```