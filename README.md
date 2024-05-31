# Desafio Criar um Artigos Técnicos com ChatGPT e Lexica.art

Projeto com o objetivo de gerar um artigo técnico com um layout rico, leitura agradável e com foco em promover sua autoridade técnica.

<a href="https://medium.com/@fanciscosoares/modelos-de-suavização-exponencial-para-previsão-de-séries-temporais-sem-sazonalidade-6c25c4e5d048" title="View PDF now"> 📕 Clique aqui para ler o artigo</a>

## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) - para título e conteúdo
- [Lexica.art](https://lexica.art/) - para gerar imagens
- [Posit Cloud](https://posit.cloud) - Para fazer os cálculos e gerar os gráficos

## 📄 Prompts e ferramentas


ChatGPT：
**Título**

**Escrever o artigo**
Escreva um artigo detalhando os modelos de suavização exponencial usados para realizar previsões a partir de séries temporais sem sazonalidade. Iniciando pela análise exploratória dos dados, em seguida cada uma das séries é dividida em duas partes, uma para o treino do modelo e outra para o teste. A partir do período de treino, cada série temporal é analisada utilizando os seguintes métodos de Suavização Exponencial: método com tendência aditiva e erro aditivo (AA), método com tendência aditiva e erro multiplicativo (MA), método com tendência multiplicativa e erro multiplicativo (MM), método com tendência aditiva amortecida e erro aditivo (AAd), método com tendência aditiva amortecida e erro multiplicativo (MAd) e método com tendência multiplicativa amortecida e erro multiplicativo (M Md). Cada um dos modelos gerados para cada fonte de emissão de CO2e é  avaliado em função da parcimoniosidade, feito pelos critérios de informação AIC, AICc e BIC. Também é feita a análise dos resíduos para verificar a autocorrelação, a heterocedasticidade e se a série possuía uma distribuição normal, através dos testes de Ljung-Box, ARCH e Jarque-Bera, respectivamente. Foram então gerados para cada fonte de emissão seis modelos. Por fim, deve ser identificado o modelo que apresente a maior capacidade preditiva, utilizando RMSE, MAE e MAPE.

{REGRAS}
> A serie temporal são das emissões de CO2 e no estado do Amazonas emitidas pela agropecuária, no período de 1990 a 2022: agropecuaria <- c(1677081, 1701660, 1674009, 1802964, 1948464, 2097143, 1864106, 1963283, 2076821, 2143739, 2189929, 2255185, 2300605, 2774262, 2845493, 2937939, 3010741, 2749716, 3016568, 3103937, 3141964, 3273834, 3302693, 3323927, 3196871, 2968262, 3025446, 3096496, 3178738, 3348516, 3320480, 3497115, 3641670)
 
> A linguagem de programação usada será o R.
