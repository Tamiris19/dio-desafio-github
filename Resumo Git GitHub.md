# Resumo Git/GitHub



### Falando um pouco sobre o Git:

O Git foi criado por Linus Torvalds. Ele tem uma arquitetura distribuída, diante disso, é considerado seguro.

O Git tem três objetos internos: BLOBS; TREES; e COMMITS.

- Blobs: Cada arquivo no Git é armazenado como um objeto blob, a partir do conteúdo do arquivo ele gera um hash (SHA-1), ou seja, o Git vai guardar os arquivos encriptando-os;
- Trees: A árvore guarda toda estrutura de onde estão os arquivos. Ela aponta para os blobs (arquivos) e/ou outras árvores (diretórios);
- Commit: Ele vai juntar tudo, vai dar sentido à alteração que você está fazendo. Se você alterar um dado dentro de um blob, vai alterar os metadados de uma árvore, aí nessa aponta para outras árvores, e consequentemente vai refletir no COMMIT.



#### _Falando sobre GitHub..._

#### O Git e Github são complementares, mas não são a mesma coisa, eles são diferentes

### Então, qual a diferença entre Git e GitHub?

| O GitHub é uma plataforma que pode conter repositórios de código em armazenamento baseado em nuvem para que vários desenvolvedores possam trabalhar em um único projeto e ver as edições de cada um deles em tempo real. É uma plataforma colaborativa. |
| ------------------------------------------------------------ |
| **O Git é um software de controle de versão distribuído que permite aos desenvolvedores salvar seus projetos ao longo do tempo.** |

##### _Ou seja, o Git é uma ferramenta para versionar projetos, o GitHub é o site no qual você colocará esses projetos versionados._

Um ponto importante do GitHub é que ele identifica arquivo Markdown (md).

Para maiores informações sobre este tipo de arquivo, [clique aqui](https://www.markdownguide.org/basic-syntax/).

