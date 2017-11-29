# Introdução
Neste trabalho irei apresentar uma forma de detecção de parada de sinal.
Este código leva um sinal de parada "protótipo" (stopPrototype.png) e cria uma pirâmide para fora por meio do downsampling

![image](https://user-images.githubusercontent.com/32276018/33354042-9735a860-d48f-11e7-8193-4ba4c08ab322.png)

# Downsampling
Pyramid, ou representação de pirâmide, é um tipo de representação de sinal de escala múltipla desenvolvida pelas comunidades de processamento de imagem, processamento de imagem e processamento de sinal, em que um sinal ou uma imagem está sujeita a suavização repetida e subamostragem. A representação da pirâmide é uma antecessora da representação da escala espacial e da análise de multi-resolução.
"No dataset deste projeto se encontra algumas amostras de imagens!"

Existem dois tipos principais de pirâmides: passagem baixa e passagem de banda.
PASSAGEM BAIXA 
Uma pirâmide de passagem baixa é feita suavizando a imagem com um filtro de suavização apropriado e depois submetendo-se a imagem suavizada, geralmente por um fator de 2 ao longo de cada direção de coordenada. A imagem resultante é então submetida ao mesmo procedimento, e o ciclo é repetido várias vezes. Cada ciclo deste processo resulta em uma imagem menor com suavização aumentada, mas com diminuição da densidade de amostragem espacial (ou seja, redução da resolução da imagem). Se ilustrado graficamente, toda a representação em escala múltipla parecerá uma pirâmide, com a imagem original na parte inferior e a imagem menor resultante de cada ciclo empilhada uma sobre a outra.

PASSAGEM DE BANDA
Uma pirâmide de passagem de banda é feita formando a diferença entre imagens em níveis adjacentes na pirâmide e executando algum tipo de interpolação de imagem entre níveis adjacentes de resolução, para permitir a computação de diferenças de pixel. 





