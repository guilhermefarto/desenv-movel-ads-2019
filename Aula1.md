# Plataforma Ionic

## Instalação e configuração

#### 1. Nodejs e npm

[**Nodejs**](https://nodejs.org/) é um ambiente de execução que permite o processamento de Javascript em *server-side*

Possui diversas ferramentas e utilitários para desenvolvedores como, por exemplo, Ionic CLI - uma interface de comando que contribui com o desenvolvimento de aplicações na plataforma Ionic, simplificando desde (i) a criação de um novo projeto a partir de um *template*, (ii) a geração de novos artefatos (como páginas e componentes customizados), (iii) a compilação e distribuição final (empacotamento), bem como outras *features* importantes no contexto de desenvolvimento móvel

[**npm**](https://www.npmjs.com/) (ou *Node Package Manager*) é um gerenciador de pacotes (ou módulos) para a plataforma Nodejs

Permite que desenvolvedores instalem, desenvolvam, empacotem e compartilhem suas dependências (ou bibliotecas) como sendo módulos de pacotes para Nodejs

A plataforma **[Ionic](https://ionicframework.com/)** pode ser instalada por de um ambiente de desenvolvimento baseado em Nodejs e npm

Para verificar se o ambiente já está configurado com Nodejs e npm, execute as instruções abaixo no "*terminal (prompt) de comandos*".

###### Versão do Nodejs
```
$ node --version
```
> v10.13.0

###### Versão do npm
```
$ npm --version
```
> 6.4.1

#### 2. Ionic CLI (*Command Line Interface*)

Após instalação do ambiente Nodejs e npm, deve-se instalar a ferramenta **Ionic CLI**, uma interface de comandos específica para a plataforma Ionic que possui ferramentas e utilitários para desenvolvedores

Para instalar o Ionic CLI [globalmente](https://docs.npmjs.com/downloading-and-installing-packages-globally), execute a instrução:

```
$ npm install -g ionic
```

Assim como realizado para o Nodejs e npm, a versão do Ionic CLI pode ser verificada:

###### Versão do Ionic CLI
```
$ ionic info
```

##### Ionic Help

Pode-se acessar o recurso de ajuda (*help*) do Ionic CLI por meio da instrução:

```
$ ionic --help
```

Além disto, também se pode especificar o comando desejado na consulta:

```
$ ionic <command> --help
```

> Por exemplo, ```ionic start --help```

