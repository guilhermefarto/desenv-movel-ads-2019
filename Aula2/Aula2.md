# Hello, Ionic

Para criar uma nova aplicação baseada na plataforma Ionic, o comando ```ionic start``` (do Ionic CLI) deve ser executado:

```
$ ionic start <app-name> <template>
```

*Templates* de aplicações Ionic podem ser utilizados para simplificar a criação de um novo projeto a partir de um modelo

Por padrão, os valores ```blank```, ```tabs``` e ```sidemenu``` podem ser informados como *templates*

A listagem completa pode ser consulta por meio da instrução:

```
$ ionic start --list
```

Consulte a [documentação oficial da instrução ```ionic start```](https://ionicframework.com/docs/cli/commands/start)

## Criação do app 'Hello, Ionic'

1. Crie um diretório ```..\desenvmovel\workspace``` para armazenar os projetos;

2. Via terminal (*prompt* de comandos), navegue até este diretório;

3. Crie uma nova aplicação via Ionic CLI (com template ```blank```);

```
$ ionic start hello-ionic blank
```

> Nesta etapa, também são solicitadas (via terminal) algumas informações para criação do projeto como, por exemplo, (i) instalação do Ionic Appflow (inicialmente, informar ```n``` nesta opção), (ii)

> Além da criação da hierarquia padrão (estrutura do projeto Ionic), também é realizado o download das dependências do projeto que são armazenadas do diretório ```..\hello-ionic\node_modules```

> A estrutura inicial de um projeto Ionic com dependências pode resultar em um diretório de ```400 MB``` a ```500 MB```

4. Abrir o diretório do projeto ```..\desenvmovel\workspace\hello-ionic``` via Visual Studio Code (ou IDE de preferência);

![Projeto 'Hello, Ionic' no Visual Studio Code](img/Image1_VSCode_HelloIonic.png)

5. Navegue pelos diretórios e subdiretórios do projeto Ionic para conhecer sua estrutura

Em um novo projeto Ionic, os principais arquivos a serem analisados são:

* ```package.json```: arquivo responsável pela definição de dependências e bibliotecas do projeto;
* ```main.ts```: arquivo responsável pela inicialização da aplicação;

> Este arquivo quem define o fluxo inicial da página de abertura da aplicação

> ```main.ts```

> ```platformBrowserDynamic().bootstrapModule(AppModule)```

> ```app.module.ts```

> ```app.component.ts```

> ```app.component.html```

> ```app-routing.module.ts```

* Diretório ```\app\```: diretório que contém os arquivos da aplicação, incluindo páginas HTML, arquivos Javascript (.js) e Typescript (.ts), componentes, serviços e outros artefatos de desenvolvimento

> Tais artefatos podem ser gerados (criados) por meio da instrução:

```
$ ionic generate <type> <name> [options]
```

Consulte a [página sobre ```ionic generate```](https://ionicframework.com/docs/cli/commands/generate/) para detalhes

Também é possível verificar os tipos de artefatos da instrução ```ionic generate``` via terminal:

```
$ ng g --help
```

ou

```
$ ng g <type> --help
```

* Diretório ```\app\home```: diretório (de exemplo) do *template* ```blank``` utilizado na criação do projeto

> Neste diretório, podem ser localizados os ```home.module.ts```, ```home.page.html``` e ```home.page.ts``` de exemplo da aplicação
