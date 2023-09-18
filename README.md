# Curso: JavaScript e HTML: Desenvolva um Jogo e Pratique Lógica de Programação

Este repositório contém a documentação do curso "JavaScript e HTML: Desenvolva um Jogo e Pratique Lógica de Programação", onde são abordados os seguintes tópicos:

1. **Dê Seus Primeiros Passos de Maneira Prática!**
   - Introdução ao mundo da programação utilizando JavaScript diretamente no seu navegador.

2. **Inicie na Programação com JavaScript no seu Navegador**
   - Exploração e prática com os fundamentos essenciais do JavaScript para desenvolver um jogo.

3. **Entenda Variáveis e seu Uso**
   - Aprofundamento no conceito de variáveis e como utilizá-las de forma eficaz no desenvolvimento do jogo.

4. **Repita Tarefas com Laços, Loops, Fors e Whiles**
   - Aprendizado sobre a aplicação de laços (loops), 'for' e 'while' para repetição de tarefas e otimização de código no jogo.
  
## Estrutura do Repositório

Geral:
- Função pulaLinha(): Esta função simplesmente escreve duas quebras de linha na página.
- Função mostra(frase): Essa função escreve a frase fornecida como argumento na página e chama a função pulaLinha() para adicionar duas quebras de linha após a frase.

[01 - IMC](/imc.html): Esse código basicamente pede ao usuário seu nome, peso e altura, calcula o IMC e fornece diferentes mensagens com base no resultado do cálculo do IMC.
Aqui estão várias estruturas condicionais (if) que comparam o IMC calculado para fornecer diferentes mensagens ao usuário, dependendo do valor do IMC.

[02 - Futebol](/futebol.html): Este código se concentra em calcular e analisar o desempenho de um time esportivo com base no número de vitórias e empates, e fornece feedback com base nesses cálculos.
Usamos novamente estruturas condicionais (if) e estruturas de comparação. 

[03 - Media das Idades](/media_idades_familiares.html): O código pede ao usuário a quantidade de familiares, solicita a idade de cada um deles, calcula a média das idades e exibe essa média.
Usamos laço while para obeter as idades. O número de familiares é controlado pela variável numero, que é incrementada a cada iteração e realizamos o calculo da média
Calculo da Média

[04 - Advinhação 01](/adivinhacao.html): jogo de adivinhação onde o usuário tem até três tentativas para adivinhar um número aleatório gerado. Se acertar, é exibida uma mensagem de sucesso; caso contrário, uma mensagem de erro é exibida. O jogo termina após três tentativas ou se o usuário acertar o número.
- O código gera um número aleatório entre 0 e 10 (inclusive) usando a função Math.random() e arredonda esse número para o inteiro mais próximo usando Math.round(). Esse número aleatório é armazenado na variável numeroPensado.
- Loop while para Realizar Tentativas
- Contador de Tentativas: O número de tentativas é controlado pela variável tentativas, que começa com valor zero e é incrementada a cada tentativa.

[05 - Advinhação 02](/adivinhacao2.html): jogo em que o usuário pode inserir um número na caixa de entrada e clicar em um botão para comparar esse número com uma lista de números aleatórios. Se o número estiver na lista, uma mensagem de acerto é exibida; caso contrário, uma mensagem de erro é exibida. O objetivo é adivinhar um dos números aleatórios gerados.
- usamos a tag <strong>input</strong> para uma caixa de entrada, onde o usuário pode digitar um número e a tag <strong>button</strong> para criar um botão que o usuário pode clicar para comparar o número digitado na caixa de entrada com um segredo.
- Definimos que, quando o botão é clicado, a função verifica() é chamada. Essa função verifica se o número digitado pelo usuário na caixa de entrada coincide com algum número na lista de segredos. Exibe uma mensagem de acerto ou erro com base na verificação.

![Certificado](certificado.png)
