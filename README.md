# 📚 Análise de Dados: O que determina o sucesso de um livro? (Goodreads)

Este projeto realiza uma investigação estatística avançada e modelagem preditiva sobre uma base de dados do Goodreads contendo mais de 11.000 títulos extraídos via API oficial. O objetivo principal é mapear os fatores determinantes para a recepção de uma obra, tratando disparidades amostrais e preparando os dados para algoritmos de Machine Learning.

---

## 🛠️ Tecnologias e Conceitos Aplicados
* **Linguagem:** Python
* **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn
* **Estatística Avançada:** Média Ponderada Bayesiana, Tratamento de Outliers, Quartis e Desvio Padrão

---

## 📈 Etapas Concluídas (Fase 1: Análise Exploratória & Normalização)
* **Tratamento de Dados:** Limpeza de ruídos e filtragem de outliers amostrais.
* **Definição de Piso Estatístico:** Estabelecimento de um limite de significância (mínimo de 100 avaliações), identificando o comportamento do limite inferior do mercado (Caso *Citizen Girl*, nota 2.4).
* **Descarte de Variáveis Irrelevantes:** Validação estatística de que número de páginas e idioma não ditam o sucesso ou a popularidade das obras na base.
* **Engenharia de Recursos (Média Bayesiana):** Implementação do algoritmo de Média Ponderada Bayesiana para corrigir a distorção de escala entre livros de nicho altamente avaliados e Best-Sellers massivos com milhões de votos.

---

## 🎯 Status Atual & Próximos Passos (Fase 2: Modelagem)
Atualmente, o projeto avançou para a fase de inteligência preditiva. Estamos desenvolvendo:
* **Clusterização:** Para agrupar perfis de livros semelhantes com base no comportamento de engajamento e editoras.
* **Árvore de Decisão:** Construção do modelo para extrair a *Feature Importance* (importância das variáveis), identificando o fator de maior peso que altera a direção de um livro entre ser bem quisto ou não pelo público.

---

## 📁 Estrutura do Repositório
* `notebooks/`: Código completo da análise exploratória e cálculos no Google Colab.
* `slides/`: Apresentação executiva em PDF utilizada no LinkedIn.

---
**Desenvolvido por Cleber Santos**  
👋 Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/cleber-xcl-esc/) | Conheça meus projetos no [GitHub](https://github.com/xcl-esc/)
