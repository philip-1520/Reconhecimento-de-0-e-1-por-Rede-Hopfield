# Reconhecimento-de-0-e-1-por-Rede-Hopfield
Rede neural Hopfield que identifica em imagens 7 x 5 de pixels binários os dígitos 0 e 1.

A base de dados contém 20 imagens divididas igualmente para representarem os dígitos 0 e 1. A cada ciclo de teste uma imagem de cada dígito é aleatoriamente selecionada para treinar a rede Hopfield, e as outras são utilizadas de teste, totalizando 18 imagens de teste por ciclo.

Após análise de ciclos de treinamento e teste, observou-se que aproximadamente 89% dos ciclos obtêm pelo menos 9 acertos entre os 18 exemplos de teste.

Em toda a faixa analisada, a probabilidade acumulada de obter pelo menos k acertos permaneceu igual ou superior à prevista por uma distribuição binomial com p=0,5, indicando desempenho superior ao esperado por um classificador aleatório.

Como a base de dados é composta por apenas 20 imagens, os ciclos de avaliação correspondem a diferentes reamostragens do mesmo conjunto de dados, e não a experimentos independentes.

Acurácia: a rede estabilizou no exato estado do dígito utilizado para treino.
Lembrança: a rede estabilizou no exato estado do dígito utilizado para treino ou na região de mínima energia oposta, criada pela simetria dos pesos.

<img width="811" height="411" alt="image" src="https://github.com/user-attachments/assets/c8140fb1-16e3-4f15-897c-da024c64cb8c" />
