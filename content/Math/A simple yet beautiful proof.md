[🇧🇷](#uma-simples-mas-bela-prova) / 🇺🇸

Proving that $\sqrt{2}$ is irrational is very simple: one can do it with nothing more than the tools we learn in elementary school, and I believe more people should appreciate it and all the knowledge one can get from diving into the history behind it.

First things first, what is an *irrational number?* In simple terms, a *rational* number is a real number that can be expressed as the ratio of two integers $\dfrac{a}{b}$, and an *irrational* number is a real number that isn't rational. If you took the diagonal of a unit square, you'd have a segment of length $\sqrt{2}$. Now, what makes this number - or irrational numbers in general - so special?

Let's take a step back and think about it in terms of geometry. Take two lengths such as $473 cm$ and $100cm$, for instance. They both can me measured in terms of a common unit (e.g. the centimeter) with precision, so we call them *commensurable*. Now, take the diagonal of a unit square and its side. Those measures are *incommensurable*: if two lengths can't be expressed as a reason of integers, this means there's no common unit of measure - as small as it could get - that could be used to measure both these lengths to their exact size. Let's prove why is it so for $\sqrt{2}$ . We'll prove using a tool called *reductio ad absurdum* (latin for "reduction to absurdity"), which consists of (1) assuming that a hypothesis is true, (2) showing that if this hypothesis is true, it leads to a contradiction, and (3) if this leads to a contradiction, the hypothesis must be false. 

So, let's construct our proof:

1) Suppose that $\sqrt{2}$ can be expressed as the reason of two integers $a$ and $b$, and $a$ and $b$ have no common denominator other than 1 (in other words, you cannot "simplify" the fraction):
$$\dfrac{a}{b} = \sqrt{2}$$
2) Squaring both sides and then multiplying both sides by $b^2$, we have:
$$
\begin{aligned}
\dfrac{a^2}{b^2} = 2 \\ \\
a^2 = 2b^2
\end{aligned}
$$
3) From (2), we have that $a^2$ is even, and so $a$ is also even (an even number squared is always even and an odd number squared is always odd).
4) If $a$ is even, it can be written in the form $a = 2k$, where $k$ is also an integer.
5) From (2), we have:
$$
\begin{aligned}
a^2 = 2b^2 \\
(2k)^2 = 2b^2 \\
4k^2 = 2b^2 \\
b^2 = 2k^2
\end{aligned}
$$

6) So we've shown that if $a$ is even, $b^2$ is even and therefore $b$ is also even. But if $a$ and $b$ are both even numbers, this contradicts our hypothesis (1). Therefore, $\sqrt{2}$ is an irrational number, and it cannot be written a ratio of two integers. 

We don't know for sure who was the first person to show this: the proof is often attributed to Hippasus of Metapontum, but no ancient source has linked Hippasus to the discovery of irrationality. It's also said that the person who revealed this finding was thrown in the ocean as a punishment, or that they were banished from the community and a tombstone was erected with their name. These, however, are most likely myths, as [pointed out](https://kiwihellenist.blogspot.com/2015/11/were-greeks-scared-of-irrational-numbers.html) by the classicist Dr. Peter Gainsford:

> So, what does the actual evidence tell us? The surviving testimony is as follows, in chronological order.
> 
> - Late 2nd century CE: Clement of Alexandria, [_Stromateis_ 5.9.57](https://archive.org/stream/writingsofclemen02clem#page/255/mode/2up). Clement reports that a Pythagorean named "Hipparchus" revealed the teachings of Pythagoras in a book. As a symbol of his expulsion from the sect, the Pythagoreans erected a gravestone as if he were dead.
> - 3rd-4th century CE: Iamblichus, _Life of Pythagoras_ tells us:
> 	- [88-9 (§18)](https://archive.org/stream/CompletePythagoras#page/n35/mode/1up): Hippasus, a Pythagorean, revealed the discovery that the vertices of a regular [dodecahedron](https://en.wikipedia.org/wiki/Dodecahedron) coincide with the surface of a sphere, and because of his impiety he was lost at sea;
> 	- [246 (§34)](https://archive.org/stream/CompletePythagoras#page/n74/mode/1up): a man who made public the nature of rational and irrational ratios was so hated by the Pythagoreans that they expelled him and erected a tomb as if he were dead;
> 	- [247 (§34)](https://archive.org/stream/CompletePythagoras#page/n74/mode/1up): a man who revealed the construction of the dodecahedron drowned at sea, punished by a divinity; others say that this happened to the man who revealed the nature of rational and irrational ratios.
>
>[...]
>
>But the worst of it is that **even this honest summary is probably completely untrue** as well. The fullest account comes from Iamblichus, and Iamblichus is notoriously untrustworthy. Pappos makes it clear that as far as he was concerned, it was a morality fable, not a sequence of historical events.

As simple as this proof can be, we need to remind ourselves that the ancient Greek didn't manipulate numbers as we do. It was only in the 16th century that the French mathematician François Viète [introduced a notation](https://plato.stanford.edu/entries/descartes-mathematics/#GeoAnaAlg) that allowed him to treat magnitudes in a general way, such that $A + B$ could mean summing up different quantities or combining two line segments. The idea of coordinates in a plane came from René Descartes only in the 17th century (and yeah, that's why it's called the Cartesian plane). After some search I was able to find the proof of the irrationality of $\sqrt{2}$ included in an appendix to Heiberg's edition of Euclid's Elements, [translated](https://humanities.classics.narkive.com/oLNJt64V/euclid-s-elements-book-x-prop-117) by the mathematician William C. Waterhouse:

> IT IS SET FOR US TO PROVE THAT, IN A SQUARE FIGURE, THE DIAMETER AND THE SIDE ARE INCOMMENSURABLE IN LENGTH. 
> 
> Let ABCD be a square , with diameter AC. I say that CA, AB are incommensurable in length.
>
> For suppose, if possible, that they are commensurable. I say that then the same number would be even and odd. For it is clear that the square on AC is twice that on AB. As CA, AB are commensurable, they have the ratio of a number to a number. Say CA is to AB as EZ is to H, and let EZ and H be the smallest of those having that same ratio.
>
> Then EZ is not the unit. For if it is, and EZ is to H as AC to AB, and AC is greater than AB, then EZ is greater than H, the unit bigger than a number, which is absurd. Thus EZ is not the unit and hence is a number.
  > 
> Since CA is to AB as EZ is to H, then also the square on CA is to the square on AB as the square on EZ is to the square on H. But the square on CA is twice the square on AB, so the square on EZ is twice the square on H. Hence the square on EZ is even. Consequently, EZ itself is even; for if it were odd, its square would also be odd, since when an odd number of odd summands are combined, the total is odd. Thus EZ is even. 
  > 
> Split it into two equal parts at T. Since EZ, H are the smallest with the same ratio, they are prime to each other. And EZ is even, so H is odd. Indeed, if it were even, 2 would measure EZ and H, since every even number has a half; this is impossible for numbers prime to each other, and thus H is not even. Hence it is odd.
  > 
> Since EZ is twice ET, the square on EZ will be four times that on ET. But the square on EZ is twice that on H, so the square on H is twice the square on EZ. Hence the square on H is even. By what was said earlier, H is even. But it is also odd; which is impossible. Thus CA and AB are not commensurable in length, QED.

---
# Uma simples mas bela prova

Provar que $\sqrt{2}$ é irracional é muito simples: pode-se fazer isso com nada mais do que as ferramentas que aprendemos no ensino fundamental, e acredito que mais pessoas deveriam apreciar isso e todo o conhecimento que se pode obter mergulhando na história por trás disso.

Antes de mais nada, o que é um *número irracional?* Em termos simples, um número *racional* é um número real que pode ser expresso como a razão de dois inteiros $\dfrac{a}{b}$, e um número *irracional* é um número real que não é racional. Se você pegar a diagonal de um quadrado unitário, você teria um segmento de comprimento $\sqrt{2}$. Agora, o que torna esse número - ou números irracionais em geral - tão especial?

Vamos dar um passo para trás e pensar sobre isso em termos de geometria. Pegue dois comprimentos como $473 cm$ e $100cm$, por exemplo. Ambos podem ser medidos em termos de uma unidade comum (e.g. o centímetro) com precisão, então os chamamos de *comensuráveis*. Agora, pegue a diagonal de um quadrado unitário e seu lado. Essas medidas são *incomensuráveis*: se dois comprimentos não podem ser expressos como uma razão de inteiros, isso significa que não há uma unidade de medida comum - por menor que seja - que possa ser usada para medir ambos os comprimentos em seu tamanho exato. Vamos provar que esse é o caso para $\sqrt{2}$ usando uma ferramenta chamada *reductio ad absurdum* (latim para "redução ao absurdo"), que consiste em (1) assumir que uma hipótese é verdadeira, (2) mostrar que se essa hipótese for verdadeira, ela leva a uma contradição, e (3) se isso leva a uma contradição, a hipótese deve ser falsa.

Então, vamos construir nossa prova:

1) Suponha que $\sqrt{2}$ possa ser expresso como a razão de dois inteiros $a$ e $b$, e $a$ e $b$ não têm denominador comum além de 1 (em outras palavras, você não pode "simplificar" a fração):
$$\dfrac{a}{b} = \sqrt{2}$$
2) Elevando ambos os lados ao quadrado e então multiplicando ambos os lados por $b^2$, temos:
$$
\begin{aligned}
\dfrac{a^2}{b^2} = 2 \\ \\
a^2 = 2b^2
\end{aligned}
$$
3) De (2) temos que $a^2$ é par, e então $a$ também é par (um número par ao quadrado é sempre par e um número ímpar ao quadrado é sempre ímpar).
4) Se $a$ for par, pode ser escrito na forma $a = 2k$, onde $k$ também é um inteiro.
5) De (2), temos:
$$
\begin{aligned}
a^2 = 2b^2 \\
(2k)^2 = 2b^2 \\
4k^2 = 2b^2 \\
b^2 = 2k^2
\end{aligned}
$$

6) Então mostramos que se $a$ for par, $b^2$ é par e, portanto, $b$ também é par. Mas se $a$ e $b$ forem ambos números pares, isso contradiz nossa hipótese (1). Portanto, $\sqrt{2}$ é um número irracional e não pode ser escrito como uma razão de dois inteiros.

Não sabemos ao certo quem foi a primeira pessoa a mostrar isso: a prova é frequentemente atribuída a Hipaso de Metaponto, mas nenhuma fonte antiga ligou Hipaso à descoberta da irracionalidade. Também é dito que a pessoa que revelou essa descoberta foi jogada ao oceano como punição, ou que foi banida da comunidade e uma lápide foi erguida com seu nome. No entanto, esses são provavelmente mitos, como [apontado](https://kiwihellenist.blogspot.com/2015/11/were-greeks-scared-of-irrational-numbers.html) pelo classicista Dr. Peter Gainsford:

> Então, o que a evidência real nos diz? O testemunho sobrevivente é o seguinte, em ordem cronológica.
>
> - Final do século II d.C.: Clemente de Alexandria, [_Stromateis_ 5.9.57](https://archive.org/stream/writingsofclemen02clem#page/255/mode/2up). Clemente relata que um pitagórico chamado "Hiparco" revelou os ensinamentos de Pitágoras em um livro. Como um símbolo de sua expulsão da seita, os pitagóricos ergueram uma lápide como se ele estivesse morto.
> - Século III-IV d.C.: Jâmblico, _Vida de Pitágoras_ nos conta:
> 	- [88-9 (§18)](https://archive.org/stream/CompletePythagoras#page/n35/mode/1up): Hipaso, um pitagórico, revelou a descoberta de que os vértices de um [dodecaedro](https://en.wikipedia.org/wiki/Dodecahedron)regular coincidem com a superfície de uma esfera, e por causa de sua heresia ele foi jogado ao mar;
> 	- [246 (§34)](https://archive.org/stream/CompletePythagoras#page/n74/mode/1up): um homem que tornou pública a natureza das razões racionais e irracionais foi tão odiado pelos pitagóricos que eles o expulsaram e ergueram um túmulo como se ele estivesse morto;
> 	- [247 (§34)](https://archive.org/stream/CompletePythagoras#page/n74/mode/1up): um homem que revelou a construção do dodecaedro afogou-se no mar, punido por uma divindade; outros dizem que isso aconteceu com o homem que revelou a natureza das razões racionais e irracionais.
>
>[...]
>
>Mas o pior de tudo é que **mesmo este resumo honesto é provavelmente completamente falso** também. O relato mais completo vem de Jâmblico, e Jâmblico é notoriamente não confiável. Pappos deixa claro que, no que lhe diz respeito, era uma fábula moral, não uma sequência de eventos históricos.

Por mais simples que essa prova possa ser, precisamos nos lembrar de que os gregos antigos não manipulavam números como nós hoje. Foi somente no século XVI que o matemático francês François Viète [introduziu uma notação](https://plato.stanford.edu/entries/descartes-mathematics/#GeoAnaAlg) que lhe permitiu tratar magnitudes de uma forma geral, de modo que $A + B$ poderia significar somar quantidades diferentes ou combinar dois segmentos de reta. A ideia de coordenadas em um plano veio de René Descartes somente no século XVII (e sim, é por isso que é chamado de plano cartesiano). Depois de alguma pesquisa, consegui encontrar a prova da irracionalidade de $\sqrt{2}$ incluída em um apêndice da edição de Heiberg dos Elementos de Euclides, [traduzida](https://humanities.classics.narkive.com/oLNJt64V/euclid-s-elements-book-x-prop-117) pelo matemático William C. Waterhouse:

> ESTÁ DEFINIDO PARA NÓS PROVAR QUE, EM UMA FIGURA QUADRADA, O DIÂMETRO E O LADO SÃO INCOMENSURÁVEIS EM COMPRIMENTO.
>
> 	Seja ABCD um quadrado, com diâmetro AC. Eu digo que CA, AB são incomensuráveis ​​em comprimento.
>
> Pois suponha, se possível, que eles são comensuráveis. Eu digo que então o mesmo número seria par e ímpar. Pois é claro que o quadrado em AC é o dobro do que em AB. Como CA, AB são comensuráveis, eles têm a razão de um número para um número. Digamos que CA está para AB como EZ está para H, e sejam EZ e H os menores daqueles que têm a mesma razão.
>
> Então EZ não é a unidade. Pois se for, e EZ está para H como AC está para AB, e AC é maior que AB, então EZ é maior que H, a unidade maior que um número, o que é absurdo. Assim, EZ não é a unidade e, portanto, é um número.
>
> Como CA está para AB como EZ está para H, então também o quadrado em CA está para o quadrado em AB como o quadrado em EZ está para o quadrado em H. Mas o quadrado em CA é o dobro do quadrado em AB, então o quadrado em EZ é o dobro do quadrado em H. Portanto, o quadrado em EZ é par. Consequentemente, EZ em si é par; pois se fosse ímpar, seu quadrado também seria ímpar, pois quando um número ímpar de somas ímpares são combinadas, o total é ímpar. Assim, EZ é par.
>
> Divida em duas partes iguais em T. Como EZ, H são os menores com a mesma razão, eles são primos entre si. E EZ é par, então H é ímpar. De fato, se fosse par, 2 mediria EZ e H, já que todo número par tem uma metade; isso é impossível para números primos entre si, e assim H não é par. Portanto, é ímpar.
>
> Como EZ é duas vezes ET, o quadrado em EZ será quatro vezes maior que em ET. Mas o quadrado em EZ é duas vezes maior que em H, então o quadrado em H é duas vezes maior que em EZ. Portanto, o quadrado em H é par. Pelo que foi dito antes, H é par. Mas também é ímpar; o que é impossível. Portanto, CA e AB não são comensuráveis ​​em comprimento, QED.