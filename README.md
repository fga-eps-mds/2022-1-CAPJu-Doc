# CAPJu - Documentação

<div align="center">
  <img src="https://i.imgur.com/0KsqIUe.png" alt="logo">
</div>

[![GitHub contributors](https://img.shields.io/badge/all%20contributors-12-orange?style=flat-square)](https://github.com/fga-eps-mds/2022-1-CAPJu-Doc/graphs/contributors) [![GitHub issues](https://img.shields.io/github/issues/fga-eps-mds/2022-1-CAPJu-Doc?style=flat-square)](https://github.com/fga-eps-mds/2022-1-CAPJu-Doc/issues)

## Sobre Projetos

O CAPJu é abreviação para _"Controle e Acompanhamento de Processos da Justiça"_, no qual trata-se de uma projeto de código aberto que tem como objetivo ajudar os usuários da 4ª vara cível da Justiça Federal na realização de gerenciar os processos.

Este repositório é destinado exclusivamente a Documentação do projeto, que está em sua maioria em Português do Brasil, devido aos interessados do público alvo.

O CAPJu é uma aplicação _Web_ compatível com qualquer navegador.

## Tecnologias

<img src="https://download.logo.wine/logo/Node.js/Node.js-Logo.wine.png" alt="nodeJS" height="80" width="auto"/><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmiro.medium.com%2Fmax%2F5000%2F1*M1XoId5pZaVJiIDAMDTDiw.png&f=1&nofb=1" alt="Express" height="50" width="100"/><img src="https://logos-download.com/wp-content/uploads/2016/09/MongoDB_logo_Mongo_DB.png" alt="MongoBD" height="50" width="100"/><img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongoose/mongoose.png" alt="Mogoose" height="80" width="auto"/><img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Flogos-download.com%2Fwp-content%2Fuploads%2F2016%2F09%2FReact_logo_logotype_emblem.png&f=1&nofb=1" alt="ReactJS" height="60" width="auto"/><img src="https://avatars.githubusercontent.com/u/40133106?s=200&v=4" alt="Docsify" height="60" width="auto"/>

## Repositórios

- [Doc](https://github.com/fga-eps-mds/2022-1-CAPJu-Doc)
- [User](https://github.com/fga-eps-mds/2022-1-CAPJu-User)
- [Service](https://github.com/fga-eps-mds/2022-1-CAPJu-Service)
- [Interface](https://github.com/fga-eps-mds/2022-1-CAPJu-Interface)

## Instalação

A aplicação encontra-se em homologação acessando o seguinte [LINK](https://capju.vercel.app/)

### Executando as coisas localmente

Quer ver o projeto funcionando em sua máquina?

Você precisará ter o [NodeJS](https://nodejs.org/en/) e o [Yarn](https://yarnpkg.com/) previamente instalados.

E o projeto foi implementado em máquinas com sistemas operacionais de distribuição Linux, portanto os passos encontrando a seguir mostram orientações de sistemas Linux.

Em caso de tentativa de execução em outros sistemas operacionais como, o Windows, recomenda-se uma pesquisa. E os usuários do MacOS certamente podem pagar alguém para descobrir como fazer isso.

**Executando os Serviços**

Nos repositórios _2022-1-CAPJu-Service_ e _2022-1-CAPJu-User_:

```bash
$ cd ~/your/directory/
$ git clone https://github.com/fga-eps-mds/2022-1-CAPJu-Service.git
$ cd 2022-1-CAPJu-Service
```

```bash
$ cd ~/your/directory/
$ git clone https://github.com/fga-eps-mds/2022-1-CAPJu-User.git
$ cd 2022-1-CAPJu-User
```

Caso exista um serviço MongoDB em nuvem, adicione a string de conexão a um arquivo `.env` dentro na pasta raiz do projeto com nome `MONGODB_URI`

Caso não seja configurada uma string de conexão personalizada, a aplicação se conectará à porta 27017 do serviço local

No arquvo `.env` também será necessário que adicione um string com nome `JWT_SECRET` para realização autenticação do usuário

<br>
<br>

No repositórios _2022-1-CAPJu-Interface_:

```bash
$ cd ~/your/directory/
$ git clone https://github.com/fga-eps-mds/2022-1-CAPJu-Interface.git
$ cd 2022-1-CAPJu-Interface
```

Será necessário que adicione uma variavel em um arquivo `.env` dentro na pasta raiz do projeto com nome `REACT_APP_DEV=true` para que possa executar na porta 3000 do serviço local

### Rodando a documentação localmente

Documentação construida com o gerador de site estático [**Docsify**](https://docsify.js.org/#/).

Para executar a documentação na sua máquina, primeiro você precisa instalar

```bash
$ yarn global add docsify-cli
```

ou

```bash
$ npm i docsify-cli -g
```

Depois basta executar

```bash
$ docsify serve docs
```

### Deployment

O build e deploy da documentação encontra-se no [GitHub Actions](https://github.com/fga-eps-mds/2022-1-CAPJu-Doc/actions).

## Contribuição

Certifique-se de ler o [Guia de Contribuição](https://github.com/fga-eps-mds/2022-1-CAPJu-Doc/blob/main/.github/CONTRIBUTING.md) antes de realizar qualquer atividade ao projeto!

## Licença

O CAPJu está sob as regras aplicadas na licença [MIT](https://github.com/fga-eps-mds/2022-1-CAPJu-Doc/blob/main/LICENSE)

## Contribuidores

| Disciplina | Matrícula | Nome                | Github                                                      |
| ---------- | --------- | ------------------- | ----------------------------------------------------------- |
| MDS        | 202023903 | Lucas Lopes         | [luclopesr](https://github.com/luclopesr)                   |
| MDS        | 170154319 | Philipe de Sousa    | [PhilipeSousa](https://github.com/PhilipeSousa)             |
| MDS        | 202016480 | Hellen Fernanda     | [Hellen159](https://github.com/Hellen159)                   |
| MDS        | 170142434 | Gabriel Araújo      | [GabrielGaba](https://github.com/GabrielGaba)               |
| MDS        | 180126130 | Luciano Alves       | [githubviramundo](https://github.com/githubviramundo)       |
| MDS        | 200042416 | Pablo Christianno   | [PabloChristianno](https://github.com/PabloChristianno)     |
| MDS        | 190091606 | Lucas Caldas        | [lucascaldasb](https://github.com/lucascaldasb)             |
| EPS        | 160006210 | Francisco Heronildo | [FranciscoHeronildo](https://github.com/FranciscoHeronildo) |
| EPS        | 140156909 | Nathalia Lorena     | [Natilorens](https://github.com/Natilorens)                 |
| EPS        | 160010331 | José Aquiles        | [aquiles23](https://github.com/aquiles23)                   |
| EPS        | 180013637 | Arthur Paiva        | [arthurpaivat](https://github.com/ArthurPaivaT)             |
| EPS        | 180023411 | Maicon Lucas        | [MaiconMares](https://github.com/MaiconMares)               |

<a href="https://github.com/fga-eps-mds/2022-1-CAPJu-Doc/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=fga-eps-mds/2022-1-CAPJu-Interface" />
</a>
