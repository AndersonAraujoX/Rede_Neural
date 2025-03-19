# SCC0270 - Redes Neurais e Aprendizado Profundo

Este repositório contém os trabalhos práticos desenvolvidos para a disciplina SCC0270 - Redes Neurais e Aprendizado Profundo.

## Trabalho 1: Redes Densas e Convolucionais

Implementação de duas redes neurais utilizando Pytorch:

* Uma rede neural utilizando camadas densas (fully connected) para classificar imagens do dataset Fashion MNIST. 
* Uma rede neural utilizando camadas convolucionais (Conv2d) para classificar as imagens do dataset Fashion MNIST. 

### Resultados

* A rede CNN obteve melhores resultados devido à maior quantidade de parâmetros de treinamento e ao uso de convolução. 

## Trabalho 2: Previsão do valor de ações utilizando LSTM

Implementação de redes neurais recorrentes do tipo LSTM para a tarefa de previsão do valor de ações da empresa Apple, negociada na Bolsa de Valores americana NASDAQ. 

### Resultados

* O modelo básico obteve um RMSE de 53.39 no conjunto de teste. 
* Um modelo ajustado obteve um RMSE de 3.83 no conjunto de teste. 

## Trabalho 3: Detecção de bullying em tweets

Aplicação de técnicas de Processamento de Linguagem Natural (PLN) para identificar e classificar tweets com conteúdo de bullying. 
### Modelos Implementados

* Naive Bayes 
* Bidirectional LSTM 
* BERT (Transformers) 

### Resultados

* O modelo BERT obteve os melhores resultados, com uma acurácia de 95%. 
* Os modelos LSTM e Naive Bayes obtiveram acurácias de 93% e 87%, respectivamente. 
