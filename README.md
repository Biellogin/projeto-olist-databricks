# Projeto: Pipeline de Dados E-commerce Olist no Databricks

## Contexto Academico
Este projeto foi desenvolvido como parte dos meus estudos praticos em Analise e Desenvolvimento de Sistemas (ADS) na UCSal. O objetivo e aplicar conceitos de Engenharia de Dados e Big Data em cenarios reais, demonstrando a transicao da teoria academica para a pratica profissional com ferramentas de mercado.

## Sobre o Projeto
Desenvolvimento de um pipeline de dados utilizando a plataforma Azure Databricks para analisar o comportamento de vendas de um grande e-commerce brasileiro. O projeto foca na transformacao de dados brutos em insights de negocio, utilizando Spark SQL para processamento em larga escala.

## Tecnologias e Ferramentas
* Ambiente: Azure Databricks (Community Edition)
* Linguagem Principal: Spark SQL
* Processamento de Dados: Spark Engine
* Arquitetura: Conceitos de Arquitetura Medalhao (Bronze e Silver)
* Visualizacao: Databricks Built-in Visualizations

## Estrutura do Pipeline

### 1. Ingestao (Camada Bronze)
Criacao das tabelas atraves do upload de arquivos CSV brutos para o catalogo do Databricks:
* pedidos_brutos: Dados originais de pedidos.
* itens_pedidos: Detalhamento de preços e produtos por transacao.

### 2. Transformacao e Limpeza (Camada Silver)
Processamento SQL para padronizacao de tipos de dados e filtragem de registros validos:
* Conversao de strings para formatos de data (timestamps).
* Filtragem de pedidos com status entregue (delivered).
* Refatoracao de colunas para facilitar a manutencao do codigo.

### 3. Analise de Negocio (Camada Gold)
Geracao de metricas estrategicas via SQL:
* Analise de Sazonalidade: Agrupamento de pedidos por mes para identificar tendencias de volume.
* Calculo de Faturamento: Implementacao de Joins entre tabelas para consolidar o faturamento mensal total.

## Conclusao
Este projeto reforca meu dominio em SQL e minha familiaridade com ecossistemas de Big Data, preparando-me para desafios reais no mercado de analise de dados e engenharia de software.

---

## Contato
* LinkedIn: [Gabriel Cardoso Dos Santos](https://www.linkedin.com/in/gabriel-cardoso-santos0611/)
* Email: gabriel.cardoso0611@gmail.com
* Formacao: Estudante de Analise e Desenvolvimento de Sistemas - UCSalha familiaridade com ecossistemas de Big Data, preparando-me para desafios reais no mercado de análise de dados e engenharia de software.
