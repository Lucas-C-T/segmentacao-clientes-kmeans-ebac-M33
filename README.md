# Segmentação de Clientes - EBAC

## 🎯 Objetivo
Este projeto faz parte do curso de Data Science da EBAC e tem como objetivo aplicar os conceitos avançados de modelagem não supervisionada para realizar uma segmentação de clientes estruturada. Utilizando o algoritmo de clustering K-Means, o projeto busca identificar agrupamentos de consumidores com base em seus perfis para dar suporte a estratégias personalizadas de marketing e negócios.

## 🛠️ Tecnologias Utilizadas
- Python 3.9+
- Pandas, NumPy
- Scikit-learn (KMeans, Silhouette Score, StandardScaler)
- Matplotlib, Seaborn

## 📊 Metodologia
1. **Exploração dos dados**: Análise descritiva da base de dados, identificação de padrões e verificação de presença de inconsistências e dados nulos.
2. **Pré-processamento**: Padronização de escala dos dados numéricos utilizando o `StandardScaler` para garantir pesos iguais nas distâncias métricas.
3. **Modelagem**: Implementação e execução do algoritmo K-Means variando o número de clusters de forma estruturada.
4. **Validação**: Avaliação do número ideal de agrupamentos através do método do Cotovelo (Inércia/Elbow Method) e cálculo do Coeficiente de Silhueta (Silhouette Score).
5. **Resultado**: Definição da quantidade ótima de clusters e mapeamento descritivo do comportamento do cliente em cada grupo gerado.
