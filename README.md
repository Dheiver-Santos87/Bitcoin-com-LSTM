# Bitcoin-com-LSTM

O modelo de série temporal LSTM (Long Short-Term Memory) é um tipo de modelo de aprendizado profundo que é especialmente adequado para previsão de séries temporais. Ele é capaz de capturar dependências de longo prazo em dados de séries temporais e é frequentemente usado em aplicações de previsão financeira.

O modelo LSTM consiste em camadas de células LSTM, que são capazes de armazenar informações ao longo do tempo e usá-las para tomar decisões sobre como processar novas entradas. Isso permite que o modelo aprenda padrões e dependências em dados de séries temporais que podem ser difíceis de capturar com outros tipos de modelos.

No código fornecido, o modelo LSTM é construído usando a biblioteca Keras do TensorFlow. Ele é composto por duas camadas LSTM com 50 unidades cada, seguidas por duas camadas densas com 25 e 1 unidade, respectivamente. O modelo é treinado usando a função de perda mean squared error (MSE) e otimizado com o otimizador Adam.

Para avaliar o desempenho do modelo, o conjunto de treinamento é dividido em lotes de tamanho 1 e treinado por 6 épocas. A função "fit" do Keras retorna um objeto "history" que pode ser usado para plotar gráficos de perda e métricas de desempenho ao longo do treinamento.

Em resumo, o modelo LSTM é uma ferramenta poderosa para previsão de séries temporais e pode ser útil em várias aplicações, incluindo finanças. No entanto, é importante lembrar que esses modelos são geralmente mais complexos de treinar e avaliar do que modelos mais simples e podem exigir um ajuste cuidadoso de hiperparâmetros para obter o melhor desempenho.
