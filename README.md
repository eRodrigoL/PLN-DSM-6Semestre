# 📚 Atividades de Processamento de Linguagem Natural (PLN)

Este repositório contém os notebooks desenvolvidos durante as aulas práticas de PLN.  
Os arquivos estão organizados na pasta [`Aulas/`](./Aulas) e seguem uma progressão de aprendizado sobre análise, modelagem e interpretação de textos com Python.

---

## 🔍 Conteúdo das Aulas

### [Aula 02 – Python e Bibliotecas](./Aulas/PLN_Aula_02_Python_e_bibliotecas.ipynb)
**Objetivo:** Introdução ao uso do Python e bibliotecas para análise de dados.  
**Técnicas de PLN:** Leitura e análise de dados com `pandas`, visualização com `matplotlib`.  
**Observações:** Trabalha com uma base de sentimentos em tweets para contar e visualizar a frequência de categorias.

---

### [Aula 03 – Processamento de Texto](./Aulas/PLN_Aula_03_Processamento_de_Texto.ipynb)
**Objetivo:** Iniciar o pré-processamento e representação de texto.  
**Técnicas de PLN:** Vetorização com `CountVectorizer` (Bag of Words) e `TfidfVectorizer` (TF-IDF).  
**Observações:** Mostra como transformar sentenças em vetores numéricos e comparar similaridade entre palavras.

---

### [Aula 04 – Extração de Características (Features) em Texto](./Aulas/PLN_Aula_04_Extração_de_caracteristicas_(Features)_em_Texto.ipynb)
**Objetivo:** Aprender a extrair informações estruturais e linguísticas de textos.  
**Técnicas de PLN:** Tokenização, remoção de stopwords, análise morfológica com `nltk`.  
**Observações:** Enfatiza a preparação de texto para modelos de classificação e análise.

---

### [Aula 05 – Análise Sintática e Estruturas Linguísticas](./Aulas/PLN_Aula_05_Análise_Sintática_e_Estruturas_Linguisticas.ipynb)
**Objetivo:** Compreender a estrutura gramatical das frases.  
**Técnicas de PLN:** Análise sintática com `spaCy`, árvores de dependência.  
**Observações:** Explora como identificar sujeitos, verbos e complementos por meio de parsing linguístico.

---

### [Aula 06 – Análise Semântica](./Aulas/PLN_Aula_06_Análise_semantica.ipynb)
**Objetivo:** Trabalhar com o significado das palavras e relações semânticas.  
**Técnicas de PLN:** Word Embedding com `Word2Vec`, cálculo de similaridade semântica.  
**Observações:** Avalia a proximidade entre palavras a partir de corpus reduzido.

---

### [Aula 07 – Descoberta de Conhecimento](./Aulas/PLN_Aula_07_Descoberta_de_conhecimento.ipynb)
**Objetivo:** Descobrir tópicos principais em um conjunto de documentos.  
**Técnicas de PLN:** Modelagem de tópicos com `LDA` (Latent Dirichlet Allocation) via `gensim`.  
**Observações:** Utiliza dicionário e representação `Bag of Words` para gerar tópicos latentes.

---

### [Aula 08 – Análise de Relevância](./Aulas/PLN_Aula_08_Analise_de_relevancia.ipynb)
**Objetivo:** Identificar e ordenar a relevância de palavras ou documentos.  
**Técnicas de PLN:** Ranking de palavras, palavras-chave, métricas de importância.  
**Observações:** Útil para sistemas de recomendação e motores de busca.

---

## 📘 Arquivo de texto utilizado

O repositório inclui o livro **"Ubirajara"** em formato `.txt`, disponível na pasta [`LivroUbirajara/Ubirajara.txt`](./LivroUbirajara/Ubirajara.txt).  
Esse arquivo é utilizado nos notebooks como material para práticas de leitura, tokenização, extração de informações e análise linguística.
