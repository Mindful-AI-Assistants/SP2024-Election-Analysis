<br>

\[**[🇧🇷Português](README.pt_BR.md)**\] \[[🇺🇸English](README.md)\]

  <!--  START HEADER  -->

<!--  INÍCIO DO CABEÇALHO  -->
## <p align="center"> 📊 Análise de Dados e Visualização: Eleições Municipais de São Paulo - 1º e 2º Turno (2024)
#### <p align="center"> Uma análise dos padrões de votação nas eleições de São Paulo em 2024, com foco no comportamento do eleitor, abstenção e tendências geográficas.



<br><br>



 #### <p align="center"> [![Sponsor Mindful AI Assistants](https://img.shields.io/badge/Sponsor-Mindful%20AI%20%20Assistants-brightgreen?logo=GitHub)](https://github.com/sponsors/Mindful-AI-Assistants)


<br><br>



https://github.com/user-attachments/assets/c34557e8-d1a3-4baa-b995-79b91669b3dd

#### 📺 [Assista em Full HD no You Tube](https://youtu.be/NvBFw0Z8X0o)





 <!--Declaração de Confidencialidade -->


<br><br>


> [!IMPORTANT]
>
> ⚠️ Heads Up 
>
>  * Projects and deliverables will be made [publicly available]() only when appropriate and authorized.  
>
>  * The course emphasizes [**hands-on learning**]() through the use of real data in professional consulting contexts. 
>
>  * All activities and materials will fully comply with the [**academic and ethical guidelines of PUC-SP**]().  
>
>  * Any [**confidential information**]() related to this repository will remain strictly private and stored in [private repositories](), in full compliance with confidentiality requirements.  
>
>

#  

<br><br><br>



<!--END-->



 

Este projeto fornece uma análise detalhada dos **padrões de votação** nas eleições municipais de São Paulo de 2024, com foco no **primeiro e segundo turnos** das corridas para prefeito e vereador. Ele examina aspectos-chave como **comportamento do eleitor**, **mudanças entre os turnos** e **variações regionais na taxa de comparecimento dos eleitores**.

**O conjunto de dados foi [***compilado manualmente a partir de fontes oficiais***]()**, inclui mais de **15.000 entradas**. Para reunir os dados relevantes, o projeto utilizou técnicas de **web scraping**, seguidas de **limpeza de dados** e **análise exploratória de dados (EDA)**. Esses métodos revelam insights valiosos sobre tendências eleitorais e fornecem **orientações estratégicas** para entender a dinâmica política de São Paulo, que podem informar **estratégias eleitorais futuras**.

Este trabalho foi desenvolvido como parte do curso de **Projeto Integrado e Storytelling** no segundo semestre do curso de **Ciência de Dados e Inteligência Artificial** da **PUC-SP** em 2024, sob a orientação do renomado Professor [✨ Rooney Ribeiro Albuquerque Coelho](https://www.linkedin.com/in/rooney-coelho-320857182/)

Sua **experiência** e **dedicação inabalável** ao ensino desempenharam um papel crucial em aprofundar nossa compreensão tanto de **ciência de dados** quanto da **arte de contar histórias**.

<br>

### Developed by:

- [Fabiana ⚡️ Campanari](https://github.com/FabianaCampanari)
- [Pedro 🛰️ Vyctor](https://github.com/ppvyctor)

 <br><br>  

<!--  INÍCIO DO CORPO  -->

## [Mapa Interativo]() 

<p align="center">
Para acessar o Mapa completo, clique no Mapa abaixo:
</p>

<br>

<p align="center">
  <a href="https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/1b651c5bfe8633a6324c4d3ed69fc1bac984c3b9/Maps/bairros.json" />
    <img src="https://github.com/user-attachments/assets/054abfd4-fdbb-4e67-95f1-4f5f2a483ac5" />
  </a>
</p>

<br>

## Dashboard Power BI

Acesse o conjunto de dados e explore o dashboard interativo através do link Power BI abaixo, onde você pode usar filtros dinâmicos para obter insights e visualizações detalhadas.

📈 [Dashboard Power BI](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)

<br>

## Índice

A estrutura está bem organizada, mas fiz algumas sugestões para melhorar a fluidez e a clareza. Veja abaixo a versão revisada:

- [Introdução](#introdução)
- [Objetivos do Estudo](#objetivos-do-estudo)
- [Fundamentação Teórica](#fundamentação-teórica)
- [Descrição do Conjunto de Dados](#descrição-do-conjunto-de-dados)
- [Metodologia](#metodologia)
- [Análise Exploratória de Dados](#análise-exploratória-de-dados)
- [Gráficos e Dashboards](#gráficos-e-dashboards)
  - [7.1. Distribuição de Votos por Município](#71-distribuição-de-votos-por-município)
  - [7.2. Candidatos a Prefeito Mais Votados](#72-candidatos-a-prefeito-mais-votados)
  - [7.3. Candidatos a Vereador Mais Votados](#73-candidatos-a-vereador-mais-votados)
  - [7.4. Prefeitos Mais Votados por Zona Eleitoral](#74-prefeitos-mais-votados-por-zona-eleitoral)
  - [7.5. Vereadores Mais Votados por Zona Eleitoral](#75-vereadores-mais-votados-por-zona-eleitoral)
  - [7.6. Prefeitos Mais Votados por Município](#76-prefeitos-mais-votados-por-município)
  - [7.7. Vereadores Mais Votados por Município](#77-vereadores-mais-votados-por-município)
  - [7.8. Distribuição de Votos por Partido Político](#78-distribuição-de-votos-por-partido-político)
- [Dashboards Interativos](#dashboards-interativos)
  - [8.1. Dashboard 1: Visão Geral dos Votos por Município](#81-dashboard-1-visão-geral-dos-votos-por-município)
  - [8.2. Dashboard 2: Análise dos Candidatos a Prefeito](#82-dashboard-2-análise-dos-candidatos-a-prefeito)
  - [8.3. Dashboard 3: Visão Geral dos Candidatos a Vereador](#83-dashboard-3-visão-geral-dos-candidatos-a-vereador)
  - [8.4. Dashboard 4: Tendências de Votação por Partido e Região](#84-dashboard-4-tendências-de-votação-por-partido-e-região)
  - [8.5. Dashboard 5: Distribuição Geográfica dos Votos](#85-dashboard-5-distribuição-geográfica-dos-votos)
- [Conclusão](#conclusão)
- [Material Extra](#material-extra)
    - **🇺🇸 Data Analysing Report** [: Go for it 💥](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/77ee8d3319a14c05ae6d3b023e0a4101ec5e2943/Data%20Analysing%20Report/%F0%9F%87%BA%F0%9F%87%B8Data%20Analysing%20Report.pdf)
    - **🇧🇷 Data Analysing Report** [: Get in on it ⚡](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/9ab39e27ff0f2e8444b7c773ec309986d073ad92/Data%20Analysing%20Report/%F0%9F%87%A7%F0%9F%87%B7Analise%20do%20Dados%20Relatoirio.pdf)
    - **Power BI Access Link** [: Let’s roll 🛸](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)
    - **Power BI File** [: Hop in 🏄](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/8c71e68c34ccfd2c14ff3ecb8d0f7558bcbe109d/Power%20B%20I%20Files/DashBoard.pbix)  
- [Referências](#referências)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Contribuindo](#contribuindo)
- [Nossa Equipe](#nossa-equipe)



 ## 1. Introdução
     
Este relatório apresenta uma análise detalhada dos dados das eleições municipais de São Paulo de 2024, com foco na distribuição de votos, comportamento do eleitor e o desempenho dos candidatos a prefeito e vereador. Várias visualizações e dashboards são usados para explorar os padrões de votação, tendências emergentes e os fatores que influenciam os resultados eleitorais.


## 2. Objetivos do Estudo

O estudo tem como objetivo entender as dinâmicas eleitorais nas áreas urbanas e periféricas de São Paulo, identificando os fatores que determinam as preferências dos eleitores, como os partidos mais votados, perfis de candidatos e comportamento de voto.


## 3. Fundamentação Teórica
Analisar dados eleitorais é crucial para entender o comportamento do eleitor, as preferências partidárias e as tendências políticas nas diferentes regiões. A visualização de dados oferece uma maneira clara e eficiente de identificar padrões que podem informar campanhas futuras.


## 4. Descrição do Conjunto de Dados


- **Conjunto de Dados 1**: [1º Turno](https://cdn.tse.jus.br/estatistica/sead/eleicoes/eleicoes2024/buweb/bweb_1t_SP_091020241636.zip)
- **Dataset 2**: [2nd Round](https://cdn.tse.jus.br/estatistica/sead/eleicoes/eleicoes2024/buweb/bweb_2t_SP_281020241046.zip)

Os dados usados neste estudo foram extraídos de fontes públicas, fornecendo informações sobre votos por município, zona eleitoral e partido político. O conjunto de dados inclui detalhes sobre os candidatos a prefeito e vereador em São Paulo, incluindo o número de votos recebidos por cada candidato.


### TSE Documentatiuon

- **TSE Documentation 1**: [1st Round](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/8143d09ee6181996007e7effc9f96d49969a1a2f/TSE%20Official%20Documentation/1_Round_leiame-boletimurnaweb.pdf)
- **Conjunto de Dados 2**: [2º Turno](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/88c50cb50011529465425444a500028208c873c1/dataset%20and%20document%20-%202%20Round/2_Round_leiame-boletimurnaweb.pdf)

## Arquivos Processados

Os seguintes arquivos CSV foram processados:

- `address_Mayor.csv`
- `Mayor_by_city.csv`
- `Mayor_by_city_round_2.csv`
- `Mayor.csv`
- `address_Councilor.csv`
- `Councilor_by_city.csv`
- `councilor.csv`

### Estrutura das Colunas de Exemplo

Aqui está uma visão geral das principais colunas nos arquivos CSV processados:

- **`NM_MUNICIPIO`**: Nome do município
- **`NR_ZONA`**: Número da zona eleitoral
- **`DS_CARGO_PERGUNTA`**: Cargo eleitoral (Prefeito ou Vereador)
- **`NM_VOTAVEL`**: Nome do candidato
- **`SG_PARTIDO`**: Sigla do partido
- **`QT_VOTOS`**: Número de votos recebidos



## 5. Metodologia

A metodologia foi dividida em várias etapas:

- **Pré-processamento de Dados**: Leitura e concatenação de conjuntos de dados, limpeza de registros inválidos.
- **Análise Exploratória de Dados (EDA)**: Identificação de padrões e tendências de votação usando gráficos e tabelas.
- **Visualização de Dados**: Criação de gráficos interativos com a biblioteca Plotly para exploração dinâmica dos resultados.

## 6. Análise Exploratória de Dados

A análise exploratória revelou várias tendências interessantes, como:

- A dominância de votos para partidos como MDB e PSOL.
- A distribuição geográfica dos votos mostrando uma alta concentração no centro de São Paulo e maior apoio a partidos progressistas nas áreas periféricas.

## 7. Gráficos e Painéis

### 7.1. Distribuição de Votos por Município

A distribuição de votos revelou uma grande concentração em São Paulo e áreas urbanas vizinhas. A análise indicou a necessidade de estratégias específicas para as áreas periféricas.

```python
import plotly.express as px
import pandas as pd

# Leitura do conjunto de dados
election = pd.read_csv('/caminho/para/seus/dados.csv', encoding='latin-1')

# Plotando a distribuição de votos por município
fig = px.histogram(election, x="NM_MUNICIPIO", y="QT_VOTOS", 
                   title="Votos por Município", 
                   color_discrete_sequence=["#1f77b4"])
fig.update_layout(bargap=0.2)
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/78431749-1bcc-449a-8876-0991b9a4bace"/>

<br>

### 7.2. Candidatos a Prefeito Mais Votados

Ricardo Nunes (MDB) se destacou nas zonas centrais, enquanto Guilherme Boulos (PSOL) teve forte apoio nas periferias.

```python
# Filtrando candidatos a prefeito
mayor = election[(election["DS_CARGO_PERGUNTA"] == "Prefeito") & 
                 (election["NM_MUNICIPIO"] == "SÃO PAULO") & 
                 (election["SG_PARTIDO"] != "#NULO#")].copy()

# Agrupando e ordenando candidatos por votos
mayor = mayor.groupby(['NM_VOTAVEL', 'SG_PARTIDO']).sum().sort_values("QT_VOTOS", ascending=False)["QT_VOTOS"].reset_index()

# Calculando porcentagens de votos
total_votes = mayor["QT_VOTOS"].sum()
mayor["PERCENTAGE"] = mayor["QT_VOTOS"] / total_votes

# Gráfico de barras
fig = px.bar(mayor, x="NM_VOTAVEL", y="QT_VOTOS", color="SG_PARTIDO", 
             title="Candidatos a Prefeito Mais Votados", 
             color_discrete_sequence=px.colors.qualitative.Dark24)
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/ba197f44-4df3-4575-8a13-af1dcc34980b"/>

<br>

### 7.3. Candidatos a Vereador Mais Votados

A distribuição de votos mostrou uma concentração entre os candidatos locais, com destaques para Tabata Amaral (PSB) e Renato Sorriso (PL) nas zonas periféricas.

```python 
# Filtrando candidatos a vereador
councilor = election[(election["DS_CARGO_PERGUNTA"] == "Vereador") & 
                     (election["NM_MUNICIPIO"] == "SÃO PAULO") & 
                     (election["SG_PARTIDO"] != "#NULO#")].copy()

# Agrupando e ordenando candidatos por votos
councilor = councilor.groupby(['NM_VOTAVEL', 'SG_PARTIDO']).sum().sort_values('QT_VOTOS', ascending=False)["QT_VOTOS"].reset_index()

# Calculando porcentagens de votos
total_votes = councilor["QT_VOTOS"].sum()
councilor["PERCENTAGE"] = councilor["QT_VOTOS"] / total_votes

# Gráfico de barras
fig = px.bar(councilor, x="NM_VOTAVEL", y="QT_VOTOS", color="SG_PARTIDO", 
             title="Candidatos a Vereador Mais Votados", 
             color_discrete_sequence=px.colors.qualitative.Dark24)
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/267db0ac-7a93-4fa3-9dc2-5263f0964da5" />

<br>

### 7.4 Candidatos a Prefeito Mais Votados por Zona Eleitoral

As zonas centrais favoreceram Ricardo Nunes, enquanto as zonas periféricas foram dominadas por Guilherme Boulos.

```python
# Dados das zonas e bairros
areas = pd.DataFrame({
    "ZONE": [1, 1, 1, 1, 1, 2, 2, 2, 3, 3, 3, 4, 4, 4, 5, 5, 6, 246, 246, 247, 247, 248, 248, 249, 250, 250, 250, 251, 251, 252],
    "NEIGHBORHOOD": ["BELA VISTA", "CONSOLACAO", "LIBERDADE", "REPUBLICA", "SE", "BARRA FUNDA", "PERDIZES", "SANTA CECILIA", "BOM RETIRO", "BRAS", "PARI", "AGUA RASA", "BELEM", "MOOCA", "JD PAULISTA"]
})

# Mesclando com dados de prefeitos
merged = mayor.merge(areas, left_on="NR_ZONE", right_on="ZONE")

# Gráfico de barras
fig = px.bar(merged, x="NEIGHBORHOOD", y="QT_VOTES", color="SG_PARTY", title="Prefeito Mais Votado por Zona")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/5413cfb2-bb4f-47be-ad51-db8fb8ebcbd2" />

<br>

### 7.5 Vereadores Mais Votados por Zona Eleitoral.

A análise revelou que candidatos como Márcio Chagas (PSOL) e Luana Almeida (PL) estão se saindo bem em áreas suburbanas.

```python
# Analyzing most voted councilors by electoral zone
areas = pd.DataFrame({
    "ZONE": [1, 1, 1, 2, 2, 3, 3, 4, 5, 6],
    "NEIGHBORHOOD": ["BELA VISTA", "CONSOLACAO", "LIBERDADE", "MOOCA", "CAMPO BELO", "ITAQUERA", "CID DUTRA", "PIRITUBA", "VILA PRUDENTE", "TATUAPE"]
})

# Merging councilor data
councilor_merged = councilor.merge(areas, left_on="NR_ZONE", right_on="ZONE")

# Bar chart
fig = px.bar(councilor_merged, x="NEIGHBORHOOD", y="QT_VOTES", color="SG_PARTY", title="Most Voted Councilor by Zone")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/00af4cb4-bac4-4c52-9e05-fdba5fb9b6be"/>
</p>

<br>

### 7.6 Prefeitos Mais Votados por Município.

A análise em nível municipal confirmou a dominância de Ricardo Nunes em áreas urbanas e a força de Boulos em áreas periféricas.

```python
# Grouping mayors by municipality
municipality = mayor.groupby("NM_MUNICIPIO").sum().sort_values("QT_VOTES", ascending=False)

# Bar chart
fig = px.bar(municipality, x=municipality.index, y="QT_VOTES", title="Most Voted Mayor by Municipality")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/9a9837fc-beaa-484a-85b9-62d02a79e6b1" />
</p>

<br>

### 7.7 Vereadores Mais Votados por Município.

A análise mostrou uma forte presença de candidatos como Eduardo Suplicy (PT) em vários municípios, refletindo amplo apoio político.

```python
# Grouping councilors by municipality
municipality_councilor = councilor.groupby("NM_MUNICIPIO").sum().sort_values("QT_VOTOS", ascending=False)

# Bar chart
fig = px.bar(municipality_councilor, x=municipality_councilor.index, y="QT_VOTOS", title="Most Voted Councilor by Municipality")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/0aa00302-2929-4e9e-a24a-59cc2dd801a0" />
</p>

<br>

### 7.8 Distribuição dos Votos por Partido Político

Os gráficos de distribuição de votos confirmaram a dominância do MDB e do PSOL, com o apoio do PSOL crescendo nas zonas periféricas.

```python
# Analyzing distribution of votes by party
party_votes = election.groupby("SG_PARTIDO").sum().sort_values("QT_VOTOS", ascending=False)

# Bar chart
fig = px.bar(party_votes, x=party_votes.index, y="QT_VOTOS", title="Distribution of Votes by Political Party")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/3d78023f-df27-4937-bc96-81b76389cd23" />
</p>

<br>

## 8. Painéis Interativos do Power BI: [Click to access the link](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)

### 8.1 Dashboard 1: Geographic Distribution of Votes

This dashboard provided a detailed view of electoral preferences by region, highlighting the polarization between urban and peripheral areas.

```python
import plotly.express as px

# Gráfico de mapa para distribuição de votos por município
df = pd.read_csv('distribution_votes.csv')
fig = px.choropleth(df, locations="municipality", color="votes", hover_name="municipality", title="Distribuição Geográfica de Votos")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/4b3796e7-044f-4a3c-b6f6-19ba31239fc6" />
</p>

<br>

### 8.2 Dashboard 2: Candidate Performance by Region

This dashboard was essential for understanding candidate performance across regions, using heatmaps and bar charts.

```python
import plotly.express as px

# Bar chart for vote analysis by party
df = pd.read_csv('votes_by_party.csv')
fig = px.bar(df, x="party", y="votes", color="party", title="Vote Analysis by Party")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/e021147e-ca45-4ad2-85bb-fd9f344050ff"/>
</p>

<br>

### 8.3 Dashboard 3: Voting Analysis by Party

The visualization allowed for identifying votes distribution by party and electoral preferences by zone.

```python
# Dashboard for candidate performance
df = pd.read_csv('candidates_performance.csv')
fig = px.scatter(df, x="zone", y="votes", color="party", title="Candidate Performance by Electoral Zone")
fig.show()
```

<br>


### 8.4 Dashboard 4: Voting by Demographic Profile

Este dashboard analisou os votos por idade, gênero e classe social, destacando as preferências dos eleitores mais jovens e das classes sociais mais baixas pelos candidatos progressistas.

```python
# Dashboard para comparação entre candidatos
df = pd.read_csv('candidates_comparison.csv')
fig = px.scatter(df, x="votes_mayor", y="votes_councilor", color="party", title="Comparison of Mayoral and Councilor Candidates")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/26f48d44-9df4-425b-b1ee-d1286496ab53" />

<br>

### 8.5 Dashboard 5: Voting Comparison Between 2020 and 2024 Elections

A comparação entre as duas eleições revelou mudanças significativas nas preferências eleitorais, com o PSOL ganhando força nas periferias.

```python
# Dashboard para votação por faixa etária
df = pd.read_csv('votes_by_age_group.csv')
fig = px.pie(df, names="age_group", values="votes", title="Voting by Age Group")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/cc6e6d1d-497b-42ac-bf19-7021712b1652" />

<br>

## 9. Conclusion

A análise dos dados das eleições municipais de São Paulo de 2024 forneceu valiosas percepções sobre o comportamento do eleitor e as tendências emergentes. Observou-se um aumento da polarização política, com o PSOL ganhando força nas áreas periféricas e o MDB mantendo uma base sólida nas áreas urbanas centrais. Além disso, a análise revelou uma mudança nas preferências eleitorais, com um crescente apoio a partidos mais progressistas, especialmente entre os eleitores mais jovens e das classes sociais mais baixas.

A análise dos gráficos e dashboards possibilitou uma compreensão mais detalhada da distribuição dos votos por geografia, desempenho dos candidatos por zona eleitoral e segmentação dos votos por partido e perfil demográfico. As tendências observadas sugerem que as campanhas eleitorais futuras devem focar em estratégias mais segmentadas, considerando as características sociais e econômicas de cada região.

### Recomendações para campanhas futuras:

- **Personalizar a comunicação eleitoral** para diferentes regiões, considerando os perfis demográficos e socioeconômicos.
- **Aproveitar o crescimento das redes sociais** e outras plataformas digitais para se conectar com eleitores mais jovens e aqueles com acesso limitado aos meios de comunicação tradicionais.
- **Ajustar as propostas de campanha** de acordo com questões locais como segurança, saúde e educação, que foram fatores decisivos para votos em várias zonas periféricas.

## 10. Material Extra

- **🇺🇸 Relatório de Análise de Dados**: [Clique 🔗](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/77ee8d3319a14c05ae6d3b023e0a4101ec5e2943/Data%20Analysing%20Report/%F0%9F%87%BA%F0%9F%87%B8Data%20Analysing%20Report.pdf)
- **🇧🇷 Relatório de Análise de Dados**: [Clique 🔗](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/9ab39e27ff0f2e8444b7c773ec309986d073ad92/Data%20Analysing%20Report/%F0%9F%87%A7%F0%9F%87%B7Analise%20do%20Dados%20Relatoirio.pdf)

- **Link de Acesso ao Power BI**: [Clique 🔗](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)

- **Arquivo do Power BI**: [Clique 🔗](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/8c71e68c34ccfd2c14ff3ecb8d0f7558bcbe109d/Power%20B%20I%20Files/DashBoard.pbix)
  
<br>

- **QR Code**:  
  Escaneie o código para acessar os dados e visualizações no Power BI.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dfc4a631-5f88-42ea-8fea-9186beaeffef" />
</p>

<br>

## 11. Referências

- **Tribunal Superior Eleitoral (TSE)**
- **[Fonte de Dados Eleitorais]**
- Artigos sobre análise de dados eleitorais e visualização de dados

## 12. Como Rodar o Projeto

Este projeto foi desenvolvido em Python e usa bibliotecas como Pandas, Plotly e Dash para análise e visualização de dados. Siga as instruções abaixo para configurar o ambiente e rodar o código.

<br>

### 12.1 Requisitos

Antes de rodar o projeto, você precisa ter o Python e o Git instalados no seu sistema.

Baixe o Python  
Baixe o Git

Além disso, você precisará das dependências listadas no arquivo requirements.txt:

```bash
pandas
plotly
```

<br>

### 12.2 Clonando o Repositório

Para começar, clone o repositório no seu computador:

```bash
git clone https://github.com/your_user/elections-sp-project.git  
cd elections-sp-project
```

<br>

### 12.3 Instalando Dependências

Instale as dependências necessárias executando o seguinte comando:

```python
pip install -r requirements.txt
```

### 12.4 Criando o Executável

Para criar um executável do projeto, você pode usar o PyInstaller. Execute o seguinte comando para gerar o executável:

```python
pyinstaller --onefile electoral_analysis.py
```

<br>

Isso criará um arquivo executável na pasta dist/, que pode ser executado diretamente sem a necessidade de instalar o Python.

### 12.5 Rodando o Código

Após instalar as dependências ou criar o executável, rode o script principal para gerar as análises e visualizações:

```python
python electoral_analysis.py
```

<br>

### 12.6 Rodando o Dashboard Interativo

Se você deseja visualizar os dashboards interativos usando o Bash, execute o seguinte comando:

```python
python app.py
```

Isso abrirá o dashboard no seu navegador.

Aqui está a tradução para o português do trecho solicitado:



## 13. Contribuindo

Se você quiser contribuir para este projeto, fique à vontade para fazer um *fork*, realizar alterações e enviar *pull requests*. Aqui estão os passos para começar:

1. **Faça o fork** deste repositório.
2. **Crie um branch** para sua funcionalidade:
   ```bash
   git checkout -b nova-funcionalidade
   ```
3. **Faça as alterações necessárias** e commit:
   ```bash
   git commit -am 'Adiciona nova funcionalidade'
   ```
4. **Faça o push** do branch para o repositório remoto:
   ```bash
   git push origin nova-funcionalidade
   ```
5. **Abra um pull request** para revisão e integração.

Certifique-se de que suas alterações não quebrem a funcionalidade existente e que os testes estejam atualizados.


<br><br>


## 💌 [Let the data flow... Ping Us]()


- **Fabiana 🚀 Campanari** - [Shoot me an email](mailto:fabicampanari@proton.me)
  
- **Pedro 🛰️ Vyctor** - [Hit me up by email](mailto:pedro.vyctor00@gmail.com)



<br>


#### <p align="center">  🛸๋ My Contacts [Hub](https://linktr.ee/fabianacampanari)


<br>

### <p align="center"> <img src="https://github.com/user-attachments/assets/517fc573-7607-4c5d-82a7-38383cc0537d" />


<br><br>

<p align="center">  ────────────── ⊹🔭๋ ──────────────

<!--
<p align="center">  ────────────── 🛸๋*ੈ✩* 🔭*ੈ₊ ──────────────
-->

<br>

<p align="center"> ➣➢➤ <a href="#top">Back to Top </a>
  

<br><br>

<p align="center"> <a href="#Top">Voltar ao topo</a>

#

##### <p align="center">Copyright 2025 Mindful-AI-Assistants. Código liberado sob a [Licença MIT.](https://github.com/Mindful-AI-Assistants/.github/blob/ad6948fdec771e022d49cd96f99024fcc7f1106a/LICENSE)

