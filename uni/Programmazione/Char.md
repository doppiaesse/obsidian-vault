as Il [[Tipi primitivi e di riferimento|tipo]] **char** rappresenta caratteri **[[unicode]]**.
In Java anche il tipo char è un tipo intero. [[Conversioni implicite ed esplicite|Conversione implicita]] di char a int.


È possibile confrontare due caratteri utilizzando gli operatori di confronto.
- `'a' < 'b`   true
- `'b' < 'c'`   true

Le maiuscole precedono le minuscole
- `'Z' < 'a'`    true


```Java
for(char c = 'a'; c <= 'z'; c++)
	out.println(c)
```