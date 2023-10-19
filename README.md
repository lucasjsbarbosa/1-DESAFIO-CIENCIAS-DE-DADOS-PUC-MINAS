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














