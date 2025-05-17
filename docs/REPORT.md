 # Análise Comparativa das Tendências de Inflação Global (1980-2024): Impactos, Disparidades Regionais e Eventos Econômicos
---


**Aluno, email**

**Aluno, email**

**Aluno, email**

**Pedro Dias Soares**, **pedro3soares@gmail.com** / **pdsoares@sga.pucminas.br**

**Thiago Domingos Venturim RIbeiro dos Santos, thiagodomingosventutim@gmail.com**


---

**Professores:**

* **Prof. Hugo Bastos de Paula**

* **Prof. Hayala Nepomuceno Curto**

---

_Curso de Ciência de Dados, Unidade Praça da Liberdade_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

_**Resumo**. Escrever aqui o resumo. O resumo deve contextualizar rapidamente o trabalho, descrever seu objetivo e, ao final, 
mostrar algum resultado relevante do trabalho (até 10 linhas)._


*******
   <h3 align="center"><strong> SUMARIO </strong></h3>
   
[1. Introdução](#Introdução)   

[2. Contextualização](#Contextualização)

[3. Problema](#Problema)

[4. Pergunta Direcionada a Dados](#Pergunta_Direcionada_a_Dados)

[5. Objetivos](#Objetivos)

[6.Justificativas ](#Justificativas)

[7. Público alvo](#Público_alvo)

[8. Preparação dos dados](#Preparação_dos_dados)

[9. Análise exploratórida dos dados](#Análise_exploratórida_dos_dados)

[10. Resultados ](#Resultados)

[11. Conclusão ](#Conclusão)

[12. Referências ](#REFERÊNCIAS)

[13. Apêndices](#APÊNDICES)



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

O problema que buscamos compreender é: "Como a taxa de inflação projetada para 2024 se compara com a média histórica de inflação dos últimos 10 anos (2014–2023) em países com dados disponíveis?"

---
<div id='Pergunta_Direcionada_a_Dados'/>  
    <h3 align="center"><strong>  Pergunta Direcionada a Dados  </strong></h3>
	
**Como a taxa de inflação projetada para 2024 se compara com a média histórica de inflação dos últimos 10 anos (2014–2023) em países com dados disponíveis?**



  
---

<div id='Objetivos'/>  
   <h3 align="center"><strong> Objetivo geral  </strong></h3> 
	
Analisar comparativamente a inflação projetada para 2024 em relação à média inflacionária do período de 2014 a 2023, com foco em identificar variações significativas, padrões regionais e possíveis implicações econômicas.

---

   <h3 align="center"><strong> Objetivos específicos   </strong></h3> 
   
* Calcular a média das taxas de inflação anuais para cada país entre 2014 e 2023.

* Comparar essa média com a taxa projetada de inflação para o ano de 2024.

* Identificar países com variações significativas (altas ou quedas abruptas) na projeção para 2024.

* Classificar os países por região a fim de observar padrões ou disparidades regionais.

* Analisar possíveis correlações entre a variação inflacionária e eventos econômicos globais recentes, como a pandemia de COVID-19, crises energéticas e políticas monetárias restritivas.
 
---

<div id='Justificativas'/>  
	
   <h3 align="center"><strong> Justificativas  </strong></h3> 
   
 A inflação é um dos indicadores mais sensíveis e relevantes para avaliar a saúde econômica de uma nação. Alterações abruptas em sua trajetória podem sinalizar problemas estruturais, choques externos ou mudanças significativas na política econômica. A década entre 2014 e 2023 foi marcada por eventos que colocaram à prova a estabilidade econômica global: crises econômicas em mercados emergentes, a pandemia de COVID-19, rupturas nas cadeias de suprimentos, choques nos preços de energia e alimentos, além de respostas variadas por parte de governos e bancos centrais.

Neste cenário, a projeção de inflação para 2024 torna-se um termômetro importante para medir a recuperação ou persistência de desequilíbrios em diferentes economias. Comparar essa projeção com a média da década anterior permite identificar se os países estão caminhando para a estabilização, se enfrentam riscos de superaquecimento ou deflação, ou se seguem expostos a choques recorrentes.

Além disso, a análise comparativa revela quais regiões ou perfis econômicos apresentam maior volatilidade inflacionária, podendo indicar fragilidades sistêmicas ou ineficiência das políticas econômicas adotadas. Ao destacar os países com maiores variações projetadas, a investigação contribui para uma leitura crítica dos rumos da economia mundial, oferecendo subsídios para formuladores de políticas públicas, analistas de risco, investidores e pesquisadores.

Essa abordagem orientada por dados, focada em projeções e médias históricas, combina simplicidade analítica com alto potencial de interpretação estratégica — reforçando a relevância de uma análise empírica baseada em evidências para compreender o presente e antecipar o futuro da inflação globa

---

<div id='Público_alvo'/>  
    <h3 align="center"><strong>  Público alvo   </strong></h3> 

O público-alvo desta pesquisa são os países que apresentam as maiores taxas de inflação, especialmente aqueles que evidenciam variações significativas entre a média histórica (2014–2023) e a projeção para 2024. Esses países representam casos críticos para análise devido ao impacto mais intenso que a inflação exerce sobre suas economias, sociedades e políticas públicas.

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
	
*Importância da Análise Exploratória de Dados (AED) no Contexto do Tema e Pergunta Orientada*:A Análise Exploratória de Dados (AED) é fundamental para responder à pergunta orientada "Como a taxa de inflação projetada para 2024 se compara com a média histórica de inflação dos últimos 10 anos (2014–2023) em países com dados disponíveis?", pois:

1. **Entendimento Inicial dos Dados**: Limpeza e Validação: Identifica valores ausentes (como os 5 valores nulos em 2024 no dataset) e inconsistências, garantindo a confiabilidade das comparações. Descrição Estatística: Calcula médias, desvios padrão e distribuições das taxas de inflação históricas e projetadas, oferecendo uma base quantitativa para comparações.

2.  **Identificação de Variações Significativas**: Outliers - Detecta países com projeções para 2024 drasticamente superiores ou inferiores à média histórica (ex.: Argentina, Turquia ou Zimbábue em cenários hiperinflacionários). Disparidades Regionais: Agrupa países por regiões (ex.: América Latina, Europa, África) para identificar padrões geográficos. Por exemplo, países importadores de energia podem mostrar picos em 2022–2023 devido à guerra na Ucrânia.

3.  **Correlações com Eventos Econômicos**: Eventos Globais- Usa matrizes de correlação (como a gerada com seaborn.heatmap) para vincular aumentos abruptos de inflação a eventos como:

* Pandemia de COVID-19 (2020–2021): Impacto em cadeias de suprimentos e gastos públicos.

* Guerra na Ucrânia (2022): Choques em preços de energia e alimentos.

* Políticas Monetárias: Efeitos de aumentos de juros em países como EUA ou Brasil.

* Análise Temporal: Gráficos de séries temporais revelam tendências (ex.: inflação persistentemente alta em economias emergentes vs. controle em países desenvolvidos).

4. **Classificação de Países Críticos**: Foco no Público-Alvo: Prioriza países com maiores variações (ex.: projeção de 2024 > 2x média histórica), destacando casos como:

* Venezuela: Hiperinflação crônica agravada por sanções.

* Turquia: Queda da moeda e políticas monetárias não convencionais.

* UE/EUA: Pressões pós-pandemia e transição energética.

5. **Subsídios para Interpretação Estratégica**: Padrões Estruturais: Revela se economias dependentes de commodities (ex.: Nigéria, petróleo) são mais vulneráveis a choques externos. Eficácia de Políticas: Compara países que adotaram medidas restritivas (ex.: juros altos) vs. expansionistas, avaliando seu impacto na inflação projetada.


**A AED não apenas responde à pergunta orientada, mas também direciona o foco para casos críticos, contextualiza causas e apoia recomendações políticas. Ao combinar estatísticas descritivas, visualizações e correlações, ela transforma dados brutos em insights acionáveis, essenciais para formuladores de políticas e investidores em um cenário econômico volátil.**


[Codigo da Analise Exploratoria](/code/Exploratory_Analysis_Code/Code_Exploratory_Data_Analysis.ipynb)


	
---


<div id='Resultados'/>  
<h3 align="center"><strong> Resultados  </strong></h3>
	
[Resultados](/others/Exploratory_Analysis.md)

---

<div id='Conclusão'/>  
	 <h3 align="center"><strong> Conclusão  </strong></h3> 


---
<div id='REFERÊNCIAS'/>  
   <h3 align="center"><strong> REFERÊNCIAS   </strong></h3> 


*[1]* Kaggle: Global Inflation Dataset- Annual Inflation Rate of 196 Countries (1980-2024)Disponível em: [https://www.kaggle.com/datasets/sazidthe1/global-inflation-data](https://www.kaggle.com/datasets/sazidthe1/global-inflation-data).Acesso em: 06 mai. 2025.


---

<div id='APÊNDICES'/>  
 <h3 align="center"><strong> APÊNDICES  </strong></h3> 
