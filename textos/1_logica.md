📘 1. Lógica – Guia Completo e Simples
🔹 1. Fundamentos Sentenciais

A lógica começa com a ideia de proposição.

👉 Proposição é uma frase declarativa que pode ser classificada como:

Verdadeira (V)
Falsa (F)

Exemplos:

“2 + 2 = 4” → V
“O Brasil fica na Europa” → F

⚠️ Não são proposições:

Perguntas: “Você está bem?”
Ordens: “Feche a porta!”
Frases vagas: “Hoje está bonito”
🔸 Conectivos Lógicos

Usamos conectivos para formar proposições mais complexas:

Símbolo	Nome	Exemplo	Leitura
¬p	Negação	¬p	“não p”
p ∧ q	Conjunção	p ∧ q	“p e q”
p ∨ q	Disjunção	p ∨ q	“p ou q”
p → q	Condicional	p → q	“se p, então q”
p ↔ q	Bicondicional	p ↔ q	“p se e somente se q”
🔹 2. Sintaxe e Semântica (Tabelas-Verdade)

Aqui você aprende a avaliar proposições.

🔸 Tabela-Verdade

É uma tabela que mostra todos os valores possíveis.

Exemplo: p ∧ q

p	q	p ∧ q
V	V	V
V	F	F
F	V	F
F	F	F
🔸 Classificações importantes
Tautologia → sempre verdadeira
Ex: p ∨ ¬p
Contradição → sempre falsa
Ex: p ∧ ¬p
Contingência → às vezes verdadeira, às vezes falsa
Ex: p ∧ q
🔹 3. Álgebra de Proposições

Aqui você aprende a manipular proposições como se fosse álgebra.

Algumas leis importantes:

Dupla negação: ¬(¬p) = p
Leis de De Morgan:
¬(p ∧ q) = ¬p ∨ ¬q
¬(p ∨ q) = ¬p ∧ ¬q
Condicional:
p → q = ¬p ∨ q

👉 Isso permite simplificar expressões sem precisar montar tabela.

🔹 4. Lógica de Primeira Ordem

Agora entramos em frases mais complexas com variáveis.

🔸 Predicados

São proposições abertas (dependem de uma variável).

Exemplo:

P(x): “x é par”

Só vira proposição quando você define o valor:

P(2) → verdadeiro
P(3) → falso
🔸 Quantificadores

Eles dizem para quantos elementos a frase vale:

✔ Universal (∀)

“para todo”

Ex:

∀x (x > 0) → “todo x é maior que 0”
✔ Existencial (∃)

“existe pelo menos um”

Ex:

∃x (x > 0) → “existe um x maior que 0”
🔹 5. Negação de Sentenças Complexas

Essa parte é MUITO importante.

🔸 Regras principais:
¬(∀x P(x)) = ∃x ¬P(x)
👉 “Nem todo…” = “Existe pelo menos um que não…”
¬(∃x P(x)) = ∀x ¬P(x)
👉 “Não existe…” = “Todos não…”
🔸 Exemplos práticos

Frase:
👉 “Todo aluno passou”
(∀x P(x))

Negação:
👉 “Existe um aluno que não passou”
(∃x ¬P(x))

Frase:
👉 “Existe um número par”
(∃x P(x))

Negação:
👉 “Nenhum número é par”
(∀x ¬P(x))
