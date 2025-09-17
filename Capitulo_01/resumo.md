Este capítulo introduz os conceitos fundamentais da programação em Python, começando com o uso do shell interativo, também conhecido como REPL (Read-Evaluate-Print-Loop), como uma ferramenta para executar instruções Python individuais e ver resultados imediatos.

## Expressões, Operadores e Tipos de Dados

O bloco de construção mais básico em Python é a **expressão**, que consiste em **valores** (como `2` e `'hello'`) e **operadores** (como `+` e `*`). Toda expressão é avaliada, ou reduzida, a um único valor. O capítulo aborda os operadores matemáticos padrão, incluindo adição (`+`), subtração (`-`), multiplicação (`*`), divisão (`/`), divisão inteira (`//`), módulo/resto (`%`) e exponenciação (`**`). A ordem das operações (precedência) segue as convenções matemáticas e pode ser controlada com parênteses.

Cada valor em Python pertence a um **tipo de dado**. Os três tipos principais apresentados são:
* **Inteiros (`int`):** Números inteiros, como `42` e `-10`.
* **Ponto flutuante (`float`):** Números com casas decimais, como `3.14`.
* **Strings (`str`):** Valores de texto, que devem ser colocados entre aspas simples, como `'Python'`.

O comportamento de um operador pode mudar dependendo dos tipos de dados com os quais ele opera. Por exemplo, o operador `+` realiza **concatenação de strings** ao ser usado com duas strings (`'Alice' + 'Bob'` resulta em `'AliceBob'`), enquanto o operador `*` realiza **replicação de strings** quando usado com uma string e um inteiro (`'Alice' * 3` resulta em `'AliceAliceAlice'`).

## Variáveis e o Primeiro Programa

Para armazenar valores para uso posterior, são utilizadas **variáveis**. Um valor é atribuído a uma variável por meio de uma **instrução de atribuição**, usando o operador de atribuição `=` (por exemplo, `idade = 25`). O capítulo descreve as regras para nomear variáveis e como o valor de uma variável pode ser sobrescrito com uma nova atribuição.

A criação de um programa completo é demonstrada através de um script simples que cumprimenta o usuário e solicita seu nome e idade. Este exemplo introduz várias funções essenciais:
* `print()`: Exibe um valor na tela.
* `input()`: Pausa a execução para aguardar a entrada de texto do usuário, sempre retornando o valor como uma string.
* `len()`: Retorna o número de caracteres em uma string como um inteiro.
* `str()`, `int()`, `float()`: Funções usadas para converter valores entre os tipos de dados string, inteiro e ponto flutuante. Essa conversão é vital, por exemplo, para realizar cálculos matemáticos com um número que foi inserido pelo usuário como texto.

Funções adicionais como `type()`, `round()` e `abs()` também são brevemente mencionadas para demonstrar a experimentação no shell interativo. Por fim, o capítulo oferece uma explicação conceitual de como os computadores representam todos os tipos de dados internamente usando o sistema numérico **binário** (base-2).
