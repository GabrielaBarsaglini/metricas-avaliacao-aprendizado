# Cálculo de Métricas de Avaliação de Aprendizado

Análise de Interrupções de Energia Elétrica - ANEEL
Este projeto realiza a análise de dados de interrupções de energia elétrica fornecidos pela Agência Nacional de Energia Elétrica (ANEEL). O foco é simular um modelo de classificação para os tipos de interrupção e calcular métricas de avaliação de modelos de machine learning, como acurácia, sensibilidade, precisão e F1-score.

 Dados
Os dados utilizados são do conjunto "Interrupções de Energia Elétrica" disponível no Portal de Dados Abertos da ANEEL. O conjunto de dados contém registros de interrupções nas redes elétricas de distribuição, incluindo informações como tipo de interrupção, motivo, data de início e fim, e identificação do agente regulado.

Estrutura do Conjunto de Dados
O arquivo CSV original contém as seguintes colunas relevantes para esta análise:

DscTipoInterrupcao: Descrição do tipo de interrupção (ex.: Programada, Não Programada)

IdeMotivoInterrupcao: Identificador do motivo da interrupção

DscFatoGeradorInterrupcao: Descrição do fato gerador da interrupção

NomAgenteRegulado: Nome do agente regulado (empresa responsável)

 Objetivo
O objetivo principal é calcular métricas de avaliação para modelos de classificação através de uma matriz de confusão simulada, utilizando dados reais de interrupções de energia elétrica no Brasil.

 Métricas Calculadas
Acurácia: Proporção de previsões corretas sobre o total

Sensibilidade (Recall): Capacidade de identificar corretamente casos positivos

Especificidade: Capacidade de identificar corretamente casos negativos

Precisão: Proporção de verdadeiros positivos entre as previsões positivas

F1-Score: Média harmônica entre precisão e recall

 Tecnologias Utilizadas
Python 3.x

Pandas para manipulação de dados

NumPy para operações numéricas

Scikit-learn para cálculo de métricas

Matplotlib e Seaborn para visualização

Google Colab para execução

Considerações
O conjunto de dados original é muito grande (cerca de 5 milhões de registros), portanto, o projeto trabalha com uma amostra de 50.000 registros para viabilizar o processamento

As previsões do modelo são simuladas, uma vez que não há um modelo real treinado
