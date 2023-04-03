#### Metodo per dimostrare proprietà dei numeri naturali.

Per dimostrare che $P(n)$ è vera per ogni $n \geq n_0$ si possono controllare i seguenti punti:
- **base di induzione** - $P(n_0)$ è vera
- **passo di induzione** - considero vera l'ipotesi di induzione per $n = t$    $P(t)$ vera e dimostro $P(t + 1)$

$P(n)$ proprietà che dipende da $n$.



Es. proprietà: ogni numero $n \in \mathbb{N}$ è pari oppure dispari.

Ma $\mathbb{N}$ è un insieme infinito quindi procedendo in questo modo ci vorrebbe un **tempo infinito**.

Posso dire che
- se $t$ è pari allora $t +1$ è dispari
- se $t$ è dispari allora $t + 1$ è pari

Unendo queste affermazioni con il fatto che $1$ è dispari, possiamo dire che tutti i numeri sono o **pari** o **dispari**.



Es. se   $| x | = n$   allora   $|P(x)| = 2^n$   per ogni   $n \geq 0$
*Proprietà che dipende da n*

**Supponiamo** di controllare il risultato per $n = t$
- Se   $|x| = t$   allora   $|P(x)| = 2^t$

**Dimostriamo** che se
- $|y| = t + 1$   allora   $|P(y)| = 2^{t+1}$

Se   $|x| = 1$   allora   $|P(x)| = 2$
Unendo possiamo quindi affermare che **è vera sempre**



Es. per ogni $n \geq 1$

$1 + ... + n = \frac{n(n+1)}{2}$ 

- **base**          $n = 1$          $1 = \frac{1*2}{2}$          **verificata**
- **passo di induzione**        $P(t + 1)$      cioè        $1 + ... + t +(t+1) = \frac{(t+1)(t+2)}{2}$

$1 + ... + t + (t+1) = \frac{t(t+1)}{2} + (t +1) = \frac{t(t+1)+2(t+1)}{2} = \frac{(t+1)(t+2)}{2}$

Quindi la proprietà vale per ogni $n \geq 1$


