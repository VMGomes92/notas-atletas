Cálculo de Média de Notas de Atletas (JavaScript Puro)
Um pequeno script em JavaScript para processar uma lista de atletas e calcular a "média válida" de suas notas, descartando a nota mais alta e a nota mais baixa.

Funcionalidades
O script realiza as seguintes tarefas:

Processamento de Dados: Itera sobre um Array de Objetos (cada um representando um atleta e suas notas).

Ordenação: Utiliza o método .sort() para colocar as notas em ordem crescente.

Descarte de Extremos: Utiliza o método .slice() para remover as notas mais alta e mais baixa do conjunto.

Cálculo da Soma: Utiliza o método .reduce() para somar as notas válidas.

Cálculo da Média: Divide a soma das notas pelo número de notas restantes.

Saída Formatada: Exibe o nome do atleta, suas notas originais e a média válida formatada no console.


Como Executar o Projeto
Este projeto é um script JavaScript simples e pode ser executado em qualquer ambiente que suporte Node.js ou diretamente no console do seu navegador (como o Chrome DevTools).

Pré-requisitos
Você precisa ter o Node.js instalado em sua máquina.
