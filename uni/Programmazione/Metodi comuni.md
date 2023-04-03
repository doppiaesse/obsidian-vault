Alcuni dei [[Metodo|metodi]] più comuni:

- `public String toUpperCase()` - restituisce come risultato il riferimento a una **nuova stringa** costituita dagli stessi caratteri della stringa che esegue il metodo, con l'eccezione delle lettere minuscole, che diventeranno maiuscole.
- `public String toLowerCase()` - come `toUpperCase()` ma le lettere maiuscole diventano minuscole.
- `public int length()` - restituisce un valore di tipo int uguale alla **lunghezza** della stringa rappresentata dall’oggetto che esegue il metodo.
- `public String concat(String s)` - restituisce un riferimento alla stringa ottenuta **concatenando** alla stringa che esegue il metodo la stringa fornita come argomento.
- `public String substring(int begin, int end)` - restituisce il riferimento a una stringa formata dai caratteri che vanno dalla posizione **begin** fino alla posizione **end** - 1 della stringa che esegue il metodo. Specificando solo **begin**, continuerà automaticamente fino alla fine.
- `public String charAt(int pos)` - restituisce un valore di tipo **char** uguale al carattere che si trova nella posizione specificata come argomento.
- `public String trim()` - restituisce la stessa stringa che esegue il metodo, ma con i caratteri di spazio, che si trovano **prima** e **dopo** alla stringa, rimossi.
- `public String valueOf(int i)` - restituisce il riferimento alla stringa che rappresenta il valore dell'int fornito come argomento.
- `public boolean equals(Object anotherObject)` - confronta l’oggetto su cui viene richiamato con l’oggetto passato come parametro e restituisce un valore booleano.