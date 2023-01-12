# Predicao Custo Seguro de Vida

Predição Custo Seguro de Vida
1.0 Entendimento do Problema
O objetivo desta etapa é entender o contexto, as premissas, objetivos e requisitos a serem considerados no desenvolvimento do projeto.

1.1 Introdução
A saúde pública é um setor relevante para a sociedade como um todo, sendo uma esfera de grande preocupação para governantes ao redor do mundo. Vidas humanas e saúde pública podem ser ameaçadas por calamidades naturais, epidemias e pandemias globais, crises globais, dentre outros fatores, que aumentam a vulnerabilidade da saúde humana.

As pessoas podem se deparar com circunstâncias inevitáveis e imprevistos, como acidentes e doenças crônicas, em qualquer ponto de suas vidas. Com a possibilidade de eventualidades ocorreram quando menos se esperam, é de comum acordo a instabilidade da vida. Contudo, apesar de não ser possível erradicar de uma vez por todas, tais risco, é possível amenizar seus impactos negativos.

Para conter os impactos dessas casualidades, países e empresas atuam continuamente para mitigá-los. De acordo com o Instituto de Estudos para Políticas de Saúde (IEPS), nos últimos dez anos, o gasto total com saúde no Brasil vem aumentando, alcançando 9,5% do PIB em 2018. Sendo que, 3,96% deste foram gastos totais do governo e o restante equivale a gastos privados das famílias brasileiras. [1]. Assim como, nas últimas duas décadas, a assistência universal à saúde quase dobrou, ultrapassando US$ 8,5 trilhões em 2019, ou 9,8% do PIB global. [2]

A partir do aumento de investimentos e recursos, incorporados a procedimentos hospitalares, tais operações não são acessíveis pela maior parte da população. Assim, o seguro de saúde se tornou uma forma de investimentos para as pessoas, devido ao custo crescente nos cuidados de saúde de qualidade, combinados com maior expectativa de vida da população. Os seguros de saúde foram criados como forma de reembolsar e compensar os custos financeiros de incidentes passíveis de acontecer na vida das pessoas.

Por conta dos avanços nos investimentos em saúde, o mercado de seguradoras está, constantemente, explorando maneiras para impulsionar suas operações e serviços.

Um grande desafio em negócios de seguro de vida, é definir o preço justo de seus serviços. Isso ocorre, pois envolve questões de concorrência, que não está sob controle das empresas ou de sua própria sobrevivência. Na área de seguros esse desafio é ainda maior, pois o custo efetivo do produto somente é conhecido a posteriori, em função de fatores aleatórios, como o sinistro e a rentabilidade financeira. Por conta disso, o preço do seguro reflete uma perspectiva de custos futuros, com base em probabilidades e descontos financeiros, mais um carregamento de segurança.

Desta forma, trabalhar com o preço abaixo da expectativa de custos leva a operadora à insolvência, se não houver capital de risco suficiente para bancar essa operação. Por outro lado, se a operadora trabalhar com um preço muito alto, ela também pode quebrar, não somente por diminuir a sua carteira de clientes. Portanto, cobrar um preço abaixo do custo ou acima do custo pode quebrar uma operadora, o que torna o desafio do preço justo ainda maior, pois somente um preço muito bem calibrado pode evitar o pior, que é a insolvência.

1.2 Escopo do problema de negócio
Uma empresa de seguro de saúde está enfrentando um momento de grande crescimento na quantidade de clientes.

O que era para ser um momento prospero, está sendo um momento de stress em todo o negócio. A questão é que, a companhia não conta com processos definidos para precificação dos serviços para os inúmeros perfis de novos clientes. A ineficiencia e falta de padrão nos métodos, gera retrabalho e perda de tempo entre os funcionários responsáveis pelo cálculo das taxas a serem cobradas para cada novo cliente.

O que reflete diretamente na receita e fluxo de caixa organização. A empresa enfrenta um problema de inconsistência em seu processo que inviabiliza a escalabilidade do produto e, consequentemente, da entidade como um todo.

No momento da contratação de um seguro de saúde, o valor do serviço é diferente para cada cliente, a depender do perfil da pessoa. Idade, peso, se é fumante, histórico de doenças, entre outros, são fatores de influenciam na taxa que será cobrada. O desafio desta empresa de seguros é esta diverfência de valores a serem ofertados para cada um desses novos clientes que desejam o produto da companhia.

Por conta disso, a empresa deseja contratar uma consultoria para tornar este processo de precificação mais ágil, eficiente e preciso.

1.3 Como a solução vai ser usada?
Para a resolução do problema desta empresa, será implementado um Sistema de Predição para Precificação de Seguro Saúde.

Este Sistema de Predição será elaborado a partir de um modelo de regressão, utilizando algoritmos de Machine Learning. O modelo será responsável por estimar e prever valores de seguro baseado em dados passados, do histórico de clientes que já passaram pela empresa.

O método de predição será avaliado de acordo com métricas estatisticas de modo que a acurácia das previsões sejam minimizadas e atendam as necessidades do negócio. Para que, com isso, seja criado o Sistema de Predição, em que a partir das informações de entrada, dos novos clientes, o modelo irá retornar a predição dos valores, instantaneamente, melhorando a eficiência e otimizando o processo de precificação.

1.4 Quais são as soluções já existentes?
Existem diversos métodos de precificação, aplicados em função das informações disponíveis e das circunstâncias às quais a precificação será aplicada.

O método mais simples e, também, o mais frágil, é o método subjetivo, quando não existem informações disponíveis, cabendo ao underwriter definir o preço do seguro em função da sua experiência em riscos similares.

O segundo método utilizado é o da sinistralidade, em que o preço de um seguro em vigor é revisto em função desta. Se a sinistralidade superar um nível aceitável, os preços são corrigidos para trazê-la ao nível aceitável.

O terceiro é o método das tábuas de mortalidade, utilizado nos seguros de vida e previdência. Nele, as probabilidades de morte são obtidas pelas tábuas de mortalidade desenvolvidas por órgãos de classe atuarial, ou mesmo por órgãos reguladores.

O ramo de seguro de saúde brasileiro chega a ser um dos setores de precificação mais complexos do mundo. No Brasil, as informações que são levadas em consideração, no geral, é: idade, região, tipo de rede assistencial, existência de fator moderador, franquia e tipo de plano. Há mais segmentos de risco que podem ser considerados, como sexo, índice de massa corporal e outros, que poderiam ser obtidos a partir de modelos preditivos, com técnicas de Big Data. Nisso aparece um desafio tecnológico: a maioria das operadoras ainda não possui bancos de dados estruturado para a utilização de Big Data, nem equipe técnica capacitada para tal [3].

1.5 Premissas do projeto
O projeto é realizado a partir de uma abordagem de aprendizado supervisionado, a partir desta perspectiva serão testados modelos de Regressão Linear e Regressão Polinomial, a fim de encontrar a melhor solução ao problema.

No site Kaggle [4] foi obtido o conjunto de dados, que será referente as informações necessárias para resolver o problema de negócio em questão. O Dataset será explorado e tratado para se adequar da melhor maneira no desenvolvimento do Sistema de Predição para Precificação de Seguro Saúde.

Após estruturar o modelo de regessão, serão consideradas as métricas abaixo para avaliar o desempenho do algoritmo:

R2_Score
Root Mean Square Error (RMSE)
Mean absolute error (MAE)
1.6 Plano de desenvolvimento do projeto
Após a introdução ao problema de negócio apresentado acima, as próximas etapas para a elaboração da solução são as seguintes:

Entendimento dos Dados;
Preparação dos Dados;
Construção do Modelo de Machine Learning;
Avaliação dos Resultados;
Implementação do Sistema de Predição.
