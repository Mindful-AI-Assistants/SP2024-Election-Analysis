<br>

 \[[🇧🇷 Português](README.pt_BR.md)\] \[**[🇺🇸 English](README.md)**\]

<br>

  <!--  START HEADER  -->
## <p align="center">    📊 Data Analysis and Visualization: São Paulo Municipal Elections  - 1st and 2nd Round (2024)
#### <p align="center">  [An analysis of voting patterns in São Paulo's 2024 elections](), focusing on voter behavior, absenteeism, and geographic trends.



<br><br>

 #### <p align="center"> [![Sponsor Mindful AI Assistants](https://img.shields.io/badge/Sponsor-Mindful%20AI%20%20Assistants-brightgreen?logo=GitHub)](https://github.com/sponsors/Mindful-AI-Assistants)


 <br><br>


https://github.com/user-attachments/assets/1b17d66f-3fa0-40dc-bfdc-031ca5b703aa

 <br>
 
#### 📺 [Watch in Full HD on YouTube](https://youtu.be/x3A6pHZuOD4)


 <!--Confidentiality Statement -->



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




This project provides an in-depth analysis of **voting patterns** in the 2024 São Paulo municipal elections, with a focus on the **first and second rounds** of mayoral and city council races. It examines key aspects such as **voter behavior**, **shifts between rounds**, and **regional variations in voter turnout**. 

**The dataset was [***manually compiled from official sources***]()** , includes over **15,000 entries**. To gather relevant data, the project employed **web scraping** techniques, followed by **data cleaning** and **exploratory data analysis (EDA)**. These methods uncover valuable insights into electoral trends and provide **strategic guidance** for understanding the political dynamics of São Paulo, which can inform **future election strategies**


This work was developed as part of the **Integrated Project and Storytelling** course in the second semester of the undergraduate program in **Data Science and Artificial Intelligence** at **PUC-SP** in 2024, under the mentorship of the renowned  Professor [✨ Rooney Ribeiro Albuquerque Coelho](https://www.linkedin.com/in/rooney-coelho-320857182/) 

His **expertise** and **unwavering dedication** to teaching played a crucial role in deepening our understanding of both **data science** and the **art of storytelling**.

<br>

### Developed by:

- [Fabiana ⚡️ Campanari](https://github.com/FabianaCampanari)
- [Pedro 🛰️ Vyctor](https://github.com/ppvyctor)


 <br><br>  

<!--  START BODY  -->

## [Interactive Map]() 

#### ➢ [Osint](https://www.myosint.training/courses/introduction-to-osint?ref=f7428c)

#### ➢ [Kepler](https://kepler.gl/demo)

#### ➣ [Shapefiles Geolocation Sao Paulo](https://clubedogis.com.br/download-shapefiles-de-sao-paulo/#:~:text=Descubra%20onde%20encontrar%20e%20como%20fazer)

#### ➢ [Big Query](https://console.cloud.google.com/bigquery?p=basedosdados&d=br_bd_diretorios_brasil&t=area_conhecimento&page=table&project=gen-lang-client-0293405067&ws=!1m9!1m4!4m3!1sbasedosdados!2sbr_bd_diretorios_brasil!3scep!1m3!3m2!1sbasedosdados!2sbr_datahackers_state_data&invt=Abt3Qg)

#### ➣ Click and access the [Full Map](https://kepler.gl/demo/map?mapUrl=https://dl.dropboxusercontent.com/scl/fi/j9043tqmx3f6f43mp2oy9/keplergl_b3rkgfo.json?rlkey=go52o1cgn9t3bgh60lhhlju8n&dl=0)




<br>

<p align="center">
  <a href="https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/1b651c5bfe8633a6324c4d3ed69fc1bac984c3b9/Maps/bairros.json" />
    <img src="https://github.com/user-attachments/assets/054abfd4-fdbb-4e67-95f1-4f5f2a483ac5" />
  </a>
</p>

<br>

## Power BI Dashboard

Access the dataset and explore the interactive dashboard via the Power BI link below, where you can use dynamic filters for detailed insights and visualizations.

📈 [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)


<br>

## Table of Contents

- [Introduction](#introduction)
- [Study Objectives](#study-objectives)
- [Theoretical Background](#theoretical-background)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Charts and Dashboards](#charts-and-dashboards)
  - [7.1. Vote Distribution by Municipality](#71-vote-distribution-by-municipality)
  - [7.2. Most Voted Mayoral Candidates](#72-most-voted-mayoral-candidates)
  - [7.3. Most Voted Councilor Candidates](#73-most-voted-councilor-candidates)
  - [7.4. Most Voted Mayors by Electoral Zone](#74-most-voted-mayors-by-electoral-zone)
  - [7.5. Most Voted Councilors by Electoral Zone](#75-most-voted-councilors-by-electoral-zone)
  - [7.6. Most Voted Mayors by Municipality](#76-most-voted-mayors-by-municipality)
  - [7.7. Most Voted Councilors by Municipality](#77-most-voted-councilors-by-municipality)
  - [7.8. Vote Distribution by Political Party](#78-vote-distribution-by-political-party)
- [Interactive Dashboards](#interactive-dashboards)
  - [8.1. Dashboard 1: Overview of Votes by Municipality](#81-dashboard-1-overview-of-votes-by-municipality)
  - [8.2. Dashboard 2: Mayoral Candidates Analysis](#82-dashboard-2-mayoral-candidates-analysis)
  - [8.3. Dashboard 3: Councilor Candidates Overview](#83-dashboard-3-councilor-candidates-overview)
  - [8.4. Dashboard 4: Voting Trends by Party and Region](#84-dashboard-4-voting-trends-by-party-and-region)
  - [8.5. Dashboard 5: Geographic Distribution of Votes](#85-dashboard-5-geographic-distribution-of-votes)
- [Conclusion](#conclusion)
- [Extra Material](#extra-material)
    - **🇺🇸 Data Analysing Report** [: Go for it 💥](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/77ee8d3319a14c05ae6d3b023e0a4101ec5e2943/Data%20Analysing%20Report/%F0%9F%87%BA%F0%9F%87%B8Data%20Analysing%20Report.pdf)
    - **🇧🇷 Data Analysing Report** [: Get in on it ⚡](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/9ab39e27ff0f2e8444b7c773ec309986d073ad92/Data%20Analysing%20Report/%F0%9F%87%A7%F0%9F%87%B7Analise%20do%20Dados%20Relatoirio.pdf)
    - **Power BI Access Link** [: Let’s roll 🛸](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)
    - **Power BI File** [: Hop in 🏄](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/8c71e68c34ccfd2c14ff3ecb8d0f7558bcbe109d/Power%20B%20I%20Files/DashBoard.pbix)  
- [References](#references)
- [How to Run the Project](#how-to-run-the-project)
- [Contributing](#contributing)
- [Our Team](#our-team)





 ## 1. Introduction
     
This report presents a detailed analysis of the data from São Paulo's 2024 municipal elections, focusing on vote distribution, voter behavior, and the performance of mayoral and councilor candidates. Various visualizations and dashboards are used to explore voting patterns, emerging trends, and the factors influencing electoral outcomes.


## 2. Study Objectives

The study aims to understand electoral dynamics in São Paulo's urban and peripheral areas, identifying factors determining voter preferences, such as the most-voted parties, candidate profiles, and voting behavior.


## 3. Theoretical Background
Analyzing electoral data is crucial for understanding voter behavior, party preferences, and political trends across different regions. Data visualization offers a clear and efficient way to identify patterns that can inform future campaigns.


## 4. Dataset Description

### Access Dataset:

- **Dataset 1**: [1st Round](https://cdn.tse.jus.br/estatistica/sead/eleicoes/eleicoes2024/buweb/bweb_1t_SP_091020241636.zip)
- **Dataset 2**: [2nd Round](https://cdn.tse.jus.br/estatistica/sead/eleicoes/eleicoes2024/buweb/bweb_2t_SP_281020241046.zip)

   
The data used in this study were extracted from public sources, providing information on votes by municipality, electoral zone, and political party. The dataset includes details about mayoral and councilor candidates in São Paulo, including the number of votes received by each candidate.


### TSE Documentatiuon

- **TSE Documentation 1**: [1st Round](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/8143d09ee6181996007e7effc9f96d49969a1a2f/TSE%20Official%20Documentation/1_Round_leiame-boletimurnaweb.pdf)
- **TSE Documentatio 2**: [2nd Round](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/88c50cb50011529465425444a500028208c873c1/dataset%20and%20document%20-%202%20Round/2_Round_leiame-boletimurnaweb.pdf)



## Processed Files


👉🏻 [Access Here All Processed Files](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/tree/7e44e7a2317aa0adedfd19adc6d14ef9ae13036a/Processed%20Database%20for%20Analysis%20-%20Base%20de%20Dados%20Processada%20para%20Ana%CC%81lise)

The following CSV files were processed:

- `address_Mayor.csv`
- `Mayor_by_city.csv`
- `Mayor_by_city_round_2.csv`
- `Mayor.csv`
- `address_Councilor.csv`
- `Councilor_by_city.csv`
- `councilor.csv`



### Sample Column Structure

Here is an overview of the main columns in the processed CSV files:

- **`NM_MUNICIPIO`**: Municipality name  
- **`NR_ZONA`**: Electoral zone number  
- **`DS_CARGO_PERGUNTA`**: Election role (Mayor or Councilor)  
- **`NM_VOTAVEL`**: Candidate name  
- **`SG_PARTIDO`**: Party acronym  
- **`QT_VOTOS`**: Number of votes received  


## 5. Methodology

The methodology was divided into several steps:

- **Data Preprocessing**: Reading and concatenating datasets, cleaning invalid records.
- **Exploratory Data Analysis (EDA)**: Identifying voting patterns and trends using graphs and tables.
- **Data Visualization**: Creating interactive charts with the Plotly library for dynamic result exploration.


## 6. Exploratory Data Analysis

The exploratory analysis uncovered several interesting trends, such as:

- The dominance of votes for parties like MDB and PSOL.
- A geographic vote distribution showing high concentration in central São Paulo and greater support for progressive parties in peripheral areas.


## 7. Charts and Dashboards
   
### 7.1. Vote Distribution by Municipality

The votes distribution revealed a large concentration in São Paulo and neighboring urban areas. The analysis indicated the need for specific strategies for peripheral areas.

```python
import plotly.express as px
import pandas as pd

# Reading the dataset
election = pd.read_csv('/path/to/your/data.csv', encoding='latin-1')

# Plotting vote distribution by municipality
fig = px.histogram(election, x="NM_MUNICIPIO", y="QT_VOTOS", 
                   title="Votes by Municipality", 
                   color_discrete_sequence=["#1f77b4"])
fig.update_layout(bargap=0.2)
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/78431749-1bcc-449a-8876-0991b9a4bace"/>

<br>

### 7.2. Most Voted Mayoral Candidates

Ricardo Nunes (MDB) stood out in central zones, while Guilherme Boulos (PSOL) had strong support in the peripheries.

```python
# Filtering mayoral candidates
mayor = election[(election["DS_CARGO_PERGUNTA"] == "Prefeito") & 
                 (election["NM_MUNICIPIO"] == "SÃO PAULO") & 
                 (election["SG_PARTIDO"] != "#NULO#")].copy()

# Grouping and ordering candidates by votes
mayor = mayor.groupby(['NM_VOTAVEL', 'SG_PARTIDO']).sum().sort_values("QT_VOTOS", ascending=False)["QT_VOTOS"].reset_index()

# Calculating vote percentages
total_votes = mayor["QT_VOTOS"].sum()
mayor["PERCENTAGE"] = mayor["QT_VOTOS"] / total_votes

# Bar chart
fig = px.bar(mayor, x="NM_VOTAVEL", y="QT_VOTOS", color="SG_PARTIDO", 
             title="Most Voted Mayoral Candidates", 
             color_discrete_sequence=px.colors.qualitative.Dark24)
fig.show()
```
<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/ba197f44-4df3-4575-8a13-af1dcc34980b"/>

<br>

7.3. Most Voted Councilor Candidates

Vote distribution showed a concentration among local candidates, with highlights for Tabata Amaral (PSB) and Renato Sorriso (PL) in peripheral zones.

```python 
# Filtering councilor candidates
councilor = election[(election["DS_CARGO_PERGUNTA"] == "Vereador") & 
                     (election["NM_MUNICIPIO"] == "SÃO PAULO") & 
                     (election["SG_PARTIDO"] != "#NULO#")].copy()

# Grouping and ordering candidates by votes
councilor = councilor.groupby(['NM_VOTAVEL', 'SG_PARTIDO']).sum().sort_values('QT_VOTOS', ascending=False)["QT_VOTOS"].reset_index()

# Calculating vote percentages
total_votes = councilor["QT_VOTOS"].sum()
councilor["PERCENTAGE"] = councilor["QT_VOTOS"] / total_votes

# Bar chart
fig = px.bar(councilor, x="NM_VOTAVEL", y="QT_VOTOS", color="SG_PARTIDO", 
             title="Most Voted Councilor Candidates", 
             color_discrete_sequence=px.colors.qualitative.Dark24)
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/267db0ac-7a93-4fa3-9dc2-5263f0964da5" />

<br>

### 7.4 Most Voted Mayors by Electoral Zone

Central zones favored Ricardo Nunes, while peripheral zones were dominated by Guilherme Boulos.

```python
# Data of zones and neighborhoods
areas = pd.DataFrame({
    "ZONE": [1, 1, 1, 1, 1, 2, 2, 2, 3, 3, 3, 4, 4, 4, 5, 5, 6, 246, 246, 247, 247, 248, 248, 249, 250, 250, 250, 251, 251, 252],
    "NEIGHBORHOOD": ["BELA VISTA", "CONSOLACAO", "LIBERDADE", "REPUBLICA", "SE", "BARRA FUNDA", "PERDIZES", "SANTA CECILIA", "BOM RETIRO", "BRAS", "PARI", "AGUA RASA", "BELEM", "MOOCA", "JD PAULISTA"]
})

# Merging with mayor data
merged = mayor.merge(areas, left_on="NR_ZONE", right_on="ZONE")

# Bar chart
fig = px.bar(merged, x="NEIGHBORHOOD", y="QT_VOTES", color="SG_PARTY", title="Most Voted Mayor by Zone")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/5413cfb2-bb4f-47be-ad51-db8fb8ebcbd2" />

<br>

### 7.5 Most Voted Councilors by Electoral Zone

The analysis revealed candidates like Márcio Chagas (PSOL) and Luana Almeida (PL) performing well in suburban areas.

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

<br>

### 7.6 Most Voted Mayors by Municipality

The municipality-level analysis confirmed Ricardo Nunes' dominance in urban areas and Boulos’ strength in peripheral zones.

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

<br>

### 7.7 Most Voted Councilors by Municipality

The analysis showed a strong presence of candidates like Eduardo Suplicy (PT) across several municipalities, reflecting broad political support.

```python
# Grouping councilors by municipality
municipality_councilor = councilor.groupby("NM_MUNICIPIO").sum().sort_values("QT_VOTES", ascending=False)

# Bar chart
fig = px.bar(municipality_councilor, x=municipality_councilor.index, y="QT_VOTES", title="Most Voted Councilor by Municipality")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/0aa00302-2929-4e9e-a24a-59cc2dd801a0" />

<br>

### 7.8 Distribution of Votes by Political Party

The vote distribution charts confirmed the dominance of MDB and PSOL, with PSOL's support growing in peripheral zones.

```python
# Analyzing distribution of votes by party
party_votes = election.groupby("SG_PARTIDO").sum().sort_values("QT_VOTES", ascending=False)

# Bar chart
fig = px.bar(party_votes, x=party_votes.index, y="QT_VOTES", title="Distribution of Votes by Political Party")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/3d78023f-df27-4937-bc96-81b76389cd23" />

<br>

## 8. Interactive Power BI Dashboards: [Click to access the link](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)

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

<br>


### Dashboard 2: Candidate Performance by Region

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

<p align="center">
 <img src="https://github.com/user-attachments/assets/07c2ff20-98a1-4778-ba27-5f56e2872c3c"/>

<br>

### 8.4 Dashboard 4: Voting by Demographic Profile

This dashboard analyzed voting by age, gender, and social class, highlighting preferences of younger voters and lower social classes for progressive candidates.

```python
# Dashboard for comparison between candidates
df = pd.read_csv('candidates_comparison.csv')
fig = px.scatter(df, x="votes_mayor", y="votes_councilor", color="party", title="Comparison of Mayoral and Councilor Candidates")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/26f48d44-9df4-425b-b1ee-d1286496ab53" />

<br>

### 8.5 Dashboard 5: Voting Comparison Between 2020 and 2024 Elections

The comparison between the two elections revealed significant changes in electoral preferences, with PSOL gaining ground in the peripheries.

```python
\# Dashboard for voting by age group
df = pd.read_csv('votes_by_age_group.csv')
fig = px.pie(df, names="age_group", values="votes", title="Voting by Age Group")
fig.show()
```

<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/cc6e6d1d-497b-42ac-bf19-7021712b1652" />


<br>

## 9. Conclusion

The analysis of the 2024 São Paulo municipal election data provided valuable insights into voter behavior and emerging trends. We observed increasing political polarization, with PSOL gaining strength in peripheral areas and MDB maintaining a solid base in central urban areas. Additionally, the analysis revealed a shift in electoral preferences, with growing support for more progressive parties, especially among younger voters and lower social classes.

The analysis of charts and dashboards enabled a more detailed understanding of vote distribution by geography, candidate performance by electoral zone, and vote segmentation by party and demographic profile. The trends observed suggest that future electoral campaigns should focus on more segmented strategies, considering the social and economic characteristics of each region.

### Recommendations for future campaigns:

- **Personalize electoral communication** for different regions, considering demographic and socioeconomic profiles.
- **Leverage the growth of social media** and other digital platforms to connect with younger voters and those with limited access to traditional media.
- **Tailor campaign proposals** according to local issues such as security, health, and education, which were decisive factors for votes in various peripheral zones.


## 10. Extra Material

- **🇺🇸 Data Analysing Report**: [Click 🔗](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/77ee8d3319a14c05ae6d3b023e0a4101ec5e2943/Data%20Analysing%20Report/%F0%9F%87%BA%F0%9F%87%B8Data%20Analysing%20Report.pdf)
- **🇧🇷 Data Analysing Report**[Click 🔗](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/9ab39e27ff0f2e8444b7c773ec309986d073ad92/Data%20Analysing%20Report/%F0%9F%87%A7%F0%9F%87%B7Analise%20do%20Dados%20Relatoirio.pdf)

- **Power BI Access Link**: [Click 🔗](https://app.powerbi.com/view?r=eyJrIjoiNTNmY2Y2YzgtODY3Yy00M2ViLWI0NDItMTdiZDJlNTg4Zjk2IiwidCI6IjhlYjI5MjAxLWEyN2QtNDMwMi04NDczLWM5ODJlYjViZTkzNSJ9)

- **Power BI File**: [Click 🔗](https://github.com/Mindful-AI-Assistants/SP2024-Election-Analysis/blob/8c71e68c34ccfd2c14ff3ecb8d0f7558bcbe109d/Power%20B%20I%20Files/DashBoard.pbix)

<br>

- **QR Code**:  
  Scan the code to access the data and visualizations on Power BI.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dfc4a631-5f88-42ea-8fea-9186beaeffef" />
</p>

<br>


## 11. References

- **Superior Electoral Court (TSE)**
- **[Electoral Data Source]**
- Articles on electoral data analysis and data visualization


## 12. How to Run the Project

This project was developed in Python and uses libraries like Pandas, Plotly, and Dash for data analysis and visualization. Follow the instructions below to set up the environment and run the code.

<br>

### 12.1 Requirements

Before running the project, you need to have Python and Git installed on your system.

Download Python
Download Git

Additionally, you will need the dependencies listed in the requirements.txt file:

```dash
pandas
plotly
```

<br>

### 12.2 Cloning the Repository

To get started, clone the repository to your computer:

```bash
git clone https://github.com/your_user/SP2024-Election-Analysis.git  
```

<br>

### 12.3 Installing Dependencies

Install the required dependencies by running the following command:

```python
pip install -r requirements.txt
```

### 12.4 Creating the Executable

To create an executable of the project, you can use PyInstaller. Run the following command to generate the executable:

```python
pyinstaller --onefile electoral_analysis.py
```

<br>

This will create an executable file in the dist/ folder, which can be run directly without needing to install Python.

### 12.5 Running the Code

After installing the dependencies or creating the executable, run the main script to generate the analyses and visualizations:

```python
python electoral_analysis.py
```

<br>

### 12.6 Running the Interactive Dashboard

If you wish to view the interactive dashboards using Bash, run the following command:

```python
python app.py
```

This will open the dashboard in your browser.



## 13. Contributing

If you'd like to contribute to this project, feel free to fork it, make changes, and submit pull requests. Here are the steps to get started:

1. **Fork** this repository.
2. **Create a branch** for your feature:
   ```bash
   git checkout -b new-feature
   ```
3. **Make the necessary changes** and commit:
   ```bash
   git commit -am 'Adds new feature'
   ```
4. **Push** the branch to the remote repository:
   ```bash
   git push origin new-feature
   ```
5. **Open a pull request** for review and integration.

Make sure your changes do not break existing functionality and that the tests are up to date.



<br><br>


## 💌 [Let the data flow... Ping Me !](mailto:fabicampanari@proton.me)


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
  

#
 
##### <p align="center">Copyright 20245 Mindful-AI-Assistants. Code released under the  [MIT license.]( https://github.com/Mindful-AI-Assistants/.github/blob/ad6948fdec771e022d49cd96f99024fcc7f1106a/LICENSE)
