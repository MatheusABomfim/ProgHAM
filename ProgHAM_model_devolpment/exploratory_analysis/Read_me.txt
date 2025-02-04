Desfecho avaliado HAM/TSP vs Oligoassintomático:

- Tomek foi o melhor modelo de undersampling
- SMOTENC o melhor do oversampling
- Testarei de forma iterativa os modelos reduzindo o número de features, visando avaliar o N para combinação de boa capacidade classificatória sem overfitting. As variáveis serão selecionadas respeitando o resultado do K-Best priorizando as variáveis com correlação positiva na regressão linear e T-student

- Tomek: Iniciei N = 13
- A partir do N = 10 a capacidade preditiva foi reduzida, N = 11 foi selecionado como o melhor subconjunto para Tomek

- SMOTENC: Iniciei com N = 12
- A partir do K=11 Já foi possível identificar redução da capacidade classificatória, o subconjunto selecionado foi o N = 12

- O método SMOTENC resultou em uma maior capacidade preditiva como ilustrado nas matrizes de confusão, sendo selecionado como método de balanceamento a ser empregado