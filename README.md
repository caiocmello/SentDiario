# Sobre o projeto

Quão positiva (ou negativa) foi a cobertura da imprensa acerca do novo Acordo Ortográfico? E quanto à comunidades minorizadas como a LGBT? SentDiário é uma ferramenta que permite uma análise diacrônica detalhada das tendências midiáticas relativas a diferentes tópicos de interesse social. Nós apresentamos um modelo que permite classificar automaticamente o sentimento dos títulos de notícias, através de assuntos selecionados. Para esta versão *demo*, incluímos notícias publicadas nos sites dos 10 principais portais de notícias de Portugal, de acordo com o [Instituto Reuters para o Estudo do Jornalismo](https://reutersinstitute.politics.ox.ac.uk/digital-news-report/2023/portugal): 

- SIC Notícias online
- Notícias ao Minuto
- Correio da Manhã online
- Correio da Manhã TV online
- Sapo
- Jornal de Notícias online
- CNN Portugal online
- Observador
- Expresso online
- Público online

## Porque analisar o sentimento de textos jornalísticos?
[Vizeu](https://revistaseletronicas.pucrs.br/ojs/index.php/revistafamecos/article/view/6321) (2009, p.77) argumenta que o jornalismo é um ‘lugar de referência’. Isto é, um lugar que estabelece parâmetros da realidade, aonde as pessoas vão em busca de ‘estabilidade’. Desta forma, é através do consumo de notícias que temos acesso a fatos diversos do cotidiano, e a forma como os interpretamos é mediada pelos meios de comunicação. O fato de um jornal publicar mais notícias positivas ou negativas sobre determinado assunto tem, portanto, o potencial de não apenas reproduzir, mas também, construir uma visão positiva ou negativa acerca daquele determinado tópico. Assim, analisar o sentimento das notícias ajuda a compreender como assuntos de relevância social são reportados pelos diferentes meios e qual o ‘tom’ adotado pelos jornais.  

## Mas notícias não deveriam ser sempre neutras?  
Quando falamos em neutralidade no jornalismo ([Ojala,2021](https://www.tandfonline.com/doi/full/10.1080/1461670X.2021.1942150)), nos referimos à busca por uma reportagem que não tome partido e apresente uma visão equilibrada dos fatos. Ao propor uma análise de sentimento, estamos levando em consideração que textos de notícia podem ser positivos, negativos ou neutros, na medida em que o discurso faz usos de palavras que carregam esses sentimentos. Veja abaixo exemplos de notícias de polaridade positiva, neutra e negativa:
- Exemplo 1
- Exemplo 2
- Exemplo 3

## E porque analisar somente os títulos das notícias? E quanto ao resto do texto?
Títulos de notícias exercem uma série de funções ([Scacco & Muddiman, 2016](https://mediaengagement.org/research/clickbait-headlines/)), especialmente quando se trata do jornalismo online, que depende de clicks para mensurar sua audiência. Seja o título um resumo do conteúdo ou um clickbait, ele é o primeiro nível de acesso à informação (a primeira impressão) e, muitas vezes, também a única. 

´´´
*Clickbait* é o nome dado à estratégia de se utilizar de títulos super atrativos ao leitor. Esses títulos, muitas vezes, fazem uso de palavras alarmantes, criam mistérios ou perguntas a serem respondidas (ou não) pelo restante do texto caso o leitor o acesse. 
´´´

Devido ao uso de paywalls ou por conta de hábitos de consumo de notícias pelas redes sociais, os títulos acabam sendo a única dimensão da notícia que muitos leitores consomem. Por fim, a análise dos textos apresenta um desafio técnico que pode elevar a imprecisão dos algoritmos devido aos longos parágrafos, os quais tendem a apresentar fatos diversos com conteúdos contraditórios e fazendo uso de uma linguagem menos adjetivada (portanto mais objetiva), o que tende a acontecer de forma oposta em títulos. 


## Como usar a ferramenta?

- [List the specific goals and objectives of the project.]

## Metodologia 

Utilizamos a API do Arquivo.pt para realizar as buscas, identificando, para cada tema, as palavras-chave, os diferentes portais de notícias e fixando o período de tempo relevante. Cada notícia extraída é classificada automaticamente, a partir do respectivo título, como: a) positiva, b) negativa ou c) neutra.

´´´
Sobre a análise de sentimento: 

[FinBERT-PT-BR](https://huggingface.co/lucas-leme/FinBERT-PT-BR) foi o modelo utilizado por ter apresentado os melhores resultados quando comparado a diferentes modelos de análise de polaridade. Testamos os seguintes modelos: ´pysentimiento´, ´lxyuan´, ´citizenlab´, ´HeyLucasLeao´, ´igoramf´ e ´satoken´. Também testamos a combinação de diferentes modelos, porém, FinBERT-PT-BR apresentou a melhor acurácia a partir de uma avaliação manual de 150 títulos realizada por dois anotadores falantes nativos de português.

´´´

Os resultados obtidos são, então, processados para serem apresentados de maneira otimizada. Primeiramente, para cada tópico, fornecemos a distribuição do número de publicações por mês e por portal de notícias. Em seguida, apresentamos a tendência global (ou seja, todos os portais combinados) das publicações e a evolução temporal. Além disso, para cada portal, é possível verificar as diferentes evoluções diacrônicas relativas às diferentes etiquetas utilizadas em nossa classificação.
Nós selecionamos quatro tópicos para demonstrar o interesse da nossa ferramenta (imigração, novo acordo ortográfico, LGBT e direitos reprodutivos/aborto), porém, o potencial dela vai além. 

## Timeline

[Provide a rough timeline of the project's milestones and anticipated completion dates.]


## Autores

- **Name:** [Caio Mello]
- **Position:** [PhD Candidate]
- **Affiliation:** [School of Advanced Study, University of London]
[Personal website](https://caiocmello.github.io/) | [E-mail](caiomellodh@gmail.com) 

- **Name:** [Dr. Diego Alves]
- **Position:** Postdoctoral Researcher 
- **Affiliation:** Saarland University
[Personal website](https://dfvalio.github.io/) | [E-mail](dfvalio@gmail.com) 

- **Name:** [Dr. Gaurish Thakkar]
- **Position:** [Researcher]
- **Affiliation:** [University of Zagreb]
[Personal website](https://thak123.github.io/) | [E-mail](thak123@gmail.com) 
---

Thank you for visiting our About page. For more information, feel free to reach out to us.
