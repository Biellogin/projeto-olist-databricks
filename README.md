Projeto: Pipeline de Dados E-commerce (Olist) no Databricks 
  Contexto Acadêmico
Este projeto foi desenvolvido como parte dos meus estudos práticos em Análise e Desenvolvimento de Sistemas (ADS) na UCSal. O objetivo é aplicar conceitos de Engenharia de Dados e Big Data em cenários reais, demonstrando a transição da teoria acadêmica para a prática profissional com ferramentas de mercado.

  Sobre o Projeto
Desenvolvimento de um pipeline de dados utilizando a plataforma Azure Databricks para analisar o comportamento de vendas de um grande e-commerce brasileiro. O projeto foca na transformação de dados brutos em insights de negócio, utilizando Spark SQL para processamento em larga escala.

  Tecnologias e Ferramentas
Ambiente: Azure Databricks (Community Edition)

Linguagem Principal: Spark SQL

Processamento de Dados: Spark Engine

Arquitetura: Conceitos de Arquitetura Medalhão (Bronze e Silver)

Visualização: Databricks Built-in Visualizations

  Estrutura do Pipeline
1. Ingestão (Camada Bronze)
Criação das tabelas através do upload de arquivos CSV brutos para o catálogo do Databricks:

pedidos_brutos: Dados originais de pedidos.

itens_pedidos: Detalhamento de preços e produtos por transação.

2. Transformação e Limpeza (Camada Silver)
Processamento SQL para padronização de tipos de dados e filtragem de registros válidos:

Conversão de strings para formatos de data (timestamps).

Filtragem de pedidos com status "entregue" (delivered).

Refatoração de colunas para facilitar a manutenção do código.

3. Análise de Negócio (Camada Gold)
Geração de métricas estratégicas via SQL:

Análise de Sazonalidade: Agrupamento de pedidos por mês para identificar tendências de volume.

Cálculo de Faturamento: Implementação de Joins entre tabelas para consolidar o faturamento mensal total.

📈 Conclusão
Este projeto reforça meu domínio em SQL e minha familiaridade com ecossistemas de Big Data, preparando-me para desafios reais no mercado de análise de dados e engenharia de software.
