# Desafio_CodeGirl_StepFunctions
 Anotações e insights adquiridos durante a prática.

 AWS Step Functions — Anotações do Desafio Code Girl
 
## O que é Step Functions?

O AWS Step Functions é um serviço da AWS que funciona como um orquestrador de processos na nuvem. É usado para criar fluxos de trabalho que conectam e controlam vários serviços da AWS de forma visual e organizada. Ele define qual etapa vem primeiro, como tratar erros e quando avançar para a próxima etapa.


## Quando deve ser utilizado?

O Step Functions é utilizado quando precisamos executar várias etapas em sequência, principalmente em aplicações serverless.
Exemplos de uso:

•	coordenar chamadas entre vários serviços AWS

•	dividir uma lógica complexa em etapas menores

•	criar workflows que ficam fáceis de visualizar e entender

•	controlar a sequência de tarefas de forma automática


## Benefícios que eu percebi

•	Visual: dá pra ver o fluxo inteiro, parece um mapa de processo

•	Menos código: a lógica fica declarativa no próprio Step Functions

•	Funciona super bem com arquiteturas serverless

•	Automatiza tentativas e tratamento de erros

•	Ajuda a manter o código mais organizado



## Como funciona?

O fluxo é definido usando Amazon States Language (ASL), que é um arquivo JSON que descreve cada estado (step) do processo.
Cada “step” é chamado de State, e pode ser:

•	uma tarefa (Task)

•	uma condição (Choice)

•	espera (Wait)

•	execução em paralelo (Parallel)
etc.


## Insights principais que aprendi

•	Step Functions deixa mais claro o “fluxo da lógica” do que tentar fazer tudo dentro de uma Lambda só.

•	E por ser visual, fica muito mais fácil entender a ordem do processo e onde cada parte entra.

Usar Step Functions é uma forma organizada de controlar processos complexos na AWS, principalmente quando temos várias etapas que dependem uma da outra.


##Dicionário: 

Step Functions:	Orquestrador de tarefas

ASL:	Linguagem JSON para definir o fluxo

Workflows:	A sequência que descreve o processo

States:	Cada etapa do processo (task, choice, wait, etc)




