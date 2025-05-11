# Classificacao das flores do conjunto Íris
Modelo de Machine Learning que classifica espécies de flores Iris com base em características como comprimento e largura das sépalas e pétalas, utilizando o TensorFlow para construir, treinar e avaliar o modelo.

## Lógica utilizada
O modelo foi criado com uma rede neural simples usando TensorFlow, treinado com o dataset Iris, e teve como objetivo classificar corretamente a espécie da flor com base em suas características. O processo seguiu uma pipeline típica de Machine Learning: importação → preparo → modelo → avaliação → previsão.

O que o código faz:
- Pré-processa os dados (divisão e normalização).
- Constrói e treina uma rede neural com duas camadas ocultas.
- Avalia a performance do modelo.
- Realiza previsões com base no modelo treinado.
- Mostra os 10 primeiros resultados previstos comparados com os reais.
