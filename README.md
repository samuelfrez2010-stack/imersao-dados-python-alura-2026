# Imersão Dados Python Alura 2026

Este projeto foi desenvolvido durante a **Imersão Dados Python da Alura**. Ele consiste em uma ferramenta interativa para explorar e visualizar tendências salariais no mercado de dados global, permitindo filtros por senioridade, ano, tipo de contrato e tamanho da empresa.

---

## Tecnologias Utilizadas

- **Python**: Linguagem base para toda a lógica e tratamento de dados.
- **Pandas**: Biblioteca fundamental para manipulação e análise de DataFrames.
- **Plotly**: Criação de gráficos dinâmicos e interativos.
- **Streamlit**: Framework para transformar scripts Python em dashboards web.

---

## O que aprendi em cada aula?

### Aula 1: Exploração de Dados com Pandas
- Carregamento de datasets externos via URL.
- Utilização de métodos como `.head()`, `.info()` e `.describe()` para entender a estrutura dos dados.
- Análise de frequências e estatísticas básicas
  
### Aula 2: Limpeza e Preparação de Dados
- Tratamento de valores nulos e duplicados.
- Manipulação de colunas e tipos de dados.
- Filtragem de dados específica para responder perguntas de negócio (ex: salários acima de X).

### Aula 3: Visualização com Plotly
- Criação de gráficos de barras, histogramas, gráficos circulares e mapas (choropleth).
- Customização de escalas de cores e layouts de gráficos.
- Agrupamento de dados (`groupby`) para gerar insights visuais.

### Aula 4: Desenvolvimento de Dashboard Interativo
- Estruturação de interface com `Streamlit`.
- Barra Lateral Interativa (Sidebar): Implementação de filtros dinâmicos para seleção de anos e níveis de senioridade, permitindo consultas customizadas em tempo real.
- Visualização de Dados Dinâmica: Integração de gráficos do Plotly que se adaptam automaticamente aos filtros aplicados pelo usuário.

---

## Acesso ao Projeto

Você pode interagir com o Dashboard e explorar os dados ao vivo aqui:

**[![Abrir no Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://samuel-frez-santos-imersao-dados-python-alura-2026.streamlit.app/)**

---

## Futuras Melhorias e Evolução (Versão Autoral)

Este projeto foi o meu ponto de partida na análise de dados com Python. Embora siga a estrutura da Imersão Alura, já estou planejando uma **versão 2.0 totalmente autoral**, onde pretendo:

- **Substituição do Dataset**: Aplicar a mesma lógica de análise em um conjunto de dados exclusivo (ex: mercado tech regional).
- **Novas Funcionalidades Backend**: Implementar filtros de busca por texto livre e cálculos estatísticos avançados (como desvio padrão e projeções salariais).
- **Otimização de Performance**: Refinar o uso do cache do Streamlit para lidar com volumes maiores de dados.
- **Interface Customizada**: Desenvolver um layout focado em UX (User Experience) que vá além do modelo padrão de tutoriais.

Meu objetivo é transformar esta base técnica em uma ferramenta personalizada que resolva problemas reais de negócio.

---
## Créditos

Projeto desenvolvido durante a Imersão Dados com Python da **Alura**, sob orientação dos instrutores **Marcell Almeida**, **Vinícius Caridá** e **Valquíria Alencar**.
