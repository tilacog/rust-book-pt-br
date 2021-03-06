# Enums e Casamento de Padrões (_Pattern Matching_)

Neste capítulo vamos ver *enumerações*, também chamadas de *enums*. Enums
permitem definir um tipo por meio da enumeração de seus possíveis valores.
Primeiro, vamos definir e usar uma enum para mostrar como ela pode atrelar
significado aos nossos dados. Depois, vamos explorar uma enum particularmente
útil, chamada `Option`, que expressa um valor que tanto pode ser algo quanto
pode não ser nada. Em seguida, vamos ver como o casamento de padrões por meio
da expressão `match` facilita a execução de códigos diferentes para diferentes
valores de uma enum. Por fim, vamos abordar o `if let`, outra forma concisa e
conveniente que você pode usar para tratar enums no seu código.

Enums são ferramentas que aparecem em muitas linguagens, mas suas
características variam de uma para outra. Em Rust, enums são mais parecidas com
os *tipos de dados algébricos* das linguagens de programação funcional como F#,
OCaml e Haskell.
