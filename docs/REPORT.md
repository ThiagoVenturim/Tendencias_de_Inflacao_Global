 # Análise Comparativa das Tendências de Inflação Global (2015-2024): Impactos, Disparidades Regionais e Eventos Econômicos
---


**Integrantes:**

* **Rafael Silvestre da Silva, rafaelsilvestres03@gmail.com**

* **Pedro Dias Soares**, **pedro3soares@gmail.com** / **pdsoares@sga.pucminas.br**

* **Thales Ribeiro Melo, thales.melo@sga.pucminas.br**

* **Thiago Domingos Venturim RIbeiro dos Santos, thiagodomingosventutim@gmail.com/ tdvrsantos@sga.pucminas.br**
  


---

**Professores e Assistentes:**

* **Prof. Hugo Bastos de Paula**

* **Prof. Hayala Nepomuceno Curto**

* **Kenia Aparecida Caires Cardoso**


---

_Curso de Ciência de Dados, Unidade Praça da Liberdade_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

_**Resumo:** O trabalho analisou a inflação global entre 2015 e 2024, contextualizando o impacto de eventos econômicos marcantes como a pandemia de COVID-19 e a guerra na Ucrânia sobre diferentes países e regiões. O objetivo central foi comparar a inflação projetada para 2024 com a média histórica da década anterior, identificando padrões, disparidades regionais e fatores explicativos, como políticas monetárias e choques externos. A análise exploratória dos dados revelou uma forte persistência inflacionária em países com histórico de inflação elevada, especialmente na América Latina e África. Um resultado relevante foi a identificação de que políticas monetárias restritivas ajudaram a conter a inflação em alguns países, enquanto outros permaneceram vulneráveis a choques globais. Esses achados reforçam a importância de respostas econômicas coordenadas para promover a estabilidade de preços e reduzir desigualdades regionais._


----

   <h3 align="center"><strong> SUMARIO </strong></h3>
   
[1. Introdução](#Introdução)   

[2. Contextualização](#Contextualização)

[3. Problema](#Problema)

[4. Pergunta Direcionada a Dados](#Pergunta_Direcionada_a_Dados)

[5. Hipóteses](#Hipóteses)

[6. Objetivos](#Objetivos)

[7.Justificativas ](#Justificativas)

[8. Público alvo](#Público_alvo)

[9. Preparação dos dados](#Preparação_dos_dados)

[10. Análise exploratórida dos dados](#Análise_exploratórida_dos_dados)

[11. Resultados ](#Resultados)

[12. Analise Critica](#Analise_Critica)

[12. Conclusão ](#Conclusão)

[13. Referências ](#REFERÊNCIAS)

[14. Apêndices](#APÊNDICES)



*******
<div id='Introdução'/>  

 <h3 align="center"><strong> Introdução </strong></h3>
 
 Escolhemos a base [*Global Inflation Data (1980-2024)*](https://www.kaggle.com/datasets/sazidthe1/global-inflation-data) para o tema "Análise Comparativa das Tendências de Inflação Global (2015-2024): Impactos, Disparidades Regionais e Eventos Econômicos". Essa base é particularmente relevante para investigar como diferentes regiões do mundo enfrentaram a inflação na última década, especialmente diante de eventos econômicos marcantes como a pandemia de COVID-19, a guerra na Ucrânia, flutuações nos preços das commodities e as políticas monetárias adotadas em resposta às crises. 
 
 [Base de Dados Completa](/data/DataSet/Raw_Data/SetGlobal_Inflation_Data.csv)

---

<div id='Contextualização'/>  

   <h3 align="center"><strong> Contextualização </strong></h3>
   
A inflação, medida pelo aumento contínuo dos preços de bens e serviços, é um dos principais indicadores da saúde econômica de um país. No entanto, suas causas e consequências variam amplamente de acordo com fatores estruturais, geopolíticos, fiscais e monetários. Entre 2015 e 2024, o mundo vivenciou eventos sem precedentes que impactaram significativamente a estabilidade econômica global. A pandemia de COVID-19, por exemplo, provocou rupturas nas cadeias de suprimento e mudanças abruptas na demanda e nos gastos públicos, pressionando os preços em muitos setores. Posteriormente, a guerra entre Rússia e Ucrânia acentuou a volatilidade nos preços de energia e alimentos, afetando sobretudo países dependentes de importações.

Além disso, a resposta monetária dos bancos centrais – como o aumento das taxas de juros para conter a inflação – teve efeitos variados em diferentes contextos nacionais, exacerbando desigualdades regionais. Países desenvolvidos, emergentes e em desenvolvimento enfrentaram cenários distintos em termos de inflação acumulada, capacidade de resposta institucional e resiliência social. Em meio a esse panorama, torna-se essencial realizar uma análise comparativa que não apenas destaque as tendências gerais da inflação, mas também revele as disparidades entre regiões, níveis de renda e modelos econômicos.

Com esse foco, o período de 2015 a 2024 oferece um campo fértil para investigações sobre os impactos das políticas econômicas, a influência de choques externos e a capacidade de adaptação das economias nacionais. A inflação, além de ser um fenômeno econômico, tornou-se um problema político e social central, afetando diretamente o poder de compra das populações, a estabilidade de governos e a confiança nos sistemas financeiros.


---

<div id='Problema'/>  
  <h3 align="center"><strong>  Problema </strong></h3>
	
Apesar de a inflação ser um fenômeno econômico amplamente monitorado, sua manifestação prática, causas e efeitos variam significativamente entre países e regiões, especialmente em contextos marcados por choques econômicos globais e crises prolongadas. Entre 2015 e 2024, o mundo passou por uma sucessão de eventos disruptivos – como a pandemia de COVID-19, tensões geopolíticas (como a guerra na Ucrânia), crises energéticas e alimentares, além de variações abruptas nas políticas monetárias. Esses eventos impactaram de maneira desigual os países, revelando vulnerabilidades estruturais, diferentes níveis de resiliência econômica e disparidades regionais na capacidade de resposta à inflação.

O problema que buscamos compreender é: "Como a taxa de inflação projetada para 2024 se compara com a média histórica de inflação dos últimos 10 anos (2015–2023) em países com dados disponíveis?"

---
<div id='Pergunta_Direcionada_a_Dados'/>  
    <h3 align="center"><strong>  Pergunta Direcionada a Dados  </strong></h3>
	
**Como a taxa de inflação projetada para 2024 se compara com a média histórica de inflação dos últimos 10 anos (2015–2023) em países com dados disponíveis?**


---
<div id='Hipóteses'/>  
    <h3 align="center"><strong> Hipóteses </strong></h3>

Persistência estrutural: países com altos índices de inflação entre 2015 e 2023 tendem a manter projeções elevadas para 2024.

Vulnerabilidade regional: países localizados na América Latina, África e partes da Ásia apresentarão as maiores projeções de inflação, refletindo maior exposição a choques externos.

Impacto de políticas monetárias: países que adotaram políticas restritivas (ex.: aumento de juros) após a pandemia tendem a ter inflação projetada mais baixa em 2024.

Efeitos de eventos globais: países com forte dependência de commodities ou importações devem exibir variações inflacionárias associadas à pandemia e à guerra na Ucrânia.



  
---

<div id='Objetivos'/>  
   <h3 align="center"><strong> Objetivo geral  </strong></h3> 
	
Analisar comparativamente a inflação projetada para 2024 em relação à média inflacionária do período de 2015 a 2023, com foco em identificar variações significativas, padrões regionais e possíveis implicações econômicas.

---

   <h3 align="center"><strong> Objetivos específicos   </strong></h3> 
   
* Calcular a média das taxas de inflação anuais para cada país entre 2015 e 2023.

* Comparar essa média com a taxa projetada de inflação para o ano de 2024.

* Identificar países com variações significativas (altas ou quedas abruptas) na projeção para 2024.

* Classificar os países por região a fim de observar padrões ou disparidades regionais.

* Analisar possíveis correlações entre a variação inflacionária e eventos econômicos globais recentes, como a pandemia de COVID-19, crises energéticas e políticas monetárias restritivas.
 
---

<div id='Justificativas'/>  
	
   <h3 align="center"><strong> Justificativas  </strong></h3> 
   
 A inflação é um dos indicadores mais sensíveis e relevantes para avaliar a saúde econômica de uma nação. Alterações abruptas em sua trajetória podem sinalizar problemas estruturais, choques externos ou mudanças significativas na política econômica. A década entre 2015 e 2023 foi marcada por eventos que colocaram à prova a estabilidade econômica global: crises econômicas em mercados emergentes, a pandemia de COVID-19, rupturas nas cadeias de suprimentos, choques nos preços de energia e alimentos, além de respostas variadas por parte de governos e bancos centrais.

Neste cenário, a projeção de inflação para 2024 torna-se um termômetro importante para medir a recuperação ou persistência de desequilíbrios em diferentes economias. Comparar essa projeção com a média da década anterior permite identificar se os países estão caminhando para a estabilização, se enfrentam riscos de superaquecimento ou deflação, ou se seguem expostos a choques recorrentes.

Além disso, a análise comparativa revela quais regiões ou perfis econômicos apresentam maior volatilidade inflacionária, podendo indicar fragilidades sistêmicas ou ineficiência das políticas econômicas adotadas. Ao destacar os países com maiores variações projetadas, a investigação contribui para uma leitura crítica dos rumos da economia mundial, oferecendo subsídios para formuladores de políticas públicas, analistas de risco, investidores e pesquisadores.

Essa abordagem orientada por dados, focada em projeções e médias históricas, combina simplicidade analítica com alto potencial de interpretação estratégica — reforçando a relevância de uma análise empírica baseada em evidências para compreender o presente e antecipar o futuro da inflação globa

---

<div id='Público_alvo'/>  
    <h3 align="center"><strong>  Público alvo   </strong></h3> 

O público-alvo desta pesquisa são os países que apresentam as maiores taxas de inflação, especialmente aqueles que evidenciam variações significativas entre a média histórica (2015–2023) e a projeção para 2024. Esses países representam casos críticos para análise devido ao impacto mais intenso que a inflação exerce sobre suas economias, sociedades e políticas públicas.

Focar nos países com maior inflação permite compreender as causas subjacentes e as consequências desse fenômeno em contextos diversos, desde economias emergentes até algumas desenvolvidas que enfrentam desafios específicos. Esses países são geralmente mais vulneráveis a choques externos, como flutuações nos preços de commodities, crises cambiais ou instabilidades políticas, e costumam apresentar maior sensibilidade a políticas monetárias restritivas ou expansivas.

Além disso, o estudo desses países possibilita a identificação de padrões regionais e estruturais, bem como a avaliação da eficácia das respostas adotadas para mitigar os efeitos da inflação elevada. Esse entendimento é crucial para que formuladores de políticas, organismos internacionais, investidores e instituições financeiras possam desenvolver estratégias adequadas para promover a estabilidade econômica e social nesses contextos.

Portanto, a pesquisa é particularmente relevante para países que enfrentam desafios inflacionários severos, buscando fornecer insights que auxiliem na formulação de medidas que visem à contenção da inflação, à proteção do poder de compra da população e à promoção do crescimento sustentável.

---

<div id='Preparação_dos_dados'/>  
 <h3 align="center"><strong> Preparação dos dados  </strong></h3> 

### Dicionario de Dados:
O conjunto de dados fornece informações organizadas por país, ano, tipo de indicador e taxa de inflação média anual. Essa estrutura permite comparar como a inflação se comportou em diferentes locais ao longo do tempo e sob diferentes circunstâncias. Ao focarmos nos anos de 2015 a 2024, podemos observar a transição de um período de relativa estabilidade para um cenário de incerteza e rápida transformação econômica. A base possibilita também a identificação de tendências setoriais (como inflação de alimentos ou energia) e a construção de análises que considerem tanto aspectos quantitativos quanto qualitativos das políticas macroeconômicas.


| Nome da Coluna     | Tipo de Dado         | Descrição                                                                 | Classificação               |
|--------------------|----------------------|---------------------------------------------------------------------------|-----------------------------|
| `country_name`     | string               | Nome do país.                                                             | Categórica nominal          |
| `indicator_name`   | string               | Nome do indicador econômico. Nesse caso, sempre "Annual average inflation (consumer prices) rate". | Categórica nominal          |
| `1980` a `2024`    | float (numérico)     | Taxa média anual de inflação para o respectivo ano (em %).               | Quantitativa contínua       |


Estrutura do Conjunto de Dados
O arquivo global_inflation_data.csv contém as seguintes colunas:

`Country`: Nome do país

`Indicator`: Tipo de indicador de inflação (ex.: inflação geral, inflação de alimentos, etc.)

`Year`: Ano da medição (de 1980 a 2024)

`Inflation Rate`: Taxa de inflação média anual (%)

Essa estrutura, embora simples, oferece um panorama robusto que permite realizar análises temporais, geográficas e setoriais, fornecendo um suporte valioso para investigações sobre causas, consequências e estratégias de enfrentamento da inflação em diferentes contextos nacionais e regionais.

[Visualização dos Dados da Tabela](/code/DataSet_Dictionary/Dicionario_de_Dados.ipynb)

[Dicionário de Dados ](/others/Data_Dictionary.md)


### Limpeza e Tratamento da Base de Dados: 

---
<div id='Análise_exploratórida_dos_dados'/>  
  <h3 align="center"><strong>  Análise exploratórida dos dados  </strong></h3>
	
*Importância da Análise Exploratória de Dados (AED) no Contexto do Tema e Pergunta Orientada*:A Análise Exploratória de Dados (AED) é fundamental para responder à pergunta orientada "Como a taxa de inflação projetada para 2024 se compara com a média histórica de inflação dos últimos 10 anos (2015–2023) em países com dados disponíveis?", pois:

**A AED não apenas responde à pergunta orientada, mas também direciona o foco para casos críticos, contextualiza causas e apoia recomendações políticas. Ao combinar estatísticas descritivas, visualizações e correlações, ela transforma dados brutos em insights acionáveis, essenciais para formuladores de políticas e investidores em um cenário econômico volátil.**


[Codigo da Analise Exploratoria](/code/Exploratory_Analysis_Code/Code_Exploratory_Data_Analysis.ipynb)

	
[Resultados](/others/Exploratory_Analysis.md)


<div id='Resultados'/>  

## **Resultados**

### 1. Matriz de Correlação

![Matrix de Correlação](https://github.com/user-attachments/assets/3e24d311-6ac7-47bc-b7ef-f073085e8a22)

**Objetivo:** Identificar a relação entre variáveis como inflação projetada para 2024, inflação acumulada e médias históricas anuais.

**Descrição:** A matriz evidencia uma **correlação positiva forte** entre a inflação acumulada na década e a projeção para 2024.

**Resultado:** Países que sofreram com alta inflação no passado tendem a continuar enfrentando esse desafio, sugerindo uma **persistência estrutural** do fenômeno.

---

###  2. Top 10 Inflações Acumuladas (2015–2023)

![Top10\_Inflações\_Acumuladas](https://github.com/user-attachments/assets/10e0f35e-0eed-44f3-ba3d-a5f64b240c3e)

**Objetivo:** Listar os países com maiores níveis acumulados de inflação na última década.

**Descrição:** Venezuela, Argentina e Zimbábue lideram com **inflações extremas**, sinalizando colapsos econômicos prolongados.

**Resultado:** Esses casos destacam o impacto de políticas monetárias frágeis, instabilidade institucional e choques severos.

---

###  3. Inflação Média Global (2015–2023)

![Inflação Media Global](https://github.com/user-attachments/assets/c6c8d4ac-7018-4739-ad63-b3684cf78dd3)

**Objetivo:** Observar a tendência global da inflação média ao longo dos anos.

**Descrição:** Estabilidade até 2019, seguida de um aumento expressivo após 2020.

**Resultado:** O aumento coincide com a pandemia de COVID-19 e seus efeitos sobre a oferta e a demanda globais, além das consequências da guerra na Ucrânia.

---

###  4. Mapa de Inflação por País (2024)

![Mapa de Inflação por Pais](https://github.com/user-attachments/assets/1a41cf09-2983-4157-8a78-176de1216ce6)

**Objetivo:** Visualizar a inflação projetada para 2024 em escala global.

**Descrição:** Altos índices concentram-se na América Latina, África e partes da Ásia.

**Resultado:** As projeções revelam **vulnerabilidades regionais persistentes**, com países em desenvolvimento mais expostos a choques externos.

---

### 5. Boxplot Interativo – Distribuição da Inflação por País

![Boxplot Interativo\_ Distribuição da Inflação por País](https://github.com/user-attachments/assets/b5440614-f94b-485b-9401-bfc8b83192a3)

**Objetivo:** Explorar a distribuição estatística da inflação nos países entre 2015 e 2023.

**Descrição:** A maioria dos países apresenta inflação moderada, mas alguns outliers registram picos extremamente altos.

**Resultado:** Evidencia **grande desigualdade entre países**, com alguns enfrentando hiperinflação, enquanto outros mantêm estabilidade.

---

### 6. Gráfico Interativo – Inflação por País e Eventos Econômicos

![Gráfico Interativo de Inflação por País Evento](https://github.com/user-attachments/assets/bca55a59-eaa5-4e51-883f-bef7641458d8)

**Objetivo:** Relacionar picos inflacionários a eventos específicos, como pandemias ou conflitos.

**Descrição:** Alguns países tiveram **saltos claros de inflação** em 2020 (COVID-19) e 2022 (guerra na Ucrânia).

**Resultado:** Mostra como eventos globais afetam **de forma desigual** os países, dependendo da resiliência e estrutura econômica.

---

###  7. Comparação Direta da Inflação Entre Países

![Comparação da Inflação Entre País](https://github.com/user-attachments/assets/42bdc6f6-0254-405d-adeb-bd2b4f65c469)

**Objetivo:** Comparar a inflação média entre países selecionados.

**Descrição:** Países da América do Sul e África apresentam médias muito superiores às nações da Europa ou América do Norte.

**Resultado:** Reforça disparidades regionais e mostra que **estruturas econômicas frágeis** tornam países mais suscetíveis à inflação.

---

### 8. Inflação Média por Continente

![Inflação Media por Continente](https://github.com/user-attachments/assets/a09b2580-53c2-443c-8936-723ce0441148)

**Objetivo:** Observar padrões regionais agregados de inflação.

**Descrição:** África lidera, seguida pela América do Sul. Europa e América do Norte têm as menores médias.

**Resultado:** Indica que **desenvolvimento econômico e estabilidade institucional** influenciam fortemente os níveis inflacionários.

---

### 9. Top 10 Países com Maior Aumento de Inflação em 2024

![Top 10 paises com maior aumento em 2024](https://github.com/user-attachments/assets/b42bcfd7-1cb0-42d8-bf82-3c2b79804704)

**Objetivo:** Identificar países onde a inflação deve crescer mais em 2024, comparado à média anterior.

**Descrição:** Países com inflação projetada muito acima da média histórica recente.

**Resultado:** Pode sinalizar **instabilidade emergente**, choques de mercado ou falhas de controle monetário.

---

###  10. Top 10 Países com Maior Redução de Inflação em 2024

![Top 10 paises com maior e redução em 2024](https://github.com/user-attachments/assets/bb2eadf9-9a90-48d9-b2f5-92318ca9b035)

**Objetivo:** Destacar países onde a inflação projetada está bem abaixo da média anterior.

**Descrição:** Indica processos de estabilização ou recuperação econômica após períodos críticos.

**Resultado:** Países que conseguiram **reverter trajetórias inflacionárias**, sinalizando sucesso em políticas de contenção.

---

###  11. Inflação Projetada (2024) vs Média Histórica (2015–2023)

![Gráfico Interativo\_ Inflação Projetada (2024) vs Média Histórica (2015–2023)](https://github.com/user-attachments/assets/62f1be1f-bf1e-4f77-9539-517d2bf3686f)

**Objetivo:** Comparar diretamente, país por país, a inflação projetada para 2024 com a média histórica da última década.

**Descrição:** Evidencia **desvios positivos e negativos**. Países com grandes variações merecem análise aprofundada.

**Resultado:** Permite **classificar países entre estabilizados, em alerta ou em deterioração**, com base na comparação entre passado e futuro.

---

<div id='Analise_Critica'/>  
	 <h3 align="center"><strong> Análise Crítica  </strong></h3> 
	
**Revisão do Problema e das Hipóteses:**

O problema central do trabalho foi compreender como a inflação projetada para 2024 se compara à média histórica dos últimos 10 anos (2015–2023) e identificar quais fatores explicam as variações observadas entre países e regiões. As hipóteses levantadas abordam persistência estrutural, vulnerabilidade regional, impacto de políticas monetárias e efeitos de eventos globais.

**1. Persistência Estrutural da Inflação**
A análise da matriz de correlação revelou uma forte correlação positiva entre a inflação acumulada no período de 2015 a 2023 e a inflação projetada para 2024. Esse resultado indica que países que enfrentaram níveis elevados de inflação na última década tendem a manter projeções igualmente altas para o próximo ano, evidenciando um comportamento inflacionário persistente e estrutural. Tal persistência é consistente com a literatura econômica que aponta para a existência de uma “memória inflacionária” nas economias, onde choques passados e mecanismos de indexação de preços (como reajustes salariais, contratos e preços administrados) influenciam a dinâmica atual da inflação. Essa persistência pode ser agravada pela perda de credibilidade das políticas monetárias e pela dificuldade em romper ciclos inflacionários, especialmente em países com histórico de instabilidade econômica. Portanto, os dados confirmam que a inflação não é um fenômeno pontual, mas sim um processo que tende a se perpetuar, reforçando a hipótese de persistência estrutural.

**2. Vulnerabilidade Regional**

Os dados evidenciam que países localizados na América Latina (como Venezuela e Argentina), África e partes da Ásia apresentam as maiores taxas acumuladas de inflação e projeções elevadas para 2024. Essa concentração regional sugere que essas áreas são mais vulneráveis a choques externos, como flutuações nos preços de commodities, crises políticas e econômicas internas, além de fragilidades institucionais. A literatura destaca que essas regiões possuem mercados de trabalho menos flexíveis, sistemas financeiros menos desenvolvidos e maior dependência de importações, o que amplifica o impacto de choques globais e limita a eficácia das políticas econômicas. A persistência de inflação elevada nessas regiões também está associada a déficits fiscais crônicos e políticas monetárias menos eficazes, que dificultam o controle dos preços. Assim, os resultados reforçam a hipótese de vulnerabilidade regional, demonstrando que desigualdades estruturais e conjunturais influenciam diretamente a dinâmica inflacionária.


**3. Impacto das Políticas Monetárias**

Embora os gráficos não apresentem diretamente indicadores detalhados sobre políticas monetárias, a análise qualitativa e a comparação entre países indicam que aqueles que adotaram medidas restritivas, como elevação das taxas de juros e controle da oferta monetária após a pandemia, tendem a apresentar projeções de inflação mais moderadas para 2024. Por outro lado, países com políticas monetárias frouxas ou instáveis, como Venezuela e Zimbábue, continuam registrando inflação extremamente alta. Esse padrão está alinhado com a teoria econômica que aponta que políticas monetárias restritivas “esfriam” a economia ao reduzir o consumo e a demanda agregada, contribuindo para a desaceleração da inflação. No entanto, é importante destacar que o impacto dessas políticas pode variar conforme o contexto econômico e a credibilidade das instituições, e que a análise quantitativa mais aprofundada seria necessária para mensurar com precisão essa relação. Ainda assim, os dados qualitativos dão suporte à hipótese de que políticas monetárias restritivas são um fator importante na contenção da inflação.


**4. Efeitos de Eventos Globais**
Os gráficos temporais e as análises indicam um aumento significativo da inflação global a partir de 2020, período que coincide com a pandemia de COVID-19 e, posteriormente, com a guerra na Ucrânia. Esses eventos geraram rupturas nas cadeias de suprimentos, aumentos abruptos nos preços de energia e alimentos, além de mudanças na demanda global. Países fortemente dependentes de commodities ou importações refletem essas oscilações de forma mais intensa, apresentando picos inflacionários mais acentuados. A pandemia causou choques simultâneos de oferta e demanda, enquanto a guerra agravou a volatilidade dos preços internacionais, especialmente de energia, impactando diretamente a inflação doméstica em diversas economias. Portanto, os dados corroboram a hipótese de que eventos globais recentes exerceram papel central na elevação e volatilidade da inflação, destacando a interconectividade das economias e a vulnerabilidade a choques externos.

---

<div id='Conclusão'/>  
	 <h3 align="center"><strong> Conclusão  </strong></h3> 
	
A análise comparativa das tendências de inflação global entre 2015 e 2024 permitiu compreender, de modo abrangente, como diferentes países e regiões foram impactados por choques econômicos, eventos globais e políticas internas ao longo da última década. Ao confrontar a inflação projetada para 2024 com a média histórica dos dez anos anteriores, foi possível identificar padrões de persistência, vulnerabilidades regionais e os efeitos das respostas econômicas adotadas.


Os resultados confirmam que a inflação é, em muitos países, um fenômeno estruturalmente persistente. A matriz de correlação revelou uma forte relação positiva entre a inflação acumulada na década e as projeções para 2024, indicando que economias com histórico inflacionário elevado – como Venezuela, Argentina e Zimbábue – tendem a manter taxas altas, mesmo diante de novos cenários globais. Isso sugere a existência de mecanismos internos, como indexação de preços e falta de credibilidade institucional, que dificultam o rompimento do ciclo inflacionário.

A análise dos Top 10 países com maiores inflações acumuladas evidenciou a concentração de casos críticos na América Latina e África, reforçando a hipótese de vulnerabilidade regional. Essas regiões, marcadas por estruturas econômicas frágeis, dependência de commodities e frequentes instabilidades políticas, mostraram-se mais suscetíveis a choques externos, como variações nos preços internacionais de energia e alimentos.

O estudo também apontou a relevância das políticas monetárias. Países que adotaram medidas restritivas, como elevação de juros e controle da oferta monetária, conseguiram limitar o avanço da inflação projetada para 2024. Em contrapartida, países com políticas monetárias frouxas ou inconsistentes continuam enfrentando inflação elevada, agravando os desafios econômicos e sociais.

Outro ponto central foi o impacto de eventos globais recentes. Os gráficos mostraram que, após um período de relativa estabilidade até 2019, a inflação global disparou a partir de 2020, em resposta à pandemia de COVID-19 e, posteriormente, à guerra na Ucrânia. Esses eventos provocaram rupturas nas cadeias de suprimentos, aumentaram custos de produção e pressionaram os preços de energia e alimentos, afetando especialmente países mais dependentes de importações.

Em síntese, os dados e análises apresentados confirmam as hipóteses iniciais: a inflação global recente resulta da interação entre fatores estruturais internos, vulnerabilidades regionais e choques externos de grande magnitude. Destaca-se, ainda, a importância de políticas econômicas sólidas e coordenadas para mitigar os efeitos da inflação, sobretudo em países mais expostos a riscos sistêmicos.

Por fim, esta análise reforça a necessidade de monitoramento constante, transparência nas políticas públicas e cooperação internacional para enfrentar desafios inflacionários futuros. O estudo contribui para o entendimento das causas e consequências da inflação em diferentes contextos, servindo de subsídio para formuladores de políticas, analistas e pesquisadores interessados na estabilidade econômica global.

---
<div id='REFERÊNCIAS'/>  
   <h3 align="center"><strong> REFERÊNCIAS   </strong></h3> 


*[1]* Kaggle: Global Inflation Dataset- Annual Inflation Rate of 196 Countries (1980-2024)Disponível em: [https://www.kaggle.com/datasets/sazidthe1/global-inflation-data](https://www.kaggle.com/datasets/sazidthe1/global-inflation-data).Acesso em: 06 mai. 2025.


---

<div id='APÊNDICES'/>  
 <h3 align="center"><strong> APÊNDICES  </strong></h3> 

[Drive](https://drive.google.com/drive/folders/1FxsYgWBBPNWUVAd0GjdZ0GcjgJay4qLJ?usp=drive_link)
Visualizar: Base de Dados, Base de dados apos a Limpeza, Graficos em PNG e Graficos em HTML, Codigo que foi utilizado para Limpeza e Analise Exploratoria, Video sobre a explicação dos Graficos e documentação completa.

[Repositorio Git-Hub](https://github.com/ThiagoVenturim/Tendencias_de_Inflacao_Global)
