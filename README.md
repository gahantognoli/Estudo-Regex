# Estudo Expressões Regulares

### Regex operators
* | = OU
* i = ignorecase
* g = extrai um padrão mais do que uma correspondencia.
* . = coringa = simboliza qualquer caracter.
* [ abcd ] = encontrar um grupo de caracter definidos no interior dos colchetes.
* [ a-z ] = encontrar o range definidos no interior dos colchetes.
* [ ^abcd ] = negar um conjunto de caracteres
* "+" = encontrar um caracter ou conjunto de caracteres que se repetem em sequencia.
* "*" = enncontrar zero ou mais repetições no conjunto de caracteres
* "?" = lazy matching
* "^" = Pesquisar por padrões no **começo** de uma string.
* "$" = Pesquisar por padrões no **fim** de uma string.
* "\w" = Pesquisa por qualquer letra do alfeto ou número tanto em caixa alta quanto em caixa baixa em uma string. (incluindo também o "_").
* "\W" = Pesquisa por qualquer caracter que não seja uma letra do alfeto ou número tanto em caixa alta quanto em caixa baixa em uma string. 
* "\d" = Pesquisa por números **(e somente números)** em uma string.
* "\D" = Pesquisa por caracteres não números **(incluindo caracteres especiais)** em uma string.
