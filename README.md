Como funciona a otimização:
A cada fase, o algoritmo percorre o vetor e compara os elementos adjacentes.
Se houver pelo menos uma troca, a flag trocou é definida como true, indicando que ainda há desordem no vetor.
Se ao final de uma fase não houver trocas (isto é, trocou permanece false), o vetor já está ordenado e o algoritmo para, economizando tempo de execução em casos de vetores já ordenados ou quase ordenados.
