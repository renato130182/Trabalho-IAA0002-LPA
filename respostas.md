**Respostas das Questões Discursivas - Trabalho de IAA002**

**Questão 1.f: Breve explicação sobre os principais resultados da Análise Exploratória dos dados**
A análise exploratória revelou a presença de alguns valores ausentes na base de dados, que foram tratados utilizando métodos adequados. 
Além disso, observamos uma distribuição variada dos preços dos carros, com variações entre as marcas.
Identificamos também a predominância de determinados tipos de combustível e engrenagens.

**Questão 2.e: Breve explicação sobre os resultados do gráfico da média de preço dos carros por marca e tipo de engrenagem**
O gráfico da distribuição da média de preço dos carros por marca e tipo de engrenagem mostra a variação dos preços médios entre diferentes marcas e tipos de câmbio (manual e automático). 
Os dados indicam que, dentro de cada marca, veículos com câmbio automático apresentam preços médios superiores aos de câmbio manual. 
A marca VW - VolksWagen registrou a maior diferença de preço entre os tipos de câmbio.

**Questão 2.g: Breve explicação sobre os resultados do gráfico da média de preço dos carros por marca e tipo de combustível**
O gráfico da distribuição da média de preço dos carros por marca e tipo de combustível mostra a variação dos preços médios entre diferentes marcas e tipos de combustível (álcool, diesel e gasolina). 
Observa-se que, em geral, carros movidos a diesel tendem a ter preços médios mais elevados em comparação aos carros movidos a álcool e gasolina. 
A marca VW - VolksWagen apresenta a maior diferença de preço entre os tipos de combustível, com os carros a diesel sendo significativamente mais caros.
Este gráfico permite identificar tendências de preços com base no tipo de combustível utilizado pelos veículos.

**Questão 3.f: Breve explicação sobre a análise de importância das variáveis para estimar a variável target**
A análise de importância das variáveis indicou que o tamanho do motor (engine_size) e o ano do modelo (year_model) são os fatores que mais influenciam a determinação do preço médio dos carros (avg_price_brl). 
Além disso, variáveis como o tipo de combustível (fuel) e o modelo do carro (model) também apresentaram impacto relevante. 
Em contrapartida, a marca (brand) e o mês de referência (month_of_reference) demonstraram menor influência na estimativa do preço.

**Questão 3.h: Explicação sobre qual modelo gerou o melhor resultado e a métrica de avaliação utilizada**
O modelo Random Forest apresentou o melhor desempenho com base nas métricas avaliadas.
Ele obteve um MSE menor, indicando menor erro médio, e um MAE reduzido, mostrando previsões mais próximas dos valores reais.
Além disso, o R² mais alto revelou que o modelo explicou melhor a variabilidade dos preços dos carros.
Portanto, o Random Forest foi considerado o modelo mais adequado para previsão.

