# Questão 13

Guilherme possui 8 miniaturas de carrinhos de modelos distintos, sendo 2 vermelhos, 2 amarelos e 4 azuis. De quantas maneiras diferentes Guilherme pode organizar seus carrinhos sobre uma prateleira horizontal, de maneira que todos fiquem de frente para ele, um ao lado do outro, à mesma distância entre cada um deles e de modo que os carrinhos de mesma cor permaneçam juntos?

(A) 72

(B) 96

(C) 128

(D) 216

(E) 576

## Resolução

Podemos usar o Princípio Fundamental da Contagem (PFC), para calcular todas estas possíveis maneiras diferentes. São 4 etapas independentes:

- Escolha da ordem das 3 cores
- Escolha da ordem dos carrinhos vermelhos
- Escolha da ordem dos carrinhos amarelos
- Escolha da ordem dos carrinhos azuis


Primeiro pensamos em como ordenar as 3 cores:

- Vermelho - Amarelo - Azul
- Vermelho - Azul - Amarelo
- Amarelo - Azul - Vermelho
- Amarelo - Vermelho - Azul
- Azul - Amarelo - Vermelho
- Azul - Vermelho - Amarelo

Só existem estas 6 formas, que também poderíamos pensar que são as 6 permutações possívesis de 3 elementos. \\( P_3 = 3! = 3 \cdot 2 \cdot 1 = 6 \\).

Já entre os carrinhos de mesma cor, eles são diferentes entre si, pois foi dito que os 8 carrinhos possuem modelos diferentes. Assim, na escolha de quantas formas podemos ordená-los, basta ver quantas permutações de X elementos (\\(P_X\\)) podemos calcular. Aqui X é o número de elementos da cor que queremos ordenar.

Vermelho: \\( P_2 = 2! = 2 \cdot 1 = 2 \\)

Amarelo: \\( P_2 = 2! = 2 \cdot 1 = 2 \\)

Azul: \\( P_4 = 4! = 4 \cdot 3 \cdot 2 \cdot 1 = 24 \\)

Portanto, conseguimos calcular as quantidade de formas possíveis para cada etapa. Aplicando o PFC, chegamos que são \\( 6 \cdot 2 \cdot 2 \cdot 24 = 576\\) formas de se ordenar os 8 carrinhos seguindo as condições dadas.

> Resposta: Alternativa (E)

