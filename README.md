Repositório para a atividade 5.2 de Computação Experimental Esta tarefa utiliza os arquivos disponibilizados no repositório: https://github.com/projectmesa/mesa

O exemplo em questão utilizado para realização da tarefa 'bank_reserves', que consiste na seguinte situação, cada pessoa se move por um espaço, tendo a chance de encontrar com outra pessoa e, novamente, tendo a chance de trocar dinheiro com essa outra pessoa. Todas as probabilidades desse teste, com exceção dos encontros, são de 50%. Esses testes feitos separam as pessoas presentes no espaço em 3 "catetgorias", ricos, 'pobres' e 'classe média'. Nos testes feitos usando as ferramentas, o ponto de início é a 'classe média' e irão evoluindo ou regredindo de acordo com a classe se irá passar a ser, rica ou pobre respectivamente.

A hipótese causal em questão foi criar um cenário onde existissem em maioria pessoas pobres, ou que o número de pessoas pobres fosse superior a pessoas de classe média ou ricas. Para isso atualizei as trocas que as pessoas devem fazer e diminui a quantidade de empréstimos que a pessoa pode fazer.

Essas alterações foram feitas, apenas nos arquivos agents.py e model.py.


No arquivo agents.py, as linhas alteradas foram a 79, 80, 84 e 85. E no arquivo model.py as linhas alteradas para testar a hipótese causal, foram as linhas 38 e 48. No arquivo 


Para execução do código em questão onde foi testada a hipótese, basta rodar mesa runserver bank_reserves.
