# 📊 Dashboard de Gestão Cirúrgica

Dashboard desenvolvido em Power BI para análise e acompanhamento de procedimentos cirúrgicos, permitindo monitorar volume de cirurgias, cumprimento de prazo, tempo de realização, distribuição por unidade e principais motivos de atraso.

## 🎯 Objetivo

O projeto tem como objetivo transformar dados operacionais em informações visuais que permitam acompanhar o desempenho dos procedimentos cirúrgicos e identificar situações que demandam atenção.

Entre os principais pontos analisados estão:

- Volume de procedimentos realizados;
- Pacientes com idade superior a 60 anos;
- Tempo médio e máximo entre autorização e realização;
- Cumprimento do prazo estabelecido;
- Procedimentos cancelados;
- Óbitos;
- Distribuição dos procedimentos por UF e unidade;
- Principais motivos de atraso;
- Evolução dos indicadores ao longo do tempo.

## 📌 Principais Indicadores

O dashboard apresenta indicadores como:

- Quantidade de cirurgias;
- Pacientes >60 anos;
- Tempo médio até a realização;
- Tempo máximo até a realização;
- Percentual de procedimentos dentro do prazo;
- Procedimentos cancelados;
- Óbitos.

## 📈 Análises Desenvolvidas

### Visão Geral

A primeira página apresenta uma visão executiva dos principais indicadores, permitindo uma análise rápida do cenário geral.

Entre os visuais estão:

- Procedimentos por UF;
- Motivos dos atrasos;
- Ranking por unidade;
- Cumprimento do SLA por mês para pacientes >60 anos;
- Cumprimento do SLA por mês para pacientes <60 anos.

### Visão Analítica

A segunda página apresenta uma análise mais detalhada dos dados, permitindo acompanhar:

- Evolução da quantidade de cirurgias por mês;
- Tempo médio por mês;
- Distribuição dos status das cirurgias;
- Tempo médio por unidade;
- Indicadores detalhados por unidade;
- Consulta individual de pacientes.

## 🛠️ Tecnologias Utilizadas

- **Power BI**
- **DAX**
- **Power Query**
- **Microsoft Excel**
- **Figma**
- **Git**
- **GitHub**

## 🔄 Tratamento e Modelagem dos Dados

Os dados foram tratados utilizando o Power Query, incluindo processos de:

- Limpeza e padronização;
- Tratamento de valores nulos;
- Padronização de categorias;
- Tratamento de datas;
- Criação e transformação de campos;
- Preparação dos dados para análise no Power BI.

A modelagem foi estruturada para permitir análises temporais, operacionais e gerenciais.

## 🎨 Design

A interface do dashboard foi planejada previamente no **Figma**, permitindo definir a disposição dos indicadores, gráficos, filtros e elementos de navegação antes da implementação no Power BI.

O objetivo foi criar uma interface limpa, organizada e orientada à análise dos indicadores.

## 📂 Estrutura do Repositório

```text
Dashboard_PowerBI_Gestao_Cirurgica/
│
├── Dashboard/
│   └── Arquivo do Power BI (.pbix)
│
├── Imagens/
│   └── Imagens e prévias do dashboard
│
├── Dataset/
│   └── Base de dados anonimizada
│
├── README.md
├── LICENSE
└── .gitignore


### Mas eu faria uma mudança importante

**Não colocaria "Dataset" na estrutura agora**, já que você ainda está decidindo quais informações vão permanecer na base. Podemos deixar essa parte para quando você realmente adicionar o arquivo.

E tem outra coisa que eu acho legal fazer: **colocar imagens do dashboard logo no começo do README**. Quem entrar no GitHub já vê o resultado antes mesmo de começar a ler.

Algo assim:

```markdown
# 📊 Dashboard de Gestão Cirúrgica

![Dashboard - Visão Geral](Imagens/visao-geral.png)

Dashboard desenvolvido...