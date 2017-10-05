## Começando a usar o `ghci`

### Mostrando a ajuda
`:?`

### Mudando o prompt de "Prelude>" para "ghci>"

`:set prompt "ghci>"`


### É possível fazer operações aritméticas como no python
`1 + 4`  
`6 - 2`  
`3 * 7`  
`10 / 2` -- Divisão padrão. Fracionada.  
`2 * (-10)`  
  
10 \`div\` 2 -- Igual à 5. Divisão inteira.  
10 \`mod\` 2 -- Igual à 0. Módulo.  
  
`True && True`  
`False || True`  
`not True`  
  
`1 == 1`  
`10 == 3`  
`10/=3` -- Resultado True. Esse é o sinal de diferente no Haskell.  
`5 > 10`  -- False.  
`5 <= 10`  -- True.  
`"Olá" == "Olá"` -- Resultado é True.  
