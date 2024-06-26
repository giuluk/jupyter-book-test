# Introduzione
```{epigraph}
"Er, quadratic equations mostly, sir. Fiendishly  difficult  ones
by all accounts. And then they sulk."

-- Douglas Adams, 'Life, the Universe and Everything'
```

## Forma canonica delle equazioni di 2° grado
````{prf:definition}
Una **equazione di 2° grado** (o **quadratica**) è una [equazione polinomiale](https://it.wikipedia.org/wiki/Equazione_algebrica) il cui grado massimo dell'incognita è $2$. In generale un'equazione di 2° grado può essere ricondotta nella forma:

```{math}
ax^2+bx+c=0 \qquad a \neq 0
```
````

Se anche $b$ e $c$ sono diversi da zero, allora l'equazione si dice *completa*, altrimenti *incompleta*.

In questi appunti i coefficienti $a$, $b$ e $c$ sono numeri razionali, tuttavia, in generale, tale limitazione non è necessaria.

Un'equazione di 2° grado, a coefficienti razionali, può  essere sempre ricondotta a un'equazione di 2° grado a coefficienti interi. Questo si ottiene moltiplicando ogni termine dell'equazione per il minimo comune multiplo ($mcm$) dei denominatori di $a$, $b$ e $c$.

````{prf:example}
Sia $\dfrac{1}{3}x^2+\dfrac{5}{2}x-2=0$ un'equazione di 2° grado a coefficienti frazionari. Per ottenere un'equazione equivalente a coefficienti interi, basta calcolare il $mcm$ di $3$ e $2$, rispettivamente i denominatori di $a$ e $b$ ($c$ è già un numero intero), e  moltiplicare tutti i termini dell'equazione per $mcm(3,2)=6$:

```{math}
\dfrac{1}{3}x^2+\dfrac{5}{2}x-2=0 \Leftrightarrow 2x^2+15x-12=0
```
````
Oltre ai coefficienti interi, per una questione di praticità, le 'nostre' equazioni dovranno rispettare le seguenti condizioni:
1. il *coefficiente direttivo* $a$ deve essere un numero maggiore di zero. 
2. i coefficienti $a$, $b$ e $c$ devono essere *coprimi*. 

Se $a$ non è positivo, è sufficiente invertire i segni di tutti i termini dell'equazione. Se il massimo comun divisore ($mcd$) di $a$, $b$ e $c$ è un numero $n \neq 1$, allora semplificheremo tutti i termini dell'equazione dividendo per $n$.

```{prf:remark}
Un gruppo di numeri interi si dicono **coprimi** se il loro unico divisore, intero positivo, comune è $1$.
```

Questi accorgimenti non sono necessari ma consentono di avere equazioni 'comode' con le quali poter operare.

````{prf:example}
Ricondurre l'equazione $-\dfrac{6}{5}x^2+4x-\dfrac{2}{3}=0$ in un'equazione polinomiale a coefficienti interi.

Dato che:
1. l'equazione è a coefficienti frazionari, calcolo il $mcm$ dei denominatori e lo moltiplico per tutti i termini dell'equazione in modo da trasformarla, fatte le opportune semplificazioni, in un'equazione a coefficienti interi;
2. il coefficiente direttivo è minore di zero, cambio tutti i segni dei termini dell'equazione;
3. i coefficienti dei termini dell'equazione non sono coprimi, divido i termini per il loro massimo comun divisore.

Per l'equazione $-\dfrac{6}{5}x^2+4x-\dfrac{2}{3}=0$ è possibile procedere come segue:
1. $mcd(5,3)=15$ quindi, a seguito delle moltiplicazioni, l'equazione diventerà 

$$-18x^2+60x-10=0$$

2. $a=-18$ quindi, dopo aver cambiato i segni, l'equazione diventerà 

$$18x^2-60x+10=0$$

3. $mcm(16,60,10)=2$ quindi, dopo aver semplificaro per $2$, l'equazione diventerà 

$$9x^2-30x+5=0$$

Ricapitolando:

```{math}
-\dfrac{6}{5}x^2+4x-\dfrac{2}{3}=0 \Leftrightarrow 9x^2-30x+5=0
```

````
