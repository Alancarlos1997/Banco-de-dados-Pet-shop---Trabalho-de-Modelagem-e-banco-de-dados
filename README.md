# Modelagem de Banco de Dados para Mercadão Pet

## Introdução

O presente projeto tem como objetivo realizar a modelagem conceitual de um banco de dados para o Mercadão Pet, organização que atua na venda de produtos para animais, serviços de banho e tosa e atendimento relacionado à clínica veterinária.

A partir de uma pesquisa de campo realizada na organização, foram levantadas informações sobre seus principais processos, incluindo cadastro de clientes e pets, agendamentos, atendimentos, vendas, cadastro de produtos e controle de estoque.

Durante o levantamento, foi identificado como principal problema operacional a utilização de dois sistemas separados para o gerenciamento das vendas e do estoque. Como esses sistemas não são integrados, as informações relacionadas às vendas e à movimentação dos produtos não são atualizadas de forma conjunta, dificultando o acompanhamento da quantidade de itens disponíveis e tornando o controle de estoque menos eficiente.

Dessa forma, o projeto busca propor uma estrutura conceitual de banco de dados capaz de organizar e integrar as principais informações utilizadas pelo estabelecimento. A modelagem será delimitada aos processos relacionados a clientes, pets, funcionários, serviços, atendimentos, produtos, vendas e controle de estoque.

## Desenvolvimento

### Caracterização da Organização

**Nome e natureza da organização:**  
O grupo escolheu o Mercadão Pet, um estabelecimento do setor pet que atua com a venda de produtos para animais, serviços de banho e tosa e atendimento relacionado à clínica veterinária.

**Contexto e porte:**  
A organização possui diferentes áreas de atuação, envolvendo a comercialização de produtos e a prestação de serviços para animais. Entre as atividades realizadas, destaca-se o serviço de banho e tosa, que apresenta um volume aproximado de 400 atendimentos por semana. A organização conta com 20 funcionários envolvidos em suas atividades.

**Problemas e necessidades identificados:**  
Durante a pesquisa de campo, foi identificado que a organização utiliza dois sistemas separados para gerenciar as vendas e o estoque. Como esses sistemas não são integrados, as informações relacionadas às vendas e à movimentação do estoque não são atualizadas de forma conjunta.

Essa falta de integração pode dificultar o acompanhamento da quantidade de produtos disponíveis, exigindo maior controle por parte dos funcionários e tornando o gerenciamento do estoque menos eficiente.

Também foi observado que o cadastro de produtos é realizado manualmente, sendo registradas informações como preço de custo, NCM e código de barras. Diante disso, uma das principais necessidades identificadas é a integração entre as informações de vendas e estoque, permitindo um controle mais organizado e eficiente dos produtos e de suas movimentações.

**Justificativa da escolha:**  
O Mercadão Pet foi escolhido por apresentar uma variedade de processos de negócio e um volume significativo de informações relacionadas a clientes, pets, funcionários, serviços, atendimentos, produtos, vendas e estoque.

A diversidade de atividades realizadas pela organização torna o estabelecimento um caso adequado para o desenvolvimento de uma modelagem conceitual abrangente, permitindo representar diferentes processos e seus relacionamentos em uma estrutura integrada de banco de dados.

**Evidências da organização:**  

A existência da organização e o acesso para a realização da pesquisa de campo podem ser comprovados por meio das informações abaixo:

- **Endereço:** [Google Maps](https://maps.app.goo.gl/yea361WY7wQY4v9aA)
- **Telefone:** (11) 93015-6713
- **Responsável entrevistado:** Guilherme (Gerente)
- **Imagens:** 
