# 📊 Análise de Sentimentos e NLP em Português

Uma aplicação web interativa desenvolvida com **Streamlit** que realiza análise de sentimentos e processamento de linguagem natural (PLN/NLP) em textos em português. 

O projeto combina o poder do **SpaCy** para análise gramatical, **NLTK (VADER)** para a classificação de sentimentos (com tradução automática via **Deep Translator**), além de realizar tokenização e filtragem de *Stop Words*.

---

## 🚀 Funcionalidades

*   **Análise de Sentimento:** Identifica se o texto é **Positivo**, **Negativo** ou **Neutro** utilizando o algoritmo VADER (com tradução em tempo real para maior precisão).
*   **Tokenização:** Divisão do texto em unidades individuais (palavras/pontuações).
*   **Filtragem de Stop Words:** Remoção automática de palavras irrelevantes (como "de", "a", "o", "eu") para destacar o conteúdo essencial.
*   **Análise Gramatical (POS Tagging):** Identifica a classe gramatical (verbo, substantivo, adjetivo, etc.) de cada palavra do texto usando inteligência artificial.

---

## 🛠️ Tecnologias Utilizadas

*   [Python](https://www.python.org/) (Linguagem base)
*   [Streamlit](https://streamlit.io/) (Interface Web)
*   [SpaCy](https://spacy.io/) (Processamento de Linguagem Natural)
*   [NLTK](https://www.nltk.org/) (Tokenização e Análise de Sentimento VADER)
*   [Deep Translator](https://github.com/nidhaloff/deep-translator) (Tradução automática)

---

## 📦 Como Instalar e Executar o Projeto

Siga os passos abaixo para rodar a aplicação na sua máquina local.

### 1. Clonar o repositório
```bash
git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
cd NOME-DO-REPOSITORIO
