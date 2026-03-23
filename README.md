# apresentacao-bim1-2026a-gabriel-maroneze
apresentacao-bim1-2026a-gabriel-maroneze created by GitHub Classroom

Paradigmas de Programação
Gabriel Maroneze Ramos – 202512445

Tuplas
•	O que são?
Tuplas são, nada mais que estruturas de dados imutáveis – ou seja, uma vez que criados, seus valores não podem ser alterados, adicionados ou removidos.
Tuplas podem conter elementos de diferentes tipos, como números, strings, e até mesmo outras tuplas.
Cada elemento da túpla possui uma posição definida, um índice, que é usado para acessar o tal elemento.
Tuplas podem ser usadas para representar dados fíxos, agrupar diferentes dados que sejam relacionados e substituir o uso de estruturas de dados mais complexas (structs)

•	Tuplas em Haskell
O tipo de uma tupla será definido pelos tipos dos seus elementos
Tuplas serão escritas entre parênteses, com o uso de vírgulas

Exemplo de definição de uma tupla:

(“Cândia”, 19) :: (String, Int)
(True, “C”, 3,14) :: (Bool, Char, Float)

Haskell apresenta algumas funções específicas para tuplas prontas, dentre elas:

fst (First), que retorna o primeiro elemento da tupla
snd (Second), que retorna o segundo elemento da tupla

•	Tuplas em Python
Tuplas serão escritas entre parênteses(ou sem, em casos específicos), também com o uso de vírgulas

Exemplo:

aluno = (“Gabriel”, 20, 1.75)
indice = (5,) >>> Python aceita tuplas de 1 elemento, desde que contenha uma vírgula
coordenadas = (5, 6)
Python tem algumas funções úteis para o uso com tuplas, são elas:

len((3, 2, 5)) que retorna o número de elementos da tupla
max(3, 5, 2) que retorna o maior elemento da tupla
min(3, 5, 2) que retorna o menor elemento da tupla


