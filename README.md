✨ Desafio: Troco Mínimo (Cash)em Python

Este repositório contém a solução para o desafio de programação que calcula o número mínimo de moedas necessárias para fornecer um troco. 💰

💡 Sobre o Desafio

O objetivo é implementar um programa em Python que solicite ao usuário um valor em dinheiro e retorne o menor número de moedas possível para compor esse valor, considerando as moedas disponíveis: 25¢, 10¢, 5¢ e 1¢.

🔍 Exemplo de Entrada e Saída:

Se o usuário inserir 0.41, o programa deve imprimir:

📚 Especificação

O programa deve solicitar um valor decimal positivo ao usuário.

Caso o usuário insira um valor negativo ou inválido, ele deve ser solicitado novamente.

Utilizar a função get_float() da biblioteca CS50 para capturar a entrada do usuário.

Utilizar apenas as seguintes moedas para calcular o troco: 25¢, 10¢, 5¢ e 1¢.

Exibir na saída apenas um número inteiro, indicando o número mínimo de moedas necessárias.

🚀 Como Executar

Clone este repositório:

Acesse o diretório do projeto:

Execute o script:

Insira o valor do troco quando solicitado.

🛠 Testes

Para verificar o funcionamento do programa, realize os seguintes testes:

Entrada

Saída Esperada

0.41

4

0.01

1

0.15

2

1.60

7

23

92

4.2

18

-1

Solicita nova entrada

foo

Solicita nova entrada

''

Solicita nova entrada

Você também pode validar a exatidão e o estilo do seu código utilizando os comandos:

💪 Contribuição

Sinta-se à vontade para contribuir com melhorias!

Faça um fork do repositório.

Crie um branch para sua feature (git checkout -b minha-feature).

Faça um commit (git commit -m 'Adiciona minha feature').

Envie um pull request.

🌟 

Desafio inspirado no curso CS50 de Harvard.
