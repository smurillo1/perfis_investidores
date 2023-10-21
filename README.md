# <img width="48" height="48" src="https://img.icons8.com/emoji/48/fire.png" alt="fire"/> Introdução
Trabalhando no projeto de finanças pessoais, foi obtido acesso a uma base de dados que inclui informações características dos clientes, bem como seu histórico bancário e transações de cartão de crédito.
# <img width="48" height="48" src="https://img.icons8.com/plasticine/100/dice.png" alt="dice"/> Desafio
**Desenvolver uma solução para agrupar clientes baseado nos seus perfis de gastos**.
# <img width="48" height="48" src="https://img.icons8.com/color/48/writing-down.png" alt="writing-down"/> Metodologia
- Leitura inicial do df's disponibilizados;
- Análise exploratória e construção do dataset principal;
- Feature Engineering
  - Construção de variáveis numéricas relacionadas as categorias transacionadas (média, max, min, total);
  - Classificação de transações fixas e variáveis;
  - Criação da 'category_max': categoria em que o cliente mais gastou;
- Modelagem
  - Utilização de Kmeans e Kprototypes;
  - Utilização de 4 df's com features diferentes, buscando a mais assertiva;
- Evaluation
- Escolha do modelo e análise dos perfis
# <img width="48" height="48" src="https://img.icons8.com/doodle/48/improvement.png" alt="improvement"/> Resultados
- A partir da observação dos agrupamentos, optou-se por explorar o modelo de cluster gerado pelo algoritmo Kprototypes e intitulado de 'model_2': 'popo_2';
- 4 grupos com recebimentos bem distribuidos (com recebimentos até 2, 5, 9 e 11 mil, respectivamente);
- Os investimentos seguem a mesma linha em cada grupo;
- os gastos idem, podendo variar em até 40, 60, 140 e 260 mil em cada grupo;
- O grupo 1 o que mais gasta com despesa fixa e o grupo 0 o que menos gasta e isso é um bom insight para saber onde atacar esses grupos futuramente;
- Sobre as despesas variáveis, dois grupos obtem destaque (1 e 3);
- As categorias que mais impactam nos gastos: Compras, Educação, Saúde, Moradia, Lazer e 'Outras Saídas';
- Sobre o perfil de investimento, o que conseguimos obter foi que o grupo 3 tem um volume maior de investidores conservadores, esse conservadorismo pode ser gerado, também por um alto indice de gastos variáveis, falta de conhecimento de mercado e receio de perder o investimento.
- Futuramente esse dado pode ser investigado junto à o tipo de pagamento utilizado pelo cliente para tentarmos linkar as informações
