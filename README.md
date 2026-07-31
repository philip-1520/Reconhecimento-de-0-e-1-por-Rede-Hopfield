# Reconhecimento-de-0-e-1-por-Rede-Hopfield
Rede neural Hopfield que identifica em imagens 7 x 5 de pixels binários os dígitos 0 e 1.

A base de dados contém 20 imagens divididas igualmente para representarem os dígitos 0 e 1. A cada ciclo de teste uma de cada dígito é aleatoriamente selecionada para treinar a rede Hopfield, e as outras são utilizadas de teste, totalizando 18 testes por ciclo de teste.

Após análises de milhares de ciclos, foi encontrado um comportamento consistente de que em 89% dos casos a rede acerta ao menos 9 dos dígitos de teste.

Ao longo de toda a curva a taxa de acerto do modelo não é inferior à calda superior da distribuição binomial.

<img width="811" height="411" alt="image" src="https://github.com/user-attachments/assets/a8346139-f4de-40ca-895d-63d8ebc6778d" />
