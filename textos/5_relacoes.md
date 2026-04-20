📘 5. Relações – Guia Completo e Intuitivo

Esse módulo conecta vários conceitos anteriores (conjuntos, pares ordenados, funções) e mostra como elementos podem se relacionar.

🔹 1. Definição de Relação
🔸 O que é uma relação?

Uma relação é um subconjunto do produto cartesiano.

👉 Se A e B são conjuntos:

A × B = {(a, b)}

Uma relação R ⊆ A × B

🔸 Exemplo

A = {1,2,3}
B = {a,b}

Uma relação possível:

R = {(1,a), (2,b)}

👉 Isso significa:

1 está relacionado com a
2 está relacionado com b
🔸 Relação em um conjunto

Quando A = B:

👉 R ⊆ A × A

Exemplo:

“≤” nos números
“igualdade”
🔹 2. Propriedades das Relações

Considere uma relação R em um conjunto A.

🔸 Reflexiva

👉 Todo elemento se relaciona consigo mesmo

(a,a) ∈ R para todo a

Exemplo:

“=” (igualdade)
🔸 Simétrica

👉 Se vai, volta

Se (a,b) ∈ R → então (b,a) ∈ R

Exemplo:

“é irmão de”
🔸 Antissimétrica

👉 Não permite troca (exceto iguais)

Se (a,b) e (b,a) → então a = b

Exemplo:

“≤”
🔸 Transitiva

👉 Relação em cadeia

Se (a,b) e (b,c) → então (a,c)

Exemplo:

“≤”
“é ancestral de”
🔹 3. Modelagem Visual

Agora você vai visualizar relações.

🔸 Matriz de Adjacência

Se A = {1,2,3}

Criamos uma tabela:

	1	2	3
1	1	0	1
2	0	1	0
3	1	0	1

👉 1 = existe relação
👉 0 = não existe

🔸 Dígrafos (Grafos Direcionados)
Cada elemento → um ponto (vértice)
Cada relação → uma seta

Exemplo:

(1,2) → seta de 1 para 2

👉 Muito útil para visualizar transitividade.

🔹 4. Fechos (Closures)

Às vezes a relação não tem uma propriedade, então a gente “completa”.

🔸 Fecho Reflexivo

👉 Adiciona todos os (a,a)

🔸 Fecho Simétrico

👉 Se (a,b) existe → adiciona (b,a)

🔸 Fecho Transitivo

👉 Se (a,b) e (b,c) → adiciona (a,c)

🔸 Algoritmo de Warshall (ideia)

É um método para encontrar o fecho transitivo.

👉 Ideia simples:

Verifica caminhos indiretos
Se existe caminho de A → B → C
então adiciona A → C
🔸 Intuição forte

👉 Você está “completando” a relação até ela obedecer a regra desejada.
