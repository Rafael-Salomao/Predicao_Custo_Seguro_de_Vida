# Predicao_Custo_Seguro_de_Vida

<p align="center">
  <img width="650" height="350" src="https://github.com/Rafael-Salomao/Predicao_Custo_Seguro_de_Vida/blob/9acb7eeb8e543fe1a9ee4d7ffa7bbd2fcfb3341f/seguro-de-vida-entenda-como-funciona-e-quais-as-suas-principais-coberturas.jpg">
</p>

## 1.0 Introdução

A partir do aumento de investimentos e recursos, incorporados a procedimentos hospitalares, tais operações não são acessíveis pela maior parte da população. Assim, o seguro de saúde se tornou uma forma de investimentos para as pessoas, devido ao custo crescente nos cuidados de saúde de qualidade, combinados com maior expectativa de vida da população. Os seguros de saúde foram criados como forma de reembolsar e compensar os custos financeiros de incidentes passíveis de acontecer na vida das pessoas.

Um grande desafio em negócios de seguro de vida, é definir o preço justo de seus serviços. Isso ocorre, pois envolve questões de concorrência, que não está sob controle das empresas ou de sua própria sobrevivência. Na área de seguros esse desafio é ainda maior, pois o custo efetivo do produto somente é conhecido a posteriori, em função de fatores aleatórios, como o sinistro e a rentabilidade financeira. Por conta disso, o preço do seguro reflete uma perspectiva de custos futuros, com base em probabilidades e descontos financeiros, mais um carregamento de segurança.

## 2.0 Qual problema foi resolvido

A empresa de seguro de saúde, enfrenta um problema de inconsistência em seu processo de precifição da taxa a ser cobrada de seus clientes, que inviabiliza a escalabilidade do produto e, consequentemente, da entidade como um todo.

No momento da contratação de um seguro de saúde, o valor do serviço é diferente para cada cliente, a depender do perfil da pessoa. Idade, peso, se é fumante ou não, histórico de doenças, entre outros, são fatores de influenciam na taxa que será cobrada. O desafio desta empresa de seguros é estruturar um modelo de precificação de mensalidades a serem ofertados para cada um desses novos clientes que desejam adiquirir o seguro da companhia.

## 3.0 Como foi resolvido

Para a resolução do problema desta empresa, foi implementado um Sistema de Predição para Precificação de Seguro Saúde.

Este Sistema de Predição foi elaborado a partir de um modelo de Regressão Polynomial, utilizando algoritmos de Machine Learning. O modelo é responsável por estimar e prever valores de seguros baseados em dados passados, do histórico de clientes que já passaram pela empresa.

O método de predição foi avaliado de acordo com métricas estatísticas, de modo que, a acurácia das previsões seja maximizada e atenda as necessidades do negócio. E, com isso, foi criado o Sistema de Predição, em que a partir das informações de entrada dos novos clientes, o modelo retorna a predição dos valores, de imediato, melhorando a eficiência e otimizando o processo de precificação.

## 4.0 Tecnologias utilizadas

- Sklearn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Pyplot

## 5.0 Resultados obtidos

Após estruturar os modelos de regressão, as métricas consideradas para avaliar o desempenho do modelo foram:

- R2_Score;
- Root Mean Square Error (RMSE);
- Mean absolute error (MAE).

A partir dos valores obtidos, pode-se ver que o modelo de Regressão Polinomial performou melhor, com um R2-score de 0.81. Como também, um RMSE de 5353.93 e MAE de 3278.01. Já o modelo de Regressão Linear alcançou um R2-score de 0.75. Sendo que, quando considerado grau n=3 a Regressão Polinomial retornou uma boa adequação aos dados reais, para compor o Sistema de Predição para Precificação de Seguro Saúde.

Ao testar o modelo com os dados de teste, obtive-se uma performance ainda melhor da regressão. Sendo, RMSE de 4600.51, MAE de 2991.27 e R2-score de 0.87. Com isso, este modelo pode ser incorporado pela empresa para o cálculo das taxas a serem cobrados de seus clientes, de forma rápida e confiável, economizando tempo e custos da empresa.

## 6.0 Implementações futuras/ evoluções

Tal sistema, em um estágio posterior de seu ciclo de vida, pode ser implantado em plataformas de nuvem e, assim, quando os dados aumentarem ainda mais, serem integrados com recursos de computação de ponta para processamento mais rápido e em tempo real das informações.

## 7.0 Referências

[1] "Diagnósticos sobre a Saúde Pública no Brasil", Agenda Mais SUS, Nov/22, [Online]. Available: https://bit.ly/3Xihd9P

[2] "Global expenditure on health: Public spending on the rise?", WHO annual report 2021, [Online]. Available: https://bit.ly/3gpgi6Y

[3] P. P. Ferreira. "Desafios do preço justo no seguro saúde", Nov/22, [Online]. Available: https://bit.ly/3AxHYND

[4] "Health Insurance Cost Prediction", [Online]. Available: https://bit.ly/3ENyRuP

[5] Panda S., Purkayastha B., Das D., Chakraborty M., Biswas S. K. "Health Insurance Cost Prediction Using Regression Models". International Conference on Machine Learning, Big Data, Cloud and Parallel Computing (COM-IT-CON), Andhra Pradesh, India, 2022, [Online]. Available: https://bit.ly/3gjUPfD
