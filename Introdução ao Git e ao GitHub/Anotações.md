# Anotações :pen:

- O que é o Git?

  O Git é um sistema open-source de controle de versão utilizado pela grande maioria dos desenvolvedores atualmente. Com ele podemos criar todo histórico de alterações no código do nosso projeto e facilmente voltar para qualquer ponto para saber como o código estava naquela data.

  

- O que é o GitHub?

  O ***\*Github\**** é um serviço online de hospedagem de ***\*repositórios\**** ***\*Git\**** (como são chamados os projetos que utilizam Git). Com ele podemos manter todos nossos **commits** e ramos sincronizados entre os membros do time.

  

- Qual a vantagem do GitHub?

  Para os profissionais da área de tecnologia, as vantagens de utilizar o GitHub são inúmeras.

  A maior delas, talvez, seja a oportunidade de aprender com programadores e programadoras mais experientes que você, especializado nas mesmas ou em diferentes áreas. 

  Estas conexões são riquíssimas para os estudantes.

  Outros benefícios são:

  - Possibilidade de acompanhar e colaborar com projetos de diferentes equipes;

  - Aprender programação na prática ao observar o avanço do desenvolvimento de aplicações de terceiros;

  - Participar de discussões a respeito de novas tecnologias;

  - Obter auxílio de outros programadores para resolver problemas relacionados a seus projetos;

  - Controlar as diferentes versões de um código com armazenamento em nuvem;

  - Registrar ações e projetos desenvolvidos por você em uma espécie de portfólio online, etc.

    

- O que é um repositório Git?

  Um [repositório do Git](https://bitbucket.org/product/br/code-repository) é um armazenamento virtual para projetos. Ele permite que você salve versões do código, que você pode acessar quando precisar.

  Você pode possuir um ou mais repositórios, públicos ou privados, locais ou remotos, e eles podem armazenar não somente os próprios códigos a serem modificados, mas também imagens, áudios, arquivos e outros elementos relacionados ao seu projeto.

  É através dos seus repositórios públicos que outros programadores poderão ter acesso aos seus códigos no GitHub, podendo, inclusive, cloná-los para adicionar melhorias.

  

- Conceito de Branch

  Branches são os ramos, cópias do código original que podem ser manipuladas de forma livre pela pessoa que trabalha em programação, sem afetar as funcionalidades em produção no código-fonte.

  Isso **permite que todas as alterações sejam realizadas de forma segura**, sem que erros ocorram na cópia principal do projeto.

  

- Inicializando um novo repositório: **git init**

  Para criar um novo repositório, você vai usar o comando `git init`. `git init` é um comando único que você usa durante a configuração inicial de um novo repositório. A execução desse comando cria um novo subdiretório `.git` no diretório de trabalho atual. Essa ação também vai criar uma ramificação principal.

  *git init <project directory>*

  

- Clonando um repositório existente: **git clone**

  Se um projeto já foi configurado em um repositório central, o comando clonar é a forma mais comum para os usuários obterem um clone de desenvolvimento local. `git clone` é usado para criar uma cópia ou clone de repositórios remotos. Você transmite o `git clone` em uma URL de repositório. O Git é compatível com alguns protocolos de rede diferentes e formatos correspondentes de URL.

  *git clone <repo url>*

  

- **git add**

  O comando `git add` adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, `git add` não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar `git commit`.

  Junto com esses comandos, você também vai precisar de `git status` para ver o estado do diretório ativo e da área de staging.

  

- **git commit**

  Este comando move os arquivos da *stage area* para um repositório local.

  

- **git push**

  Este comando envia arquivos de um repositório local para um repositório remoto. No GitHub, por exemplo.

  

- **git pull**

  Ao contrário do push, este comando traz um arquivo do repositório remoto para o repositório local.

  

- **git merge**

  Este comando serve para unir arquivos alterados ao arquivo original de um projeto. Em outras palavras, é ele quem une os branchs as *commits*.

  

## Links Úteis

[Download do Git] (https://git-scm.com/downloads)

[Documentação do Git] (https://git-scm.com/doc)
