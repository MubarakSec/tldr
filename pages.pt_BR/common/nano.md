# nano

> Editor de texto de linha de comando. Um clone melhorado de `Pico`.
> Mais informações: <https://nano-editor.org/dist/latest/nano.html>.

- Inicia o editor:

`nano`

- Inicia o editor sem usar arquivos de configuração:

`nano {{[-I|--ignorercfiles]}}`

- Abre arquivos específicos, passando para o próximo arquivos ao fechar o anterior:

`nano {{caminho/para/arquivo1 caminho/para/arquivo2 ...}}`

- Abre um arquivo e posiciona o cursor na linha e coluna especificadas:

`nano +{{linha}},{{coluna}} {{caminho/para/arquivo}}`

- Abre um arquivo e habilita soft wrapping:

`nano {{[-S|--softwrap]}} {{caminho/para/arquivo}}`

- Abre um arquivo e indenta novas linhas de acordo com a indentação da linha anterior:

`nano {{[-i|--autoindent]}} {{caminho/para/arquivo}}`

- Abre um arquivo e cria um arquivo de backup (`caminho/para/arquivo~`) ao salvá-lo:

`nano {{[-B|--backup]}} {{caminho/para/arquivo}}`
