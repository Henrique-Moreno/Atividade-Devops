# Relatório sobre o modelo de Machine Learning que classifica espécies de flores Iris 

## Introdução

> Nessa atividade consiste em criar um modelo de machine learning que classifica espécies de flores Iris com base em características como comprimento e largura das sépalas e pétalas. Para isso, utilizei a biblioteca TensorFlow, que é amplamente usada para construir e treinar modelos de aprendizado de máquina.

## Métodos

## Linguagem Python

> Python é uma linguagem de programação de alto nível, conhecida por sua sintaxe 
simples e legibilidade. É amplamente utilizada para desenvolvimento web, 
automação, análise de dados e muito mais.

> O Google Colab é uma ferramenta online gratuita que permite escrever e executar código Python diretamente no navegador. Com essa plataforma, não é necessário instalar nenhum software no computador, o que torna o processo mais simples e acessível. Além disso, o Colab oferece recursos como acesso a GPUs e a possibilidade de colaboração em tempo real.

## Desenvolvimento

> O código é feito em várias etapas. Primeiro, importei as bibliotecas necessárias, como TensorFlow, Pandas e scikit-learn. Em seguida, carreguei o conjunto de dados Iris e dividi os dados em conjuntos de treinamento e teste. Depois, normalizei os dados para melhorar a performance do modelo.
Na etapa seguinte, construí um modelo de rede neural simples com uma camada oculta e uma camada de saída. O modelo foi treinado usando os dados de treinamento por 50 épocas. Após o treinamento, avaliei a precisão do modelo utilizando os dados de teste e fiz previsões sobre as classes das flores.

## Conclusão

> O modelo conseguiu classificar corretamente as espécies de flores Iris com uma boa precisão. Abaixo, você encontrará um print da aplicação em funcionamento.