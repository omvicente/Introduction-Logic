## 🔹 Algorítimos 🔹

Algorítimos são sequencias de instruções bem definidas normalmente utilizadas para resolver problemas específicos ou executar tarefas.

> [!IMPORTANT]
> Utilizaremos o pseudocódigo Portugol para exemplificar os próximos exemplos.

```
Algoritmo AtravessarRua
    Olhar para Direita
    Olhar para Esquerda
        Se estiver vindo carro
            Não atravesse
        senao
            Atravesse
        FimSe
FimAlgoritmo
```
Isso, por mais simples que possa parecer, é um algoritmo e utilizamos ele sempre no dia a dia.

## Como os algoritmos são criados 👾

Para começarmos com a construção de um algoritmo, precisamos primeiramente definir qual é o problema que será solucionado. Depois, precisamos analisar e elaborar a sequência de passos para solucionar esse problema e por fim, colocar esses passos em uma linguagem de programação adequada.

- 🧠 Lógica Humana 
- 👾 Linguagem de Programação 
- ✅ Aplicativo/Resolução de problemas.  

## Variáveis 📚

Uma variável é um **espaço na memória** do computador destinado a um dado que é alterado durante a execução do algoritmo.

## Exemplos de problemas relacionados a lógica de programação com a utilização do pseudocódigo Portugol para a resolução.

### **Problema 01** 📚

Determinada pessoa **precisa saber sua idade** com base no ano atual.

- **Utilizaremos como nome fictício, _Maria_.**

```
Algoritmo "MariaIdade"
   var
        AnoNascimento, AnoAtual, Resultado: inteiro
   inicio
        Escreva ("Em que ano estamos?")
        Leia (AnoAtual)
        Escreva ("Em que ano eu nasci?")
        Leia (AnoNascimento)
        Resultado <- AnoAtual - AnoNascimento
        Escreva ("Em ", AnoAtual," você terá ",Resultado, " anos")
FimAlgoritmo
```

### **Problema 02** 📚

Maria vai viajar e precisa saber quanto vale seu dinheiro lá nos EUA.  

- **Iremos perguntar a quantidade de reais que a pessoa tem e qual a cotação atual do dólar.**

```
Algoritmo "MariaDolar"
   var
        realPossui, valorDolar, R: real
   inicio
        Escreva ("Quantos reais você tem? R$")
        Leia (realPossui)
        Escreva ("Qual a cotação atual do dolar?")
        Leia (valorDolar)
        R <- realPossui / valorDolar
        Escreva ("Você pode trocar seus R$",realPossui," em ",R:4:2," dolares")
FimAlgoritmo
```

### **Problema 03** 📚

Maria já viajou e agora **precisa saber quanto de imposto vai pagar em cada item** comprado lá nos EUA.  

- **Iremos perguntar quanto custou o produto e utilizar a taxação base de 60%.**

```
Algoritmo "Imposto"
   var
       imposto, valorProduto, valorProdutoImposto: real
   inicio
        Escreva ("Quantos reais você pagou no produto? R$")
        Leia (valorProduto)
        imposto <- (valorProduto * 0.60)
        valorProdutoImposto <- valorProduto + imposto
        Escreva ("Você vai pagar no produto com imposto R$", valorProdutoImposto:5:2)
FimAlgoritmo
```
### **Problema 04** 📚

Maria já viajou e agora **precisa de um empréstimo**.  

- **Iremos perguntar quanto ela precisa e qual a taxa do banco**

```
algoritmo "EmprestimoMari"
var
   valorEmp, valorParc, parcEmp, jurEmp, jurBanc, valorPag: real
inicio
   Escreva("Qual é o valor que você precisa?")
   Leia(valorEmp)
   Escreva("Qual é o valor da taxa bancaria em %?")
   Leia(jurBanc)
   Escreva("Qual é a quantidade de parcelas que quer fazer?")
   Leia(parcEmp)
   jurEmp <- valorEmp * (jurBanc/100)
   valorPag <- jurEmp + valorEmp
   valorParc <- valorPag / parcEmp
   EscrevaL("Voce vai pagar", parcEmp, "x de R$", valorParc:5:2)
   EscrevaL("O valor do juros total é R$", jurEmp:5:2)
fimalgoritmo
```

## **Estruturas condicionais - Exercício** 🔥

### **Problema 01** 📚

A ideia é descobrir a idade da pessoa e mostrar se já pode tirar carteira de habilitação.  

- **Iremos perguntar o ano atual e o ano de nascimento da pessoa**

```
algoritmo "Habilitacao"
var
   ano, nasc, idade: inteiro
inicio
   Escreva("Em que ano nós estamos?")
   Leia(ano)
   Escreva("Em que ano você nasceu?")
   Leia(nasc)
   idade <- ano - nasc
   EscrevaL("Em ", ano, " voce tera ", idade, " anos.")
   Se (idade >= 21) entao
      EscrevaL("Você já pode tirar sua habilitação.")
      Senao
         EscrevaL("Você ainda não pode tirar sua habilitação.")
   FimSe
fimalgoritmo
```
