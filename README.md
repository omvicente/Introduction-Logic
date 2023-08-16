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
