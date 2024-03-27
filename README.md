## Objetivo do Projeto

O objetivo principal deste projeto é desenvolver um modelo de concessão de crédito robusto e confiável para a PoD Bank, uma startup no setor financeiro. Através da análise de dados e da aplicação de técnicas de machine learning, busquei aprimorar as decisões de crédito da empresa, fornecendo um score de risco preciso e fundamentado para a contratação de produtos de crédito.

O objetivo específico é criar um modelo que seja capaz de avaliar o risco de crédito de cada cliente. Isso nos permitirá identificar com maior precisão os clientes que representam um risco elevado de inadimplência, minimizando as perdas e otimizando a carteira de crédito da PoD Bank.

Ao alcançar esse objetivo, espero fornecer à PoD Bank uma ferramenta poderosa para aprimorar sua análise de riscos, aumentar a eficiência operacional e impulsionar o crescimento sustentável do negócio. Além disso, busco contribuir para a missão da empresa de oferecer soluções de crédito inovadoras e sustentáveis, atendendo às necessidades financeiras da população de forma responsável e ética.

## Introdução ao Framework CRISP-DM

Para o desenvolvimento deste projeto de concessão de crédito, estou seguindo o framework CRISP-DM (Cross-Industry Standard Process for Data Mining). O CRISP-DM é uma metodologia amplamente reconhecida e utilizada em projetos de mineração de dados e análise preditiva.

Ao adotar o CRISP-DM, estou empregando uma abordagem estruturada e sistemática para enfrentar os desafios deste projeto. Este framework me guia através de seis fases principais: entendimento do negócio, entendimento dos dados, preparação dos dados, modelagem, avaliação e implantação.

Ao seguir o CRISP-DM, busco garantir que meus esforços estejam alinhados com os objetivos deste projeto, permitindo-me desenvolver modelos de crédito mais robustos e confiáveis. Esta metodologia me ajuda a garantir que estou aproveitando ao máximo os recursos e dados disponíveis, resultando em decisões de crédito mais informadas e eficazes.

- Emtendimento do Negócio

A PoD Bank, uma startup no setor financeiro, estabeleceu uma sólida presença de mercado ao atender a população com escassa informação de crédito. Oferecendo crédito imobiliário, veicular e empréstimo pessoal, a empresa identificou a necessidade de aprimorar suas decisões de crédito, superando a dependência exclusiva do Business Intelligence (BI).

A Head de crédito solicitou à área de planejamento e modelagem da PoD Bank um modelo de crédito que tenha a capacidade de gerar um score de risco para contratação de produtos de crédito.

Essa estratégia visa melhorar a análise de riscos e garantir uma tomada de decisão mais fundamentada. Reflete o compromisso contínuo da empresa em oferecer soluções de crédito inovadoras e sustentáveis.

- Entendimento dos Dados

Durante a fase de entendimento dos dados, conduzi uma análise exploratória dos dados da base application_train. Esta base contém informações sobre o público-alvo do nosso projeto de concessão de crédito.

Durante essa análise, explorei as características e distribuições das variáveis disponíveis, identificando padrões, tendências e possíveis relacionamentos entre os dados. Além disso, busquei compreender a qualidade e integridade dos dados, identificando valores ausentes, outliers e possíveis inconsistências.

Essa etapa foi fundamental para ganhar insights iniciais sobre o público-alvo e entender melhor a natureza dos dados com os quais estou trabalhando. Essas informações orientarão as próximas etapas do projeto, incluindo a preparação dos dados e o desenvolvimento de modelos de machine learning.

- Preparação dos Dados

Na fase de feature engineering, estou focada em enriquecer os dados através da criação de novas variáveis em todas as tabelas relevantes do projeto. Este processo envolve a seleção cuidadosa de variáveis existentes, a aplicação de transformações adequadas e a criação de novas características que capturem informações relevantes e distintivas sobre o comportamento dos clientes no contexto de concessão de crédito.

Ao criar essas variáveis adicionais, estou buscando extrair insights mais profundos e significativos dos dados, aprimorando assim a capacidade dos modelos de machine learning em capturar os padrões subjacentes e fazer previsões precisas. Isso inclui a consideração de fatores como histórico de pagamentos, comportamento financeiro, perfil demográfico e outras informações relevantes para o processo de concessão de crédito.

Uma vez que tenho criado as variáveis em todas as tabelas pertinentes, o próximo passo será integrá-las através de operações de junção, permitindo uma visão abrangente e integrada do histórico de cada cliente. Esta abordagem holística nos proporcionará uma base sólida para a construção e treinamento de modelos de machine learning que serão aplicados na previsão de risco de crédito e na tomada de decisões informadas e eficazes.

