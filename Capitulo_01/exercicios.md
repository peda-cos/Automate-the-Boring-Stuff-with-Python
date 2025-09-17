# Questões Práticas - Capítulo 1

## 1. Quais dos seguintes são operadores e quais são valores?
```python
*
'hello'
-88.8
-
/
+
5
```

**Resposta:**
- **Operadores:** `*`, `-`, `/`, `+`.
- **Valores:** `'hello'`, `-88.8`, `5`.

## 2. Qual dos seguintes é uma variável e qual é uma string?
```python
spam
'spam'
```

**Resposta:**
- **Variável:** `spam`.
- **String:** `'spam'`.

## 3. Nomeie três tipos de dados.

**Resposta:**
- **Inteiro** (`int`) - números inteiros como 42, -3, 0.
- **String** (`str`)  - texto como 'olá', "Python".
- **Float** (`float`) - números decimais como 3.14, -2.5.

## 4. Do que uma expressão é composta? O que todas as expressões fazem?

**Resposta:**
Uma expressão é composta de valores e operadores. Todas as expressões retornam para um único valor.

## 5. Qual é a diferença entre uma expressão e uma declaração?

**Resposta:**
- **Expressão:** retorna para um valor. Exemplos: `2 + 3`, `'olá'`, `len('spam')`.
- **Declaração:** Uma instrução que executa uma ação mas não retorna para um valor. Exemplos: `spam = 10` (atribuição), `print('olá')` (chamada de função).
Você pode usar expressões em qualquer lugar onde um valor é esperado, mas declarações executam ações.

## 6. O que a variável bacon contém após o seguinte código ser executado?
```python
bacon = 20
bacon + 1
```

**Resposta:**
A variável `bacon` ainda contém `20`.
A expressão `bacon + 1` retorna para `21`, mas este valor não é atribuído de volta para `bacon`. Para alterar `bacon`, você precisaria: `bacon = bacon + 1` ou `bacon += 1`.

## 7. Para que valores as seguintes duas expressões devem retornar?
```python
'spam' + 'spamspam'
'spam' * 3
```

**Resposta:**
- `'spam' + 'spamspam'` retorna para `'spamspamspam'`.
- `'spam' * 3` retorna para `'spamspamspam'`.

## 8. Por que eggs é um nome de variável válido enquanto 100 é inválido?

**Resposta:**
Nomes de variáveis em Python devem seguir essas regras:
- Devem começar com uma letra (a-z, A-Z) ou sublinhado (_).
- Não podem começar com um número.
- Podem conter letras, números e sublinhados.
- Não podem ser palavras-chave do Python.

## 9. Quais três funções podem ser usadas para obter a versão inteira, de ponto flutuante ou string de um valor?

**Resposta:**
- `int()` - converte para inteiro.
- `float()` - converte para número de ponto flutuante.
- `str()` - converte para string.

## 10. Por que esta expressão causa um erro? Como você pode corrigir?
```python
'I eat ' + 99 + ' burritos.'
```

**Resposta:**
Isso causa um TypeError porque você não pode concatenar uma string e um inteiro usando o operador `+`.

**Como corrigir:**
```python
#Converter o inteiro para string
'I eat '+ str(99) + ' burritos.'
```

## Crédito Extra: Funções len(), bin() e hex()

### Função len()
A função `len()` retorna o comprimento (número de itens) de um objeto:
```python
len('olá')       # Retorna 3
len([1, 2, 3])   # Retorna 3
len('')          # Retorna 0
```

### Função bin()
A função `bin()` converte um inteiro para uma string binária:
```python
bin(10)    # Retorna '0b1010'
bin(255)   # Retorna '0b11111111'
bin(42)    # Retorna '0b101010'
```

### Função hex()
A função `hex()` converte um inteiro para uma string hexadecimal:
```python
hex(10)    # Retorna '0xa'
hex(255)   # Retorna '0xff'
hex(42)    # Retorna '0x2a'
```
