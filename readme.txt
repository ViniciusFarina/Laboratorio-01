Foram notadas as seguintes variações na temporização devido a alteração dos níveis de otimização do compilador, conforme segue:

Level none: aproximadamente 1 segundo em cada estado;

Level low: LED D4 aproximadamente 1 segundo em cada estado;

Level medium: Frequência do LED D4 mais que dobrou;

Level high: Led D4 sempre ligado, o programa não entra mais no laço de repetição FOR, ao utilizar o step over, ele até troca de estado, mas não passa pelo FOR;

Retornando ao nível de otimização low e alterando a frequência de clock de 24Mhz para 120Mhz a frequência de troca de estados ficou semelhante ao caso com 24Mhz e nível de otimização do compilador em medium.
