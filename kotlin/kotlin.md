
# Tutorial de Kotlin

Tudo é executado dentro da função principal.

Sintaxe: 
fun main() {
	println("Hello World!")
}

## Hello World e Tipos de Dados

**Tipos de dados**

- Int
- Long
- Float
- Double
- Array
- Boolean
- Char
- Byte
- Short
- Null

**MAX_VALUE**

Constante que permite identificar o valor máximo dos tipos em Kotlin

Como acessar:

- Int.MAX_VALUE
- Float.MAX_VALUE
- Long.MAX_VALUE
- Byte.MAX_VALUE
- Short.MAX_VALUE

**Conversão de dados**

- variavel.toByte()
- variavel.toSHort()
- variavel.toInt()
- variavel.toLong()
- variavel.toFloat()
- variavel.toDouble()
- variavel.toChar()

O Kotlin permite a conversão implícita!!!

## Declarando variáveis

### Sintaxe

- var (mutável, camelCase)
- val (imutável, camelCase, similar ao final do java, utilizar em funções)
- const val (imutável, SNAKE_CASE, para constantes, utilizar se for global)

### Utilização

- var
	- Usando inferência de tipo
		- var idadeMinima = 22
	- Usando declaração de tipo
		- var idadeMinima:Int  
		idateMinima = 22
- val
	- Usando inferência de tipo
		- val idadeMinima = 22
	- Usando declaração de tipo
		- val idadeMinima:Int  
		idateMinima = 22
- const val
	- const val IDADE_MINIMA = 16

**Observação 1:** Uma variável não pode ser declarada sem tipo e sem atribuição  
**Observação 2:** Uma variável com inferência de tipo só receberá valroes do mesmo tipo da primeira atribuição

### Nulabilidade

Qualquer tipo pode ser nulo, porém deve ser explicitado usando "?". Inferência de tipo não atribui nullability

- var month:Int? = null

## Operadores aritméticos

Expressões: 
- soma: +
- subtração: -
- multiplicação: *
- divisão: /
- resto: %

Comandos
- variavel.plus(outraVariavel)
- variavel.minus(outraVariavel)
- variavel.times(outraVariavel)
- variavel.div(outraVariavel)
- variavel.mod(outraVariavel)

Atribuição - permite que a variável a receba o resultado da operação aritimética
- a += b
- a -= b
- a *= b
- a /= b
- a %= b

## Operadores comparativos

## Operadores lógicos e Operadores In e Range

## Strings

## Diferenças entre Empty e Blank

## Funções