# URI-2654
  URI Online Judge | 2654
  Godofor
  Por Abner Samuel P. Palmeira, IFSULDEMINAS BR Brazil

  Timelimit: 1

Após a morte de Ares, o último godofor, os outros deuses decidiram fazer um concurso para decidir quem seria o novo godofor. Porém seres de diversos universos tinham interesse na vaga. Por haver tantos candidatos os deuses estão com muita dificuldade para selecionar um deles, então eles decidiram recorrer a você o deus da programação, eles querem que você desenvolva um programa que decida quem será o novo godofor com base nos critérios definidos pelos deuses.

Os candidatos serão avaliados com base em três atributos, nível de poder do candidato, quantos deuses o candidato já matou e quantas vezes o candidato já morreu. O godofor deve ser o candidato mais poderoso, caso ocorra empate deverá ser o candidato que mais matou outros deuses, caso ocorra empate novamente o escolhido será o candidato que menos morreu, se mesmo assim o empate persistir o godofor será o candidato com o menor nome lexicograficamente.

Entrada
A primeira linha contém um inteiro N (1 ≤ N ≤ 100)representando quantos seres se inscreveram para tentar ser o novo godofor. Cada uma das N linhas seguintes contém uma string S (1 ≤ |S| ≤ 100) representando o nome do ser, seguida por três inteiros P (1 ≤ P ≤ 100),K (1 ≤ K ≤ 100), M (1 ≤ M ≤ 100) representando respectivamente o poder do ser, quantos deuses ele já matou, e quantas vezes ele já morreu. A string é composta por letras maiúsculas e minúsculas.

Saída
Seu programa deverá exibir quem vai ser o novo godofor.

Exemplo de Entrada

5
Kratos 70 12 2
Goku 80 0 3
Kuririn 15 0 4
Saitama 100 0 0
Hulk 90 0 0

Exemplo de Saída

Saitama
