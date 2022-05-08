## Aula 3 - Concorrência

**Concorrência:** principio básico dos sistemas multiprogramaveis, onde 2 ou mais programas concorrem/disputam o uso do seu equipamento (to o seu recurso operacional)

**CPU Bound:** usa muita CPU

**I/O Bound:** usa muito I/O

**Throughput:** taxa de transferencia entre os barramentos

**Thread:** evolução de processo



**South Brigde** e **North Brigde**: deixou de ser trabalho da cpu e passa ser responsabilidade do controlador (está na placa-mães)

**Buffer**: área de memória temporárea que vai ser utilizada de alguma forma

___________________________________________

## Sistemas monoprogramável X multiprogramável

monoprogramável: apenas 1 tarefa ativa no sistema (2 programas, o SO e o programa do usuario)

multiprogramavel: varios aplicativos ativos no computador

____________________________
## Interrupção e Exceção

são muito parecidos porém interrupção se refere a hardware e exceção (trap) a software

**Interrupção:** evento externo, ex clique do mouse, chamada de sistema, impressora. Toda interrupção é assincrona (nao depende de nenhum programa pra ocorrer) e pode ocorrer múltiplas vezes.

**Exceção**: evento sincrono, pq depende da execução de programa. É um ponto do programa que aconteceu algum erro e ele precisa ser tratado pelo sistema operacional.
