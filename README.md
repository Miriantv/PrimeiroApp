fun main(){
    val p: Pessoa = Pessoa ("Mirian", 36)
    val p2: Pessoa = Pessoa ("Nathalia", 33)
    // (atributos)Construtor

    println(p)
    println(p2)

}
data class Pessoa(
// data class é uma classe apenas para armazenar dados

    val nome: String,
    val idade: Int,
)

/* PRECISO CADASTRAR 2 PESSOAS
/** NOME, IDADE
val nome: String = "Mirian"
val idade: Int = 36

val nome2: String = "Nathalia"
val idade2: Int = 33

printiln(nome)
println(nome2)

println(idade)
println(idade2)

SERIA MAIS INTERESSANTE CRIAN UM OBJETO, ASSIM O CÓDIGO FICARIA MAIS LEVE
*/
