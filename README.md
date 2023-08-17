# Prova_2_IA
Repositório com os códigos da prova de IA

# Alunos
Hugo de Abreu Biella

Pedro Augusto Borges Assis

# Tema
Problema da mochila (Knapsack problem)

# Metodologia
O método utilizado foi uma busca local iterativa utilizando uma estratégia de busca aleatória, onde uma solução inicial é gerada aleatoriamente.

- A cada iteração, um vizinho(neighbor[i]) da solução atual(current_solution) é gerado fazendo pequenas mudanças aleatórias.

- Se o vizinho violar alguma restrição do problema (no caso da mochila, se o peso exceder a capacidade), ele é descartado(0).

- Se válido, é avaliado se ele é uma melhoria em relação à solução atual, ou seja, a solução atual é atualizada para esse vizinho(1).

No final, o código demonstra os items que estão, ou não, dentro da mochila (1 - dentro / 0 - fora), o peso(weight) total dos items que estão na mochila, o valor(value) total dos items que estão na mochila, e retorna(if weight > C) se o peso excedeu o limite total da mochila(C).
