# 📚 AI Book Recommender: Inovação no Acesso à Leitura (ODS 9)

Este projeto consiste no desenvolvimento de um **Sistema de Recomendação de Livros** focado em personalizar o acesso ao conhecimento. O trabalho foi desenvolvido como parte do Projeto Aplicado III do curso de Ciência de Dados da Universidade Mackenzie, alinhando tecnologia de ponta ao **Objetivo de Desenvolvimento Sustentável 9 (Indústria, Inovação e Infraestrutura)** da ONU.

## 🎯 Objetivo
Promover a inovação digital e fortalecer a infraestrutura de acesso à educação através de um algoritmo de filtragem colaborativa capaz de sugerir obras relevantes com alta precisão, reduzindo a sobrecarga de informação.

## 🛠️ Stack Técnica
* **Linguagem:** Python 3.x
* **Processamento de Dados:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (NearestNeighbors)
* **Estrutura de Dados:** Scipy (Sparse Matrices)
* **Visualização:** Matplotlib

## ⚙️ Arquitetura do Sistema
O motor de recomendação utiliza a técnica de **Filtragem Colaborativa Usuário-Usuário** baseada no algoritmo **KNN (K-Nearest Neighbors)**.

### Destaques Técnicos:
* **Matrizes Esparsas (CSR):** Implementação de `csr_matrix` para otimização de memória RAM, permitindo o processamento de uma matriz de 17.424 usuários por 4.585 livros.
* **Tratamento de Cold Start:** Desenvolvimento de uma função para novos usuários que coleta preferências iniciais e gera recomendações imediatas sem necessidade de histórico prévio.
* **Métrica de Similaridade:** Utilização da **Similaridade de Cosseno** para encontrar vizinhos próximos com padrões de avaliação idênticos.
