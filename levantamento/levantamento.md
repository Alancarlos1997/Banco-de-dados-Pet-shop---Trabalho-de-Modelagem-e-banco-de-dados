# Levantamento

## 1. O que Perguntamos

Em nossa visita presencial à organização, entrevistamos o responsável pela gestão para compreender a rotina do estabelecimento. Durante a conversa, perguntamos sobre os serviços oferecidos e confirmamos que a empresa atua em três frentes principais: venda de produtos, serviços de banho e tosa e atendimento em clínica veterinária vinculada.

Em relação ao volume de operações, confirmamos a realização de aproximadamente **400 atendimentos de banho e tosa por semana**, o que exige um fluxo constante de agendamentos. Perguntamos como esses agendamentos são realizados e confirmamos que eles cobrem os serviços de estética animal, registrando o horário, os dados do pet, o endereço (quando há necessidade de transporte) e a identificação do funcionário responsável pelo atendimento.

Sobre o cadastro de clientes e animais, confirmamos que a empresa cadastra os tutores coletando nome e CPF, e registra os pets com nome, idade, peso e pelagem. Perguntamos sobre o histórico de atendimento e confirmamos que o estabelecimento mantém o registro dos serviços prestados a cada animal.

Quanto à gestão de produtos e vendas, confirmamos que o faturamento ocorre no caixa e que a empresa utiliza o Sistema Moura para o controle de estoque. Para o cadastro de produtos, perguntamos quais dados são armazenados e confirmamos o registro de preço de custo, NCM e código de barras, sendo que a entrada de mercadorias é feita de forma manual. Também questionamos sobre a venda de rações e itens a granel, confirmando que esses produtos também são comercializados e registrados.

Por fim, perguntamos sobre outras atividades e dificuldades operacionais. Confirmamos que a empresa não realiza feiras de adoção nem mantém lar temporário, apenas arrecada doações para uma ONG parceira. Também identificamos que não possui um cadastro estruturado de fornecedores no sistema.

---

## 2. O que Observamos Presencialmente na Visita Técnica

Durante o tempo em que estivemos no local acompanhando a rotina de trabalho, contrapusemos o relato do entrevistado com a prática diária:

- **Gestão de Fornecedores:** Observamos que o contato com fornecedores e o recebimento de mercadorias acontecem de forma informal, por meio de anotações manuais e mensagens, sem uma rotina de lançamento e rastreio de compras dentro do sistema atual.
- **Falta de Integração entre Sistemas:** Identificamos que o sistema utilizado pelo pet shop não está integrado ao sistema da clínica veterinária. Dessa forma, as informações dos clientes, dos animais e dos atendimentos não são compartilhadas automaticamente entre os sistemas, dificultando a centralização dos dados e a consulta unificada dos históricos.

---

## 3. O que Mudou ou se Confirmou em Relação à Entrega 1

Em relação ao que tínhamos estruturado na Entrega 1, a pesquisa de campo nos permitiu validar e refinar os seguintes aspectos:

- **Manutenção da Organização Real:** Confirmamos a continuidade do estudo sobre a mesma organização real analisada na Entrega 1.
- **Ajuste de Volumes e Porte:** Conseguimos dimensionar o porte da empresa, confirmando o volume de aproximadamente 400 atendimentos de banho e tosa por semana, o que fundamenta a quantidade de registros que aplicaremos na nossa massa de dados e no script SQL.
- **Refinamento dos Problemas Identificados:** Confirmamos a ausência de um cadastro estruturado de fornecedores e identificamos a falta de integração entre o sistema do pet shop e o sistema da clínica veterinária. Esses problemas direcionam a criação de tabelas, relacionamentos e consultas gerenciais no nosso modelo lógico.
- **Adequação do Escopo dos Processos e Regras:** Identificamos que processos como feiras de adoção e lar temporário não fazem parte do escopo da empresa, sendo removidos das premissas do modelo. Por outro lado, a venda de produtos a granel e a associação do profissional responsável ao atendimento foram incorporadas como regras de negócio explícitas para garantir a integridade do banco de dados.
