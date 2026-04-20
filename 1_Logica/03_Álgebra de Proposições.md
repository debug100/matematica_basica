Para o seu arquivo 03_Álgebra_de_Proposições.md, o foco é mostrar que, na lógica, existem caminhos diferentes para chegar ao mesmo resultado. Para um programador, isso é Refatoração de Código: transformar uma expressão complexa em algo mais simples e elegante, sem mudar o comportamento (o resultado final).
Dizemos que duas fórmulas são equivalentes ($p \equiv q$) quando suas tabelas-verdade são idênticas.
------------------------------
## 1. Leis de De Morgan (A Negação Distributiva)
Essas são as leis mais famosas. Elas ensinam como negar uma conjunção ("e") ou uma disjunção ("ou"). O segredo é: Nega tudo e inverte o conectivo.

* Negação do "E": $\neg(p \land q) \equiv \neg p \lor \neg q$
* Exemplo: "Não é verdade que sou rico E feliz" é o mesmo que dizer "Ou não sou rico, OU não sou feliz".
* Negação do "OU": $\neg(p \lor q) \equiv \neg p \land \neg q$
* Exemplo: "Não vou tomar café OU chá" significa que "Não vou tomar café E não vou tomar chá".
* 

## 2. Condicional como Disjunção (A Regra do "Neymar")
Muitas vezes é difícil trabalhar com o "Se... então" ($\to$). Podemos transformá-lo em um "OU" ($\lor$) usando uma regra mnemônica muito comum entre estudantes: "NE-MA" (Nega a primeira, Mantém a segunda).

* Equivalência: $(p \to q) \equiv \neg p \lor q$
* Por que funciona? Pense na promessa: "Se você pagar, eu entrego". Isso é verdade se: Você NÃO pagar (tô livre da promessa) OU se você pagar e eu entregar.
* 

## 3. A Contrapositiva (A "Volta Negando")
Esta é a única forma de inverter uma condicional sem mudar o sentido dela. Se você inverter sem negar, você comete um erro lógico.

* Equivalência: $(p \to q) \equiv \neg q \to \neg p$
* Exemplo: "Se é um gato, então mia" é equivalente a "Se NÃO mia, então NÃO é um gato".
* 

## 4. Outras Leis Importantes (Álgebra Booleana)

* Idempotência: $p \land p \equiv p$ (Repetir a mesma condição no if não muda nada).
* Dupla Negação: $\neg(\neg p) \equiv p$ (Não não é sim).
* Comutativa: $p \land q \equiv q \land p$ (A ordem dos fatores não altera o valor verdade).

------------------------------
## 💻 Aplicação na Programação
Imagine que você tem o seguinte código:

if not (usuario_logado and tem_permissao):
    return "Acesso negado"

Usando De Morgan, você pode refatorar para:

if not usuario_logado or not tem_permissao:
    return "Acesso negado"

Ambos fazem a mesma coisa, mas o segundo costuma ser mais fácil de ler em lógicas complexas.
------------------------------
Dica para o vídeo:
Faça um desafio de "Simplificação de Expressão". Dê uma fórmula gigante e vá aplicando as leis passo a passo até ela virar algo minúsculo. É muito satisfatório de assistir!
Quer que eu prepare a próxima seção sobre Lógica de Primeira Ordem (Predicados)?

