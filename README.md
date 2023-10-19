# Radiografia das Desigualdades Raciais no Brasil: Um Exame Multidimensional dos Determinantes Sociais e Econômicos
A análise dos indicadores sociais e econômicos é fundamental para entender as disparidades sociais existentes no Brasil e em muitos outros países. A relação entre esses indicadores e a raça das pessoas é um tema de grande relevância, pois revela como fatores como educação, saúde, trabalho e padrão de vida podem afetar de forma desigual grupos raciais específicos, destacando a persistência das desigualdades raciais

## Análise Generalizada do Índice de Pobreza Multidmensional no Brasil
Afim de fazer uma análise generalizad do IPM deve-se levar em consideração os indicadores que são usados para que o cálculo do índice seja feito: 

### Dimensão: Educação

- (E1) Frequência: Domicílio com pelo menos uma pessoa com idade entre 6 e 17 anos que não frequenta escola (Peso: 8,33)
- (E2) Distorção Idade-série: Domicílio com pelo menos uma pessoa com idade entre 8 e 17 anos com 2 ou mais anos de idade acima do recomendado para a série/ano que está cursando (Peso: 8,33)
- (E3) Escolaridade: Domicílio com pelo menos uma pessoa com 18 anos ou mais que não tenha completado o ensino fundamental (Peso: 8,33)

### Dimensão: Saúde

- (S1) Mortalidade Infantil: Domicílio em que ao menos uma criança de até 5 anos de idade tenha falecido no ano de referência (Peso: 6,25)
- (S2) Água Potável: Domicílio onde não há abastecimento de água via rede geral de distribuição (Peso: 6,25)
- (S3) Saneamento Básico: Domicílio em que o esgoto do banheiro ou sanitário não é lançado em rede geral (Peso: 6,25)
- (S4) Tratamento do Lixo: Domicílio cujo lixo não é coletado por serviço de limpeza (Peso: 6,25)

### Dimensão: Trabalho

- (T1) Trabalho Infantil: Domicílio em que pelo menos uma criança de 10 a 15 anos estava trabalhando na semana de referência (Peso: 8,33)
- (T2) Desocupação: Domicílio com pelo menos uma pessoa de 18 anos ou mais que estava desocupada no mês de referência (Peso: 8,33)
- (T3) Trabalho Informal: Domicílio com pelo menos uma pessoa de 18 anos ou mais ocupada em posição informal (Peso: 8,33)

### Dimensão: Padrão de Vida

- (P1) Material do Domicílio: Domicílio onde não foi utilizado material de alvenaria (com ou sem revestimento) para sua construção das paredes externas (Peso: 6,25)
- (P2) Densidade Morador/Dormitório: Domicílio com mais de 2 moradores por dormitório (Peso: 6,25)
- (P3) Consumo: Domicílio sem máquina de lavar roupa (Peso: 6,25)
- (P4) Renda Domiciliar: Domicílio com renda domiciliar per capita inferior a linha de pobreza – U$$5,50 por dia ou R$93,27 por mês (Peso: 6,25)


Com a finalidade de conduzir a análise de maneira gradual e sistemática, é inicialmente aplicada uma abordagem centrada na construção de um histograma. Essa abordagem se revela relevante no contexto da pesquisa, visto que a utilização de um histograma desempenha um papel fundamental no processo de análise exploratória de dados, permitindo a visualização e interpretação da distribuição de variáveis, fatores críticos para a compreensão aprofundada dos padrões e tendências subjacentes nos conjuntos de dados em estudo.

<div align="center">
  <img src="https://github.com/lucasjsbarbosa/1-DESAFIO-DE-CIENCIA-DE-DADOS-PUC-MINAS/assets/106505340/46fef24b-01ea-48f7-964b-a5c036cf2228" alt="Descrição da Imagem">
</div>


No contexto observado, é evidente que a maioria dos dados apresenta uma frequência consideravelmente mais alta antes de atingirem o valor de IPM igual a 20. No entanto, a partir desse ponto, a interpretação dos resultados se torna mais desafiadora e menos conclusiva. Essa observação sugere um padrão inicialmente identificável na distribuição dos dados, mas a complexidade e a variedade dos dados se tornam mais evidentes após o ponto de IPM 20, o que torna a análise subsequente potencialmente mais complexa e sujeita a interpretações diversas.

Nesse cenário, evidencia-se a importância da elaboração de quatro histogramas distintos e uma tabela com estatística, cada um referente a um dos quatro grupos demográficos estipulados, a saber: (1) Branca - Masculino, (2) Branca - Feminino, (3) Preta ou Parda - Masculino e (4) Preta ou Parda - Feminino. A finalidade dessa abordagem reside na busca por insights e conclusões mais robustas e esclarecedoras a respeito das características analisadas, dado que a segmentação dos dados por raça e sexo é fundamental para identificar eventuais diferenças e tendências específicas associadas a cada grupo. Portanto, a plotagem dos quatro histogramas e tabela estatística se apresentam como recursos valioso no processo de análise de dados, possibilitando uma compreensão mais aprofundada e precisa dos padrões subjacentes a essas demografias.

<div align="center">
  <img src="https://github.com/lucasjsbarbosa/1-DESAFIO-DE-CIENCIA-DE-DADOS-PUC-MINAS/assets/106505340/f66c7861-f0d6-42d4-906a-605e00f741ee" alt="Descrição da Imagem">
</div>

<div style="text-align:center; font-size:14px;">


| Grupo Demográfico         | Média | Mediana | Desvio Padrão | Mínimo | Máximo | Q1   | Q3   | IQR   |
|:--------------------------|:-----:|:-------:|:-------------:|:------:|:------:|:----:|:----:|:----:|
| Branca Masculino         | 15.49 | 14.84   | 9.56          | 0.14   | 55.34  | 7.41 | 22.04| 14.64 |
| Branca Feminino          | 14.40 | 13.37   | 9.26          | 0.07   | 55.45  | 6.63 | 20.53| 13.90 |
| Preta ou Parda Masculino  | 18.89 | 18.71   | 10.27         | 0.00   | 56.87  | 10.52| 26.28| 15.75 |
| Preta ou Parda Feminino   | 17.88 | 17.46   | 9.96          | 0.00   | 55.89  | 9.71 | 24.83| 15.11 |

Comparando os grupos Branca Masculino, Branca Feminino, Preta ou Parda Masculino e Preta ou Parda Feminino em relação ao Índice de Pobreza Multidimensional (IPM), observamos algumas distinções. O grupo Preta ou Parda Masculino tem a média mais alta, indicando que, em média, possui um IPM mais elevado. Por outro lado, o grupo Branca Feminino tem a média mais baixa, sugerindo um IPM mais baixo em média. A mediana segue um padrão semelhante, com o grupo Preta ou Parda Masculino tendo a mediana mais alta e o grupo Branca Feminino com a mediana mais baixa. O desvio padrão revela que o grupo Preta ou Parda Masculino tem maior variabilidade nos valores do IPM, indicando uma dispersão mais ampla dos dados. Os quartis destacam que o grupo Preta ou Parda Masculino possui valores mais altos em ambos Q1 (primeiro quartil) e Q3 (terceiro quartil). Em resumo, o grupo Preta ou Parda Masculino demonstra uma tendência a ter um IPM mais alto, com maior variação, enquanto o grupo Branca Feminino apresenta um IPM mais baixo em média e menor variabilidade.

Neste ponto da análise, já podemos observar evidências sólidas das desigualdades no Índice de Pobreza Multidimensional (IPM), com ênfase na segmentação por raça. A diferenciação entre grupos demográficos, notadamente 'Branca' e 'Preta ou Parda', revela disparidades significativas em uma ampla gama de dimensões socioeconômicas. É fundamental que exista também uma plotagem de um heatmap (mapa de calor) pra cada um dos grupos para ver com qual intensidade eles se encaixam em cada indicador do IPM

<div align="center">
  <img src="https://github.com/lucasjsbarbosa/1-DESAFIO-DE-CIENCIA-DE-DADOS-PUC-MINAS/assets/106505340/e84f131b-35f6-4c39-b464-4f65bd6771ef" alt="Descrição da Imagem">
</div>

Como  são muitos dados em uma único gráfico, ressalta-se a importância de coloca-los em uma tabela para melhor visão e compreenão

| raca           | sexo       | qtd_pes_E1 | qtd_pes_E2 | qtd_pes_E3 | qtd_pes_S1 | qtd_pes_S2 | qtd_pes_S3 | qtd_pes_S4 | qtd_pes_T1 | qtd_pes_T2 | qtd_pes_T3 | qtd_pes_P1 | qtd_pes_P2 | qtd_pes_P3 | qtd_pes_P4 |
|----------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|
| Branca         | Feminino   | 0.024566   | 0.045657   | 0.144675   | 0.000322   | 0.093607   | 0.140431   | 0.078364   | 0.017413   | 0.028785   | 0.106584   | 0.048810   | 0.083435   | 0.143893   | 0.043458   |
| Branca         | Masculino  | 0.024637   | 0.045640   | 0.144479   | 0.000289   | 0.097069   | 0.140690   | 0.082090   | 0.018543   | 0.026280   | 0.107311   | 0.049642   | 0.078922   | 0.143149   | 0.041258   |
| Negra ou Parda | Feminino   | 0.025621   | 0.056533   | 0.135868   | 0.000414   | 0.083250   | 0.127149   | 0.077945   | 0.014963   | 0.030239   | 0.099113   | 0.044752   | 0.098104   | 0.148435   | 0.057614   |
| Negra ou Parda | Masculino  | 0.026114   | 0.057554   | 0.135756   | 0.000366   | 0.086213   | 0.126213   | 0.081800   | 0.016155   | 0.027931   | 0.099236   | 0.046277   | 0.094151   | 0.147202   | 0.055033   |

Dada a disponibilidade abrangente de informações, torna-se imperativo proceder à análise das distribuições desses dados com base nas regiões geográficas, a fim de aprofundar nossa compreensão sobre a dinâmica subjacente. A consideração da segmentação geográfica é crucial para identificar variações regionais nos indicadores previamente discutidos, bem como para contextualizar as disparidades socioeconômicas. Esse enfoque possibilita uma abordagem mais holística na avaliação do Índice de Pobreza Multidimensional (IPM) e dos fatores que contribuem para as desigualdades, fornecendo insights valiosos que podem orientar estratégias de políticas públicas mais eficazes e direcionadas para a promoção da equidade em diferentes áreas geográficas

<div align="center">
  <img src="https://github.com/lucasjsbarbosa/1-DESAFIO-DE-CIENCIA-DE-DADOS-PUC-MINAS/assets/106505340/f59f6f2b-81d0-4087-9218-1a4befaa67c8">
</div>

Pode-se observar uma significativa discrepância nas médias do Índice de Pobreza Multidimensional (IPM) entre as regiões geográficas. Para uma análise mais aprofundada, é relevante investigar a predominância étnica em cada região.

<div align="center">
  <img src="https://github.com/lucasjsbarbosa/1-DESAFIO-DE-CIENCIA-DE-DADOS-PUC-MINAS/assets/106505340/8ff78c49-ce6c-41db-b803-eee9f61dcdc8">
</div>

Um aspecto interessante a se destacar é que, no Norte e no Nordeste, as duas regiões com as médias mais elevadas de IPM, também se concentram as maiores proporções de pessoas de raça "negra ou parda". Esse fato sublinha a importância de considerar a interseção entre raça e desenvolvimento social, destacando como a equidade racial é uma questão fundamental para a melhoria das condições de vida nessas regiões.

Essas descobertas enfatizam a necessidade de políticas públicas que visem a redução das desigualdades regionais e raciais, promovendo um desenvolvimento mais inclusivo e equitativo em todo o país. O entendimento dessas tendências no IPM por região é crucial para orientar esforços no sentido de garantir uma sociedade mais justa e igualitária para todos os brasileiros.

## Machine Learning 

As discrepâncias significativas nos índices de pobreza entre as diferentes regiões tornaram evidente a necessidade de aplicar técnicas avançadas de machine learning para uma análise mais aprofundada. O objetivo principal é desenvolver um modelo preditivo capaz de determinar se um indivíduo pertence ao grupo étnico 'preto ou pardo' ou 'branco', exclusivamente com base nos indicadores do Índice de Pobreza Multidimensional (IPM), incidência, intensidade e em outras variáveis relevantes, como o Índice de Desenvolvimento Humano Municipal (IDHM), Índice de Vulnerabilidade Social (IVS), Índice de Bem-Estar Urbano (IBEU) e a renda média. Esta abordagem visa não apenas aprofundar a compreensão das disparidades socioeconômicas, mas também aprimorar a capacidade de previsão e identificação de fatores subjacentes às diferenças étnicas nas condições de bem-estar, permitindo uma análise mais holística das complexas interações entre essas variáveis.

### Árvore de Decisão 

As árvores de decisão são uma poderosa técnica de aprendizado de máquina e análise de dados que oferecem insights valiosos e auxiliam na tomada de decisões com base em informações disponíveis. Essa abordagem hierárquica utiliza critérios de divisão para classificar ou prever dados, proporcionando uma estrutura clara e facilmente interpretável

Após a normalização e o treinamento dos dados, uma árvore de decisão foi concebida

<div align="center">
  <img src="https://github.com/lucasjsbarbosa/1-DESAFIO-DE-CIENCIA-DE-DADOS-PUC-MINAS/assets/106505340/530238bd-b4d3-4d2d-ae6d-fc3dd78a0c2f">
</div>

Torna se necessário a verificação e consolidação na prática do modelo, abaixo as tabelas representam métricas de avaliação do desempenho de um modelo de árvore de decisão, especificamente em uma tarefa de classificação. Isso inclui precisão (quão precisas são as previsões), recall (quão bem o modelo identifica casos positivos), F1-score (uma média ponderada da precisão e recall), suporte (o número de amostras em cada classe) e acurácia (a proporção de previsões corretas em relação ao total de previsões). Essas métricas são fundamentais para avaliar a eficácia do modelo de árvore de decisão em diferentes cenários de treinamento e teste.

#### Reporte Teste

|              | precision | recall | f1-score | support |
|--------------|-----------|--------|----------|---------|
| 0.0          | 0.69      | 0.65   | 0.67     | 3298    |
| 1.0          | 0.68      | 0.72   | 0.70     | 3380    |
| accuracy     |           |        | 0.68     | 6678    |
| macro avg    | 0.68      | 0.68   | 0.68     | 6678    |
| weighted avg | 0.68      | 0.68   | 0.68     | 6678    |

#### Reporte Completo

|              | precision | recall | f1-score | support |
|--------------|-----------|--------|----------|---------|
| 0.0          | 0.71      | 0.66   | 0.69     | 11130   |
| 1.0          | 0.68      | 0.73   | 0.71     | 11130   |
| accuracy     |           |        | 0.70     | 22260   |
| macro avg    | 0.70      | 0.70   | 0.70     | 22260   |
| weighted avg | 0.70      | 0.70   | 0.70     | 22260   |

É fundamental notar que, com o intuito de garantir a validade dos resultados, apenas 30% dos dados totais foram empregados no processo de treinamento do modelo. Essa prática visa a assegurar que uma porção substancial dos dados seja reservada para a fase de teste e validação, permitindo uma avaliação mais precisa da eficácia da árvore de decisão. A divisão de dados em treinamento e teste é uma estratégia comum no campo de aprendizado de máquina, que ajuda a prevenir possíveis vieses e superestimações do desempenho do modelo. 

É notável que os resultados alcançados nas métricas, incluindo precisão, acurácia e outras, não deixaram a desejar. Isso demonstra que o modelo de árvore de decisão, mesmo com apenas 30% dos dados utilizados para treinamento, conseguiu realizar previsões com um grau satisfatório de acerto. Esses resultados são encorajadores e destacam a eficácia da árvore de decisão na análise dos dados em questão

Para uma visualização prática do modelo foi criada um DataFrame chamado "X_new", no qual se encontram 3 linhas de índice [6785, 7586, 2195], cada uma com informações detalhadas sobre incidência, qtd_pes_E1, qtd_pes_E2 e outras variáveis relevantes. Nota-se que as informações contidas nessas colunas não fazem referência à raça.

Neste contexto, a tarefa de classificação é de natureza binária, onde a raça é a variável de destino. Esta variável de destino é codificada como "1" para "preta ou parda" e "0" para "branca", configurando uma classificação binária. A classificação binária refere-se a situações em que há apenas duas categorias distintas, sem ênfase em uma ordem específica entre elas.

|   Índice   | incidência | qtd_pes_E1 | qtd_pes_E2 | qtd_pes_E3 | qtd_pes_S1 | qtd_pes_S2 | qtd_pes_S3 | qtd_pes_S4 | qtd_pes_T1 | qtd_pes_T2 | ... | qtd_pes_P1 | qtd_pes_P2 | qtd_pes_P3 | qtd_pes_P4 | intensidade |    IPM    | num_idhm | num_ivs | num_ibeu | num_renda |
|:---------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:| ... |:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:-------:|:-------:|:-------:|:-------:|
|   6785    |   0.598478  |   0.005574  |   0.009047  |   0.011864  |   0.000000  |   0.016905  |   0.010180  |   0.037248  |   0.012578  |   0.002891  | ... |   0.001507  |   0.004468  |   0.013200  |   0.015129  |   0.738597  | 0.460271 | 0.333333 | 0.667147 | 0.560158 | 0.104537 |
|   7586    |   0.223892  |   0.086413  |   0.131075  |   0.135824  |   0.053985  |   0.058966  |   0.115893  |   0.140461  |   0.093029  |   0.148285  | ... |   0.014442  |   0.097988  |   0.152819  |   0.140660  |   0.693010  | 0.161560 | 0.621622 | 0.380403 | 0.672584 | 0.232756 |
|   2195    |   0.679095  |   0.007895  |   0.011134  |   0.013673  |   0.020280  |   0.023076  |   0.013329  |   0.065434  |   0.019654  |   0.003338  | ... |   0.023693  |   0.009788  |   0.019899  |   0.032404  |   0.779424  | 0.551139 | 0.367117 | 0.646974 | 0.627219 | 0.065707 |


