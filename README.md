# AdaBoosting
Processo de AdaBoosting Completo

Sabemos que erros de um modelo de previs˜ao podem ser decompostos em dois fatores: vi´es
e variˆancia. Um modelo complexo apresenta pouco vi´es, mas grande variˆancia, enquanto um
modelo simples apresenta grande vi´es e pouca variˆancia.
Boosting ´e o processo de reduzir o vi´es de um grande conjunto de modelos simples (i.e.,
com baixa variˆancia). Esses modelos s˜ao chamados de modelos fracos, e s˜ao levemente correlacionados com a classificao correta. No processo de Boosting, os modelos fracos formam
um modelo mais forte de maneira iterativa. Os modelos fracos s˜ao escolhidos iterativamente,
de forma que cada modelo ´e escolhido levando-se em conta vi´eses independentes. Ou seja,
cada modelo componente realiza erros diferentes de outros modelos componentes.
