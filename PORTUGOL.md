algoritmo

"nome_programa"

Inicio - Inicia
Escreva - exibe a mensagem na tela
fim - determina o inicio e fim do nome_programa
inteiro - Ex. 10, 5, -3 (Int)
Reais - Ex. 3.12, 5.12 (Float)
Caracteres - "João, "Al" (String)
Logicos - Valores Booleanos (true, false)
var

algoritmo "OPERAÇÕES"
var
    num1, num2, soma: inteiro
inicio
    Escreva("Digite o primeiro numero: ")
    leia(num1)
    escreva("Digite o segundo numero: ")
    leia(num2)
    soma <- num1 + num2
    escreva ("A soma é: ", soma)
fim



algoritmo "OPERAÇÕES"
var
    idade: inteiro
inicio
    escreva("Digite sua idade: ")
    leia(idade)
    se idade >= 18 entao
        escreva("Você é maior de idade.")
    senao
        escreva("Você é menor de idade.")
    fimse
fim


algoritmo "Contagem"
var
    i: inteiro
inicio
    i <-1
    enquanto i <=10 faca
        escreva (i, "  ")
    fimenquanto
fim