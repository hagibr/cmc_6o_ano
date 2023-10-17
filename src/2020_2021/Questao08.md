# Questão 8

O *display* de um relógio digital que está situado na sala de aula do aluno João é formado por lâmpadas que podem ser ligadas ou desligadas de forma independente. Cada dígito pode ser composto por até 7 (sete) lâmpadas ligadas e o display é formado por 4 (quatro) blocos (dezena da hora, unidade da hora, dezena do minuto, unidade do minuto), conforme a figura 1.

![image](./questao08_fig01.png)

No entanto, o relógio dessa sala de aula está com defeito.

Nos quatro blocos, exatamente as mesmas duas lâmpadas de cada bloco queimaram e se mantém desligadas.

Considere que no exato momento em que João olha para o relógio, o horário mostrado é o da representação da figura 2:

![image](./questao08_fig02.png)

Com relação à figura 2, qual será a representação do relógio passados 21 (vinte e um) minutos após João tê-lo olhado?

(A)

![image](./questao08_figA.png)

(B)

![image](./questao08_figB.png)

(C)

![image](./questao08_figC.png)

(D)

![image](./questao08_figD.png)

(E)

![image](./questao08_figE.png)

<details>
  <summary>Resolução</summary>
  
  ## Resolução

  Observando o dígito referente às unidades de hora, vemos que das 7 lâmpadas, 5 estão acesas. Assim, a única possibilidade é que as lâmpadas queimadoa sejam a central e a inferior direita.

  Os valores possíveis para as dezenas de horas são 0 (para valores de horas de 00~09), 1 (para valores de horas 10~19) e 2 (para valores de horas 21~23). Não pode ser dezena 0 porque obrigatoriamente a lâmpada superior esquerda estaria acesoa e não pode ser 1 porque para formar este dígito só podem estar acesas as lâmpadas superior direita e inferior direita. Sendo assim, a conclusão é que este dígito é o 2, ou seja, o dígito para unidades de horas só pode ser o 0, pois é o único que pode formar uma hora válida (20, 21, 22, 23), dadas as lâmpadas que já estão acesos.

  Agora vamos pensar nos minutos. Nas dezenas só podemos ter o dígito 3, pois não tem como formar algo válido acendendo somente 1 das lâmpadas queimadas. E nas unidades só pode ser o dígito 9, pelos mesmos motivos.

  Assim, concluímos que quando João olha para o relógio são 20:39h, e quando se passam 21 minutos, chegamos a 21:00h, mas não podemos marcar a alternativa (B) por conta das lâmpadas queimadas, então temos que imaginar como seria a representação de 21:00h com os lâmpadas central e inferior direita apagadas.

  > Resposta: Alternativa (C)

</details>