🎮 Jogo Maior, Menor ou Igual em C

Este projeto é uma implementação de um jogo interativo em C, onde o jogador compete contra o computador escolhendo um número e o tipo de comparação desejada: Maior, Menor ou Igual. O computador gera um número aleatório entre 1 e 100, e o resultado da partida depende da comparação escolhida pelo jogador.

⚙️ Como funciona o jogo

O jogador escolhe o tipo de comparação:

M → Maior

N → Menor

I → Igual

Em seguida, o jogador digita um número entre 1 e 100.

O computador gera automaticamente outro número aleatório.

O programa compara os dois números:

Se a condição escolhida pelo jogador for verdadeira → Vitória do jogador 🎉

Caso contrário → Vitória do computador 💻

Se os números forem iguais e a opção escolhida for "Igual" → Empate 🤝

🧑‍💻 Conceitos aplicados

Operadores ternários (? :) para simplificar decisões.

Estruturas condicionais (if, if-else, switch) para organizar a lógica do jogo.

Geração de números aleatórios usando rand() e srand().

🚀 Objetivo do projeto

Consolidar o uso de diferentes estruturas de decisão em C e demonstrar como integrá-las para criar programas mais complexos, dinâmicos e interativos.

▶️ Como executar

Compile o código com o GCC:

gcc maior_menor_igual.c -o jogo


Execute o programa:

./jogo

🕹️ Exemplo de gameplay
Bem-vindo ao jogo Maior, Menor ou Igual
Você deve escolher um número e o tipo de comparação
M. Maior
N. Menor
I. Igual

Escolha a comparação:
M
Digite seu número (entre 1 e 100): 50
Você escolheu a opção maior!
O número do computador é: 37 e o do jogador é: 50
Parabéns você venceu!
