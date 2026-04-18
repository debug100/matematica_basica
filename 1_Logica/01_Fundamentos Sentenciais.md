Para estender o seu documento 01_Fundamentos Sentenciais.md, vamos aprofundar na "mecânica" da coisa: como as proposições se combinam e como a negação funciona na prática.
Aqui está o conteúdo expandido com uma linguagem bem "papo de programador":
------------------------------
## 1. O que é uma Proposição? (O Boolean da Vida Real)
Pense na proposição como uma variável do tipo bool que já vem inicializada. Ela é uma frase declarativa que você pode olhar e dizer: "Isso é verdade" ou "Isso é mentira".

* Exemplo que é proposição: "O Campus da UFC é em Quixadá." (Verdadeiro)
* Exemplo que NÃO é proposição: "Estude matemática!" (É um comando, não tem valor V ou F).
* 

## 2. Conectivos: Os Operadores Lógicos
Se as proposições são os blocos, os conectivos são a "cola". Eles dizem como uma frase depende da outra.

| Conectivo | Símbolo | Nome | Analogia na Programação |
|---|---|---|---|
| Não | $\neg$ | Negação | !p (Inverte o sinal) |
| E | $\land$ | Conjunção | p && q (Exigente: tudo deve ser V) |
| Ou | $\lor$ | Disjunção | `p |
| Ou exclusivo | $\oplus$ | Disjunção Exclusiva | p != q (Apenas um ou outro, nunca ambos) |
| Se... então | $\to$ | Condicional | if (p) { q } (Uma promessa ou fluxo) |
| Se e somente se | $\leftrightarrow$ | Bicondicional | p == q (Gêmeos: valores iguais dão V) |

------------------------------
## 3. Aprofundando nos "Chatos": $\oplus$ e $\to$## A "Treta" do Ou Exclusivo ($\oplus$)
No dia a dia, o "ou" é confuso. Se eu digo "Vou levar café ou água", posso levar os dois. Isso é o $\lor$ (Disjunção inclusiva).
No $\oplus$, é a escolha de Matrix: Ou você toma a pílula azul, ou a vermelha. Se tomar as duas, a lógica quebra (Falso).
## A Promessa do "Se... então" ($\to$)
Esse é o que mais cai em prova. Imagine que eu te prometo: "Se você estudar, então passará".

* Você estudou e passou? V (Promessa cumprida).
* Você estudou e NÃO passou? F (Eu menti pra você).
* Você não estudou? Aqui está o segredo: Eu não prometi nada para quem não estuda! Então, se você não estudou e passou (por sorte) ou não passou, a frase continua "não-falsa" (Verdadeira por vacuidade).
* 

------------------------------
## 4. Tabela Verdade Resumida (O Cheat Sheet)

| $p$ | $q$ | $p \land q$ | $p \lor q$ | $p \oplus q$ | $p \to q$ | $p \leftrightarrow q$ |
|---|---|---|---|---|---|---|
| V | V | V | V | F | V | V |
| V | F | F | V | V | F | F |
| F | V | F | V | V | V | F |
| F | F | F | F | F | V | V |

------------------------------
Dica para o seu vídeo:
Use o exemplo do if/else para explicar a condicional ($\to$). O único jeito de um if dar erro de lógica é a condição ser verdadeira e o resultado esperado não acontecer.
Quer que eu crie agora o roteiro de um desafio prático (exercício) para colocar no final desse arquivo .md?

