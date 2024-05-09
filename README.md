# trabalhoCPA


*Bin Packing (BP)*

A entrada consiste de n itens, que devem ser empacotados em caixas de um tamanho inteiro fixo B.
Os tamanhos dos itens são denotados como s1,··· ,sn e o objetivo é encontrar um empacotamento que minimize a quantidade de caixas necessárias para guardar todos os itens. Portanto, a entrada é um arranjo s de forma que s[i] representa o tamanho do item i e um inteiro B; e a saída é um conjunto de conjuntos E = {P1,··· , Pk}, onde cada Pi representa um pacote com itens cuja soma dos tamanhos não ultrapasse B, além disso, a quantidade |E| de pacotes deve ser mínima.

Devem ser entregues dois algoritmos: um de força bruta e um algoritmo aproximado/heurística.

A entrada dos dados é manual e será compilado utilizando um makefile, portanto é necessário um arquivo makefile para definir o uso do software.

Organização do código: (1) dê nomes a variáveis, funções e estruturas que façam sentido semântico; (2) divida a implementação em módulos que tenham um significado bem definido; (3) acrescente comentários sempre que julgar apropriado; (4) não é necessário parafrasear o código, mas é interessante acrescentar descrições de alto nível que ajudem outras pessoas a entender como sua implementação funciona; (5) evite utilizar variáveis globais; (6) mantenha as funções concisas: seres humanos não são muito bons em manter uma grande quantidade de informação na memória ao mesmo tempo. Funções muito grandes, portanto, são mais difíceis de entender; (7) lembre-se de indentar o código: escolha uma forma de indentar (tabulações ou espaços) e mantenha-se fiel a ela, misturar duas formas de indentação pode fazer com que o código fique ilegível quando você abri-lo em um editor de texto diferente do que foi utilizado originalmente; (8) evite linhas de código muito longas.
