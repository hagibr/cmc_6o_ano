# Questão 11

Vinícius resolveu criar uma estratégia de treinamento para participar da Maratona de Curitiba cujo percurso é de 42.195 m. A cada semana, ele corre 650 m a mais do que na semana anterior. Nesse ritmo ele correu na vigésima oitava semana 23.750 m.

Considerando as informações acima, pode-se estimar que faltam quantas semanas para Vinícius ultrapassar pela primeira vez a medida da Maratona de Curitiba?

(A) 20 semanas

(B) 24 semanas

(C) 26 semanas

(D) 29 semanas

(E) 32 semanas

<details>
  <summary>Resolução</summary>
  
  ## Resolução

  Como a cada semana existe um acréscimo de 650 m em relação à semana anterior, podemos dizer que as quantidade de metros em relação ao número da semana formam uma Progressão Aritmética (P.A.).
  Na P.A., o termo geral \\(a_n\\) é calculado por:
  \\[a_n = a_1 + (n-1) \cdot r\\]
  Sendo \\(a_1\\) o primeiro termo, que no caso seria a quantidade de metros da 1ª semana, \\(n\\) é o número da semana e \\(r\\) a razão, ou seja, 650.
  Vamos calcular \\(a_1\\):
  \\[a_1 = a_{28} - (28-1) \cdot r = 23750 - 27 \cdot 650 = 23750 - 17550 = 6200\\]
  OK, sabendo que na primeira semana ele percorrei 6200 metros, podemos calcular qual será a semana \\(k\\) que ultrapassará o valor de 42195:

  \\[
    a_1 + (k-1) \cdot r > 42195 \\\\
    6200 + (k-1) \cdot 650 > 42195 \\\\
    (k-1) \cdot 650 > 42195 - 6200 \\\\
    k-1 > \frac{35995}{650} \\\\
    k > 1 + \text{55,37} \\\\
    k > \text{56,37}
  \\]
  O menor valor possível inteiro de k é 57. Se estamos na 28ª semana, faltam 29 semanas.

  > Resposta: Alternativa (D)

</details>