# montyhall
Algoritmo baseado no paradoxo de Monty Hall, feito na linguagem Fortran.

O paradoxo de Monty Hall surgiu a partir de um programa de televisão onde há três portas e atrás de cada uma dela há um carro. O participante então escolhe uma porta e o apresentador do programa abre uma porta vazia e então o apresentador pergunta: “Você quer trocar sua escolha?”. Nosso objetivo é saber se é vantajoso trocar de porta ou não, ou seja, o participante tem mais probabilidade de ganhar o jogo se trocar de porta? 
No algoritmo feito, consideramos que o participante sempre troca de porta e assim, vemos qual a porcentagem de vezes em que trocando de porta ele ganha o carro. Geramos aleatoriamente a porta em que o carro está e depois a porta que o participante escolhe. Assim, se ele escolher a porta em que o carro está na primeira vez, ao trocar ele perde e se ele escolher uma porta vazia (que não contém o carro) ele ganha. 
Pode-se surgir a dúvida “Mas e se ele não trocar?”, que podemos responder com a quantidade de vezes em que a porta que ele escolheu é a porta do carro. Se ele não trocar, todas as vezes em que ele escolher a porta do carro ele ganha.
