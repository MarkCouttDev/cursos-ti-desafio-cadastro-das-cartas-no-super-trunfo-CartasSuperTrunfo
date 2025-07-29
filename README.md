🌆 Super Trunfo de Cidades - Projeto em C
Projeto desenvolvido por Marcos Augusto do Couto como parte do desafio nível novato, nível aventureiro, e nível avançado da plataforma SAVA.

🎯 Objetivo
Desenvolver um programa em linguagem C que permita cadastrar cartas representando cidades brasileiras e realizar batalhas comparativas entre elas no estilo Super Trunfo. O projeto envolve o cálculo de Densidade Populacional, PIB per Capita, e agora também o poderoso índice de Super Poder para determinar a carta vencedora por atributo.

🃏 Informações por Carta
Cada carta representa uma cidade brasileira e contém os seguintes atributos:
- Estado (char) — letra de A a H
- Código da carta (char[4]) — ex: A01
- Nome da cidade (char[50])
- População (unsigned long int)
- Área (float) — em km²
- PIB (float) — em bilhões de reais
- Número de pontos turísticos (int)
- Densidade Populacional (float) — habitantes por km²
- PIB per Capita (float) — em reais
- Super Poder (float) — soma ponderada dos atributos numéricos, incluindo o inverso da densidade

⚙️ Funcionalidades
- Cadastro completo das duas cartas
- Cálculo automático dos indicadores:
- Densidade Populacional
- PIB per Capita
- Super Poder
- Comparação entre as cartas:
- Para a densidade populacional, vence o menor valor
- Para os demais atributos, vence o maior valor
- Exibição clara dos resultados de cada atributo:
- Indicando se Carta 1 venceu (1) ou Carta 2 venceu (0)

🧪 Tecnologias Usadas
- Linguagem: C
- Compilador: Dev-C++
- Estilo: sem estruturas de repetição ou decisão
- Ambiente compatível: Windows / Linux / macOS

🚀 Como Compilar e Executar
Linux/macOS com GCC:
gcc super_trunfo.c -o super_trunfo
./super_trunfo


Windows com Dev-C++:
- Abra o projeto
- Compile com F9
- Execute com Ctrl + F10
