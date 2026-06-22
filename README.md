# Liturgia Cantada

Bem-vindo ao Liturgia Cantada, um recurso central para o estudo e a prática do canto gregoriano.

Os aplicativos e ferramentas aqui reunidos são desenvolvidos e/ou mantidos pela **AISCGre-BR** — *Associação Internacional de Estudos de Canto Gregoriano, Seção Brasileira*, dedicada à pesquisa, ao ensino e à interpretação do repertório gregoriano no Brasil, na linha semiológica de Dom Eugène Cardine, OSB.

*   🌐 **Site oficial:** [aiscgre.org.br](https://aiscgre.org.br/)
*   💻 **GitHub:** [github.com/AISCGre-BR](https://github.com/AISCGre-BR)

## Aplicativos Web

*   **Augustinus:** [augustinus.liturgiacantada.com.br](https://augustinus.liturgiacantada.com.br) - O Augustinus é uma ferramenta robusta para a criação de partituras em notação gregoriana, utilizando o formato GABC. A aplicação automatiza o complexo processo de silabificação de textos em português e atribui as notas musicais adequadas conforme o tipo de canto litúrgico selecionado — como Oração, Salmo, Evangelho ou Prefácio. Com uma interface intuitiva, o Augustinus simplifica a composição de peças musicais, tornando a notação gregoriana mais acessível a músicos, estudiosos e liturgistas.

*   **GregoSearch:** [busca.liturgiacantada.com.br](https://busca.liturgiacantada.com.br) - GregoSearch é uma interface de busca avançada e interativa para o vasto acervo de cantos gregorianos do GregoBase. A ferramenta permite aos usuários localizar cantos específicos com precisão, utilizando filtros por título (incipit), parte do ofício e modo. Além da busca, oferece a visualização da partitura e funcionalidades de exportação em formatos GABC e SVG, facilitando o uso do material em outros softwares e publicações.

## Aplicativo Desktop

*   **Notker:** [github.com/AISCGre-BR/notker](https://github.com/AISCGre-BR/notker) - Editor desktop de canto gregoriano (GABC/NABC) construído com Tauri e CodeMirror 6. Reúne realce de sintaxe, diagnósticos e formatação em tempo real, transposição de notas, busca de neumas e renderização de partituras num só ambiente. Nomeado em homenagem a Notker Balbulus. *(Em fase alpha, distribuído sob licença GPL-3.0.)*

## Ferramentas para Editores de Código

Suporte completo a GABC/NABC em diversos editores, compartilhando a mesma gramática [tree-sitter-gregorio](https://github.com/AISCGre-BR/tree-sitter-gregorio) e o servidor de linguagem [gregorio-lsp](https://github.com/AISCGre-BR/gregorio-lsp).

*   **vscode-gregorio:** [github.com/AISCGre-BR/vscode-gregorio](https://github.com/AISCGre-BR/vscode-gregorio) - Extensão para o Visual Studio Code com realce de sintaxe (TextMate e semântico via tree-sitter), diagnósticos, *hover*, autocompletar, símbolos, formatação, comandos de edição (transposição de notas, preenchimento de grupos vazios, conversão de ligaduras) e *snippets* para arquivos GABC/NABC.

*   **zed-gregorio:** [github.com/AISCGre-BR/zed-gregorio](https://github.com/AISCGre-BR/zed-gregorio) - Extensão para o editor Zed com suporte à notação gregoriana GABC/NABC.

*   **gregorio.nvim:** [github.com/AISCGre-BR/gregorio.nvim](https://github.com/AISCGre-BR/gregorio.nvim) - Plugin para o Neovim com suporte à linguagem GABC/NABC.

*   **gregorio-lsp:** [github.com/AISCGre-BR/gregorio-lsp](https://github.com/AISCGre-BR/gregorio-lsp) - Implementação completa do *Language Server Protocol* (LSP) para arquivos GABC/NABC, escrita em Rust. Oferece análise semântica, validação da alternância `nabc-lines`, verificação de referências cruzadas, autocompletar, informações de *hover* e diagnósticos em tempo real.

*   **tree-sitter-gregorio:** [github.com/AISCGre-BR/tree-sitter-gregorio](https://github.com/AISCGre-BR/tree-sitter-gregorio) - Gramática tree-sitter para a notação GABC+NABC.

*   **gregolint:** [github.com/AISCGre-BR/gregolint](https://github.com/AISCGre-BR/gregolint) - Linter de linha de comando para arquivos GABC do Gregorio, reutilizado como núcleo de verificação pelo LSP e pela extensão do VS Code.

## Outras Ferramentas

*   **Mocquereau:** [github.com/AISCGre-BR/mocquereau](https://github.com/AISCGre-BR/mocquereau) - Ferramenta de tabelas neumáticas comparativas para o estudo do canto gregoriano.

## Guia de GABC

*   **[Guia de referência rápida para GABC](https://gregoriochant.org/dokuwiki/doku.php/cheat_sheet)** - Um guia de referência rápida para a sintaxe GABC, a notação usada pelo software Gregorio para escrever partituras de canto gregoriano.

## Links Úteis

Uma seleção de links para projetos e bancos de dados essenciais para estudantes e entusiastas do canto gregoriano.

*   **Projeto Gregorio:** [gregorio-project.github.io](https://gregorio-project.github.io) - O Projeto Gregorio é uma iniciativa de software livre e de código aberto que fornece um conjunto de ferramentas para a composição de partituras de canto gregoriano. O seu principal componente converte arquivos de texto simples, escritos numa sintaxe chamada `gabc`, em partituras de alta qualidade através do sistema de composição tipográfica TeX. O projeto é amplamente adotado por abadias e grandes projetos de música litúrgica.

*   **GregoBase:** [gregobase.selapa.net](http://gregobase.selapa.net) - GregoBase é um extenso banco de dados de partituras de canto gregoriano. O projeto, embora em desenvolvimento contínuo, já oferece um vasto repositório de cânticos e é um recurso valioso para a comunidade, contendo milhares de partituras, incluindo coleções completas como o Gradual e o Antifonário Dominicano.

*   **GregoWiki:** [gregoriochant.org](https://gregoriochant.org) - Um wiki com documentação, tutoriais e recursos para o software Gregorio.
