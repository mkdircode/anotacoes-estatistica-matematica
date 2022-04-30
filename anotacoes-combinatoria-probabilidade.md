
Resumão:

- [ ] Combinatória - problemas de contagem &lt;=&gt; Prob
- [ ] **PFC** \- escolhas em cada etapa ❌
- [ ] **Elementos** ( n ) e **Posições** ( p )
- [ ] Simples e com Repetição
- [ ] Fatorial (n❗️)
- [ ] Número Binomial &lt;=&gt; Cn,p . Triângulo de Pascal (soma => acha nºs binomiais)

$$
n \geq p
$$

\[\inline https://latex.codecogs.com/svg.image?\inline \bg{white}n\geq p\]
.

$$
\binom {n}{p} = \frac {n!}{p! (n - p)!}  


$$
.
dá result 1 qd: (p = 0 ) ou (n = p)

Triângulo Pascal aux cálc Combinações, achar Coeficientes binomiais

![triangpascalwiki.PNG](:/71a1ede5eca64f7bb6a1ac56c439b2c9)

- **Binômio de Newton**: técnica pra calc polinômios.
    
    - coeficientes 1 ; 1 na linha 1: $(a+b)^1$
    - coeficientes 1; 2; 1 na linha 2: $(a+b)^2 = a^2 + 2 a.b + b^2$
    - 1 ; 3; 3; 1 na linha 3: $(a+b)^3 = a^3 + 3 a^2b + 3 ab^2+b^2$
    - 1; 4; 6; 4; 1 na linha 4: $(a+b)^4=a^4+4a^3b+6a^2b^2+4ab^3+b^4$
- $(x+y)^n=\binom{n}{n-1}xy^{n-1}+ \binom{n}{n}y^n =\binom{n}{0}x^n +\binom{n}{1}x^{n-1}y + \binom{n}{2}x^{n-2}y^2. . .$
    

[Binômio Newton_mundo educacao uol](https://mundoeducacao.uol.com.br/matematica/binomio-newton-desenvolvendo-expressao-bn.htm "Binômio Newton_mundoeducacaouol")

* * *

- [ ] se ==**n > p**== ? Arranjo simples (**==An,p==** A **Ordem importa**) e Combinação simples (**==Cn,p== Ordem não importa**)
- [ ] não usa todos os elementos

$$
An,p = \frac{n!}{(n-p)!} 




$$

$$
Cn,p = \frac{n!}{p! .(n-p)!} 




$$

- [ ] se ==**n = p**== ? Permutação simples (==**Pn** = n ❗️==) : embaralhar, **ordenar usa**ndo **todos** os **elementos**;
    
- [ ] Anagramas sem repetição
    
- [ ] Permutação **COM Repetição** (==**PR** elementos! / repetições!== )
    
    $$
    P_{elementos}^{repeticões} = \frac{elementos !}{repeticões!} 
    
    
    
    
    $$
    
- [ ] **Permutação Circular (**==PCn==**)**: elementos em ordem cíclica
    

$$
PC_n = (n-1)! 




$$

- [ ] **Arranjo com Repetição** (**==AR==**, **pode ter ==n < p==**)

$$
AR_n,_p = n ^p 




$$

- [ ] **Combinação com Repetição** (==CR==)

$$
CR_n,_p = \frac {(n+p-1) ! }{p! . (n-1)!}  




$$

- [ ] Universo
    
- [ ] Espaço Amostral (==**S**==): conj Elemento / Membros => ==Todos results Possíveis==.
    
- [ ] Espaços Equiprováveis e Não equiprováveis
    
- [ ] ==Evento aleatório==: **subconj S**
    
- [ ] **P(E)** = casos favoráveis à E / casos possíveis = qtd elementos E / qtd elementos S
    
- [ ] Prob entre 0 a 1.
    
- [ ] Teorema da Soma (**A ou B = A U B**)
    
- [ ] com Intersecção P(A U B) = P(A) + P(B) - P(A $\cap$ B)
    
- [ ] sem Intersecção (intersecção = 0) => ==**Mutuamente Excludentes**== **P(A U B) = P(A) + P(B)**
    
- [ ] Evento **Complementar** 1 - Prob
    
- [ ] ==Prob **Condicional**==
    

$$
P(A | B) = \frac{P(A\cap B)}{P(B)}  \leftrightarrow Teorema \ do \ Produto \ P(A\cap B)= P(A | B) . P(B) 




$$

- [ ] Eventos ==**Independentes**==

$$
P(A\cap B)= P(A) . P(B) 




$$

- [ ] ==**Teorema da Prob Total**==

$$
P(B) = \sum\limits_{i=1}^{n} P(A_i \cap B) \leftrightarrow P(B)= \sum\limits_{i=1}^{n} P(B | A_i). P(A_i) 



$$

- [ ] ==**Teorema de Bayes**==
    
    $$
    P(A_k | B) = \frac {P (B | A_k) . P(A_k)} {P(B)} = \frac {P (B | A_k) . P(A_k)}{\sum\limits_{i = 1}^{n} P(B| A_i) . P(A_i) } 
    
    
    
    $$
    

# **Vars Aleatórias Quantitativas ==(V.A)==**

- [ ] ==**V.A Discreta**==: enumerável
- [ ] **F.D.P para V.A Discretas** (Função Distribuição Probabilidade): contar nº casos favoráveis e casos possíveis.

> **FDP** nos dá a **probabilidade acumulada**. Chance de X assumir valores $FDP(número) = P(X\leq número)$.

- E(x), Var, Dp, CV** de Vars Discretas

⭐️ Na Dist. Binomial, **E(X) = n.p**. **Var = (n.p.q)**

- [ ] ==**V.A Contínua**==: não enumerável (infinitos pontos na reta real)
    
- [ ] f.d.p Função Densidade Prob
    
- [ ] **F.D.P para V.A Continua** (Função Distribuição Probabilidade): não consegue CONTAR nº casos favoráveis, nem o nº casos possíveis. Pra determinar as probabilidades usamos a **FUNÇÃO DENSIDADE** (área do gráfico = probabilidade)
    
- [ ] **E(x), Var, Dp, CV** de Vars ==Contínuas==
    

* * *

# Distribuições V.A Discretas

- [ ] Distribuição Uniforme Discreta
- [ ] Distribuição/ **Experimento de ==Bernoulli q = 1 - p==**
- [ ] sucesso 1, p
- [ ] fracasso 0, q

$P(X=x)= p^x(1-p)^{1-x}$

- [ ] ==**Distribuição Binomial**==: experimento Bernoulli repetida n vezes. Calc prob k sucessos em n tentativas. O nº lançamentos é FIXO, a var X india o nº de sucessos.

$P(X =k) = \binom{n}{k} p^k(1-p)^{n-k}$

k = qtd sucessos

[Geogebra - Dist Binomial - Dhiego Loiola](https://www.geogebra.org/m/xc6wqd5t)

- [ ] **Esperança** na Dist Binomial $\mu = E(X) = np$
    
    - [ ] n = qtas vezes repete experimento; p=prob sucesso; q=prob fracasso
- [ ] **Variância** $\sigma^2 = npq$
    
- [ ] ==**Dist. Geométrica**==: repetir até o 1º sucesso
    
- [ ] Enquanto na Binomial o nº lançamentos é cte e a variável X indica o nº de sucessos, na GEOMÉTRICA, o **nº de sucessos** é **FIXO** valendo **= 1** (pq está interessado em apenas 1 sucesso) e **variável** **X** indica o **nº de lançamentos**.
    

$$
X = k = (q^{k-1}).(p)


$$

$$
E(X) = \frac{1}{p}


$$

$$
V(X)= \frac{1}{p^2}


$$

- [ ] ==**Dist. Hipergeométrica**==: Prob varia de acordo com tamanho da amostra
    
- [ ] ==**Dist Poisson**==
    

https://www.geogebra.org/m/PUS7ZYW8

# Distribuições V.A Contínua

- [ ] **f.d.p** (Função Densidade Prob) &lt;–&gt; proprieds Histograma (ÁREA = 1, **ÁREA &lt;–&gt; Prob**)
- [ ] Histograma: densidade freq = Fr / h
- [ ] f.d.p = amplitude (h), ou seja, tamanho do intervalo tende a zero.

> áreas: Trapézio = (B+b)/2 * h
> 
> Triângulo = b.h / 2
> 
> Retângulo = b.h

- f.d.p com **Integral**: qd função não é uma reta, Integral facilita cálc área.

> $$
> integral\ X^n = \frac{x^{n+1}}{n+1}
> 
> 
> $$

> $$
> e^x = e^x 
> 
> 
> $$

> $$
> e^{ax} = \frac{e^{ax}}{a}
> 
> 
> $$

- [ ] Distribuição Uniforme Contínua
- [ ] ==**Distribuição Normal / Gaussiana**==
- [ ] \[ \]

* * *

- [ ] *Como pode viciar um dado? baralho? bolas na roleta de um bingo?*
    
- [ ] *jogo de baralho: 52 cartas,*
    

* * *

* * *

* * *

# **Análise Combinatória**

- pte da Matemática pra resolver problemas de contagem (possibilidades).

## **PFC** (Princp Fund Contagem / Princp Multiplicativo ❌ ):

- Etapas sucessivas e independentes. Em cada etapa faz n escolhas => Multiplica escolhas.

> 👕Possibilidades de looks de 2 calças, 3 blusas, 4 chapéus => 3 etapas, => 2 x 3 x 4 = 24 possibilidades de looks.
> 
> Qtos nºs naturais com 3 algarismos podemos formar? => 10 Algarismos 0 a 9 => Restrição no 1º algarismo não pode ser nº 0 => 9 x 10 x 10 = 900 possibilidades.

> Qtos nºs Naturais pares com 3 algarismos podemos formar?
> 
> $$
> Número  \neq Algarismo 
> 
> 
> 
> 
> $$
> 
> Restrição: ser nº par, pra ser par tem q terminar (0,2,4,6,8) 1º algarismo, Restrição é não começar com 0 => tem 9 opções ; 2º algarismo, sem restrição => 10 opções ; 3º algarismo, ser par => 5 opções (0,2,4,6,8) ;
> 
> 9 x 10 x 5 = 450 possibilidades de nºs naturais

## Fatorial (n❗️)

- nº inteiro positivo;
- multiplica pelos antecessores
- 0! =1! = 1

> 2 . 5! = 2 .(5 x 4 x 3 x 2 x 1) = 2 x 120 = 140
> 
> (2.5)! = 10! = 3.628.800
> 
> 2! . 3! = 2 x1 x 3 x 2 x 1 = 12
> 
> (2.3)! = 6! = 720

## Número Binomial

$$
n \geq p




$$

$$
\binom {n}{p} = \frac {n!}{p! (n - p)!}  




$$

- se p = 0 => result 1
- se n = p => result 1

**Triângulo de Pascal**: acha nºs binomiais **somando**

- **n Elementos, p Posições** elementos n >= p posições

# Permutação Simples (sem repetir, n = p) Pn = n!

- técnica de contagem pra determinar qtas maneiras tem de ORDENAR, embaralhar elementos de um conjunto FINITO.
- Permutação simples (Pn = n ❗️) é um caso particular do Arranjo Simples (Ordem importa);
- ANAGRAMAS SEM Repetição

> 5 pessoas e 5 cadeiras. Qtas formas podemos acomodar estas pessoas nas cadeiras? 5 x 4 x 3 x 2 x 1 = 5! = 120 formas
> 
> Anagramas da palavra MEL: n = 3, p = 3. $P_3$ = 3! = 6 anagramas.
> 
> Anagramas da palavra REVISTA, devendo manter letras EVI juntas e nesta ordem? : considera EVI como um bloco => 5! = 120
> 
> Anagramas da palavra REVISTA, devendo iniciar com a letra T: 1ª posição reservado pra T e outras letras ordenadas nas posições seguintes => 1 . 6! = 720

## Permutação com Repetição (elementos! / repetições! )

$$
Permutacão \ com \ Repeticão \neq Arranjo \ com \ Repeticão 




$$

tem elemento repetido;

- ANAGRAMAS COM Repetição

*no **Arranjo com Repetição** pode repetir elemento; pode ter **n < p* posições maior elementos &lt;=&gt; PFC *

> Anagramas ATA => ATA, TAA, AAT 3 letras, A repete 2 vezes
> 
> $$
> P_{3}^{2} =  \frac {3!} {2!} = 3 
> 
> 
> 
> 
> $$
> 
> Anagramas ARARA => 5 letras, 3 repetições A, 2 repetições R
> 
> $$
> P_{5}^{3,2} = \frac{5!}{3! . 2!} = 10 
> 
> 
> 
> 
> $$

## Permutação Circular

- n elementos em ordem cíclica

$$
PC_n = (n-1)! 




$$

> Qtas formas 4 crianças podem sentar em um brinquedo gira gira carrossel de 4 cadeiras? as posições não mudam, quem está sentado em uma cadeira (independente de qtas vezes girar) sempre ficará com as mesmas pessoas ao lado e a frente. Então, as 4 posições, formam a mesma combinação. 4! / 4 = 3! &lt;=&gt; PC (4-1)! = 6

* * *

# Arranjo e Combinação Simples (sem repetir, n > p)

- **Arranjo Simples**: Ordem importa;
    - Não utiliza todos os elementos;
    - Sem repetir elementos;

$$
An,p = \frac{n!}{(n-p)!} 




$$

> Qtas possibilidades de senhas existem em um cofre, sabendo q nesse cofre as senhas tem 4 dígitos e q os dígitos de cada senha devem ser distintos?
> 
> n = 10 {0,1,2…9}; p = 4 => n > p
> 
> 10 x 9 x 8 x 7 = 5040
> 
> ou com a fórmula A10, 4 = 10! / (10-4)! = 5040

> Qtas possibilidades de senhas existem em um cofre que funciona apenas os botões (4, 5, 7 e 8) sabendo q nesse cofre as senhas tem 4 dígitos e q os dígitos de cada senha devem ser distintos?
> 
> n = 4 = p => Permutação Simples;
> 
> 4! = 24 possibilidades de senhas; Se usasse a fórmula Arranjo: 4! / 0! = 4! = 24

- **Combinação simples**: ordem Não importa; sem repetir elementos

$$
Cn,p =  	{n \choose p}  = \frac{n!}{p! .(n-p)!} 




$$

> Na aposta Mega-sena, vc escolhe 6 números dos 60 disponíveis. Qts jogos distintos é possível fazer? (60 x 59 x 58 x 57 x 56 x 55 ) / 6! pq como não importa a ordem, 6 posições são o msm conj de números = 36.045.979.200 / 720 = 50.063.860
> 
> pela fórmula: C60, 6 = 60! / 6! (54!) = 50.063.860

- relação (&lt;-&gt; Triângulo Pascal é simétrico: 1º elemento do triâng igual ao Último; 2º elemento ao Penúltimo…):

$$
C_n,\ _p = C_n,\ _ {n-p} 




$$

## Arranjo com Repetição (AR)

- importa a ordem e pode repetir
- pode ter p > n (qtd posições > qtd elementos)

$$
AR_n,_p = n ^p 




$$

> Qts possibilids de senhas existem em um cofre sabendo q nesse cofre as senhas tem 15 dígitos? n = 10; p = 15 ; n < p
> 
> $$
> A_n,_p = 10 ^{15}  
> 
> 
> 
> 
> $$

## Combinação com Repetição (CR )

- Ordem Não importa

$$
CR_n,_p = \frac {(n+p-1) ! }{p! . (n-1)!}  




$$

- pode calcular como Combinação simples n = Cn + p - 1

$$
CR_n,_p = C_n + p-1, p 




$$

- ou pode tb como Permutação

$$
CR_n,_p = P_{n+p-1}^{p, n-1} 




$$

> Shirley faz 3 tipos de doces (brigadeiro, beijinho e cajuzinho) e vende uma caixa com 8 doces dentre estes 3 tipos. Qts combinações distintas é possível fazer, em relação a esta caixa de doces? n = 3, p = 8. n < p .
> 
> $$
> \perp 2 \ Divisorias\ dos \ Docinhos 
> 
> 
> 
> 
> $$
> 
> $$
> \triangle \ 8 Docinhos  
> 
> 
> 
> 
> $$
> 
> $$
> doce1 \triangle \ , \triangle ,\ \triangle ,\ \perp  \triangle ,\  \triangle ,\perp\ \triangle ,\ \triangle ,\ \triangle doce 8 \ 
> 
> 
> 
> 
> $$
> 
> no total: 10 elementos (8 docinhos e 2 divisórias) => Permutação desses 10 elementos Como tem repetição:
> 
> $$
> P_{10} ^ { \ 8, 2} = \frac {elementos!}{repeticões!} = \frac {10!}{8! . 2!} = 45 combinações 
> 
> 
> 
> 
> $$
> 
> pela fórmula:
> 
> $$
> CR_{3}^{8} = \frac {10!}{8!.2!} = 45 
> 
> 
> 
> 
> $$

(enem 2017) - precisava saber fórmula

> Brinquedo caminhão-cegonha formado por uma carreta com 10 carrinhos. No setor de pintura são usadas cores amarelo, branco, laranja e verde, e cada carrinho é pintado de uma cor. O caminhão-cegonha tem uma cor fixa. A empresa determina q em todo caminhão-cegonha deve haver pelo menos 1 carrinho de cada uma das 4 cores disponíveis. Mudança de posição dos carrinhos no caminhão-cegonha não gera um novo modelo do brinquedo. Quantos modelos distintos do brinquedo a empresa poderá produzir?
> 
> Ordem não importa e pode repetir => Combinação com Repetição.
> 
> n = 4, p = 6 (ñ é 10 pq já está determinado q tenha pelo menos usado uma das 4 cores. Se os 4 primeiros carrinhos já possuem uma cor, os outros 6 carrinhos pode pintar à vontade, repetindo qualquer uma das cores)
> 
> relação com Combinação Simples Cn+p-1,p = C4+6-1, 6 = C9,6. Se:
> 
> $$
> C_n,\ _p = C_n,\ _ {n-p} 
> 
> 
> 
> 
> $$
> 
> $$
> C_9,\ _6 = C_9,\ _ {9-6} = C_9,\ _ {3} 
> 
> 
> 
> 
> $$
> 
> com a fórmula
> 
> $$
> CR_4,_6 = \frac {(4+6-1)!}{6! (4-1)!} = \frac {9!}{3! 6!} = C_9,_3 
> 
> 
> 
> 
> $$

```mermaid
    flowchart LR
     id> Estatística]
        




```

- [ ] **Probab**ilidade (conhece população/ espaço amostral -> qual probabilide de ocorrer evento?);
    
- [ ] Estatística **Descritiva**;
    
- [ ] Estatística **Inferencial** (conhece evento / amostra -> como população se comporta?).
    
    ```mermaid
    flowchart LR
     id> Probabilidade]
    
    
    
    
    
    ```
    

* * *

- Fenômenos: **Determinístico** (results sempre os mesms) e **Probabilístico/ Aleatórios**.
    
- Probabilidade estuda **Aleatoriedade** e **Incerteza**
    
- Espaço **Amostral** (**S**): conjunto de todos possíveis resultados/ eventos.
    
    - Espaço **Equiprovável**: todos pontos (elementos) amostrais tem a mesma chance de ocorrer (ex dado honesto).
    - Evento Aleatório (**E**): subconjunto do (S).

> Embora os experimentos aleatórios tenham resultados incertos e não determinísticos, podemos calcular todas as possibilidades de resultados dos experimentos aleatórios através das distribuições de probabilidades. O valor de cada probabilidade na distribuição de probabilidades está no intervalo de 0 a 1, já que a soma de todas as probabilidades é 1 (ou seja 100%).

$$
P(E)= \frac{casosfavoraveis}{casos possíveis} = \frac {n(E)} {n(S)} 




$$

- P(E) entre 0 e 1
    
- n(E) qtd elementos do Evento e n(S) qtd elementos do Espaço Amostral.
    
- experimentos aleatórios => **V.A’s** (letras maiúsc)
    
- var quantitativa (valor). ex: quantificar cada ponto do espaço amostral de uma moeda atribuindo 0 pra Cara e 1 pra coroa; nº coroas lançando 2 moedas; nº itens defeituosos em uma amostra; intervalo de peso de uma amostra da população de um bairro; nº pessoas visitam site num certo período de tempo;
    
- V.A DISCRETA: conj results possíveis é FINITO, ENUMERÁVEL
    
    - 👀 Finito $\neq$ Limitado (em um intervalo entre 2 valores tem Infinitos pontos)
- V.A CONTÍNUA: valores não enumerável e por isso são expressos como intervalo ou união de nºs reais (ex: peso, altura, massa, nível de açúcar no sangue)
    

> \> Os experimentos probabilísticos (ou também chamados de aleatórios) podem ser constituídos por variáveis aleatórias discretas ou variáveis aleatórias contínuas. As variáveis aleatórias discretas são valores que podem ser quantificados e listados, enquanto que as variáveis aleatórias contínuas são valores que podem ser subdivididos, ou seja, estão em determinado intervalo.
> 
> - *Ciência é determinística ou probabilística? Se soubermos todas vars e condições, conseguimos determinar o resultado?* *teoria que prevalece hoje -> Mecânica Quântica -> sabendo todas vars ainda tem certa aleatoriedade*

&lt;–\&gt; Função q associa cada valor da V.A com a sua prob

- f.d.p (função densidade prob)

# Teorema da Soma (A OU B, com intersecção = A U B)

P(A U B) = P(A) + P(B) - P(A $\cap$ B)

> **Lançamento de dado**
> 
> S = {1, 2, 3, 4, 5 ,6}
> 
> A: result > 2, então P(A) = {3, 4, 5, 6} =
> 
> $$
> P(A)= \frac{4}{6}
> 
> 
> 
> 
> $$
> 
> B: result par , então P(B)= {2,4,6} =
> 
> $$
> P(B)= \frac{3}{6}
> 
> 
> 
> 
> $$
> 
> A $\cap$ B = {4, 6}
> 
> $$
> \frac{2}{6} 
> 
> 
> 
> 
> $$
> 
> P(A U B) = {2, 3, 4, 5, 6}
> 
> $$
> \frac{5}{6} 
> 
> 
> 
> 
> $$
> 
> Teorema da Soma: P(A U B)= P(A) + P(B) - P(A $\cap$ B)
> 
> $$
> \frac{5}{6}  = \frac{4}{6} + \frac{3}{6} - \frac{2}{6}
> 
> 
> 
> 
> $$

# Eventos Mutuamente Excludentes ( A OU B, sem intersecção)

P(A U B) = P(A) + P(B)

- P(A $\cap$ B) = 0
- União: somar prob de cada um.

# Espaços não equiprováveis

- Como viciar dados, baralhos, bolinhas? : pintar com tinta metálica pro lado ficar mais pesado e ter +chance de sair uma face.  . Pesos nas bolinhas tendem a ter +chance de saírem.

> Ex: Numa empresa 10% lâmpadas produzidas possuem algum defeito. Qual prob de ao selecionar 3 lâmpadas, no máximo, 1 possuir algum defeito?
> 
> com defeito: 0,10 e sem defeito: 0,90
> 
> C S S ou S C S ou S S C => 0,10 . 0,90 . 0,90 = 0,081 x 3 = 0,243
> 
> ou S S S => 0,90 . 0,90 . 0,90 = 0,729
> 
> P(máximo um Com defeito) = 0,972

> Ex: Prob de sair cara de uma moeda viciada é 0,6. Qual prob sair exatamente 3 coroas lançando 4 vezes?
> 
> Ca = 0,6 e Co = 0,4.
> 
> P(3 Co) = (0,4 . 0,4. 0,4 . 0,6) x 4 = 0,1536
> 
> ou como a Ordem Não importa => **Combinação**. n = 4 total de moedas, p = 3 Coroas
> 
> $$
> C_4,_3 = \frac {4!}{3! . 1!} = 4 
> 
> 
> 
> 
> $$
> 
> ou ainda, n = 4, p = 1 Cara
> 
> $$
> C_4,_1 = \frac {4!}{1! . 3!} = 4 
> 
> 
> 
> 
> $$

> Ex: Prob sair cara na moeda viciada é 0,6. Qual a prob sair pelo menos uma coroa, lançando esta moeda 4 vezes?
> 
> mais fácil calc complementar 1 - prob(4 caras)
> 
> $$
> P(Caras) = 0,6 . 0,6 . 0,6 . 0,6 = 0,6^4 = 0,1296 
> 
> 
> 
> 
> $$
> 
> ou
> 
> $$
> C4,4 = 1 
> 
> 
> 
> 
> $$
> 
> 1 - P(Caras) = 1 - 0,1296 = 0,8704

# Prob. Evento Complementar

evento A $\subset$ S

$$
P(A^\complement ) = 1 - P(A) 




$$

# Probabilidade Condicional

$$
P(A | B) = \frac{P(A\cap B)}{P(B)}  <=> Teorema \ do \ Produto \ P(A\cap B)= P(A | B) . P(B) 




$$

- Prob de ocorrer A, dado q ocorreu B
- como um evento (B) já aconteceu, o espaço amostral ‘original’ (S) fica reduzido. Agr o espaço amostral será B.

# Eventos Independentes

Prob de ocorrer um evento não depende do outro ter ocorrido. P(A | B) = P(A)

$$
P(A\cap B)= P(A) . P(B) 




$$

> Ex1: na urna tem 4 bolas vermelhas, 4 verdes, 3 amarelas e 2 azuis, qual a prob de selecionar 2 bolas em um sorteio **com reposição**?
> 
> total 13 bolas.
> 
> Eventos A: 1ª bola sair vermelha e B: 2ª bola vermelha. => sair A **e** B => P(A $\cap$ B)
> 
> 4 chances de sair vermelha em 13 tanto na A qto na B.
> 
> $$
> \frac {4}{13} .  \frac {4}{13} =  \frac {16}{169} = 0,0947 
> 
> 
> 
> 
> $$

> Ex2: na urna tem 4 bolas vermelhas, 4 verdes, 3 amarelas e 2 azuis, qual a prob de selecionar 2 bolas em um sorteio **sem reposição**?
> 
> A: sair 1ª vermelha. B: 2ª vermelha. => sair A **e** B => P(A $\cap$ B)
> 
> porém como é COM REPOSIÇÃO, A interfere no B => na Prob. Condicional P(A $\cap$ B) é:
> 
> $$
> P(A \cap B) = P(B | A). P(A) 
> 
> 
> 
> 
> $$
> 
> $$
> P(A) = \frac {4}{13}
> 
> 
> 
> 
> $$
> 
> $$
> P(B | A) = \frac {3}{12} 
> 
> 
> 
> 
> $$
> 
> $$
> P(A \cap B) = \frac {1}{13} = 0,077 
> 
> 
> 
> 
> $$

# Teorema da Prob Total

> 3 fábricas de lâmpadas X, Y e Z fornecem para o mercado. As lâmpadas da X trabalham por mais de 5.000 horas em 99% dos casos, enqto na Y trabalham por mais de 5000 h em 95% e da Z em 90% dos casos. Sabe-se q a X fornece 60% e Y fornece 30% das lâmpadas. Qual a chance de q a lâmpada comprada irá funcionar por mais de 5000 horas?
> 
> selecionar 1 lâmpada no mercado de cada fábrica:
> 
> P(X) = 0,6. P(+5k | X) = 0,99.
> 
> P(Y) = 0,3. P(+5k | Y) = 0,95
> 
> P(Z) = 0,1. P(+5k | Z) = 0,90.
> 
> pelo Teorema Prob. Total
> 
> $$
> P(B) = \sum\limits_{i=1}^{n} P(A_i \cap B) \leftrightarrow P(B)= \sum\limits_{i=1}^{n} P(B | A_i). P(A_i) 
> 
> 
> 
> $$
> 
> P(+5k) = 0,99.(0,6) + 0,95.(0,3) + 0,90.(0,1) = 0,969 = 96,9%

# Teorema de Bayes

- como chegar na fórmula T.Bayes?

Prob Condicional &lt;–&gt; T. Bayes

$$
P(A | B) = \frac{P(A\cap B)}{P(B)}  




$$

&lt;=\&gt; Teorema do Produto

$$
\ P(A\cap B) => P(A | B) . P(B)  = P(B | A). P(A) 



$$

substituindo acha o T.Bayes ‘simplificado’:

$$
P(A_k | B) = \frac{P(B | A_k) . P(A_k)}{P(B)} 



$$

Mas se não tiver o P(B), substituir pelo T. Prob. Total. Assim, o T. Bayes ‘genérico’:

$$
P(A_k | B) = \frac {P (B | A_k) . P(A_k)} {P(B)} = \frac {P (B | A_k) . P(A_k)}{\sum\limits_{i = 1}^{n} P(B| A_i) . P(A_i) } 



$$

# Função de Probabilidade

- associa cada valor da V.A com sua probabilidade
- $\geq$ 0

> - dado honesto, V.A valores obtidos no dado, f prob é:
> 
> S: 1,2,3,4,5,6
> 
> |     |     |     |     |     |     |     |
> | --- | --- | --- | --- | --- | --- | --- |
> | X   | 1   | 2   | 3   | 4   | 5   | 6   |
> | P(X = xo) | 1/6 | 1/6 | 1/6 | 1/6 | 1/6 | 1/6 |
> 
> - f prob pra par e ímpar => transformar em número => 0 par e 1 ímpar
> 
> |     |     |     |
> | --- | --- | --- |
> | X   | 0   | 1   |
> | P(X = xo) | 1/2 | 1/2 |
> 
> - 4 moedas honestas, em q V.A é qtd de caras. f prob:
> 
> qual espaço amostral? $2^4$ (2.2.2.2) = 16 => cada caso é 1/16 ordem importa? não -> Combinação ou linha 4 do Triângulo Pascal pra calc qtas formas

> | X (qtd caras) |     |
> | --- | --- |
> | 0   | 1/16 x 1 = 1/16 |
> | 1   | 1/16 x 4 = 4/16 |
> | 2   | 1/16 x 6 = 6/16 |
> | 3   | 1/16 x 4 = 4/16 |
> | 4   | 1/16 x 1 = 1/16 |
> 
> $$
> C_4,_1 = \frac{4!}{1! . 3!} = 4 
> 
> 
> $$
> 
> $$
> C_4,_2 = \frac {4!}{2!.2! } = 6 
> 
> 
> $$
> 
> $$
> C_4,_3 = \frac {4!}{3!.1! } = 4
> 
> 
> $$
> 
> Triângulo Pascal: ![triangpascalwiki.PNG](:/71a1ede5eca64f7bb6a1ac56c439b2c9)

# E(x), Var e Dp, C.V de v.a Discretas e Contínuas

==**E(X): Média ou Esperança Matemática ou Valor Esperado**==

Obs: E(x) pode ter valor Negativo (o valor da Prob q é positivo, 0 <= P <= 1 )

- v.a Discreta: média ponderada de todos os possíveis valores de X com pesos iguais às respectivas probabilidades

$$
E(x) = \sum xi.P(xi) =>  x1.P(x1) + x2.P(x2)... 




$$

⭐️ outro cálc na Dist. Binomial, E(X) = np e Var = npq

- v.a Contínuas:

**Variância**:

- v.a Discreta:
    
- v.a Contínuas:
    
    $$
    Var(X) = E (x^2) - (E(x))^2 
    
    
    
    
    
    
    
    
    
    
    
    $$
    

**Desvio-Padrão**:

- v.a Discreta:
- v.a Contínuas:

**Coeficiente de Variação (C.V)**:: relação entre dp e média

# Funções de Variáveis Aleatórias

* * *

```mermaid
flowchart 
id> V.A DISCRETAS]











```

# 1\. Vars Aleat **DISCRETAS**:

listadas, contadas

> As distribuições das variáveis aleatórias discretas estão diretamente relacionadas com o ensaio de **Bernoulli**, o qual determina que um experimento pode resultar em sucesso (o resultado interessado pelo estudo) ou fracasso (complementar do sucesso). Ao repetir várias vezes o experimento de Bernoulli, calculamos a distribuição binomial. Um exemplo do ensaio de Bernoulli é o lançamento de uma moeda honesta em que as chances de se obter cara ou coroa são as mesmas. No momento em que aumentamos a quantidade de moedas nesse experimento, a probabilidade será representada pela distribuição binomial. Portanto, o experimento de Bernoulli possui apenas dois resultados, como podemos observar nas seguintes situações: um paciente estar com certa doença ou não, ter uma peça defeituosa ou não defeituosa, alguma pergunta que possui resposta de Sim ou Não. Já a distribuição binomial considera que a probabilidade é a mesma para todos os ensaios pois ela é utilizada em grandes populações, ou seja, quando o resultado de um ensaio tem quase nenhum efeito na probabilidade de outro evento.
> 
> A distribuição **geométrica** é quando o ensaio de Bernoulli é repetido até que ocorra o primeiro sucesso. Outra característica dessa distribuição é que a probabilidade de um evento não depende dos experimentos passados. Segundo Alvarez Junior (2020) uma possível aplicação está na prática clínica: dentre os medicamentos antidepressivos disponíveis no mercado, um médico pode calcular qual o número esperado de medicamentos que serão testados até encontrar um que seja eficaz para seu paciente.
> 
> Na distribuição **hipergeométrica**, como a população é bem pequena, cada ensaio tem um grande efeito sobre a probabilidade de outros eventos e por isso a probabilidade varia de acordo com o tamanho da amostra. Uma aplicação da hipergeométrica é no controle de qualidade de processos, onde ao se constatar que não há peças defeituosas em determinada amostra, a possibilidade de ter peças defeituosas na próxima amostra é maior.

# Dist. Bernoulli (q = 1-p)

- sucesso 1, p
- fracasso 0, q

# Dist Binomial

prob k sucessos em n tentativas de experimento Bernoulli.

$P(X =k) = \binom{n}{k} p^k(1-p)^{n-k}$

k = qtd sucessos

- **Esperança** na Dist Binomial $\mu = E(X) = np$
    
    - n = qtas vezes repete experimento; p = prob sucesso; q = prob fracasso
- **Variância** $\sigma^2 = npq$
    

O setor de controle de qualidade de uma indústria realiza periodicamente testes nos produtos que fabrica. Em determinada vistoria de rotina, o chefe do setor retira de forma aleatória um lote de dez peças, já produzidas, sabendo-se previamente que 20% destas peças estão defeituosas. Com base nos dados apresentados, qual a probabilidade do chefe do setor de qualidade, ao retirar a amostra deste lote, não retire mais de duas peças defeituosas? (Resp: 67,8%). N = 10, p =0,2, 1-p=0,8 e x <=2.

# Dist. Geométrica

- repetir até ocorrer o 1º sucesso, ou seja, dá o nº (qtd &lt;-&gt; discreta) de experimentos para obter o 1º sucesso.
- Eventos são independentes entre si. Sucesso p e Fracasso q são ctes (os msms valores pra cada tentativa).

$$
X = k = (q^{k-1}).(p)


$$

$$
E(X) = \frac{1}{p}


$$

$$
V(X)= \frac{1}{p^2}


$$

- Esperança &lt;–&gt; soma dos infinitos termos P.G. Soma PG infinita é $\frac{Q1}{1-q}$

> Lançar dado honesto, considerando sucesso ( p) a ocorrencia de uma face múltipla de 3: multipla de 3 {2, 3}
> 
> p = 2/6 = 1/3, então q = 2/3
> 
> Se var X indica nº lançamentos até obter o 1º sucesso:
> 
> X = 0 (não lançar e obter sucesso?) Impossível X = 1 (sucesso logo no 1º lançamento) = 1/3
> 
> X = 2 (sucesso no 2º lançamento) = 2/3 . 1/3 = 2/9
> 
> X = 3 = 2/3 . 2/3 . 1/3 = $(\frac{2}{3})^2. \frac{1}{3}$
> 
> X = 4 = $(\frac{2}{3})^3. \frac{1}{3}$
> 
> X = 5 = $(\frac{2}{3})^4. \frac{1}{3}$
> 
> generalizando, X = k = $(\frac{2}{3})^{k-1}. \frac{1}{3}$
> 
> X tem Dist. Geométrica pois termos tem sequência P.G.

> (FCC adaptada - TecConcursos) O curso para realização experimento é R$ 500. Se o experimento falhar haverá um custo adicional de R$ 100 para realização de uma nova tentativa (ou seja, cada novo experimento custará R$ 600). sabendo-se q a prob de sucesso em qualquer tentativa é 0,4 e q todas são independentes, o custo esperado de todo procedimento até q ocorra o primeiro sucesso seja alcançado é:
> 
> p = 0,4 E(X) = 1 / 0,4 = 2,5. Serão necessários, em média, 2,5 experimentos. O primeiro custo é de R$ 500. Os outros 1,5 custam R$600 cada. Custo esperado: 500 + 1,5. (600) = 1400.
> 
> Então custo esperado é de R$ 1400.

> (FCC) Suponha q ao realizar um experimento ocorra evento A com probabilidade p e não ocoora com probabilidade (1-p). Repetimos o experimento de forma independente até q A ocorra pela primeira vez. seja: X = nº repetições do experimento até q A ocorra pela primeira vez. Sabendo q a média de X é 3, a prob condicional expressa por $P(X = 2 | X\leq3)$ é de: ___
> 
> E(X) = 1/ p = 3 => p = 1/3 , então q = 2/3
> 
> $P(A | B) = \frac{P(A \cap B)}{P(B)} = P(X = 2 | X \leq 3) = \frac{P(X=2)}{P(X \leq 3)}$
> 
> nº tentativas X = 2: conj unitário
> 
> X = 3 = {X=1, X=2, X=3}
> 
> $P(x=2 \cap x=3) = P(X=2)$
> 
> na 1ª tentativa ter sucesso $P(X = 1) = 1/3$
> 
> $P(X=2)=q.p = 2/3 . 1/3 = 2/9$
> 
> $P(X=3) = q^2 .p = (2/3)^2 . 1/3 = 4/27$
> 
> $P(X \leq 3) = 1/3 + 2/9 + 4/27 = 9 + 6 + 4 / 27 = 19/27$
> 
> voltando na prob condicional $\frac{P(X=2)}{P(X \leq 3)}= \frac{2/9}{19/27} =\frac{2}{9} . \frac{27}{19} =\frac{6}{19}$ Então Resposta = 6/19.

# Dist. Hipergeométrica

$$
\frac {(C_k, \ _x) . (C_{N - k}, \ _{n - x})}{C_N  ,\ _n}


$$

$$
E(X) = n.p


$$

$$
V(X) = n.p.q . \frac{N-n}{N-1}


$$

- Qd amostragem é **COM REPOSIÇÃO**, X segue dist. **Binomial** (prob de sucesso p e de fracasso q não mudam, ou seja, as chances são as mesmas a cada extração. Cada extração são independentes entre si). Sua E(X) = n.p e sua Variância = n.p.q.
- Porém qd amostragem é **SEM REPOSIÇÃO** a prob de sucesso p e de fracasso q mudam a cada extração. Nesse caso segue uma Dist. **Hipergeométrica**. A sua E(X) se mantém igual a da Binomial pois "p"e “q” são as proporções iniciais (antes de começar a extrair sem repôr). Na Variância agr tem o FATOR DE CORREÇÃO PARA POPULAÇÕES FINITAS (fator de ajuste)

> caixa bombons com 45 bombons pretos e 5 brancos. Extraindo-se aleatoriamente 3 bombons, sem reposição, qual a chance de q exatamente 2 sejam brancos? (amostragem sem reposição ; total bombons N = 50 ; amostra n = 3 ; casos favoráveis k = 5 ; quer a chance da amostra apresentar exatamente 2 bombons brancos P( X =2 ) )
> 
> dá pra resolver com Combinação C 50, 3 pra saber Qtos modos escolhe 3 de 50 chocolates (combinação de 50 tomados 3 a 3).
> 
> nº casos favoráveis: a) 5 bombons brancos e escolhe 2 : C 5,2 (combinação de 5 tomados 2 a 2) b) há 45 bombons pretos e escolhe 1 : C 45, 1 PFC: (C 5,2 ). (C 45, 1)
> 
> Prob = casos favoráveis / casos possíveis = (C 5,2 ). (C 45, 1) / C 50, 3
> 
> generalizando: total bombons na caixa “N” ; tamanho amostra “n” ; qtd bombons brancos na caixa “k” ; qtd bombons pretos na caixa “N - k”; qtd bombons brancos na amostra “x” ; qtd bombons pretos na amostra “n - x”
> 
> $$
> Casos totais: C_N  ,\ _n
> 
> 
> $$
> 
> $$
> Casos \ favoráveis: [escolha do branco] . [escolha do preto] = (C_k, \ _x) . (C_{N - k}, \ _{n - x})
> 
> 
> $$
> 
> $$
> Prob = casos favoráveis / casos possíveis = \frac {(C_k, \ _x) . (C_{N - k}, \ _{n - x})}{C_N  ,\ _n}
> 
> 
> $$
> 
> Variável X é qtd bombons brancos na amostra. X tem dist. Hipergeométrica

> (FCC) 4 livros didáticos com defeito na livraria foram misturados a outros 16 livros sem defeito. Um prof foi à livraria e escolheu aleatoriamente, 4 desses livros para presentear seus alunos. A prob de ter escolhido 3 livros com defeito é: __
> 
> nº total: 20 livros . Escolhe 4 => $C_{20},_4 = \binom{20}{4}$
> 
> casos favoráveis: 1ª etapa é 3 defeituosos na amostra de 4 e 2ª etapa é escolher 1 livro normal dentre 16 => $\binom{4}{3}. \binom{16}{1}$
> 
> $Prob = \frac{\binom{4}{3}. \binom{16}{1}}{\binom{20}{4}}$
> 
> p = 4/20 = 0,2, então q = 0,8 n = 4 (tamanho da amostra) e N = 20
> 
> E a média de X E(X) = n.p = 4. 0,2 = 0,8
> 
> V(X) = 0,8 . 0,8 . (20-4) / (20-1) = 0,54

# f.m.p Função Massa Prob

v.a discreta X, a fmp é: px(x) = P\[X = x\]

# Função Acumulada Probab / Função de Dist Prob

# Dist. **POISSON**

a partir da amostra q lista qtd ocorrências em determinado intervalo de tempo, área, volume, calculará o nº **exato**. A probab do evento ocorrer é a mesma para cada intervalo e o nº de ocorrências de um intervalo é independente do outro.

$$
P(X = k) = , 



$$

$$
sendo \lambda  -->a Média de ocorrências do evento) 











$$

e = 2,71 k = nº de vezes desejada

- Em Poisson, a Esperança (Média) = Variância
    
    $$
    E(x) = Var(x) = \lambda  
    
    
    
    
    
    
    
    
    
    
    
    $$
    

> Um quiosque de pretzels num shopping recebe em média 2 clientes por minuto. Observando a chegada de clientes por 30 segundos, qual a probabilidade de chegar 3 clientes? use:
> 
> $$
> e^-1 =0,36 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> $$
> 
> $$
> \lambda = 2 clientes em 1 minuto 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> $$
> 
> $$
> k = 3 clientes em 30 segundos 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> $$
> 
> minuto -> segundo : 1min = 30s + 30s, então 30s 1 cliente e outros 30s outro cliente => 1 cliente em 30s
> 
> ou segundo -> minuto : x2 => 6 clientes em 1min
> 
> $$
> P(x-3) =  \frac{e^-1 . 1^3}{3!} = 0,06 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> $$
> 
> 0,06 = 6% .
> 
> Uma empresa de telemarketing, visando realizar uma adequação no número de chamadas realizadas, verificou que se realizava em média oito chamadas por minuto. Visando aumentar a produtividade e mantendo o número de funcionários, a empresa deseja saber a probabilidade de se aumentar o número de chamadas para dez ou mais por minuto. De acordo com os dados apresentados, qual a probabilidade desse fato ocorrer? (Resp: 0,2834). Questão pede a prob de se aumentar o nº ligações para 10 ou mais. \\lamda = 8 e p = (x>=10)= 1-p(x<10)

* * *

* * *

```mermaid
flowchart 
id> V.A CONTÍNUAS]











```

# 2\. Vars Aleat **CONTÍNUAS**

## f.d.p (Função Densidade Prob)

> Estatística Descritiva - Analogia da fdp com Histogramas: no Histograma cada retângulo tem a base (**amplitude** de classe h. ex: faixa etária) e altura (**frequência**, ou seja qtas pessoas).
> 
> Para qualquer Histograma e Medida Separatriz, O **percentual** de **elementos delimitado** será **igual** ao percentual da **área** q cobrimos (ex: 3º Quartil (Q3) delimita 75% ou 3/4 das observações e da área; O 8º Decil (D8) delimita 25% das observações e tbm da área total; Calculando 10% da área do Histograma corresponde a 10% dos elementos).
> 
> Então a partir da Área total (somando todas áreas de todos os restângulos) e dividir pela Amplitude de classe (h) e dps dividir pelo nº total de elementos, resultado sempre será **Área = 1**. Área total = $h. f_1+ h. f_2 + h. f_3... = h. (f_1+f_2+f_3...)$
> 
> - h (amplitude)
> - fr (freq relativa) = fi / n
> - densidade freq relativa (dfr) = fr / h
> 
> ==**Sempre q Histograma for baseado em DENSIDADE FREQUÊNCIA RELATIVA (dfr) a área total vale 1**==.
> 
> Qd passamos da Estatística **Desritiva** para **V.As** , a **Freq Relativa** da dá lugar para a **Probabilidade** e a **Densidade de Freq Relativa (dfr**) para a **DENSIDADE DE PROBABILIDADE**. A densidade de prob é a divisão **Prob / tamanho do intervalo**.
> 
> Qd diminuímos cada vez mais o tamanho do intervalo (amplitude), temos f.d.p. Então **função densidade de prob ==(f.d.p)==** é o menor resultado da dfr (fr / h), ou seja, qd o ==**tamanho do intervalo tende a zero**==. O gfráfico da f.d.p manterá todas as propriedades do Histograma, ou seja:
> 
> ==\- **Área total = 1**==
> 
> ==\- **Área de determinado intervalo é igual à Probabilidade daquele intervalo**==

- f.d.p com **Integral**: há alguns gráficos q só consegue calc usando Integral.

> Integral: função q calcula a área abaixo do gráfico

# $fdp \neq FDP$ \- f densid prob (fdp) e f Distribuição de Prob (FDP)

# FDP

[prof Vítor Menezes - TecConcursos](https://youtu.be/MqKKNVt0PA8?list=PLX-4skTGVrWUNh2VGFIyoWVGEVRQq3gkB)

fx(x) = dFx(x) / dx

## Distribuição Contínua de Prob

# Fontes:

- canal Prof Douglas Maioli
    
- canal Murakami
    
- prof Vítor Menezes - TecConcursos
    
    - [ ] Prob https://www.youtube.com/playlist?list=PLGGUBlwLP-pVlJN6ylnXdhj8lSz-rIfhp
    - [ ] Maioli https://www.youtube.com/watch?v=snXf8YT7L3U&list=PLrOyM49ctTx8HWnxWRBtKrfcuf7ew_3nm

* * *