# Neuco On Boarding - Level 1

Seja bem vindo ao programa de on boarding da Neuco. Este é o primeiro nível do programa, e nós vamos te propor um desafio inicial para que você possa apresentar suas habilidades e conhecimentos.

Neste momento, é extremamente importante que você não se preocupe em como a NEUCO gostaria que você resolvesse o desafio, mas sim que você resolva o desafio da forma que você achar melhor. Nós queremos conhecer você, e a forma como você pensa e resolve problemas.


Desejamos a você um bom começo e que você se divirta resolvendo o desafio.

## Desafio Hotel California

### Sistema de Reservas de Quartos de Hotel:

***Objetivo:*** Desenvolver um sistema que permite aos usuários realizar reservas de quartos de hotel de forma eficiente e segura, proporcionando uma experiência de reserva amigável.

### Requisitos Funcionais:

1. Pesquisa de Quartos:
   1. Os usuários podem pesquisar quartos de hotel com base na data de check-in, data de check-out e número de hóspedes por quarto.

2. Listagem de Quartos:
   1. Exibir uma lista de quartos de hotel disponíveis que correspondem aos critérios de pesquisa. As informações devem incluir preço e disponibilidade.

3. Reserva de Quarto:
   1. Os usuários podem selecionar um quarto e fazer uma reserva para um período.
   2. Não é necessária uma integração de pagamento. A reserva é apenas registrada, mas não cobrada.

4. Notificações de Reserva:
   1. Após a reserva, simule o envio de um e-mail uma confirmação de reserva que inclui 
    detalhes da reserva, como datas e custo total.
   2. O sistema deve possuir integração com a API de previsão do tempo [OpenWeather](https://openweathermap.org/api) para que seja possível enviar no email de confirmação da reserva a previsão do tempo para o período da reserva e sugestões para o que fazer durante esse clima.
   3. Caso a reserva não seja efetuada com sucesso, o sistema simule o envio de um e-mail informando o usuário sobre o problema.
   4. **Atenção**: Implemente uma funcionalidade que armazene as os emails simulados em algum lugar, associando-as às reservas correspondentes.


## Entrega
Para o desafio em questão, será preciso construir uma solução desde a concepção arquitetural do projeto até a entrega de uma release possibilite a utilização da solução em produção. 
 


## GO TO: [Level 2](https://github.com/ProjetosNeuco/neucoon-level2-backend)