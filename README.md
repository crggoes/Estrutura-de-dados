# Estrutura-de-dados
Exercício Lógica Imperativa curso Proz talento cloud


// Elabore um algoritmo que possa descobrir, através de perguntas e respostas, em qual área 
de um restaurante uma pessoa ou grupo de pessoas precisa ser alocada.
O restaurante tem três áreas: 
térreo, 1º andar e área externa.
Clientes fumantes ou com animais de segurança precisam ser alocados em área externa.
Grupos de 5 ou mais precisam ser alocados no 1º andar , pois não dá para juntar mesas no térreo.
Qualquer outro grupo de pessoas pode ser alocado no térreo.


Vamos elaborar um algoritmo em pseudocódigo para resolver esse problema:

1. Início do algoritmo
2. Perguntar se há algum cliente fumante (resposta: sim ou não)
3. Se a resposta for "sim", alocar o cliente na área externa e encerrar o algoritmo
4. Se a resposta for "não", pergunte se há algum cliente com animal de segurança (resposta: sim ou não)
5. Se a resposta for "sim", alocar o cliente na área externa e encerrar o algoritmo
6. Se a resposta for "não", pergunte quantas pessoas estão no grupo (resposta: número inteiro)
7. Se o número de pessoas no grupo for igual ou maior que 5, alocar o grupo no 1º andar e encerrar o algoritmo
8. Se o número de pessoas no grupo for menor que 5, alocar o grupo no térreo e encerrar o algoritmo
9. Fim do algoritmo

//Esse algoritmo faz perguntas sucessivas para verificar as necessidades dos clientes e alocá-los na área correta de acordo com as regras inválidas.
