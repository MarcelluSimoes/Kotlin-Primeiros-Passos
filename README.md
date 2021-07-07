# Kotlin-Primeiros-Passos
Comandos básicos na Linguagem Kotlin com o embasamento do BootCamp Mobile oferecido pela DIO (Digital Innovation One) em parceria com o Santander
const val MIN_AGE = 16

/**fun main() {
    println(Float.MAX_VALUE)
    println(Double.MAX_VALUE)
    println(Byte.MAX_VALUE)
*/


/** Conversao de dados 
 * variavel.toByte() ou .toShort() ou toInt()...
 * 
 * 
 * Declaçao de variavel 
 * Var( valor mutavel, KamelCase):
 * Variável que pode ter ser seu valor alterado durante o código
 * 
 * Val- Funciona como uma constante(valor imutavel)
 * uma vez declarada não pode ser alterado os valores
 * Similar ao final em Java 
 * KamelCase
 * 
 * Const Val - valor setado durante a compilaçao 
 * constante cujo o valor é atribuido durante a compilacao
 * Valor usado para consulta
 * Manipuçao feita indireta
 * SNAKE_KASE = FATOR_MULT
 * Se declarado dentro da Main = Val 
 * declarado fora da Main = Const val 
 
var currentAge = 22
println(currentAge)

val idadeAtual = 4
    println(idadeAtual)

val idadePassada: Int
idadePassada = 21
    println(idadePassada)*/

    /** Nullability
     * Necessita de uma validação por parte do programandor
     * onde ele deve dizer no código que aquela variável tem um tipo (Int, Float...)
     * definido, porem aceita o tipo null
     * Temos isso definido com NullSafety
    
val testeNulo: Int?
testeNulo = null
    println(testeNulo)
    
currentAge = 23
    println(currentAge)

println(MIN_AGE)
}

/** Aritmético básico
 * soma de variáveis 
 * Seja var a = 10, seja var b = 2
 * 
 * a+b == 12
 * 
 * Subtração
 * a-b == 8
 * 
 * multiplicação 
 * a*b == 20
 * 
 * divisao
 * a/b == 5
 * 
 * Resto da divisao
 * a%b == 0
 * 
 * O que temos de diferente são declaraçoes de comandos que
 * realizam essas operações:
 * 
 * a.plus(b) == 12
 * a.minus(b) == 8
 * a.times(b) == 20
 * a.div(b) == 5
 * a.mod(b) == 0
 */
 */
 fun main(){
     var a = 12
     var b = 2
     var soma = a+b
     println(soma)
     println(a.plus(b))
     println(a)
     a+=b
     println(a)
 }
