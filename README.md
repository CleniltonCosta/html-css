# Linguagem markdown

## Alguns comandos utlizados em markdown
Ao ultilizar o sinal de astericos ou sinal de menos duas vezes o nosso texto ficará em negrito:
* **Negrito**
  
Usando o sinal de asterisco apenas uma vez e em seguida fechando, o nosso texto ficará em italico:
* *Italico*

## Listas ordenadas
Podemos criar listas tbm, tanto ordenandas quanto não ordenadas usando um numero e em seguida um pontinho:


1. Filmes de terror
   1. Sexta feira 13
   1. Chuck
   1. Annabelle
1. Filmes de comédia
   1. Ultima ressaca do ano
   2. As branquelas
   3. Todo mundo em pânico

Note que criei subitens nas listas, clicando no backspace 3 vezes consigo crias quantas eu quiser.

## Listas nao ordenadas
Pra criar listas nao ordenadas é muito simples. Apenas ultilizando o sinal de asteriscos.
* Filmes de ação
   * Deadpool
   * mercenarios
* Filmes de romance
   * A proposta
   * Como se fosse a primeira vez
Seguindo a mesma lógica acima quando criamos subitens, utilizamos a tecla de backspace 3 vezes pra chegar no resultado.

## Lista de tarefas com checkbox

Nesse topico iremos aprender a usar uma lista que pode ser de tarefas, compras, objetivos ou oque quiser. Aqui usarei como exemplo uma lista de tarefas, usando o sinal de menos e colchetes separados de um espaço.

* Lista de compras do mês
- [x] Leite
- [ ] Sal
- [ ] Arroz

Um detalhe que acabei esquecendo de comentar, é que devemos usar o espaço entre os colchetes para funcionar. E quando eu quiser marcar ela como concluida, marco com um X entre os colchetes

## Usando imagens e links
Para fazer um upload de uma img para o readme é bem simples! Arrastamos a imagem para um espacinho bem abaixo do editor como vou fazer agora.

![saint-nicktocat](https://github.com/user-attachments/assets/ac8347e0-a50a-4ed2-b064-4d2e1dbf958b)

A imagem que coloquei é um pouco grande, o recomendavel seria uma com resolução de 500x500
Mas voltando ao assunto, agora irei usar os comandos de links que seria colchetes onde ficacará o texto que vai "hospedar" o link e em seguida os parenteses que ficará o link

[Link original referente a imagem acima](https://octodex.github.com/saint-nicktocat/)

## Tabelas

As tabelas não são tão dificeis quanto imagineis, mas sempre bom se atentar na sequencia de comandos. Irei fazer um exemplo

* Boletim do Mario

  Materia|Faltas|Nota
  ---|---|---
  Historia|3|8,9
  Matematica|1|6,0
  Geografia|2|10,0

## Comandos de codigo

Aqui podemos digitar uma linha de codigo e preformatar ele pra que visualmente os leitores entendam que aquele texto é um codigo. O comando que vou usar é a crase

`console.log('Hello, world')`

A outra forma quando quisermos usar trechos de programa usamos 3 crases
```
function helloWorld() {
  return "Hello, World!";
}
```
