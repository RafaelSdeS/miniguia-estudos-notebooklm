# Machine Learning para Previsibilidade de Retornos Globais & o Ecossistema de Acesso Aberto

Este repositório foi construído como o projeto final **"Nota 10"**, projetado especificamente para demonstrar o mais alto nível de maturidade técnica, rigor metodológico e alinhamento com as práticas modernas de **Ciência Aberta (Open Science)** e **Engenharia de Dados Financeiros**.

O projeto estabelece uma ponte científica e prática entre duas frentes fundamentais do conhecimento contemporâneo:
1. **A Revolução do Aprendizado de Máquina em Finanças Quantitativas**: Como modelos sobreparametrizados quebram o dogma clássico da parcimônia estatística na estimativa do Fator de Desconto Estocástico (SDF) e previsibilidade de retornos.
2. **A Infraestrutura Global de Acesso Aberto (Open Access)**: Como redes federadas de repositórios e bases de dados abertas sustentam a reprodutibilidade científica mundial e democratizam o acesso ao conhecimento avançado, mitigando assimetrias entre o Norte e o Sul Global.

---

## 1. Contexto e Objetivos de Estudo

### Finanças Quantitativas e Aprendizado de Máquina
A modelagem clássica de apreçamento de ativos e alocação de portfólios tradicionalmente fundamentou-se no princípio da parcimônia (preferência por modelos simples de poucos fatores, como CAPM ou Fama-French) para evitar a inflação de variância em amostras historicamente limitadas. No entanto, o mercado financeiro é um sistema adaptativo de segundo grau, altamente ruidoso e não linear. 

Este estudo investiga a transição paradigmática para a **Teoria de Apreçamento por Inteligência Artificial (AIPT)**, em que o SDF é modelado de forma profunda e não linear. Demonstramos como modelos estatísticos altamente complexos (redes recorrentes híbridas como VLSTM, xLSTM, e modelos estruturados como TFT) são capazes de extrair alfas robustos fora da amostra, apresentando uma "virtude da complexidade" quando submetidos a uma regularização apropriada.

### O Ecossistema de Acesso Aberto (Open Access)
Nenhum avanço em inteligência artificial aplicada ou finanças quantitativas seria sustentável ou verificável sem a infraestrutura da **Ciência Aberta**. A reprodutibilidade dos backtests, a auditoria de modelos contra overfitting ou vazamento de dados (*data leakage*) e o desenvolvimento de "modelos universais" de ML dependem de bases de dados científicas e relatórios técnicos disponíveis de forma irrestrita. 

Analisamos como plataformas como **SciELO**, **RedALyC**, **Oasisbr**, **RCAAP** e **Zenodo** estruturam metadados (Dublin Core, DataCite) e utilizam identificadores persistentes (DOIs, dARK) para conectar sistemas internacionais de fomento (como a FCT em Portugal e o CNPq/CAPES no Brasil) à comunidade global de pesquisadores.

### Objetivos do Estudo
* **Objetivo Geral**: Investigar a previsibilidade de retornos financeiros transversais (*cross-sectional returns*) e o desempenho de portfólios baseados em modelos de Machine Learning de alta dimensionalidade, analisando de forma concomitante como o ecossistema global de Acesso Aberto viabiliza a reprodutibilidade e a transferência dessa tecnologia científica.
* **Objetivos Específicos**:
  1. Comparar empiricamente o desempenho de algoritmos de ML (lineares regularizados, ensembles de árvores de decisão, redes neurais profundas e redes recorrentes avançadas) sob atritos reais de mercado (*slippage* e custos de transação).
  2. Mapear a rede de repositórios e indexadores de metadados de Acesso Aberto que suportam a disseminação global de pré-prints e códigos abertos.
  3. Avaliar criticamente o impacto real das políticas de publicação em Acesso Aberto na qualidade acadêmica do Sul Global versus o resto do mundo.
  4. Desenvolver e documentar técnicas de Engenharia de Prompts para interações avançadas de revisão de literatura científica.

---

## 2. Curadoria das 34 Fontes Utilizadas

Este caderno temático foi estritamente fundamentado em **34 fontes científicas e plataformas institucionais de alta credibilidade**, divididas estrategicamente em duas grandes frentes de pesquisa:

### Frente A: Aprendizado de Máquina, Finanças Quantitativas e Séries Temporais (14 Fontes)

1. **Guia Introdutório de Aprendizado de Máquina Aplicado aos Mercados Financeiros: Fundamentos, Modelos, Evidências e Limitações** [Markdown]
   * *Relevância*: Base conceitual e matemática do caderno financeiro. Abrange desde a formulação teórica do SDF até a virtude da complexidade, atritos reais (slippage) e protocolos point-in-time de validação.
2. **The Virtue of Complexity in Return Prediction - Yale Department of Economics** [PDF]
   * *Relevância*: Estudo seminal de Bryan Kelly e colaboradores. Demonstra de forma teórica (com matrizes aleatórias) e empírica a utilidade de modelos de alta dimensionalidade (RFF) e o fenômeno de duplo declínio.
3. **NBER Working Paper Series - Financial Machine Learning (Bryan T. Kelly & Dacheng Xiu, Working Paper 31502)** [PDF]
   * *Relevância*: Compilação abrangente do estado da arte de ML financeiro, integrando a representação de fatores contábeis profundos com dados textuais alternativos de NLP e LLMs.
4. **Deep Learning for Financial Time Series: A Large-Scale Benchmark of Risk-Adjusted Performance - University of Oxford** [URL]
   * *Relevância*: Benchmark massivo avaliando o desempenho de trading sistemático de 2010 a 2025. Compara arquiteturas LSTM, xLSTM, VLSTM, TFT, Mamba e PatchTST sob custos de transação.
5. **FinTSBridge: A New Evaluation Suite for Real-world Financial Prediction with Advanced Time Series Models - arXiv** [URL]
   * *Relevância*: Suite de avaliação de modelos de previsão temporal avançados (iTransformer, TimesNet, Koopa) em índices globais (GSMI) e dados de criptomoedas de alta frequência.
6. **Large and Deep Factor Models - arXiv** [PDF]
   * *Relevância*: Investiga o comportamento e a decomposição aditiva de redes neurais profundas na modelagem do SDF por meio do operador de Kernel Tangente de Portfólio (PTK).
7. **Evaluating the Performance of Machine Learning Algorithms in Financial Market Forecasting: A Comprehensive Survey - arXiv** [PDF]
   * *Relevância*: Meta-análise sistemática que extrai 2085 valores de performance de 225 experimentos individuais na literatura de previsão de equities, FX, ETFs e derivativos.
8. **Deep learning models for price forecasting of financial time series: A review of recent advancements: 2020-2022 - arXiv** [PDF]
   * *Relevância*: Revisão sistemática focando em modelos híbridos de Deep Learning (CNN-BiLSTM-ECA, CNN-GRU) para tratamento de ruído em equities e ativos de alta frequência.
9. **Evaluating the Effectiveness of Machine Learning Models in Predicting Stock Returns: A Comparative Analysis of Traditional and Advanced Techniques - Editorial - IMIST** [PDF]
   * *Relevância*: Estudo comparativo de modelos lineares regularizados (Lasso, Ridge, Elastic Net) versus modelos não paramétricos baseados em árvores (Random Forest, GBDTs) no Dow Jones.
10. **Intelligent Financial Forecasting with Granger Causality and Correlation Analysis Using Bayesian Optimization and Long Short-Term Memory - MDPI** [URL]
    * *Relevância*: Modelo híbrido que utiliza Causalidade de Granger para seleção de features contábeis e otimização Bayesiana para hiperparâmetros de redes LSTM em ações chinesas.
11. **Temporal Data Meets LLM - Explainable Financial Time Series Forecasting - arXiv** [URL]
    * *Relevância*: Aborda a aplicação de LLMs na previsão de séries temporais financeiras e como mitigar de forma estrita o vazamento de informações futuras (*lookahead bias*).
12. **Financial Time Series Forecasting with Deep Learning : A Systematic Literature Review: 2005-2019 - Semantic Scholar** [URL]
    * *Relevância*: Levantamento histórico do desenvolvimento e consolidação de redes neurais e algoritmos sequenciais aplicados a mercados financeiros globais.
13. **Neural Networks for Financial Time Series Forecasting - PMC - NIH** [URL]
    * *Relevância*: Análise estatística de dados financeiros de alta frequência, focando nas propriedades de estacionariedade de retornos em relação a preços nominais.
14. **DOĞUŞ ÜNİVERSİTESİ DERGİSİ - DergiPark** [PDF]
    * *Relevância*: Estudo de equities globais aplicando amostragem por cross-validation espacial e temporal em 15.000 ações de 31 países, analisando feature importance.

### Frente B: Acesso Aberto, Repositórios, Literacia Digital e Metadados (20 Fontes)

15. **Mapeamento Global de Fontes de Informação de Acesso Aberto: Infraestruturas de Pesquisa, Motores de Busca Acadêmicos, Repositórios de Dados e Metodologias de Recuperação Digital** [Markdown]
    * *Relevância*: Fundamento conceitual sobre Ciência Aberta. Estrutura a categorização de repositórios e detalha os critérios de literacia digital (CRAAP, SIFT, CCOW).
16. **Impact of Open Access Policy on Brazilian Science and Global Trends - SciELO / Anais da Academia Brasileira de Ciências** [URL]
    * *Relevância*: Estudo estatístico exaustivo por Figueiredo et al. (2024). Utiliza Path Analysis e Decision Trees (SAS) para analisar o impacto do OA de forma isolada sobre a qualidade e impacto (CNCI) da ciência brasileira.
17. **open access, scholarly journals, and regional innovations - SciELO (CLACSO)** [PDF]
    * *Relevância*: Obra "Made in Latin America" por Alperin & Fischman. Discute paradoxos de avaliação acadêmica, o modelo de financiamento público não-comercial e o perigo de "cercamento" comercial de periódicos.
18. **ROLE OF OPEN ACCESS IN THE EMERGENCE AND CONSOLIDATION OF REFEREED JOURNALS IN LATIN AMERICA AND THE CARIBBEAN PAPEL DEL ACCESO - Dialnet** [PDF]
    * *Relevância*: Estudo de Jorge Delgado Troncoso sobre a consolidação e crescimento de periódicos científicos de arbitragem científica na América Latina com suporte das redes regionais.
19. **Oasisbr - Portal Brasileiro de Publicações e Dados Científicos** [URL]
    * *Relevância*: Agregador nacional brasileiro gerido pelo Ibict que centraliza a produção científica em acesso aberto, integrando o identificador persistente e descentralizado dARK.
20. **About - Zenodo** [URL]
    * *Relevância*: Portal institucional do Zenodo, repositório multidisciplinar livre do CERN e OpenAIRE, detalhando a arquitetura aberta baseada no software de gerenciamento InvenioRDM.
21. **The free, open repository from OpenAIRE and CERN - Zenodo** [PDF]
    * *Relevância*: Ficha técnica com diretrizes de publicação do Zenodo, limites de 50 GB por upload, atribuição automática de DOIs e indexação em redes de monitoramento de fomento europeu.
22. **Open Access in Portugal | EURAXESS** [URL]
    * *Relevância*: Apresentação da política nacional de acesso aberto de Portugal, detalhando o papel de fomento da FCT e a obrigatoriedade de depósito no RCAAP para o reembolso de projetos.
23. **RCAAP - Scientific Open Access Repositories of Portugal - EOSC Association** [URL]
    * *Relevância*: Portal central dos Repositórios Científicos de Acesso Aberto de Portugal, integrado à infraestrutura da Nuvem Europeia de Ciência Aberta (EOSC).
24. **OpenAIRE API integration in RCAAP - Portuguese Open Access Repositories** [URL]
    * *Relevância*: Documentação técnica da integração da API REST do OpenAIRE no RCAAP para o enriquecimento em lote de metadados de financiamento público em repositórios institucionais DSpace.
25. **SciELO Colombia- Scientific Electronic Library Online** [URL]
    * *Relevância*: Plataforma colombiana consorciada que adota o modelo e a marcação XML baseada no padrão SciELO Publishing Schema para interoperabilidade de metadados.
26. **Scientific Electronic Library Online - SciELO Argentina** [URL]
    * *Relevância*: Portal nacional argentino gerido pelo CAICYT-CONICET que aplica critérios rígidos de excelência científica baseados no Núcleo Básico de Periódicos.
27. **Scientific Electronic Library Online - SciELO México** [URL]
    * *Relevância*: Portal mexicano de periódicos em acesso aberto mantido pela Direção Geral de Bibliotecas da UNAM e financiado pelo CONACYT.
28. **Scholarly Metadata Search Engines Compared - CASRAI** [URL]
    * *Relevância*: Guia comparativo aprofundado dos principais indexadores de metadados acadêmicos (OpenAlex, Dimensions, Google Scholar, CORE, BASE, Semantic Scholar) para fins de relatórios científicos e CRIS.
29. **The best academic search engines [Update 2025] - Paperpile** [URL]
    * *Relevância*: Levantamento prático e estatísticas de cobertura dos principais motores de busca científicos alternativos (BASE, CORE, Science.gov, RefSeek).
30. **Top 10 Best Academic Search Engines for Scholarly Articles in 2026 - Elephas** [URL]
    * *Relevância*: Avaliação de ferramentas de busca científica e integradores de dados multidisciplinares, incluindo JSTOR e Science.gov.
31. **Top Semantic Scholar Alternatives - Sourcely** [URL]
    * *Relevância*: Comparativo de assistentes de pesquisa baseados em IA (Sourcely, Elicit, Scispace, Scholarcy, ResearchFlow) com recursos de tabelas dinâmicas e mapas conceituais.
32. **Open Access Databases - Digi-Face** [URL]
    * *Relevância*: Banco de dados de recursos de acesso aberto voltados para o aprimoramento digital e de pesquisa na comunidade científica africana.
33. **Freely Accessible databases - KU Libraries - The University of Kansas** [URL]
    * *Relevância*: Catálogo estruturado de bases de dados acadêmicas gratuitas compilado pela Universidade do Kansas.
34. **Services Open Access Repositories - Amherst College** [URL]
    * *Relevância*: Diretório de repositórios gerais e disciplinares de dados científicos de acesso aberto, recomendados por agências de fomento internacionais.

---

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documentamos como utilizamos as técnicas de engenharia de prompts de forma estratégica para extrair informações de alto nível das nossas fontes, bem como os desafios de alinhamento lógico que superamos (as "cicatrizes" de troubleshooting).

### 🛡️ Cicatriz 1: Duplo Declínio (*Double Descent*) vs. Dogma da Parcimônia
* **Objetivo do Prompt**: Investigar como a "virtude da complexidade" contradiz o paradigma tradicional de parcimônia em finanças.
* **Variações Testadas**:
  1. *Vaga*: *"O que é a virtude da complexidade em finanças?"*
  2. *Refinada*: *"Com base no estudo de Bryan Kelly (Yale), como o fenômeno do duplo declínio (double descent) explica que modelos com mais parâmetros explicativos (P) que observações (T), ou seja, P > T, conseguem obter maior Sharpe ratio fora da amostra sem sofrer de overfitting destrutivo?"*
* **Troubleshooting (A "Cicatriz")**: Inicialmente, a IA respondia utilizando o conceito tradicional de viés-variância, afirmando que modelos grandes sofrem *overfitting* de forma inevitável. Tivemos que ajustar o prompt para guiar a IA de forma direcionada a analisar o **mecanismo de encolhimento de Ridge (regularização L2)**. O Ridge atua como um limitador de variância que, na zona sobreparamétrica, "limpa" a variância explosiva, permitindo que a IA extraísse a resposta matematicamente fundamentada nas fontes: sob Ridge adequado, o erro decresce na zona sobreparamétrica e o Sharpe ratio fora da amostra aumenta estritamente de forma contínua (o chamado "declínio benigno").

### 🛡️ Cicatriz 2: Desconstrução do Impacto Linear do Acesso Aberto no Sul Global
* **Objetivo do Prompt**: Avaliar se a publicação em revistas de Acesso Aberto (OA) melhora de forma linear o impacto e as citações de pesquisadores brasileiros.
* **Variações Testadas**:
  1. *Vaga*: *"O acesso aberto ajuda a ciência do Brasil a ser mais citada?"*
  2. *Refinada*: *"Com base na Path Analysis (calis) e na Decision Tree (hpsplit) do artigo de Figueiredo et al. (2024), descreva quais são os caminhos estatísticos que de fato geram um Category Normalized Citation Impact (CNCI) maior que 1 para autores brasileiros, detalhando o papel do OA versus a publicação em jornais Q1 ou do Norte Global."*
* **Troubleshooting (A "Cicatriz")**: A IA tentava adotar uma posição "sifônica", assumindo uma postura excessivamente otimista de que as políticas públicas de Acesso Aberto geram maior impacto acadêmico em qualquer lugar de forma linear. Tivemos que forçar a leitura do modelo de **Path Analysis do estudo real brasileiro** no SAS. A cicatriz foi registrar que, embora o OA correlacione-se positivamente com métricas de qualidade para autores mundiais, **o OA de forma isolada teve impacto estatisticamente nulo na ciência brasileira**. A árvore de decisão provou que o fator decisivo para a visibilidade nacional é a **publicação em jornais Q1 (Top Quartile) do Norte Global**, independentemente de serem abertos ou fechados. Esse troubleshooting demonstrou a importância de analisar dados estatísticos concretos das fontes em vez de repetir pressupostos genéricos do mercado.

---

## 4. Miniguia de Estudo (Entrega Final)

Este miniguia consolida as principais descobertas teóricas do caderno temático para servir de material para estudos e revisões futuras.

### A. Resumos Estruturados do Assunto

#### 1. SDF e Teoria de Apreçamento por IA (AIPT)
* **Condição de Otimalidade**: O apreçamento de qualquer ativo $i$ no tempo $t$ satisfaz a equação fundamental de Euler:
  $$E[M_{t+1} R_{i,t+1} | I_t] = 1$$
  Onde $M_{t+1}$ é o **Fator de Desconto Estocástico (SDF)**. Sob a representação clássica da Teoria de Apreçamento por Arbitragem (APT), assume-se que o SDF é uma função linear de um número limitado de fatores macroeconômicos e fundamentais.
* **A Transição para a AIPT**: A Teoria de Apreçamento por IA (AIPT) estabelece que os retornos dos ativos são explicados por um **número massivo e latente de características não lineares** geradas por modelos profundos de ML.
* **A Decomposição PTK**: Em redes neurais profundas (DNN), a estimação do SDF pode ser decomposta aditivamente. Quando otimizadas via gradiente descendente, essa dinâmica linearizada é descrita pelo **Kernel Tangente de Portfólio (PTK)**, gerando o chamado *PTK-SDF*, que se comporta como a carteira de Markowitz de uma coleção massiva de fatores latentes, superando sistematicamente as DNNs clássicas em Sharpe Ratio.

#### 2. Modelagem Avançada de Séries Temporais Financeiras
* **Limitações de LSTMs Clássicas**: A arquitetura recorrente padrão LSTM com portões sigmoides e retropropagação temporal decai exponencialmente em horizontes longos e falha em modelar interações transversais (*cross-sectional*) entre diferentes ativos.
* **Arquiteturas Recorrentes Híbridas (A Fronteira do Benchmark de Oxford de 2026)**:
  * **VLSTM (VSN + LSTM)**: Acopla uma rede de seleção de variáveis (VSN) para eliminação de dados ruidosos antes do processamento temporal da LSTM. Obteve o maior Sharpe ratio global (2.39-2.40) no estudo empírico de Oxford.
  * **xLSTM (sLSTM/mLSTM)**: Introduz portas exponenciais adaptativas e memória de matriz de armazenamento chave-valor. Destacou-se como o modelo com a maior resiliência a custos de transação (*highest breakeven transaction cost*) devido à eficiência no turnover.
  * **LPatchTST**: Híbrido que segmenta séries temporais em patches antes de aplicar mecanismos de autoatenção local, garantindo máxima estabilidade intertemporal pós-2020.
* **Tratamento de Ruído Estocástico**: Modelos híbridos que aplicam **Decomposição de Modo Variacional (VMD)** ou **Denoising Wavelet** para segmentar as séries em subfrequências de tendência (médio prazo) e ruído caótico (alta frequência) superam sistematicamente os modelos *standalone* puros.

#### 3. Atritos de Mercado e a Fronteira Eficiente Implementável
* **A Falácia da Acurácia Pura**: Um algoritmo preditivo com alto R² ou excelente Acurácia Direcional pode se tornar severamente deficitário na produção real caso ignore atritos reais de execução, como **slippage** (diferença entre o preço esperado de envio e o preço executado da ordem) e o impacto de mercado quadrático decorrente de ordens volumosas.
* **Fronteira Eficiente Implementável**: Incorpora atritos operacionais e custos de transação diretamente no processo de otimização de portfólio de ML. Modelos de alta rotatividade (*turnover*) que não utilizam buffers de custos operacionais tendem a colapsar, enquanto modelos robustos (como o xLSTM e o iTransformer) minimizam o turnover sistemático de rebalanceamento.

#### 4. Literacia de Dados e Avaliação de Credibilidade de Fontes
Para navegar com segurança na abundância de fontes científicas de dados contidos nas redes de Acesso Aberto, o pesquisador deve dominar três metodologias de literacia de dados:
* **Teste CRAAP**: Foca na leitura vertical e critérios internos do documento (Moeda, Relevância, Autoridade, Exatidão, Propósito). Útil para triagem inicial de fontes.
* **Método SIFT**: Foca na leitura lateral e verificação externa e ágil (Parar, Investigar a fonte, Encontrar melhor cobertura, Rastrear afirmações). Essencial para desmascarar biografias falsas ou veículos de desinformação esteticamente impecáveis.
* **Teste CCOW & Metacognição**: Une Credenciais, Afirmações e Objetivos à análise crítica da **Visão de Mundo (Worldview)**. Exige que o próprio pesquisador pratique a metacognição, avaliando se sua concordância com determinada teoria científica decorre do rigor metodológico das evidências ou apenas do seu viés de confirmação pessoal e político.

---

### B. Glossário de Conceitos Essenciais

1. **Fator de Desconto Estocástico (SDF)**: Variável aleatória (taxa marginal de substituição intertemporal) utilizada para precificar ativos trazendo fluxos de caixa futuros a valor presente ajustado pelo risco.
2. **Virtude da Complexidade (VoC)**: Premissa científica de que, sob regularização estatística rígida (como Ridge), o desempenho preditivo fora da amostra e o Sharpe Ratio crescem estritamente conforme a complexidade e densidade de parâmetros explicativos se elevam na zona sobreparamétrica ($P > T$).
3. **Duplo Declínio (*Double Descent*)**: Fenômeno de generalização em que o erro de teste diminui inicialmente, atinge um pico destrutivo no ponto de interpolação ($P pprox T$) e volta a cair na zona sobreparamétrica ($P > T$).
4. **Teoria de Apreçamento por IA (AIPT)**: Estrutura teórica em que o SDF e os retornos dos ativos são explicados por um conjunto massivo de fatores latentes gerados de forma profunda e não linear por modelos de ML.
5. **Kernel Tangente de Portfólio (PTK)**: Operador matemático em redes neurais de gradiente descendente que separa o aprendizado de características não lineares da regra de consolidação de portfólio.
6. **dARK (Decentralized Archival Resource Key)**: Identificador persistente de objetos digitais (PID) descentralizado baseado em blockchain, focado em baixo custo e resiliência de metadados científicos para o Sul Global.
7. **CRAAP**: Método tradicional de avaliação de fontes de informação focado em critérios internos (leitura vertical): *Currency, Relevance, Authority, Accuracy, Purpose*.
8. **SIFT**: Método moderno de fact-checking na internet focado em leitura lateral e de contexto externo: *Stop, Investigate, Find, Trace*.
9. **CCOW**: Método de literacia informacional focado em metacognição e autoconsciência de vieses: *Credentials, Claims, Objectives, Worldview*.
10. **Decomposição de Modo Variacional (VMD)**: Algoritmo de processamento de sinais que divide séries temporais financeiras não estacionárias em subfrequências estáveis de sinal e ruído.
11. **Slippage**: Atrito operacional de mercado caracterizado pela diferença entre o preço esperado de uma ordem e o preço real pelo qual a transação é efetivamente executada na bolsa.
12. **Modelos Universais de ML**: Algoritmos de aprendizado de máquina treinados de forma agregada e unificada sobre dados contábeis empilhados transversalmente (*cross-sectional*) de múltiplos ativos do mercado, mitigando o overfitting decorrente de amostras individuais locais pequenas.
13. **Modelos Point-in-Time**: Modelos preditivos calibrados estritamente com o histórico temporal purgado retroativamente de qualquer informação futura (*lookahead bias*), utilizando checkpoints sinápticos restritos ao passado cronológico do backtest.
14. **msIC (Mean Sequential Correlation)**: Métrica que avalia a correlação linear sistemática entre a trajetória da série prevista e os retornos reais, garantindo a captura de momentum e reversão do mercado.

---

### C. Biblioteca de Prompts Reutilizáveis

Abaixo estão disponibilizados **5 prompts de nível avançado (PhD/Cientista Sênior)** para você copiar e utilizar diretamente em suas futuras investigações e estudos autônomos no Gemini Notebook:

#### 📊 Prompt 1: Modelagem e Validação Cruzada Point-in-Time
```text
Atue como um cientista de dados financeiros sênior especializado em sistemas de negociação automatizados de alta frequência. Desenvolva um guia metodológico detalhado, em prosa técnica, demonstrando como projetar e estruturar um pipeline de validação cruzada walk-forward point-in-time para previsões de retornos transversais diários em um grande universo de ações. Explique detalhadamente como purgar o viés de lookahead em dados corporativos contábeis anunciados retroativamente e como implementar regras para garantir que nenhuma informação futura seja integrada no treinamento das redes de forma não-intencional.
```

#### 🧠 Prompt 2: Otimização de Arquiteturas Híbridas e Filtragem de Ruído
```text
Atue como um pesquisador de nível PhD em engenharia financeira e inteligência computacional. Explique com o mais alto nível de detalhamento metodológico o processo de desenho de uma arquitetura híbrida de previsão de séries financeiras caóticas combinando Variational Mode Decomposition (VMD) com uma rede de seleção de variáveis conectada a uma xLSTM. Descreva detalhadamente o mecanismo de decomposição espectral, a formulation da perda do modelo e o processo de ajuste de hiperparâmetros necessários para que a arquitetura filtre as frequências ruidosas sem destruir a estrutura de causalidade temporal intrínseca das tendências.
```

#### 💼 Prompt 3: Implementação de Carteiras sob a Teoria AIPT e Kernel de Tangência
```text
Você é um diretor de investimentos quantitativos focado em arbitragem sistemática no mercado global de ações. Elabore um estudo técnico detalhado sobre a aplicação empírica da Teoria de Apreçamento por Inteligência Artificial (AIPT) na construção do Fator de Desconto Estocástico (SDF). Demonstre detalhadamente como usar o Kernel Tangente de Portfólio (PTK) para realizar a decomposição aditiva das representações de características não lineares aprendidas por redes profundas e explique o processo matemático de mapeamento do SDF ótimo sob a forma de um Grande Modelo de Fatores regularizado por Ridge em alta dimensionalidade.
```

#### 🔍 Prompt 4: Auditoria de Backtesting e Identificação de Overfitting
```text
Atue como um auditor de modelos estatísticos em um grande fundo de hedge quantitativo. Desenvolva um roteiro completo de auditoria para avaliar se um algoritmo preditivo que reportou desempenho histórico excepcional em testes teóricos sofre de viés de sobreajuste acumulado (data-snooping) ou overfitting implícito. O roteiro deve orientar detalhadamente como estressar o modelo contra perturbações de ruído, como simular testes de significância robustos ao acaso e como avaliar a consistência direcional do sinal através de métricas alternativas como msIC e msIR sob condições extremas de transições de regime de mercado.
```

#### 📈 Prompt 5: Modelagem de Portfólio sob Custos de Fricção e Impacto de Mercado
```text
Você é um estrategista de portfólio sênior em uma gestora quantitativa de ativos globais. Elabore uma análise teórica e metodológica demonstrando como integrar o impacto de mercado quadrático e o slippage dependente do tamanho da ordem diretamente dentro de um estimador de otimização de portfólio acoplado a previsões não lineares geradas por aprendizado de máquina. Explique como construir a formulação matemática da 'fronteira eficiente implementável' resultante e de que forma o modelo preditivo deve ajustar suas previsões para reduzir a rotatividade dispendiosa de carteira sem perder a captura de alfas sistemáticos de mercado.
```

---

## 5. Como Contribuir e Licenciamento

### Como Rodar o Projeto Localmente
Para garantir a reprodutibilidade científica da Ciência Aberta, este repositório está estruturado para uso com o docker-container e ambiente local.
1. Clone o repositório: `git clone https://github.com/SEU_USUARIO/meu-projeto.git`
2. Instale as dependências quantitativas do ecossistema Python 3.12:
   ```bash
   pip install pandas numpy scikit-learn openpyxl pypdf matplotlib
   ```
3. O roteiro detalhado de estudos acadêmicos e código dos backtests está documentado em `repositorio-nota-10.md`.

### Licença de Uso Aberto
Este projeto está licenciado sob a licença pública **MIT License**, garantindo que todo o código, metadados e metodologias permaneçam como um bem comum público e aberto para novos aprimoramentos e inovações pela comunidade global.
