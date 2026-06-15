# Elemento-basico-de-python
01 - Testando de gravidez Escrever  uma célula com controle de fluxos que tem como premissa a existência das seguintes variáveis:  sexo como str indicando os valores 'M' para masculino e 'F' para feminino beta_hcg que indica a quantidade do beta-HCG no sangue em mUI/mL.


02 -  Transformei a lista de alturas em um ndarray do NumPy e converteu as unidades de centímetros para metros.

A lógica por trás: Em vez de criar um loop for para dividir cada altura por 100, você simplesmente executou altura_em_centimetros / 100. Você utilizou o conceito de Broadcasting, onde o NumPy entende que deve aplicar essa operação matemática a cada elemento do vetor de forma simultânea e ultraveloz.
