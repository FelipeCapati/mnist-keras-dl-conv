# Deep Learning - Redes de Convolução #

## I.	 INTRODUÇÃO ##
Esse projeto tem como objetivo exemplificar a aplicação de redes convolucionais aplicadas em classificação de imagem,
utilizando o dataset mnist tem-se a proposta de modelagem no keras com foco na rede LeNet-5.<br>
Em Deep Learning é comumente aplicada redes compostas de etapas convolucionais + pooling juntamente com uma rede neural
densa mais simples.<br>

## II.	FUNDAMENTAÇÃO TEÓRICA ##

### A.	REDES DE CONVOLUÇÃO ###

## III.	METODOLOGIA ##
Para o projeto vigente foi utilizado python juntamente com o Notebook Jupyter para prototipar o modelo do
algorítimo. A base do algorítimo foi feita utilizando Keras que possibilita a prototipagem de redes convulucionais
de forma mais simples e direta.<br>
Para o teste e análise do algorítimo utilizou-se o dataset mnist, na qual o objetivo é discriminar entre 10 tipos de 
classes, sendo elas: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9; tendo como entrada imagens no padrão 28x28 grayscale.<br>
Inicialmente tem-se uma abordagem de padronização dos dados para que seja possivel processa na rede. Após a padronização
foi desenvolvida uma rede inspirada na LetNet-5 para o aprendizado do modelo.

## IV. RESULTADOS ##
Os detalhes das implementações dos problemas propostos na metodologia pode ser analisados em <b>"./LDA.ipynb"</b> 
ou <b>"LDA.html"</b>.<br>
Foi utilizado um batch-size de 128 com 5 épocas, o gráfico a seguir é, respoectivamente, a curva do modelo relativo ao
loss e ao accuracy.<br>

![Alt text](images/mnist-graph-01.png?)<br>

![Alt text](images/mnist-graph-02.png?)<br>

## V. CONCLUSÃO ##
Dado os resultados vistos em IV podemos inferir que as redes convolucionais são extremamente eficientes e solucionam
muito bem o problema proposto pelo dataset Mnist (cerca de 97% de Accurancy).<br>

O modelo de rede LeNet-5 foi capaz de aprender a classificar os 10 tipos de classificação mantento uma alta acertibilidade,
ou seja, existe uma individualidade entre os dados na qual é possível de se distinguir utilizando redes convolucionais.<br>
Como não foi utilizado nenhum indicador de performance, tais como matriz de confusão (foi utilizad apenas o accuracy)
não podemos extrair mais informações referentes ao processo de classificação.<br>

## VI. AGRADECIMENTOS ##

Agradecimentos especiais a CAPES e ao Centro Universitário FEI por financiar o mestrado que está em curso; 
ao professor Reinaldo Bianchi por proporcionar visões sobre o mundo acadêmico e orientar trabalhos científicos 
com o objetivo de lapidar os conhecimentos abordados em sala; aos meus pais e a minha família que sempre me 
apoiaram em meio a dificuldades.

## VII. REFERÊNCIAS ##

[3]	R. Bianchi, Tópicos Especiais em Aprendizagem, 2019, ppt slide Centro Universitário FEI.