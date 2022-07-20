# AdaBoosting
Processo de AdaBoosting Completo

Sabemos que erros de um modelo de previsao podem ser decompostos em dois fatores: vies
e variancia. Um modelo complexo apresenta pouco vies, mas grande variancia, enquanto um
modelo simples apresenta grande vi´es e pouca variancia.

Boosting é o processo de reduzir o vies de um grande conjunto de modelos simples (i.e.,
com baixa variancia). 

Esses modelos sao chamados de modelos fracos, e sao levemente correlacionados com a classificao correta. No processo de Boosting, os modelos fracos formam
um modelo mais forte de maneira iterativa. Os modelos fracos sao escolhidos iterativamente,
de forma que cada modelo ´e escolhido levando-se em conta vi´eses independentes. Ou seja, cada modelo componente realiza erros diferentes de outros modelos componentes.

![image](https://user-images.githubusercontent.com/14276167/180002814-2a1fb7a9-a152-4511-aadd-d9f65072ac1a.png)


## Base de dados

![image](https://user-images.githubusercontent.com/14276167/180002882-c4eca098-2462-4c65-83a0-8ac4d2d776ca.png)
![image](https://user-images.githubusercontent.com/14276167/180002949-2e9779c1-5653-42f3-87b2-a8f6e38a695f.png)

## Implementação AdaBoosting
Utlização de K-fold para validação

![image](https://user-images.githubusercontent.com/14276167/180003181-02d8b97e-9059-41f0-a6c0-7f3ab357b658.png)

## Resultados
![image](https://user-images.githubusercontent.com/14276167/180003382-db17178f-37e4-47be-b002-88a2504e2c73.png)
![image](https://user-images.githubusercontent.com/14276167/180003410-d8cc31fc-39f2-4612-a87a-eaa5f6f8fba0.png)

## Conclusão 
Durante a execução o erro de aprendizagem tende a diminuir enquanto as métricas levantadas começam a aumenta e a entrar em equilíbrio maximizando o desempendo do modelo executado.

Conclui-se que o medelo executou o que foi proposto, aumentou as métricas de forma equilibrada na medida que diminuiu a taxa de erro

