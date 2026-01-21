# UC000606
CET - Técnico(a) Especialista em Automação, Robótica e Controlo Industrial  / UC00606 - Desenvolver programas em linguagem estruturada 
# PLANO DE FORMAÇÃO MODULAR
## DESENVOLVER PROGRAMAS EM LINGUAGEM ESTRUTURADA

**Linguagem de Programação:** Python  
**Carga Horária Total:** 50 horas  
**Distribuição:** 12 sessões de 4 horas + 1 sessão de 2 horas  
**Regime:** Presencial  
**Público-Alvo:** Formandos do Ensino Profissional

---

## I – INTRODUÇÃO

A programação de computadores constitui uma competência fundamental no mundo digital contemporâneo, sendo transversal a múltiplas áreas profissionais. O paradigma da programação estruturada representa a base essencial para o desenvolvimento de aplicações robustas, eficientes e de fácil manutenção.

Este módulo formativo destina-se a proporcionar aos formandos do ensino profissional os conhecimentos teóricos e as competências práticas necessárias para desenvolver programas utilizando a linguagem Python, seguindo os princípios da programação estruturada. Python foi escolhida pela sua sintaxe clara e acessível, vasta aplicabilidade profissional e forte presença no mercado de trabalho.

A programação estruturada baseia-se em três estruturas fundamentais de controlo: sequência, seleção e repetição. Esta abordagem promove a clareza do código, facilita a deteção e correção de erros e permite a decomposição de problemas complexos em módulos mais simples e gerenciáveis.

Durante as 50 horas de formação, os formandos terão oportunidade de desenvolver progressivamente as suas competências, desde os conceitos básicos de algoritmos e lógica de programação até à criação de programas complexos que integram estruturas de dados, funções e manipulação de ficheiros.

A metodologia adotada privilegia a aprendizagem ativa, combinando exposição teórica com exercícios práticos progressivos, projetos integradores e resolução de problemas reais. Pretende-se que, ao concluir este módulo, os formandos sejam capazes de analisar problemas, desenhar algoritmos, implementar soluções em Python e testar e depurar programas de forma autónoma.

---

## II – OBJETIVOS GERAIS E ESPECÍFICOS

### OBJETIVOS GERAIS

- Desenvolver competências de análise e resolução de problemas através da programação estruturada
- Implementar programas em linguagem Python utilizando as estruturas fundamentais de controlo
- Aplicar metodologias de desenvolvimento de software seguindo boas práticas de programação
- Desenvolver autonomia na criação, teste e depuração de programas

### OBJETIVOS ESPECÍFICOS

Ao concluir este módulo, o formando deverá ser capaz de:

**No domínio cognitivo:**
- Compreender os conceitos fundamentais de algoritmos e programação estruturada
- Identificar e distinguir os diferentes tipos de dados e operadores
- Reconhecer as estruturas de controlo e a sua aplicabilidade
- Explicar o funcionamento de funções e procedimentos
- Compreender os conceitos de estruturas de dados compostas

**No domínio psicomotor:**
- Instalar e configurar o ambiente de desenvolvimento Python
- Escrever algoritmos em pseudocódigo e fluxogramas
- Desenvolver programas utilizando estruturas sequenciais, condicionais e de repetição
- Criar e utilizar funções com parâmetros e valores de retorno
- Manipular listas, tuplos, dicionários e conjuntos
- Implementar operações de leitura e escrita em ficheiros de texto
- Depurar e testar programas de forma sistemática

**No domínio afetivo:**
- Demonstrar rigor e organização na escrita de código
- Desenvolver persistência na resolução de problemas
- Trabalhar colaborativamente em projetos de programação
- Demonstrar espírito crítico na análise de soluções alternativas
- Valorizar a documentação e comentários no código

---

## III – DESENVOLVIMENTO: CONTEÚDOS PROGRAMÁTICOS POR UNIDADE TEMÁTICA

### UNIDADE TEMÁTICA 1: INTRODUÇÃO À PROGRAMAÇÃO E ALGORITMOS
**Duração:** 8 horas (2 sessões)

#### 1.1 Conceitos Fundamentais de Programação

**Definição de Programa:**
Um programa de computador é um conjunto de instruções organizadas de forma lógica e sequencial que, quando executadas, permitem realizar uma determinada tarefa ou resolver um problema específico. As instruções são escritas numa linguagem de programação que o computador pode interpretar e executar.

**Definição de Algoritmo:**
Um algoritmo é uma sequência finita de passos bem definidos e não ambíguos que, quando executados, resolvem um problema ou realizam uma tarefa. Os algoritmos são independentes da linguagem de programação e constituem a base lógica de qualquer programa.

**Características de um bom algoritmo:**
- Finitude: deve terminar após um número finito de passos
- Definição: cada passo deve ser precisamente definido
- Entrada: pode ter zero ou mais entradas
- Saída: deve produzir pelo menos uma saída
- Eficácia: as operações devem ser suficientemente básicas para serem executadas

**Exemplo 1.1 – Algoritmo em Linguagem Natural:**
```
Problema: Calcular a média de duas notas

Algoritmo:
1. Início
2. Pedir ao utilizador a primeira nota
3. Guardar a primeira nota numa variável
4. Pedir ao utilizador a segunda nota
5. Guardar a segunda nota numa variável
6. Calcular a média dividindo a soma das duas notas por 2
7. Mostrar o resultado da média
8. Fim
```

#### 1.2 Representação de Algoritmos

**Pseudocódigo:**
O pseudocódigo é uma forma de representar algoritmos utilizando uma linguagem simplificada, próxima da linguagem natural mas com estrutura semelhante às linguagens de programação. Não segue regras rígidas de sintaxe e serve como ponte entre o pensamento humano e o código real.

**Exemplo 1.2 – Pseudocódigo para cálculo de média:**
```
Algoritmo CalculoMedia
Variáveis:
    nota1, nota2, media: real
    
Início
    Escrever("Introduza a primeira nota: ")
    Ler(nota1)
    Escrever("Introduza a segunda nota: ")
    Ler(nota2)
    media ← (nota1 + nota2) / 2
    Escrever("A média é: ", media)
Fim
```

**Fluxogramas:**
Os fluxogramas são representações gráficas de algoritmos que utilizam símbolos padronizados para representar diferentes tipos de operações. São particularmente úteis para visualizar o fluxo de execução e identificar estruturas de decisão e repetição.

**Símbolos principais dos fluxogramas:**
- Oval: início e fim do algoritmo
- Retângulo: processamento (cálculos, atribuições)
- Paralelogramo: entrada/saída de dados
- Losango: decisão (condição)
- Setas: fluxo de execução

**Exemplo 1.3 – Descrição de fluxograma para verificar se um número é par:**
```
             [Início]
                 |
           [Ler número] 
                 |
  [número é divisível por 2?]
 ↓ Sim                 ↓ Não
[Escrever "Par"]  [Escrever "Ímpar"]
          |          |                           
          → [Fim] ←
```

#### 1.3 Introdução ao Python

**Características da linguagem Python:**
- Linguagem interpretada (não necessita de compilação)
- Sintaxe simples e clara
- Fortemente tipada e dinamicamente tipada
- Multiparadigma (estruturada, orientada a objetos, funcional)
- Vasta biblioteca padrão
- Grande comunidade e suporte

**Instalação e Configuração do Ambiente:**
- Python 3.x (versão mais recente recomendada)
- IDE recomendada: PyCharm Community, VS Code, IDLE ou Thonny
- Verificação da instalação através da linha de comandos

**Exemplo 1.4 – Primeiro programa em Python:**
```python
# Primeiro programa Python
print("Olá, Mundo!")
print("Bem-vindo à programação em Python")
```

**Exemplo 1.5 – Programa interativo simples:**
```python
# Programa que cumprimenta o utilizador
nome = input("Qual é o seu nome? ")
print("Olá,", nome, "! Bem-vindo ao curso de Python.")
```

#### 1.4 Estrutura Básica de um Programa Python

**Comentários:**
Os comentários são textos explicativos no código que não são executados. Servem para documentar o programa e facilitar a sua compreensão.

```python
# Este é um comentário de linha única

"""
Este é um comentário
de múltiplas linhas
ou docstring
"""
```

**Indentação:**
Em Python, a indentação (espaços no início das linhas) é obrigatória e define blocos de código. A convenção é utilizar 4 espaços por nível de indentação.

**Exemplo 1.6 – Importância da indentação:**
```python
# Correto
if True:
    print("Esta linha está corretamente indentada")
    print("Esta também")

# Incorreto (gera erro)
if True:
print("Esta linha causa erro de indentação")
```

---

### UNIDADE TEMÁTICA 2: VARIÁVEIS, TIPOS DE DADOS E OPERADORES
**Duração:** 8 horas (2 sessões)

#### 2.1 Variáveis e Atribuições

**Definição de Variável:**
Uma variável é um espaço na memória do computador identificado por um nome, onde se pode armazenar um valor que pode ser alterado durante a execução do programa.

**Regras para nomes de variáveis em Python:**
- Devem começar com uma letra (a-z, A-Z) ou underscore (_)
- Podem conter letras, números e underscores
- São case-sensitive (idade ≠ Idade)
- Não podem ser palavras reservadas do Python (if, for, while, etc.)
- Devem ser descritivas e significativas

**Exemplo 2.1 – Declaração e atribuição de variáveis:**
```python
# Atribuição simples
nome = "João Silva"
idade = 18
altura = 1.75
estudante = True

# Atribuição múltipla
x, y, z = 10, 20, 30

# Atribuição do mesmo valor a múltiplas variáveis
a = b = c = 0

# Troca de valores
a = 5
b = 10
a, b = b, a  # a passa a 10 e b passa a 5
```

#### 2.2 Tipos de Dados Primitivos

**int (Inteiro):**
Representa números inteiros, positivos ou negativos, sem casas decimais.

**Exemplo 2.2 – Números inteiros:**
```python
idade = 25
temperatura = -5
ano = 2025
numero_grande = 1000000

# Operações com inteiros
soma = 10 + 5      # 15
diferenca = 10 - 5  # 5
produto = 10 * 5    # 50
quociente = 10 // 5 # 2 (divisão inteira)
```

**float (Real):**
Representa números com casas decimais (vírgula flutuante).

**Exemplo 2.3 – Números reais:**
```python
altura = 1.75
peso = 68.5
temperatura = 36.6
pi = 3.14159

# Operações com floats
divisao = 10 / 3      # 3.333333...
potencia = 2.5 ** 2   # 6.25
```

**str (String/Cadeia de caracteres):**
Representa texto, sequências de caracteres delimitadas por aspas simples, duplas ou triplas.

**Exemplo 2.4 – Strings:**
```python
nome = "Maria"
apelido = 'Santos'
frase = "Python é fantástico!"
paragrafo = """Este é um texto
de múltiplas linhas
em Python"""

# Operações com strings
concatenacao = nome + " " + apelido  # "Maria Santos"
repeticao = "Ha" * 3                 # "HaHaHa"
tamanho = len(nome)                  # 5
maiusculas = nome.upper()            # "MARIA"
minusculas = nome.lower()            # "maria"
```

**bool (Booleano):**
Representa valores lógicos: True (verdadeiro) ou False (falso).

**Exemplo 2.5 – Valores booleanos:**
```python
esta_sol = True
esta_chuva = False
maior_idade = True

# Expressões booleanas
resultado1 = 5 > 3      # True
resultado2 = 10 == 10   # True
resultado3 = 7 < 5      # False
```

#### 2.3 Conversão entre Tipos (Type Casting)

**Definição:**
A conversão de tipos permite transformar um valor de um tipo de dados noutro tipo. Pode ser implícita (automática) ou explícita (manual).

**Exemplo 2.6 – Conversões de tipos:**
```python
# String para inteiro
texto = "25"
numero = int(texto)        # 25

# String para float
texto_decimal = "3.14"
numero_real = float(texto_decimal)  # 3.14

# Número para string
idade = 20
texto_idade = str(idade)   # "20"

# Float para int (perde decimais)
valor = 3.7
valor_inteiro = int(valor) # 3

# Verificar tipo de uma variável
print(type(numero))        # <class 'int'>
print(type(texto))         # <class 'str'>
```

**Exemplo 2.7 – Programa com conversão de tipos:**
```python
# Calcular idade no ano 2050
nome = input("Qual é o seu nome? ")
ano_nascimento = int(input("Em que ano nasceu? "))

idade_2050 = 2050 - ano_nascimento

print(nome, "terá", idade_2050, "anos em 2050")
```

#### 2.4 Operadores

**Operadores Aritméticos:**
Realizam operações matemáticas.

**Exemplo 2.8 – Operadores aritméticos:**
```python
a = 10
b = 3

adicao = a + b          # 13
subtracao = a - b       # 7
multiplicacao = a * b   # 30
divisao = a / b         # 3.333...
divisao_inteira = a // b # 3
resto = a % b           # 1 (módulo)
potencia = a ** b       # 1000
```

**Operadores de Comparação:**
Comparam valores e retornam True ou False.

**Exemplo 2.9 – Operadores de comparação:**
```python
x = 5
y = 10

igual = x == y          # False
diferente = x != y      # True
maior = x > y           # False
menor = x < y           # True
maior_igual = x >= 5    # True
menor_igual = x <= 4    # False
```

**Operadores Lógicos:**
Combinam expressões booleanas.

**Exemplo 2.10 – Operadores lógicos:**
```python
idade = 20
tem_carta = True

# and (E lógico) - verdadeiro se ambas as condições forem verdadeiras
pode_conduzir = idade >= 18 and tem_carta  # True

# or (OU lógico) - verdadeiro se pelo menos uma condição for verdadeira
fim_semana = True
feriado = False
pode_descansar = fim_semana or feriado  # True

# not (NÃO lógico) - inverte o valor booleano
dia_trabalho = not fim_semana  # False
```

**Operadores de Atribuição:**
Atribuem valores a variáveis, podendo incluir operações.

**Exemplo 2.11 – Operadores de atribuição compostos:**
```python
x = 10

x += 5   # equivalente a: x = x + 5  (x = 15)
x -= 3   # equivalente a: x = x - 3  (x = 12)
x *= 2   # equivalente a: x = x * 2  (x = 24)
x /= 4   # equivalente a: x = x / 4  (x = 6.0)
x //= 2  # equivalente a: x = x // 2 (x = 3.0)
x %= 2   # equivalente a: x = x % 2  (x = 1.0)
x **= 3  # equivalente a: x = x ** 3 (x = 1.0)
```

**Precedência de Operadores:**
Ordem de avaliação das operações (da maior para menor precedência):
1. Parênteses ()
2. Potenciação **
3. Multiplicação *, Divisão /, Divisão inteira //, Módulo %
4. Adição +, Subtração -
5. Comparação <, >, <=, >=, ==, !=
6. not
7. and
8. or

**Exemplo 2.12 – Precedência de operadores:**
```python
resultado1 = 2 + 3 * 4         # 14 (não 20)
resultado2 = (2 + 3) * 4       # 20
resultado3 = 10 + 5 * 2 - 3    # 17
resultado4 = True or False and False  # True
```

---

### UNIDADE TEMÁTICA 3: ESTRUTURAS DE CONTROLO – SELEÇÃO
**Duração:** 8 horas (2 sessões)

#### 3.1 Estrutura Condicional Simples (if)

**Definição:**
A estrutura if permite executar um bloco de código apenas se uma determinada condição for verdadeira. É a estrutura de decisão mais básica.

**Sintaxe:**
```python
if condição:
    instrução1
    instrução2
    # ...
```

**Exemplo 3.1 – if simples:**
```python
idade = int(input("Qual é a sua idade? "))

if idade >= 18:
    print("É maior de idade")
    print("Pode tirar a carta de condução")
```

**Exemplo 3.2 – Verificação de número positivo:**
```python
numero = float(input("Introduza um número: "))

if numero > 0:
    print("O número é positivo")
    
if numero == 0:
    print("O número é zero")
    
if numero < 0:
    print("O número é negativo")
```

#### 3.2 Estrutura Condicional Composta (if-else)

**Definição:**
A estrutura if-else permite executar um bloco de código se a condição for verdadeira e outro bloco diferente se a condição for falsa.

**Sintaxe:**
```python
if condição:
    instruções_se_verdadeiro
else:
    instruções_se_falso
```

**Exemplo 3.3 – if-else básico:**
```python
idade = int(input("Qual é a sua idade? "))

if idade >= 18:
    print("É maior de idade")
else:
    print("É menor de idade")
```

**Exemplo 3.4 – Validação de nota:**
```python
nota = float(input("Introduza a sua nota (0-20): "))

if nota >= 10:
    print("Aprovado! Parabéns!")
else:
    print("Reprovado. Estude mais na próxima vez.")
```

**Exemplo 3.5 – Calculadora de desconto:**
```python
preco = float(input("Preço do produto: "))
tem_cartao = input("Tem cartão de fidelidade? (sim/não): ")

if tem_cartao.lower() == "sim":
    preco_final = preco * 0.9  # 10% de desconto
    print(f"Com desconto: {preco_final:.2f}€")
else:
    print(f"Sem desconto: {preco:.2f}€")
```

#### 3.3 Estrutura Condicional Encadeada (if-elif-else)

**Definição:**
A estrutura if-elif-else permite testar múltiplas condições em sequência. É executado apenas o bloco correspondente à primeira condição verdadeira.

**Sintaxe:**
```python
if condição1:
    instruções1
elif condição2:
    instruções2
elif condição3:
    instruções3
else:
    instruções_caso_nenhuma_seja_verdadeira
```

**Exemplo 3.6 – Classificação de notas:**
```python
nota = float(input("Introduza a nota (0-20): "))

if nota >= 18:
    classificacao = "Excelente"
elif nota >= 16:
    classificacao = "Muito Bom"
elif nota >= 14:
    classificacao = "Bom"
elif nota >= 10:
    classificacao = "Suficiente"
else:
    classificacao = "Insuficiente"

print(f"Classificação: {classificacao}")
```

**Exemplo 3.7 – Calculadora de IMC:**
```python
peso = float(input("Peso em kg: "))
altura = float(input("Altura em metros: "))

imc = peso / (altura ** 2)

print(f"O seu IMC é: {imc:.2f}")

if imc < 18.5:
    categoria = "Abaixo do peso"
elif imc < 25:
    categoria = "Peso normal"
elif imc < 30:
    categoria = "Sobrepeso"
else:
    categoria = "Obesidade"

print(f"Categoria: {categoria}")
```

**Exemplo 3.8 – Sistema de avaliação de desempenho:**
```python
vendas = int(input("Número de vendas no mês: "))
meta = 50

if vendas >= meta * 1.5:
    bonus = 500
    avaliacao = "Excelente desempenho!"
elif vendas >= meta:
    bonus = 200
    avaliacao = "Bom desempenho!"
elif vendas >= meta * 0.75:
    bonus = 50
    avaliacao = "Desempenho aceitável"
else:
    bonus = 0
    avaliacao = "Desempenho abaixo do esperado"

print(avaliacao)
print(f"Bónus: {bonus}€")
```

#### 3.4 Condições Compostas e Aninhamento

**Condições Compostas:**
Utilizam operadores lógicos (and, or, not) para combinar múltiplas condições.

**Exemplo 3.9 – Condições compostas:**
```python
idade = int(input("Idade: "))
tem_autorizacao = input("Tem autorização dos pais? (sim/não): ")

# Usando operador and
if idade >= 18 and idade < 65:
    print("Pode participar no programa de voluntariado")

# Condição mais complexa
if (idade >= 16 and idade < 18 and tem_autorizacao.lower() == "sim") or idade >= 18:
    print("Pode inscrever-se no curso")
else:
    print("Não pode inscrever-se")
```

**Exemplo 3.10 – Validação de acesso:**
```python
utilizador = input("Utilizador: ")
password = input("Password: ")
token = input("Token de autenticação: ")

if (utilizador == "admin" and password == "1234") or token == "ABC123":
    print("Acesso autorizado")
else:
    print("Acesso negado")
```

**Condições Aninhadas:**
Estruturas if dentro de outras estruturas if, criando níveis de decisão.

**Exemplo 3.11 – if aninhado:**
```python
tem_bilhete = input("Tem bilhete? (sim/não): ")

if tem_bilhete.lower() == "sim":
    idade = int(input("Qual é a sua idade? "))
    
    if idade < 12:
        preco = 5
        print("Bilhete criança: 5€")
    elif idade < 65:
        preco = 10
        print("Bilhete adulto: 10€")
    else:
        preco = 7
        print("Bilhete sénior: 7€")
else:
    print("Por favor, compre um bilhete primeiro")
```

**Exemplo 3.12 – Sistema de aprovação académica:**
```python
frequencia = float(input("Nota de frequência (0-20): "))

if frequencia >= 10:
    print("Admitido a exame")
    exame = float(input("Nota de exame (0-20): "))
    
    nota_final = (frequencia * 0.4) + (exame * 0.6)
    
    print(f"Nota final: {nota_final:.1f}")
    
    if nota_final >= 10:
        print("Aprovado!")
    else:
        print("Reprovado")
else:
    print("Não admitido a exame. Reprovado por frequência.")
```

---
# Exercício – Cálculo do custo de estacionamento

## Contexto
Um parque de estacionamento pretende desenvolver um programa em **Python**, utilizando programação estruturada, para calcular o valor a pagar por um cliente.  
O cálculo deve ter em conta o **tipo de veículo**, o **tempo de permanência** e a existência de **descontos**.

O programa deve executar o cálculo **uma única vez**, não sendo permitida a utilização de ciclos (`while` ou `for`).

---

## Objetivo
Aplicar os conhecimentos adquiridos até ao **Exemplo 3.10**, nomeadamente:
- Entrada e saída de dados
- Estruturas de decisão (`if`, `elif`, `else`)
- Operadores aritméticos e lógicos
- Variáveis simples
- Validação de dados

---

## 1. Entrada de dados

O programa deve solicitar ao utilizador:

- O **tipo de veículo**:
  - `L` – Ligeiro  
  - `M` – Motociclo  
  - `P` – Pesado  

- O **número de horas** de estacionamento (inteiro positivo)

- Se o cliente é **cliente frequente**:
  - `S` – Sim  
  - `N` – Não  

---

## 2. Tabela de preços por hora

| Tipo de veículo | Preço por hora |
|-----------------|---------------|
| Ligeiro (L)     | 2,00 €        |
| Motociclo (M)   | 1,00 €        |
| Pesado (P)      | 3,50 €        |

---

## 3. Validação dos dados

O programa deve validar os dados introduzidos:

- O tipo de veículo deve ser `L`, `M` ou `P`
- O número de horas deve ser superior a zero
- A indicação de cliente frequente deve ser `S` ou `N`

Se algum dos dados for inválido, o programa deve apresentar uma mensagem de erro adequada e terminar a execução, sem efetuar quaisquer cálculos.

---

## 4. Cálculo do custo base

O custo base é calculado da seguinte forma:

    custo_base = preço_por_hora × número_de_horas


---

## 5. Desconto por tempo de permanência

Deve ser aplicado **apenas um** dos seguintes descontos:

- Mais de **10 horas** → **20%** de desconto  
- Entre **6 e 10 horas** (inclusive) → **10%** de desconto  
- Menos de **6 horas** → **0%** de desconto  

---

## 6. Desconto adicional para cliente frequente

Se o cliente for frequente (`S`), deve ser aplicado um **desconto adicional de 5%** sobre o valor já com o desconto de tempo aplicado.

---

## 7. Resultados a apresentar

Se todos os dados forem válidos, o programa deve apresentar:

- Tipo de veículo
- Número de horas de estacionamento
- Custo base
- Percentagem total de desconto aplicada
- Valor total do desconto
- Valor final a pagar

Os valores monetários devem ser apresentados com duas casas decimais.

---

## 8. Restrições técnicas

O programa deve respeitar as seguintes restrições:

- Não utilizar ciclos (`while`, `for`)
- Não utilizar listas, dicionários ou funções
- Utilizar apenas estruturas sequenciais e de decisão
- Utilizar exclusivamente os conteúdos abordados até ao **Exemplo 3.10**

---
## Solução do exercicio
```python

# Entrada de Dados
tipo_veiculo = input("Introduza tipo de veiculo L/M/P : ")
horas = int(input("Introduza nr de horas de estacionamento > 0 : "))
cliente_frequente = input("É cliente frequente ? (S)im (N)ão : ")

# Validação de dados
erro_de_dados = False

if tipo_veiculo.upper() != "L" and tipo_veiculo.upper() != "M" and tipo_veiculo.upper() != "P" :
    print("Tipo de veiculo inválido")
    erro_de_dados = True

if horas <= 0 :
    print("Horas devem ser > 0")
    erro_de_dados = True

if cliente_frequente.upper() != "S" and cliente_frequente.upper() != "N":
    print("Tipo de cliente inválido")
    erro_de_dados = True

if tipo_veiculo.upper() == "L":
    preco_hora = 2.00
elif tipo_veiculo.upper() == "M" :
    preco_hora = 1.00
else: # tipo_veiculo = "P"
    preco_hora = 3.50

custo_base = preco_hora * horas

if horas > 10 :
    preco_desconto = custo_base * 0.8
elif horas >=6 and horas <= 10 :
    preco_desconto = custo_base * 0.9
else: 
    preco_desconto = custo_base

if cliente_frequente.upper() == "S":
    valor_pagar = preco_desconto * 0.95
else:
    valor_pagar = preco_desconto

if erro_de_dados == False :
    print("\n--- Resumo do Estacionamento ---")
    print("Tipo de veiculo : ", tipo_veiculo.upper())
    print("Horas estacionamento : ", horas)
    print("Preço hora :", preco_hora)
    print("Preço com desconto : ", preco_desconto)
    if cliente_frequente.upper() == "S":
        print("É Cliente frequente, tem desconto adicional de 5% ")
    else:
        print("Cliente não frequente !")

    print(f"Total a pagar :  {valor_pagar:.2f}€")
    print("\n--- Resumo do Estacionamento ---")

else:
    print("Ocorreu um erro de validação de dados !")
```
### UNIDADE TEMÁTICA 4: ESTRUTURAS DE CONTROLO – REPETIÇÃO
**Duração:** 10 horas (2.5 sessões)

#### 4.1 Ciclo while

**Definição:**
O ciclo while repete um bloco de código enquanto uma condição for verdadeira. A condição é verificada antes de cada iteração. Se a condição for inicialmente falsa, o bloco nunca é executado.

**Sintaxe:**
```python
while condição:
    instruções
    # atualização da condição
```

**Exemplo 4.1 – while básico:**
```python
contador = 1

while contador <= 5:
    print(f"Contagem: {contador}")
    contador += 1

print("Fim da contagem")
```

**Exemplo 4.2 – Soma de números:**
```python
soma = 0
numero = 1

while numero <= 10:
    soma += numero
    numero += 1

print(f"A soma de 1 a 10 é: {soma}")
```

**Exemplo 4.3 – Validação de entrada:**
```python
password = ""
contador = 0
while password != "python123" and contador < 3:
    password = input("Introduza a password: ")
    
    if password != "python123":
        print("Password incorreta. Tente novamente.")
        contador += 1
        print("Numero de tentativas restantes : ", 3 - contador)
        if contador == 3:
            print("Nr tentivas excedidas - acesso bloqueado !")
    else: 
        print("Password correta! Acesso concedido.")
```

**Exemplo 4.4 – Menu interativo:**
```python
if saldo < valor: 
            print("Saldo insuficiente!")
```

#### 4.2 Ciclo for

**Definição:**
O ciclo for é usado para iterar sobre uma sequência (lista, tuplo, string, range) ou qualquer objeto iterável. É especialmente útil quando se conhece antecipadamente o número de iterações.

**Sintaxe:**
```python
for variável in sequência:
    instruções
```

**Função range():**
Gera uma sequência de números. Pode receber 1, 2 ou 3 argumentos:
- range(fim): de 0 até fim-1
- range(início, fim): de início até fim-1
- range(início, fim, passo): de início até fim-1, com incremento especificado

**Exemplo 4.5 – for com range:**
```python
# Imprimir números de 1 a 5
for i in range(1, 6):
    print(i)

# Imprimir números pares de 0 a 10
for i in range(0, 11, 2):
    print(i)

# Contagem decrescente
for i in range(10, 0, -1):
    print(i)
print("Lançamento!")
```

**Exemplo 4.6 – Tabuada:**
```python
numero = int(input("Que tabuada deseja? "))

print(f"\nTabuada do {numero}:")
for i in range(1, 11):
    resultado = numero * i
    print(f"{numero} x {i} = {resultado}")
```

**Exemplo 4.7 – Iteração sobre strings:**
```python
nome = "Python"

print("Letras do nome:")
for letra in nome:
    print(letra)

# Contar vogais
texto = "Programação em Python"
vogais = "aeiouAEIOU"
contador = 0

for caracter in texto:
    if caracter in vogais:
        contador += 1

print(f"Número de vogais: {contador}")
```

**Exemplo 4.8 – Cálculo de média:**
```python
soma = 0
quantidade = 5

print("Introduza 5 notas:")
for i in range(1, quantidade + 1):
    nota = float(input(f"Nota {i}: "))
    soma += nota

media = soma / quantidade
print(f"Média: {media:.2f}")
```

#### 4.3 Instruções break e continue

**break:**
Interrompe imediatamente o ciclo, saindo dele completamente.

**Exemplo 4.9 – Uso de break:**
```python
# Procurar um número
numeros = [3, 7, 2, 9, 15, 4]
procurar = 9

for num in numeros:
    if num == procurar:
        print(f"Número {procurar} encontrado!")
        break
print("Pesquisa concluída")

# Sistema de login com tentativas limitadas
tentativas = 0
max_tentativas = 3

while tentativas < max_tentativas:
    password = input("Password: ")
    
    if password == "secreta":
        print("Login bem-sucedido!")
        break
    else:
        tentativas += 1
        restantes = max_tentativas - tentativas
        if restantes > 0:
            print(f"Incorreta. Restam {restantes} tentativas")
        else:
            print("Conta bloqueada!")
```

**continue:**
Salta para a próxima iteração do ciclo, ignorando o código restante da iteração atual.

**Exemplo 4.10 – Uso de continue:**
```python
# Imprimir apenas números ímpares
for i in range(1, 11):
    if i % 2 == 0:
        continue  # Salta números pares
    print(i)

# Processar apenas valores válidos
print("Introduza números (0 para terminar):")
soma = 0

while True:
    numero = float(input("Número: "))
    
    if numero == 0:
        break
    
    if numero < 0:
        print("Valor negativo ignorado")
        continue
    
    soma += numero

print(f"Soma dos valores positivos: {soma}")
```

#### 4.4 Ciclos Aninhados

**Definição:**
Ciclos aninhados são ciclos dentro de outros ciclos. São úteis para trabalhar com estruturas bidimensionais ou realizar operações complexas.

**Exemplo 4.11 – Padrões com ciclos aninhados:**
```python
# Imprimir um triângulo de asteriscos
linhas = 5

for i in range(1, linhas + 1):
    for j in range(i):
        print("*", end="")
    print()  # Nova linha

# Resultado:
# *
# **
# ***
# ****
# *****
```

**Exemplo 4.12 – Tabuadas de 1 a 5:**
```python
for numero in range(1, 6):
    print(f"\nTabuada do {numero}:")
    for multiplicador in range(1, 11):
        resultado = numero * multiplicador
        print(f"{numero} x {multiplicador} = {resultado}")
```

**Exemplo 4.13 – Matriz de números:**
```python
# Criar uma matriz 3x3
linhas = 3
colunas = 3

print("Matriz 3x3:")
for i in range(linhas):
    for j in range(colunas):
        print(f"{i},{j}", end="  ")
    print()
```

---

### UNIDADE TEMÁTICA 5: FUNÇÕES E MODULARIZAÇÃO
**Duração:** 8 horas (2 sessões)

#### 5.1 Conceito de Funções

**Definição:**
Uma função é um bloco de código reutilizável que executa uma tarefa específica. As funções permitem organizar o código, evitar repetições e facilitar a manutenção. Em Python, as funções são definidas com a palavra-chave `def`.

**Vantagens das funções:**
- Reutilização de código
- Organização e modularização
- Facilidade de manutenção
- Redução de erros
- Abstração de complexidade

**Sintaxe:**
```python
def nome_funcao(parâmetros):
    """Documentação da função (docstring)"""
    instruções
    return valor  # opcional
```

**Exemplo 5.1 – Função simples sem parâmetros:**
```python
def saudacao():
    """Função que imprime uma saudação"""
    print("Olá! Bem-vindo ao programa.")
    print("Esperamos que se divirta!")

# Chamada da função
saudacao()
saudacao()  # Pode ser chamada múltiplas vezes
```

**Exemplo 5.2 – Função com parâmetros:**
```python
def saudacao_personalizada(nome):
    """Função que saúda uma pessoa pelo nome"""
    print(f"Olá, {nome}!")
    print("É um prazer ter-te aqui.")

# Chamadas com diferentes argumentos
saudacao_personalizada("João")
saudacao_personalizada("Maria")
```

#### 5.2 Parâmetros e Argumentos

**Parâmetros:**
São variáveis declaradas na definição da função que receberão os valores quando a função for chamada.

**Argumentos:**
São os valores reais passados à função quando esta é invocada.

**Exemplo 5.3 – Funções com múltiplos parâmetros:**
```python
def calcular_area_retangulo(largura, altura):
    """Calcula a área de um retângulo"""
    area = largura * altura
    print(f"Área: {area} unidades quadradas")

# Chamada com argumentos posicionais
calcular_area_retangulo(5, 3)

# Chamada com argumentos nomeados
calcular_area_retangulo(altura=3, largura=5)
```

**Parâmetros com valores padrão (default):**

**Exemplo 5.4 – Parâmetros com valores padrão:**
```python
def calcular_preco_final(preco, desconto=0):
    """Calcula o preço final com desconto opcional"""
    preco_final = preco * (1 - desconto)
    return preco_final

# Chamada sem desconto (usa valor padrão 0)
preco1 = calcular_preco_final(100)
print(f"Preço: {preco1}€")

# Chamada com desconto
preco2 = calcular_preco_final(100, 0.15)
print(f"Preço com 15% desconto: {preco2}€")
```

#### 5.3 Instrução return

**Definição:**
A instrução return termina a execução da função e devolve um valor ao código que a invocou. Uma função pode retornar qualquer tipo de dado.

**Exemplo 5.5 – Funções com retorno:**
```python
def somar(a, b):
    """Retorna a soma de dois números"""
    resultado = a + b
    return resultado

def subtrair(a, b):
    """Retorna a diferença entre dois números"""
    return a - b

# Usar os valores retornados
x = somar(10, 5)
y = subtrair(10, 5)

print(f"Soma: {x}")
print(f"Subtração: {y}")
print(f"Multiplicação dos resultados: {x * y}")
```

**Exemplo 5.6 – Retorno de múltiplos valores:**
```python
def operacoes_basicas(a, b):
    """Retorna soma, subtração, multiplicação e divisão"""
    soma = a + b
    subtracao = a - b
    multiplicacao = a * b
    divisao = a / b if b != 0 else None
    
    return soma, subtracao, multiplicacao, divisao

# Receber múltiplos valores
s, sub, m, d = operacoes_basicas(20, 4)

print(f"Soma: {s}")
print(f"Subtração: {sub}")
print(f"Multiplicação: {m}")
print(f"Divisão: {d}")
```

**Exemplo 5.7 – Função de validação:**
```python
def validar_nota(nota):
    """Verifica se uma nota está no intervalo válido [0, 20]"""
    if nota < 0 or nota > 20:
        return False
    return True

def obter_classificacao(nota):
    """Retorna a classificação de acordo com a nota"""
    if not validar_nota(nota):
        return "Nota inválida"
    
    if nota >= 18:
        return "Excelente"
    elif nota >= 16:
        return "Muito Bom"
    elif nota >= 14:
        return "Bom"
    elif nota >= 10:
        return "Suficiente"
    else:
        return "Insuficiente"

# Uso das funções
nota_aluno = 17
if validar_nota(nota_aluno):
    classificacao = obter_classificacao(nota_aluno)
    print(f"Nota {nota_aluno}: {classificacao}")
```

#### 5.4 Âmbito de Variáveis (Scope)

**Variáveis Locais:**
Declaradas dentro de uma função, só existem dentro dessa função.

**Variáveis Globais:**
Declaradas fora de funções, acessíveis em todo o programa.

**Exemplo 5.8 – Âmbito de variáveis:**
```python
# Variável global
total_vendas = 0

def registar_venda(valor):
    """Regista uma venda"""
    # Variável local
    comissao = valor * 0.1
    print(f"Venda: {valor}€, Comissão: {comissao}€")
    
    # Para modificar variável global, usar 'global'
    global total_vendas
    total_vendas += valor

def mostrar_total():
    """Mostra o total de vendas"""
    print(f"Total vendas: {total_vendas}€")

# Uso
registar_venda(100)
registar_venda(250)
mostrar_total()
```

**Exemplo 5.9 – Programa com funções modulares:**
```python
def ler_numero(mensagem):
    """Lê um número do utilizador com validação"""
    while True:
        try:
            numero = float(input(mensagem))
            return numero
        except ValueError:
            print("Valor inválido. Introduza um número.")

def calcular_media(notas):
    """Calcula a média de uma lista de notas"""
    if len(notas) == 0:
        return 0
    return sum(notas) / len(notas)

def main():
    """Função principal do programa"""
    print("=== CÁLCULO DE MÉDIA ===")
    
    quantidade = int(input("Quantas notas? "))
    notas = []
    
    for i in range(1, quantidade + 1):
        nota = ler_numero(f"Nota {i}: ")
        notas.append(nota)
    
    media = calcular_media(notas)
    print(f"\nMédia final: {media:.2f}")
    
    if media >= 10:
        print("Resultado: APROVADO")
    else:
        print("Resultado: REPROVADO")

# Executar programa
main()
```

#### 5.5 Funções Recursivas

**Definição:**
Uma função recursiva é uma função que se chama a si própria. Deve ter sempre uma condição de paragem para evitar recursão infinita.

**Exemplo 5.10 – Factorial recursivo:**
```python
def factorial(n):
    """Calcula o factorial de n"""
    # Condição de paragem
    if n == 0 or n == 1:
        return 1
    else:
        # Chamada recursiva
        return n * factorial(n - 1)

# Teste
numero = 5
resultado = factorial(numero)
print(f"Factorial de {numero} = {resultado}")
# 5! = 5 x 4 x 3 x 2 x 1 = 120
```

---

### UNIDADE TEMÁTICA 6: ESTRUTURAS DE DADOS COMPOSTAS
**Duração:** 8 horas (2 sessões)

#### 6.1 Listas (Lists)

**Definição:**
Uma lista é uma coleção ordenada e mutável de elementos. Os elementos podem ser de diferentes tipos e podem ser modificados após a criação da lista. As listas são delimitadas por parênteses retos [].

**Características:**
- Ordenadas (mantêm a ordem de inserção)
- Mutáveis (podem ser alteradas)
- Permitem duplicados
- Indexadas (começam em 0)

**Exemplo 6.1 – Criação e acesso a listas:**
```python
# Criar listas
numeros = [1, 2, 3, 4, 5]
nomes = ["Ana", "Bruno", "Carlos"]
mista = [1, "texto", 3.14, True]
vazia = []

# Acesso por índice (começa em 0)
print(nomes[0])     # Ana
print(nomes[1])     # Bruno
print(nomes[-1])    # Carlos (último elemento)
print(nomes[-2])    # Bruno (penúltimo)

# Slicing (fatiar listas)
print(numeros[1:4])  # [2, 3, 4]
print(numeros[:3])   # [1, 2, 3]
print(numeros[2:])   # [3, 4, 5]
print(numeros[::2])  # [1, 3, 5] (com passo 2)
```

**Exemplo 6.2 – Modificação de listas:**
```python
frutas = ["maçã", "banana", "laranja"]

# Alterar elemento
frutas[1] = "morango"
print(frutas)  # ["maçã", "morango", "laranja"]

# Adicionar elementos
frutas.append("uva")           # Adiciona no final
frutas.insert(1, "pêra")       # Insere na posição 1

print(frutas)  # ["maçã", "pêra", "morango", "laranja", "uva"]

# Remover elementos
frutas.remove("morango")       # Remove pelo valor
elemento = frutas.pop()        # Remove e retorna o último
del frutas[0]                  # Remove pela posição

print(frutas)  # ["pêra", "laranja"]
```

**Exemplo 6.3 – Operações com listas:**
```python
lista1 = [1, 2, 3]
lista2 = [4, 5, 6]

# Concatenação
lista3 = lista1 + lista2        # [1, 2, 3, 4, 5, 6]

# Repetição
lista4 = lista1 * 2             # [1, 2, 3, 1, 2, 3]

# Tamanho
tamanho = len(lista1)           # 3

# Verificar existência
existe = 2 in lista1            # True

# Ordenação
numeros = [5, 2, 8, 1, 9]
numeros.sort()                  # Ordena a lista
print(numeros)                  # [1, 2, 5, 8, 9]

numeros_desc = sorted(numeros, reverse=True)  # Nova lista ordenada
print(numeros_desc)             # [9, 8, 5, 2, 1]

# Outras operações úteis
maximo = max(numeros)           # 9
minimo = min(numeros)           # 1
soma = sum(numeros)             # 25
```

**Exemplo 6.4 – Iterar sobre listas:**
```python
alunos = ["João", "Maria", "Pedro", "Ana"]

# Iterar pelos elementos
for aluno in alunos:
    print(f"Olá, {aluno}")

# Iterar com índice
for i in range(len(alunos)):
    print(f"{i+1}. {alunos[i]}")

# Iterar com enumerate
for indice, aluno in enumerate(alunos, start=1):
    print(f"{indice}. {aluno}")
```

**Exemplo 6.5 – Lista de notas:**
```python
def processar_notas():
    """Programa para processar notas de alunos"""
    notas = []
    
    # Ler notas
    print("Introduza as notas (negativo para terminar):")
    while True:
        nota = float(input("Nota: "))
        if nota < 0:
            break
        if nota <= 20:
            notas.append(nota)
        else:
            print("Nota inválida (máximo 20)")
    
    # Processar
    if len(notas) > 0:
        media = sum(notas) / len(notas)
        maior = max(notas)
        menor = min(notas)
        
        print(f"\nEstatísticas:")
        print(f"Total de notas: {len(notas)}")
        print(f"Média: {media:.2f}")
        print(f"Maior nota: {maior}")
        print(f"Menor nota: {menor}")
        
        # Contar aprovações
        aprovados = sum(1 for n in notas if n >= 10)
        print(f"Aprovados: {aprovados}")

processar_notas()
```

#### 6.2 Tuplos (Tuples)

**Definição:**
Um tuplo é semelhante a uma lista, mas é imutável (não pode ser modificado após criação). Os tuplos são delimitados por parênteses ().

**Características:**
- Ordenados
- Imutáveis
- Permitem duplicados
- Mais rápidos que listas
- Usados para dados que não devem mudar

**Exemplo 6.6 – Tuplos:**
```python
# Criar tuplos
coordenadas = (10, 20)
pessoa = ("João", 25, "Porto")
singleton = (5,)  # Tuplo com um elemento (vírgula obrigatória)

# Acesso
print(coordenadas[0])  # 10
print(pessoa[2])       # Porto

# Desempacotamento
x, y = coordenadas
nome, idade, cidade = pessoa
print(f"{nome} tem {idade} anos e vive no {cidade}")

# Tuplos são imutáveis
# pessoa[1] = 26  # ERRO! Não é possível modificar
```

**Exemplo 6.7 – Retornar múltiplos valores com tuplos:**
```python
def obter_estatisticas(numeros):
    """Retorna média, mínimo e máximo"""
    media = sum(numeros) / len(numeros)
    minimo = min(numeros)
    maximo = max(numeros)
    return media, minimo, maximo  # Retorna um tuplo

valores = [10, 25, 30, 15, 20]
med, min_val, max_val = obter_estatisticas(valores)

print(f"Média: {med}, Mínimo: {min_val}, Máximo: {max_val}")
```

#### 6.3 Dicionários (Dictionaries)

**Definição:**
Um dicionário é uma coleção não ordenada de pares chave-valor. Cada chave é única e permite acesso rápido ao valor correspondente. São delimitados por chavetas {}.

**Características:**
- Não ordenados (até Python 3.6, a partir de 3.7 mantêm ordem de inserção)
- Mutáveis
- Chaves únicas
- Acesso rápido por chave

**Exemplo 6.8 – Dicionários básicos:**
```python
# Criar dicionários
aluno = {
    "nome": "João Silva",
    "idade": 18,
    "curso": "Informática",
    "nota": 15.5
}

# Acesso aos valores
print(aluno["nome"])        # João Silva
print(aluno.get("idade"))   # 18
print(aluno.get("email", "Não definido"))  # Valor padrão se não existir

# Modificar valores
aluno["nota"] = 16.0
aluno["email"] = "joao@email.com"  # Adicionar novo par

# Remover elementos
del aluno["idade"]
email = aluno.pop("email")  # Remove e retorna o valor

print(aluno)
```

**Exemplo 6.9 – Operações com dicionários:**
```python
produto = {
    "nome": "Portátil",
    "preco": 599.99,
    "stock": 15
}

# Verificar existência de chave
if "preco" in produto:
    print(f"Preço: {produto['preco']}€")

# Obter todas as chaves
chaves = produto.keys()
print(list(chaves))  # ['nome', 'preco', 'stock']

# Obter todos os valores
valores = produto.values()
print(list(valores))

# Obter pares chave-valor
itens = produto.items()
for chave, valor in itens:
    print(f"{chave}: {valor}")

# Número de elementos
tamanho = len(produto)
```

**Exemplo 6.10 – Agenda telefónica:**
```python
def criar_agenda():
    """Sistema de agenda telefónica"""
    agenda = {}
    
    while True:
        print("\n=== AGENDA ===")
        print("1. Adicionar contacto")
        print("2. Procurar contacto")
        print("3. Listar todos")
        print("4. Remover contacto")
        print("5. Sair")
        
        opcao = input("Opção: ")
        
        if opcao == "1":
            nome = input("Nome: ")
            telefone = input("Telefone: ")
            agenda[nome] = telefone
            print("Contacto adicionado!")
            
        elif opcao == "2":
            nome = input("Nome a procurar: ")
            if nome in agenda:
                print(f"Telefone: {agenda[nome]}")
            else:
                print("Contacto não encontrado")
                
        elif opcao == "3":
            if len(agenda) == 0:
                print("Agenda vazia")
            else:
                print("\nContactos:")
                for nome, telefone in agenda.items():
                    print(f"{nome}: {telefone}")
                    
        elif opcao == "4":
            nome = input("Nome a remover: ")
            if nome in agenda:
                del agenda[nome]
                print("Contacto removido!")
            else:
                print("Contacto não encontrado")
                
        elif opcao == "5":
            print("Até breve!")
            break

criar_agenda()
```

#### 6.4 Conjuntos (Sets)

**Definição:**
Um conjunto é uma coleção não ordenada de elementos únicos. Útil para operações matemáticas de conjuntos e para eliminar duplicados.

**Exemplo 6.11 – Conjuntos:**
```python
# Criar conjuntos
numeros = {1, 2, 3, 4, 5}
frutas = set(["maçã", "banana", "maçã"])  # Remove duplicados
print(frutas)  # {'maçã', 'banana'}

# Operações
conjunto_a = {1, 2, 3, 4}
conjunto_b = {3, 4, 5, 6}

uniao = conjunto_a | conjunto_b         # {1, 2, 3, 4, 5, 6}
intersecao = conjunto_a & conjunto_b    # {3, 4}
diferenca = conjunto_a - conjunto_b     # {1, 2}

print(f"União: {uniao}")
print(f"Interseção: {intersecao}")
print(f"Diferença: {diferenca}")
```

---

### UNIDADE TEMÁTICA 7: MANIPULAÇÃO DE FICHEIROS
**Duração:** 6 horas (1.5 sessões)

#### 7.1 Leitura de Ficheiros de Texto

**Definição:**
Python permite ler dados de ficheiros externos, o que é essencial para processar grandes volumes de informação e persistir dados entre execuções do programa.

**Modos de abertura:**
- `'r'` - Leitura (read) - modo padrão
- `'w'` - Escrita (write) - cria novo ou sobrescreve
- `'a'` - Anexar (append) - adiciona ao final
- `'r+'` - Leitura e escrita

**Exemplo 7.1 – Leitura básica de ficheiro:**
```python
# Método 1: Ler todo o conteúdo
ficheiro = open("dados.txt", "r", encoding="utf-8")
conteudo = ficheiro.read()
print(conteudo)
ficheiro.close()

# Método 2: Usar with (recomendado)
with open("dados.txt", "r", encoding="utf-8") as ficheiro:
    conteudo = ficheiro.read()
    print(conteudo)
# O ficheiro é fechado automaticamente
```

**Exemplo 7.2 – Ler ficheiro linha a linha:**
```python
# Método 1: readline()
with open("notas.txt", "r", encoding="utf-8") as ficheiro:
    linha = ficheiro.readline()
    while linha:
        print(linha.strip())  # strip() remove \n
        linha = ficheiro.readline()

# Método 2: readlines()
with open("notas.txt", "r", encoding="utf-8") as ficheiro:
    linhas = ficheiro.readlines()
    for linha in linhas:
        print(linha.strip())

# Método 3: Iterar diretamente (mais eficiente)
with open("notas.txt", "r", encoding="utf-8") as ficheiro:
    for linha in ficheiro:
        print(linha.strip())
```

**Exemplo 7.3 – Processar ficheiro de notas:**
```python
def calcular_media_ficheiro(nome_ficheiro):
    """Calcula a média de notas num ficheiro"""
    try:
        with open(nome_ficheiro, "r", encoding="utf-8") as ficheiro:
            notas = []
            for linha in ficheiro:
                linha = linha.strip()
                if linha:  # Ignorar linhas vazias
                    try:
                        nota = float(linha)
                        notas.append(nota)
                    except ValueError:
                        print(f"Valor inválido ignorado: {linha}")
            
            if len(notas) > 0:
                media = sum(notas) / len(notas)
                print(f"Total de notas: {len(notas)}")
                print(f"Média: {media:.2f}")
                return media
            else:
                print("Nenhuma nota válida encontrada")
                return None
                
    except FileNotFoundError:
        print(f"Ficheiro '{nome_ficheiro}' não encontrado")
        return None

calcular_media_ficheiro("notas.txt")
```

#### 7.2 Escrita em Ficheiros de Texto

**Exemplo 7.4 – Escrita básica em ficheiro:**
```python
# Modo 'w' - cria novo ou sobrescreve
with open("saida.txt", "w", encoding="utf-8") as ficheiro:
    ficheiro.write("Primeira linha\n")
    ficheiro.write("Segunda linha\n")
    ficheiro.write("Terceira linha\n")

# Modo 'a' - anexa ao final
with open("saida.txt", "a", encoding="utf-8") as ficheiro:
    ficheiro.write("Linha adicional\n")
```

**Exemplo 7.5 – Gravar lista em ficheiro:**
```python
def gravar_lista_ficheiro(lista, nome_ficheiro):
    """Grava uma lista de strings num ficheiro"""
    with open(nome_ficheiro, "w", encoding="utf-8") as ficheiro:
        for item in lista:
            ficheiro.write(f"{item}\n")

nomes = ["Ana", "Bruno", "Carlos", "Diana"]
gravar_lista_ficheiro(nomes, "nomes.txt")
```

**Exemplo 7.6 – Sistema de registo de vendas:**
```python
def registar_venda(produto, quantidade, preco):
    """Regista uma venda num ficheiro"""
    total = quantidade * preco
    linha = f"{produto};{quantidade};{preco:.2f};{total:.2f}\n"
    
    with open("vendas.txt", "a", encoding="utf-8") as ficheiro:
        ficheiro.write(linha)
    
    print(f"Venda registada: {produto} - {total:.2f}€")

def relatorio_vendas():
    """Gera relatório das vendas"""
    try:
        total_geral = 0
        print("\n=== RELATÓRIO DE VENDAS ===")
        print(f"{'Produto':<20} {'Qtd':<8} {'Preço':<10} {'Total':<10}")
        print("-" * 55)
        
        with open("vendas.txt", "r", encoding="utf-8") as ficheiro:
            for linha in ficheiro:
                dados = linha.strip().split(";")
                if len(dados) == 4:
                    produto, qtd, preco, total = dados
                    print(f"{produto:<20} {qtd:<8} {preco:<10} {total:<10}")
                    total_geral += float(total)
        
        print("-" * 55)
        print(f"TOTAL GERAL: {total_geral:.2f}€")
        
    except FileNotFoundError:
        print("Nenhuma venda registada ainda")

# Uso
registar_venda("Portátil", 2, 599.99)
registar_venda("Rato", 5, 15.50)
registar_venda("Teclado", 3, 45.00)
relatorio_vendas()
```

#### 7.3 Tratamento de Exceções em Ficheiros

**Exemplo 7.7 – Tratamento robusto de erros:**
```python
def ler_ficheiro_seguro(nome_ficheiro):
    """Lê um ficheiro com tratamento de erros"""
    try:
        with open(nome_ficheiro, "r", encoding="utf-8") as ficheiro:
            conteudo = ficheiro.read()
            return conteudo
    except FileNotFoundError:
        print(f"Erro: Ficheiro '{nome_ficheiro}' não encontrado")
        return None
    except PermissionError:
        print(f"Erro: Sem permissão para ler '{nome_ficheiro}'")
        return None
    except UnicodeDecodeError:
        print(f"Erro: Problema de codificação no ficheiro")
        return None
    except Exception as e:
        print(f"Erro inesperado: {e}")
        return None

# Uso
conteudo = ler_ficheiro_seguro("dados.txt")
if conteudo:
    print(conteudo)
```

**Exemplo 7.8 – Programa completo de gestão de stock:**
```python
def menu_principal():
    """Sistema de gestão de stock"""
    ficheiro_stock = "stock.txt"
    
    while True:
        print("\n=== GESTÃO DE STOCK ===")
        print("1. Adicionar produto")
        print("2. Listar produtos")
        print("3. Procurar produto")
        print("4. Atualizar quantidade")
        print("5. Sair")
        
        opcao = input("\nEscolha uma opção: ")
        
        if opcao == "1":
            adicionar_produto(ficheiro_stock)
        elif opcao == "2":
            listar_produtos(ficheiro_stock)
        elif opcao == "3":
            procurar_produto(ficheiro_stock)
        elif opcao == "4":
            atualizar_quantidade(ficheiro_stock)
        elif opcao == "5":
            print("Programa terminado!")
            break
        else:
            print("Opção inválida!")

def adicionar_produto(ficheiro):
    """Adiciona um produto ao stock"""
    nome = input("Nome do produto: ")
    quantidade = int(input("Quantidade: "))
    preco = float(input("Preço unitário: "))
    
    with open(ficheiro, "a", encoding="utf-8") as f:
        f.write(f"{nome};{quantidade};{preco:.2f}\n")
    
    print("Produto adicionado com sucesso!")

def listar_produtos(ficheiro):
    """Lista todos os produtos"""
    try:
        print(f"\n{'Produto':<20} {'Quantidade':<12} {'Preço':<10} {'Valor Total':<12}")
        print("-" * 60)
        
        total_valor = 0
        with open(ficheiro, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) == 3:
                    nome, qtd, preco = dados
                    qtd = int(qtd)
                    preco = float(preco)
                    valor_total = qtd * preco
                    total_valor += valor_total
                    print(f"{nome:<20} {qtd:<12} {preco:<10.2f} {valor_total:<12.2f}")
        
        print("-" * 60)
        print(f"Valor total em stock: {total_valor:.2f}€")
        
    except FileNotFoundError:
        print("Nenhum produto em stock")

def procurar_produto(ficheiro):
    """Procura um produto pelo nome"""
    nome_procurar = input("Nome do produto: ").lower()
    encontrado = False
    
    try:
        with open(ficheiro, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) == 3:
                    nome, qtd, preco = dados
                    if nome_procurar in nome.lower():
                        print(f"\nProduto encontrado:")
                        print(f"Nome: {nome}")
                        print(f"Quantidade: {qtd}")
                        print(f"Preço: {preco}€")
                        encontrado = True
        
        if not encontrado:
            print("Produto não encontrado")
            
    except FileNotFoundError:
        print("Nenhum produto em stock")

def atualizar_quantidade(ficheiro):
    """Atualiza a quantidade de um produto"""
    nome_atualizar = input("Nome do produto: ").lower()
    nova_quantidade = int(input("Nova quantidade: "))
    
    try:
        linhas = []
        encontrado = False
        
        with open(ficheiro, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) == 3:
                    nome, qtd, preco = dados
                    if nome_atualizar in nome.lower():
                        linhas.append(f"{nome};{nova_quantidade};{preco}\n")
                        encontrado = True
                        print(f"Quantidade de '{nome}' atualizada!")
                    else:
                        linhas.append(linha)
        
        if encontrado:
            with open(ficheiro, "w", encoding="utf-8") as f:
                f.writelines(linhas)
        else:
            print("Produto não encontrado")
            
    except FileNotFoundError:
        print("Nenhum produto em stock")

# Executar programa
menu_principal()
```

---

### UNIDADE TEMÁTICA 8: PROJETO INTEGRADOR E BOAS PRÁTICAS
**Duração:** 4 horas (1 sessão)

#### 8.1 Boas Práticas de Programação

**Nomenclatura e Convenções:**

**PEP 8 - Guia de Estilo Python:**
- Nomes de variáveis e funções: minúsculas com underscores (snake_case)
  ```python
  nome_completo = "João Silva"
  calcular_media()
  ```

- Nomes de constantes: maiúsculas com underscores
  ```python
  PI = 3.14159
  TAXA_IVA = 0.23
  ```

- Nomes de classes: CamelCase (não coberto neste módulo)
  ```python
  class ContaBancaria:
      pass
  ```

- Indentação: 4 espaços
- Linhas com máximo de 79 caracteres
- Espaços à volta de operadores

**Exemplo 8.1 – Código bem formatado:**
```python
# Bom exemplo
def calcular_preco_final(preco_base, desconto=0, iva=0.23):
    """
    Calcula o preço final de um produto.
    
    Args:
        preco_base (float): Preço base do produto
        desconto (float): Percentagem de desconto (0-1)
        iva (float): Taxa de IVA (0-1)
    
    Returns:
        float: Preço final com desconto e IVA
    """
    preco_com_desconto = preco_base * (1 - desconto)
    preco_final = preco_com_desconto * (1 + iva)
    return preco_final

# Uso
preco = calcular_preco_final(100, desconto=0.1)
print(f"Preço final: {preco:.2f}€")
```

**Comentários e Documentação:**

**Exemplo 8.2 – Documentação adequada:**
```python
# Comentário de linha única explica POR QUE, não O QUE

def validar_nif(nif):
    """
    Valida um NIF português.
    
    O algoritmo verifica se o NIF tem 9 dígitos e se o dígito
    de controlo está correto segundo as regras da AT.
    
    Args:
        nif (str): NIF a validar (9 dígitos)
    
    Returns:
        bool: True se válido, False caso contrário
    
    Exemplo:
        >>> validar_nif("123456789")
        False
    """
    # Verificar se tem 9 dígitos
    if len(nif) != 9 or not nif.isdigit():
        return False
    
    # Calcular dígito de controlo
    soma = sum(int(nif[i]) * (9 - i) for i in range(8))
    digito_controlo = 11 - (soma % 11)
    
    if digito_controlo >= 10:
        digito_controlo = 0
    
    return int(nif[8]) == digito_controlo
```

**Tratamento de Erros:**

**Exemplo 8.3 – Tratamento robusto de erros:**
```python
def divisao_segura(a, b):
    """Realiza divisão com tratamento de erros"""
    try:
        resultado = a / b
        return resultado
    except ZeroDivisionError:
        print("Erro: Divisão por zero!")
        return None
    except TypeError:
        print("Erro: Tipos inválidos para divisão")
        return None

def ler_numero_inteiro(mensagem):
    """Lê um número inteiro com validação"""
    while True:
        try:
            valor = int(input(mensagem))
            return valor
        except ValueError:
            print("Erro: Introduza um número inteiro válido")
        except KeyboardInterrupt:
            print("\nOperação cancelada pelo utilizador")
            return None
```

#### 8.2 Depuração e Testes

**Técnicas de Depuração:**

**Exemplo 8.4 – Depuração com print:**
```python
def calcular_fatorial_debug(n):
    """Calcula factorial com mensagens de debug"""
    print(f"DEBUG: Calculando factorial de {n}")
    
    if n < 0:
        print("DEBUG: Número negativo - retornando None")
        return None
    
    resultado = 1
    for i in range(1, n + 1):
        resultado *= i
        print(f"DEBUG: i={i}, resultado parcial={resultado}")
    
    print(f"DEBUG: Resultado final={resultado}")
    return resultado

# Teste
calcular_fatorial_debug(5)
```

**Testes Simples:**

**Exemplo 8.5 – Função de teste:**
```python
def testar_funcao(funcao, casos_teste):
    """
    Testa uma função com vários casos de teste.
    
    Args:
        funcao: Função a testar
        casos_teste: Lista de tuplos (entrada, saida_esperada)
    """
    print(f"\nTestando função: {funcao.__name__}")
    sucessos = 0
    falhas = 0
    
    for entrada, esperado in casos_teste:
        resultado = funcao(entrada)
        if resultado == esperado:
            print(f"✓ PASSOU: {entrada} → {resultado}")
            sucessos += 1
        else:
            print(f"✗ FALHOU: {entrada} → {resultado} (esperado: {esperado})")
            falhas += 1
    
    print(f"\nResultado: {sucessos} sucessos, {falhas} falhas")

# Exemplo de uso
def eh_par(n):
    return n % 2 == 0

casos = [
    (2, True),
    (3, False),
    (0, True),
    (-4, True),
    (7, False)
]

testar_funcao(eh_par, casos)
```

#### 8.3 Projeto Integrador: Sistema de Gestão Escolar

**Exemplo 8.6 – Projeto completo:**
```python
"""
Sistema de Gestão Escolar
Permite gerir alunos, disciplinas e notas
"""

# Constantes
FICHEIRO_ALUNOS = "alunos.txt"
FICHEIRO_NOTAS = "notas.txt"
NOTA_MINIMA_APROVACAO = 10

def menu_principal():
    """Apresenta o menu principal"""
    while True:
        print("\n" + "="*50)
        print("SISTEMA DE GESTÃO ESCOLAR")
        print("="*50)
        print("1. Registar aluno")
        print("2. Registar nota")
        print("3. Consultar pauta de aluno")
        print("4. Relatório de turma")
        print("5. Estatísticas por disciplina")
        print("6. Sair")
        print("="*50)
        
        opcao = input("\nEscolha uma opção: ")
        
        if opcao == "1":
            registar_aluno()
        elif opcao == "2":
            registar_nota()
        elif opcao == "3":
            consultar_pauta()
        elif opcao == "4":
            relatorio_turma()
        elif opcao == "5":
            estatisticas_disciplina()
        elif opcao == "6":
            print("\nPrograma terminado. Até breve!")
            break
        else:
            print("\n⚠ Opção inválida!")

def registar_aluno():
    """Regista um novo aluno"""
    print("\n--- REGISTAR ALUNO ---")
    
    numero = input("Número do aluno: ")
    nome = input("Nome completo: ")
    turma = input("Turma: ")
    
    # Verificar se aluno já existe
    if aluno_existe(numero):
        print("⚠ Aluno já registado!")
        return
    
    try:
        with open(FICHEIRO_ALUNOS, "a", encoding="utf-8") as f:
            f.write(f"{numero};{nome};{turma}\n")
        print("✓ Aluno registado com sucesso!")
    except Exception as e:
        print(f"✗ Erro ao registar aluno: {e}")

def aluno_existe(numero):
    """Verifica se um aluno existe"""
    try:
        with open(FICHEIRO_ALUNOS, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) >= 1 and dados[0] == numero:
                    return True
    except FileNotFoundError:
        return False
    return False

def obter_nome_aluno(numero):
    """Obtém o nome de um aluno pelo número"""
    try:
        with open(FICHEIRO_ALUNOS, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) >= 2 and dados[0] == numero:
                    return dados[1]
    except FileNotFoundError:
        pass
    return None

def registar_nota():
    """Regista uma nota de um aluno"""
    print("\n--- REGISTAR NOTA ---")
    
    numero = input("Número do aluno: ")
    
    if not aluno_existe(numero):
        print("⚠ Aluno não encontrado!")
        return
    
    nome = obter_nome_aluno(numero)
    print(f"Aluno: {nome}")
    
    disciplina = input("Disciplina: ")
    
    try:
        nota = float(input("Nota (0-20): "))
        if nota < 0 or nota > 20:
            print("⚠ Nota inválida! Deve estar entre 0 e 20.")
            return
    except ValueError:
        print("⚠ Valor inválido!")
        return
    
    try:
        with open(FICHEIRO_NOTAS, "a", encoding="utf-8") as f:
            f.write(f"{numero};{disciplina};{nota:.2f}\n")
        print("✓ Nota registada com sucesso!")
    except Exception as e:
        print(f"✗ Erro ao registar nota: {e}")

def consultar_pauta():
    """Consulta a pauta de um aluno"""
    print("\n--- CONSULTAR PAUTA ---")
    
    numero = input("Número do aluno: ")
    
    if not aluno_existe(numero):
        print("⚠ Aluno não encontrado!")
        return
    
    nome = obter_nome_aluno(numero)
    print(f"\nPauta de: {nome} (Nº {numero})")
    print("-" * 50)
    print(f"{'Disciplina':<30} {'Nota':<10} {'Estado':<10}")
    print("-" * 50)
    
    try:
        notas_encontradas = False
        soma_notas = 0
        contador = 0
        
        with open(FICHEIRO_NOTAS, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) == 3 and dados[0] == numero:
                    disciplina = dados[1]
                    nota = float(dados[2])
                    estado = "Aprovado" if nota >= NOTA_MINIMA_APROVACAO else "Reprovado"
                    print(f"{disciplina:<30} {nota:<10.2f} {estado:<10}")
                    soma_notas += nota
                    contador += 1
                    notas_encontradas = True
        
        if notas_encontradas:
            media = soma_notas / contador
            print("-" * 50)
            print(f"Média: {media:.2f}")
        else:
            print("Sem notas registadas")
            
    except FileNotFoundError:
        print("Sem notas registadas")

def relatorio_turma():
    """Gera relatório completo da turma"""
    print("\n--- RELATÓRIO DE TURMA ---")
    
    turma = input("Turma: ")
    
    try:
        print(f"\nAlunos da turma {turma}:")
        print("-" * 70)
        print(f"{'Número':<10} {'Nome':<30} {'Média':<15} {'Estado':<15}")
        print("-" * 70)
        
        alunos_encontrados = False
        
        with open(FICHEIRO_ALUNOS, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) >= 3 and dados[2] == turma:
                    numero = dados[0]
                    nome = dados[1]
                    media = calcular_media_aluno(numero)
                    
                    if media is not None:
                        estado = "Aprovado" if media >= NOTA_MINIMA_APROVACAO else "Reprovado"
                        print(f"{numero:<10} {nome:<30} {media:<15.2f} {estado:<15}")
                    else:
                        print(f"{numero:<10} {nome:<30} {'Sem notas':<15} {'-':<15}")
                    
                    alunos_encontrados = True
        
        if not alunos_encontrados:
            print("Nenhum aluno encontrado nesta turma")
            
    except FileNotFoundError:
        print("⚠ Ficheiro de alunos não encontrado")

def calcular_media_aluno(numero):
    """Calcula a média de um aluno"""
    try:
        soma = 0
        contador = 0
        
        with open(FICHEIRO_NOTAS, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) == 3 and dados[0] == numero:
                    nota = float(dados[2])
                    soma += nota
                    contador += 1
        
        if contador > 0:
            return soma / contador
        else:
            return None
            
    except FileNotFoundError:
        return None

def estatisticas_disciplina():
    """Apresenta estatísticas de uma disciplina"""
    print("\n--- ESTATÍSTICAS POR DISCIPLINA ---")
    
    disciplina = input("Disciplina: ")
    
    try:
        notas = []
        
        with open(FICHEIRO_NOTAS, "r", encoding="utf-8") as f:
            for linha in f:
                dados = linha.strip().split(";")
                if len(dados) == 3 and dados[1].lower() == disciplina.lower():
                    nota = float(dados[2])
                    notas.append(nota)
        
        if len(notas) > 0:
            media = sum(notas) / len(notas)
            maxima = max(notas)
            minima = min(notas)
            aprovados = sum(1 for n in notas if n >= NOTA_MINIMA_APROVACAO)
            taxa_aprovacao = (aprovados / len(notas)) * 100
            
            print(f"\nEstatísticas de {disciplina}:")
            print("-" * 40)
            print(f"Total de notas: {len(notas)}")
            print(f"Média: {media:.2f}")
            print(f"Nota máxima: {maxima:.2f}")
            print(f"Nota mínima: {minima:.2f}")
            print(f"Aprovados: {aprovados} ({taxa_aprovacao:.1f}%)")
            print(f"Reprovados: {len(notas) - aprovados}")
        else:
            print("⚠ Sem notas registadas para esta disciplina")
            
    except FileNotFoundError:
        print("⚠ Ficheiro de notas não encontrado")

# Executar programa
if __name__ == "__main__":
    print("Bem-vindo ao Sistema de Gestão Escolar")
    menu_principal()
```

---

## IV – AVALIAÇÃO

### 4.1 Critérios de Avaliação

A avaliação do módulo seguirá uma abordagem formativa e sumativa, considerando múltiplas dimensões do desempenho do formando:

**Componentes de Avaliação:**

1. **Avaliação Formativa Contínua (30%)**
   - Participação ativa nas sessões
   - Realização de exercícios práticos
   - Progressão na aprendizagem
   - Resolução de problemas em aula

2. **Trabalhos Práticos (30%)**
   - 3 Trabalhos práticos individuais (10% cada)
   - Aplicação de conceitos aprendidos
   - Qualidade e organização do código
   - Documentação e comentários

3. **Projeto Final (40%)**
   - Desenvolvimento de um programa completo
   - Integração de múltiplos conceitos
   - Funcionalidade e robustez
   - Apresentação e defesa do projeto

### 4.2 Trabalhos Práticos

**Trabalho Prático 1 – Estruturas de Controlo (Sessão 5)**
- Desenvolver um programa de gestão de biblioteca pessoal
- Utilizar estruturas condicionais e de repetição
- Implementar menu interativo
- Validação de entradas do utilizador

**Trabalho Prático 2 – Funções e Estruturas de Dados (Sessão 9)**
- Criar um sistema de gestão de contactos
- Utilizar funções para modularizar o código
- Implementar listas e dicionários
- Operações CRUD (Create, Read, Update, Delete)

**Trabalho Prático 3 – Manipulação de Ficheiros (Sessão 11)**
- Desenvolver um sistema de análise de dados
- Ler dados de ficheiros CSV/TXT
- Processar e calcular estatísticas
- Gerar relatórios em ficheiro

### 4.3 Projeto Final

**Especificações do Projeto:**

O formando deverá desenvolver um programa Python que integre todos os conceitos abordados no módulo:

**Requisitos Obrigatórios:**
- Interface de utilizador por menu
- Mínimo de 5 funções modulares
- Utilização de listas e dicionários
- Persistência de dados em ficheiros
- Estruturas condicionais e de repetição
- Validação de entradas
- Tratamento de exceções
- Documentação completa do código

**Sugestões de Projetos:**
1. Sistema de gestão de inventário
2. Aplicação de gestão financeira pessoal
3. Sistema de reservas (hotel, cinema, restaurante)
4. Jogo educativo (quiz, palavras cruzadas)
5. Analisador de texto/estatísticas
6. Sistema de gestão de tarefas (to-do list avançado)

**Critérios de Avaliação do Projeto:**
- Funcionalidade (40%) - O programa funciona conforme especificado
- Qualidade do código (30%) - Organização, boas práticas, eficiência
- Documentação (15%) - Comentários, docstrings, manual de utilizador
- Criatividade e complexidade (15%) - Funcionalidades adicionais, interface

### 4.4 Grelha de Avaliação

| Componente | Peso | Descrição |
|------------|------|-----------|
| Avaliação Formativa | 30% | Participação, exercícios, progressão |
| Trabalho Prático 1 | 10% | Estruturas de controlo |
| Trabalho Prático 2 | 10% | Funções e estruturas de dados |
| Trabalho Prático 3 | 10% | Manipulação de ficheiros |
| Projeto Final | 40% | Projeto integrador completo |
| **TOTAL** | **100%** | |

**Escala de Classificação:**
- 0-9: Insuficiente
- 10-13: Suficiente
- 14-15: Bom
- 16-17: Muito Bom
- 18-20: Excelente

**Condições de Aprovação:**
- Classificação final mínima de 10 valores
- Frequência mínima de 90% das sessões
- Entrega de todos os trabalhos práticos
- Realização e defesa do projeto final

---

## V – CONCLUSÕES / CONSIDERAÇÕES FINAIS

### 5.1 Síntese do Módulo

Este módulo de formação em programação estruturada com Python foi concebido para dotar os formandos do ensino profissional com competências sólidas e práticas em desenvolvimento de software. Ao longo das 50 horas de formação, os formandos percorreram um caminho progressivo desde os conceitos fundamentais de algoritmos até à implementação de programas complexos e integrados.

A escolha da linguagem Python como veículo de aprendizagem revelou-se adequada pelos seguintes motivos:
- Sintaxe clara e intuitiva, facilitando a compreensão dos conceitos
- Vasta aplicabilidade no mercado de trabalho atual
- Forte presença em áreas emergentes (ciência de dados, IA, automação)
- Excelente linguagem para aprender princípios de programação estruturada

### 5.2 Competências Adquiridas

Ao concluir este módulo com aproveitamento, os formandos estarão aptos a:

1. **Pensamento Algorítmico:**
   - Analisar problemas e decompô-los em passos lógicos
   - Desenhar soluções através de pseudocódigo e fluxogramas
   - Aplicar metodologias estruturadas de resolução de problemas

2. **Programação Estruturada:**
   - Dominar as três estruturas fundamentais: sequência, seleção e repetição
   - Implementar programas utilizando boas práticas de codificação
   - Criar código legível, eficiente e manutenível

3. **Modularização e Reutilização:**
   - Desenvolver funções para organizar e reutilizar código
   - Aplicar princípios de decomposição de problemas
   - Implementar programas modulares e escaláveis

4. **Manipulação de Dados:**
   - Trabalhar com estruturas de dados compostas
   - Processar informação de ficheiros externos
   - Persistir dados entre execuções de programas

5. **Debugging e Qualidade:**
   - Identificar e corrigir erros de forma sistemática
   - Aplicar técnicas de teste e validação
   - Documentar adequadamente o código desenvolvido

### 5.3 Percursos de Aprendizagem Futuros

Este módulo constitui uma base sólida para progressões futuras na área da programação:

**Percursos Técnicos:**
- Programação Orientada a Objetos (OOP)
- Desenvolvimento Web (Flask, Django)
- Ciência de Dados e Machine Learning
- Automação e scripting
- Desenvolvimento de aplicações desktop (Tkinter, PyQt)

**Percursos Profissionais:**
- Programador Python Junior
- Técnico de Automação
- Analista de Dados
- Desenvolvedor Web Backend
- DevOps e Administração de Sistemas

### 5.4 Metodologia Pedagógica Aplicada

A metodologia adotada privilegiou:

- **Aprendizagem Ativa:** Os formandos foram constantemente desafiados a praticar e experimentar
- **Progressão Gradual:** Complexidade crescente dos exercícios e projetos
- **Contextualização:** Problemas próximos da realidade profissional
- **Feedback Contínuo:** Avaliação formativa para ajustar aprendizagens
- **Trabalho Colaborativo:** Promoção da partilha e discussão de soluções

### 5.5 Recomendações para Continuação de Estudos

Para consolidar e expandir os conhecimentos adquiridos, recomenda-se:

1. **Prática Regular:**
   - Resolver desafios de programação diariamente (plataformas online)
   - Desenvolver projetos pessoais
   - Contribuir para projetos open source

2. **Aprofundamento Teórico:**
   - Estudar algoritmos e estruturas de dados
   - Aprender sobre complexidade computacional
   - Explorar padrões de design

3. **Expansão de Conhecimentos:**
   - Aprender bibliotecas Python especializadas (NumPy, Pandas, Matplotlib)
   - Explorar frameworks web
   - Experimentar outras linguagens de programação

4. **Desenvolvimento Profissional:**
   - Participar em comunidades de programadores
   - Assistir a meetups e conferências
   - Criar portfólio de projetos no GitHub

### 5.6 Impacto Esperado

Este módulo visa não apenas transmitir conhecimentos técnicos, mas também:

- Desenvolver o pensamento lógico e capacidade de resolução de problemas
- Fomentar a autonomia na aprendizagem de novas tecnologias
- Preparar para a inserção profissional na área tecnológica
- Estimular a criatividade e inovação através da programação
- Promover o trabalho colaborativo e partilha de conhecimento

### 5.7 Nota Final

A programação é uma competência transformadora no século XXI. Este módulo representa apenas o início de uma jornada de aprendizagem contínua. O domínio da programação estruturada em Python abre portas para inúmeras oportunidades profissionais e permite aos formandos serem criadores ativos de tecnologia, não apenas consumidores.

O sucesso neste módulo depende não apenas da compreensão dos conceitos, mas sobretudo da prática constante e da persistência face aos desafios. A programação é uma competência que se desenvolve com o tempo, e cada linha de código escrita representa um passo na construção de soluções inovadoras para problemas reais.

---

## VI – BIBLIOGRAFIA GERAL

### Manuais e Livros de Referência

**Bibliografia Principal:**

1. **Downey, A.** (2015). *Think Python: How to Think Like a Computer Scientist* (2ª ed.). O'Reilly Media.
   - Excelente introdução aos conceitos de programação com Python
   - Abordagem didática focada no pensamento computacional
   - Disponível gratuitamente online

2. **Matthes, E.** (2019). *Python Crash Course: A Hands-On, Project-Based Introduction to Programming* (2ª ed.). No Starch Press.
   - Abordagem prática com projetos reais
   - Excelente para iniciantes
   - Exercícios progressivos bem estruturados

3. **Sweigart, A.** (2019). *Automate the Boring Stuff with Python* (2ª ed.). No Starch Press.
   - Foco em aplicações práticas do dia-a-dia
   - Exemplos de automação de tarefas
   - Disponível gratuitamente online em: https://automatetheboringstuff.com/

4. **Lutz, M.** (2013). *Learning Python* (5ª ed.). O'Reilly Media.
   - Referência completa da linguagem Python
   - Cobertura aprofundada de todos os conceitos
   - Ideal para consulta

**Bibliografia Complementar:**

5. **Zelle, J.** (2016). *Python Programming: An Introduction to Computer Science* (3ª ed.). Franklin, Beedle & Associates.
   - Excelente para compreender fundamentos de ciência da computação
   - Abordagem académica mas acessível

6. **Guttag, J.** (2021). *Introduction to Computation and Programming Using Python* (3ª ed.). MIT Press.
   - Usado no MIT
   - Abordagem rigorosa mas compreensível
   - Foco em resolução de problemas

### Documentação Oficial e Recursos Online

7. **Python Software Foundation.** *Python Documentation* (v3.x).
   - Documentação oficial: https://docs.python.org/3/
   - Tutorial oficial: https://docs.python.org/3/tutorial/
   - Biblioteca padrão: https://docs.python.org/3/library/

8. **Real Python.** *Real Python Tutorials*.
   - Portal com tutoriais de qualidade: https://realpython.com/
   - Artigos sobre boas práticas
   - Vídeos e exercícios interativos

9. **W3Schools.** *Python Tutorial*.
   - https://www.w3schools.com/python/
   - Referência rápida com exemplos
   - Exercícios interativos online

### Plataformas de Prática e Desafios

10. **HackerRank** - https://www.hackerrank.com/domains/python
    - Desafios de programação por níveis
    - Certificações disponíveis

11. **Codewars** - https://www.codewars.com/
    - Katas (desafios) progressivos
    - Comunidade ativa

12. **LeetCode** - https://leetcode.com/
    - Problemas de programação
    - Preparação para entrevistas técnicas

13. **Python Tutor** - https://pythontutor.com/
    - Visualização da execução de código
    - Excelente para compreender o fluxo de programas

### Guias de Estilo e Boas Práticas

14. **Van Rossum, G., Warsaw, B., & Coghlan, N.** *PEP 8 – Style Guide for Python Code*.
    - https://pep8.org/
    - Guia oficial de estilo Python
    - Convenções e boas práticas

15. **Hitchhiker's Guide to Python** - https://docs.python-guide.org/
    - Guia de boas práticas
    - Recomendações da comunidade

### Recursos em Português

16. **Menezes, N.** (2019). *Introdução à Programação com Python* (3ª ed.). Novatec.
    - Livro em português europeu
    - Didático e acessível
    - Exercícios resolvidos

17. **Ramalho, L.** (2015). *Python Fluente*. Novatec.
    - Nível intermédio/avançado
    - Versão portuguesa de "Fluent Python"
    - Excelente para aprofundamento

18. **Python Brasil** - https://python.org.br/
    - Comunidade Python em português
    - Recursos e eventos

### Canais de Vídeo e Cursos Online

19. **Corey Schafer** - Python Tutorials (YouTube)
    - https://www.youtube.com/c/Coreyms
    - Tutoriais de alta qualidade
    - Tópicos variados

20. **Programming with Mosh** - Python Tutorial (YouTube)
    - Tutorial completo para iniciantes
    - Explicações claras

21. **Coursera / edX**
    - Cursos universitários online
    - Certificações disponíveis

### Referências Normativas

22. **ANQEP** - *Catálogo Nacional de Qualificações*.
    - https://catalogo.anqep.gov.pt/
    - Referenciais de formação
    - UFCDs do ensino profissional

23. **ANQEP** - *Orientações Metodológicas para Formação Modular*.
    - Princípios pedagógicos
    - Estruturação de cursos modulares

---

## ANEXOS

### ANEXO A - Distribuição Temporal das Sessões

| Sessão | Horas | Unidade Temática | Conteúdos |
|--------|-------|------------------|-----------|
| 1 | 4h | UT1 - Parte 1 | Algoritmos, pseudocódigo, instalação Python |
| 2 | 4h | UT1 - Parte 2 | Estrutura de programas, primeiro contacto Python |
| 3 | 4h | UT2 - Parte 1 | Variáveis, tipos de dados, operadores |
| 4 | 4h | UT2 - Parte 2 | Operadores, conversões, exercícios práticos |
| 5 | 4h | UT3 | Estruturas condicionais (if, elif, else) |
| 6 | 4h | UT4 - Parte 1 | Ciclo while, exercícios |
| 7 | 4h | UT4 - Parte 2 | Ciclo for, break, continue |
| 8 | 2h | UT4 - Parte 3 | Ciclos aninhados, exercícios integrados |
| 9 | 4h | UT5 - Parte 1 | Funções, parâmetros, return |
| 10 | 4h | UT5 - Parte 2 | Âmbito de variáveis, funções avançadas |
| 11 | 4h | UT6 - Parte 1 | Listas, tuplos |
| 12 | 4h | UT6 - Parte 2 | Dicionários, conjuntos |
| 13 | 4h | UT7 - Parte 1 | Leitura de ficheiros |
| 14 | 2h | UT7 - Parte 2 | Escrita em ficheiros, projeto integrado |
| 15 | 4h | UT8 | Boas práticas, projeto final |

**Total: 50 horas**

### ANEXO B - Lista de Exercícios Práticos por Unidade

**Disponível como documento separado contendo:**
- 100+ exercícios graduados
- Soluções comentadas
- Desafios adicionais
- Projetos mini-integradores

### ANEXO C - Recursos Digitais de Apoio

**Repositório do Curso:**
- Código-fonte de todos os exemplos
- Exercícios em formato editável
- Datasets para exercícios
- Templates de projetos

### ANEXO D - Glossário de Termos

Glossário completo de termos técnicos utilizados no módulo, em português e inglês, com definições claras e exemplos.

---

**Documento elaborado por:** [Nome do Formador/Organização]  
**Data:** Dezembro de 2025  
**Versão:** 1.0  
**Destinatários:** Formandos do Ensino Profissional

---

*Este documento está sujeito a atualizações conforme a evolução tecnológica e pedagógica. Feedback e sugestões são bem-vindos para melhoria contínua.*
