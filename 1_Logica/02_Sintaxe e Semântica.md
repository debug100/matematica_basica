Este é o coração da lógica proposicional. Se as proposições são os "dados", a Sintaxe é a regra de escrita (como o código deve ser digitado) e a Semântica é o que aquilo significa (se o resultado final é verdadeiro ou falso).
Aqui está uma explicação simples para o seu arquivo 02_Sintaxe_e_Semantica.md:
------------------------------
## 1. Sintaxe vs. Semântica (O "Compilador" da Lógica)

* Sintaxe: Define se uma fórmula é bem formada. Exemplo: p ∧ q está correto, mas p ∧ ∧ q é um erro de sintaxe.
* Semântica: É o significado. Na lógica, o significado é o Valor Verdade (V ou F). Para descobrir o "valor final" de uma fórmula complexa, usamos a Tabela-Verdade.
* 

## 2. Como construir uma Tabela-Verdade
Para não esquecer nenhuma combinação, a regra é simples: se você tem $n$ proposições, sua tabela terá $2^n$ linhas.

* 2 proposições ($p, q$) = 4 linhas.
* 3 proposições ($p, q, r$) = 8 linhas.
* 

Passo a passo:

   1. Liste todas as combinações de V e F para as letras individuais.
   2. Resolva o que está dentro dos parênteses primeiro.
   3. Aplique os conectivos seguindo a ordem de precedência (Negação $\to$ Conjunção/Disjunção $\to$ Condicional).

------------------------------
## 3. As Três Classificações das Fórmulas
Após preencher a última coluna da sua tabela, você terá um destes três resultados:
## A. Tautologia (O "Sempre True")
É uma fórmula que é sempre verdadeira, não importa o que aconteça com as proposições individuais. Na programação, seria como um while(true).

* Exemplo clássico: $p \lor \neg p$ ("Ou está chovendo, ou não está chovendo").
* Resultado na tabela: A última coluna é toda V.
* 

## B. Contradição (O "Bug Crítico")
É uma fórmula que é sempre falsa. É uma impossibilidade lógica.

* Exemplo clássico: $p \land \neg p$ ("Está chovendo E não está chovendo" ao mesmo tempo).
* Resultado na tabela: A última coluna é toda F.

## C. Contingência (O "Depende")
É a maioria das situações da vida e da programação. O resultado depende dos valores de entrada.

* Exemplo: $p \to q$ ("Se eu apertar o botão, a luz acende"). Se eu não apertar, ou se a lâmpada estiver queimada, o resultado muda.
* Resultado na tabela: A última coluna tem V e F misturados.

------------------------------
## 💡 Dica de Ouro para o GitHub/Vídeo:
Mostre que identificar uma Tautologia é como validar um argumento. Se uma regra de um sistema é uma tautologia, o sistema é consistente. Se você encontrar uma Contradição no código de um contrato inteligente (Smart Contract), por exemplo, o sistema pode travar ou permitir roubos, pois há uma falha lógica intransponível.
Deseja que eu monte um exemplo prático passo a passo de uma tabela-verdade de 4 linhas para você incluir como "Exemplo Resolvido" nesse documento? [1, 2]

