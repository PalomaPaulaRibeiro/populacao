# 🌍 Análise Populacional Global com HTML + Matplotlib

## 📘 Descrição

Este projeto tem como objetivo realizar uma análise visual da população mundial com base em dados extraídos de um **arquivo HTML contendo uma tabela da população por país**. A análise foi conduzida no **Google Colab**, utilizando a biblioteca `pandas` para manipulação de dados e `matplotlib` para visualização gráfica.

---

## 📥 Fonte dos Dados

- Arquivo HTML contendo tabela da população mundial (baseado em estimativas da ONU).
- A tabela foi extraída com `pandas.read_html()`.

---

## ⚙️ Tecnologias Utilizadas

- Python 3.x
- Google Colab
- Bibliotecas:
  - `pandas`
  - `matplotlib`

---

## 📊 Etapas da Análise

1. **Leitura de arquivo HTML** contendo a tabela com estimativas populacionais.
2. **Limpeza e conversão de dados** de texto para valores numéricos (remoção de pontos, espaços e símbolos).
3. **Seleção dos 10 países mais populosos** segundo a estimativa da ONU.
4. **Criação de gráfico de pizza (`pie chart`)** com `matplotlib` para representar visualmente a distribuição populacional.

---

## 📈 Resultado Esperado

Gráfico circular representando os 10 países mais populosos do mundo, com percentuais relativos à população global dos países listados no HTML.

---

## 🧠 Aprendizados

Durante o projeto, foram abordados os seguintes tópicos:

- Como importar e analisar **tabelas diretamente de arquivos HTML** usando `pandas`.
- Limpeza de dados numéricos com formatação irregular (ex.: “1.417.492.000”).
- Geração de gráficos com `matplotlib.pyplot.pie`.
- Uso do Google Colab como ambiente para análise exploratória.

---

## 🗂️ Estrutura do Projeto

