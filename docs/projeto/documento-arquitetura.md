# Documento de Arquitetura

# 1. Introdução

## 1.1 Objetivo

<p>O documento apresentado tem como finalidade oferecer uma visão abrangente da arquitetura do projeto. Dessa forma, utilizou-se visões arquiteturais que ilustram o desenvolvimento do sistema, contendo informações que compreendem as tecnologias envolvidas e suas interações. Logo, por intermédio deste documento busca-se esclarecer as decisões arquiteturais estabelecidas pela equipe durante o desenvolvimento do projeto.<p>

## 1.2 Escopo

CAPJu é uma aplicação web que propõe a gerência de processos jurídicos e automatizar tarefas repetidas realizadas via planilha. Os processos passam por etapas, e a proposta da aplicação consiste em proporcionar ao usuário um controle e acompanhamento de cada processo, como por exemplo, movimentar processos de acordo com sua categoria e etapa. Este documento tratará dos padrões de arquitetura, tecnologias, frameworks e a integração entre esses mecanismos para o desenvolvimento dessa aplicação.

## 1.3 Definições, acrônimos e abreviações

| Sigla     | Significado                                       |
| --------- | ------------------------------------------------- |
| **CAPJu** | Controle e Acompanhamento de Processos da Justiça |
| **HTTP**  | Hypertext Transfer Protocol                       |
| **API**   | Application Programming Interface                 |
| **CSS**   | Cascading Style Sheets                            |
| **JSON**  | JavaScript Object Notation                        |

## 1.4 Visão Geral

Este documento detalha os padrões arquiteturais do CAPJu, como também aborda as tecnologias utilizadas para o desenvolvimento. Para isso, os documento foi estruturado da seguinte forma:

|       | Tópico                                | Descrição                                                                                                                    |
| ----- | ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **1** | **Introdução**                        | Fornece ao leitor uma visão geral do conteúdo abordado no documento                                                          |
| **2** | **Representação da Arquitetura**      | Detalha a arquitetura utilizada no projeto e como ela está organizada                                                        |
| **3** | **Metas e Restrições da Arquitetura** | Descreve os objetivos do projeto, como também suas restrições, do ponto de vista arquitetural                                |
| **4** | **Visão Lógica**                      | Fornece ao leitor uma base para compreender a estrutura e a organização do design do sistema                                 |
| **5** | **Visão de Implementação**            | Fornece ao leitor uma base que permitirá compreender a distribuição física do sistema em um conjunto de nós de processamento |
| **6** | **Referências**                       | Fornece ao leitor um conhecimento das referências utilizadas durante a criação deste documento                               |

# 2. Representação da Arquitetura

## 2.1 Tecnologias

No que diz respeito às tecnologias que serão necessárias para o desenvolvimento temos as seguintes:

### React

O React é uma biblioteca JavaScript de código aberto com foco em criar interfaces de usuário em páginas web.

### Jest

Jest é um framework de teste em JavaScript projetado para garantir a correção de qualquer código JavaScript. Ele permite que você escreva testes com uma API acessível, familiar e rica em recursos que lhe dá resultados rapidamente.

### Styled-Components

Styled-components é uma biblioteca para React e React Native que permite que você use estilos ao nível de componente na sua aplicação. Eles são escritos em uma mistura de JavaScript com CSS.

### Docker

Docker é um conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados contêineres. Os contêineres são isolados uns dos outros e agrupam seus próprios softwares, bibliotecas e arquivos de configuração.

### NodeJs

Node.js é um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web.

### ExpressJs

Express.js é um framework para Node.js que fornece recursos mínimos para construção de servidores web. Foi lançado como software livre e de código aberto sob a Licença MIT. É um dos mais populares frameworks para servidores em Node.js.

### Joi

É uma poderosa linguagem de descrição de esquema e validador de dados para JavaScript. O Joi permite descrever dados usando uma linguagem simples, intuitiva e legível.

### MongoDB

MongoDB é um software de banco de dados orientado a documentos livres, de código aberto e multiplataforma. É classificado como um programa de banco de dados NoSQL. Além disso, o MongoDB usa documentos semelhantes a JSON com esquemas.

# 3 Metas e Restrições da Arquitetura

## 3.1 Metas

- Reusabilidade de código
- Baixo acoplamento, facilitando a manutenabilidade
- Tornar o desenvolvimento do aplicativo mais rápido

## 3.2 Restrições

- Depende de uma conexão com a internet
- Possuir conexão com a API;
- Possuir conexão com o Banco de Dados;

# 4. Visão Lógica

## 4.1 Visão Geral

![CAPJu](https://i.imgur.com/M8w2uwA.png)

O projeto CAPJu utiliza uma arquitetura **MVC** que é uma sigla do termo em inglês Model (modelo) View (visão) e Controller (Controle), este modelo facilita a troca de informações entre a interface do usuário e dados no banco, fazendo com que as respostas sejam mais rápidas e dinâmicas.

A camada **Model** possui a responsabilidade da lógica/regra de negócio, de cada módulo, após fazer o tratamento dos dados, é feito mais um mapeamento para o banco de dados, que fará o processamento requisitado e irá retorná-lo. Para essa camada será utilizado o **MongoDB**.

A partir da camada **View**, o cliente através de uma aplicação web, terá acesso a uma interface e poderá realizar requisições ao sistema quando for necessário interagir com o banco de dados. O **React** será responsável pela camada View.

A camada **Controller** será responsável por intermediar as requisições enviadas pela camada View com as respostas fornecidas pela camada Model, processando os dados que o usuário informou e repassando para outras camadas. Nessa camada será utilizado o **NodeJs**.

## 4.2 Diagrama de Pacotes

### Frontend

![Frontend](https://i.imgur.com/RDxTSwK.png)

### Backend

![Backend](https://i.imgur.com/LGhP9rk.png)

# 5. Visão de implementação

## 5.1 Diagrama de Classes

![Diagrama de Classes](https://i.imgur.com/MACcrVs.png)

# 6 Referências

Marcio. Padrão MVC - Java Magazine. Devmedia, 2011. Disponível em: <https://www.devmedia.com.br/padrao-mvc-java-magazine/21995>. Acesso em: 25 de jul. de 2022.

ZUCHER, Vitor. O que é padrão MVC? Entenda arquitetura de softwares!. lewagon, 2020. Disponível em: <https://www.lewagon.com/pt-BR/blog/o-que-e-padrao-mvc#:~:text=O%20MVC%20%C3%A9%20uma%20sigla,sejam%20mais%20r%C3%A1pidas%20e%20din%C3%A2micas>. Acesso em: 25 de jul. de 2022.

KOVACS, Leandro. O que é e para que serve o MongoDB?. Tecnoblog, 2022. Disponível em: <https://tecnoblog.net/responde/o-que-e-e-para-que-serve-o-mongodb/>. Acesso em: 25 de jul. de 2022.

Joi. Joi. Introdução ao Joi. Disponível em: <https://joi.dev/api/?v=17.6.0#introduction>. Acesso em: 25 de jul. de 2022.

Jest. Jest. Página inicial. Disponível em: <https://jestjs.io/pt-BR/>. Acesso em: 25 de jul. de 2022.

React. React. Página inicial. Disponível em: <https://pt-br.reactjs.org/>. Acesso em: 25 de jul. de 2022.

Docker (Software). Wikipedia. Disponível em: <https://pt.wikipedia.org/wiki/Docker_(software)>. Acesso em: 25 de jul. de 2022.

Express.js. Wikipedia. Disponível em: <https://pt.wikipedia.org/wiki/Express.js>. Acesso em: 25 de jul. de 2022.

# Histórico de versões

| Data       | Versão | Descrição                                                            | Autor                   |
| ---------- | ------ | -------------------------------------------------------------------- | ----------------------- |
| 26/07/2022 | 0.1    | Adicionando o tópico de Introdução e Objetivo                        | Pedro, Pablo e Nathalia |
| 26/07/2022 | 0.2    | Adicionando o tópico de Escopo                                       | Pedro, Pablo e Nathalia |
| 31/07/2022 | 0.3    | Adicionando o tópico de Definições, acrônimos e abreviações          | Nathalia                |
| 31/07/2022 | 0.4    | Adicionando o tópico de Visão Geral                                  | Nathalia                |
| 31/07/2022 | 0.5    | Adicionando o tópico de Representação da Arquitetura                 | Nathalia                |
| 31/07/2022 | 0.6    | Adicionando o tópico de Metas e Restrições da Arquitetura            | Nathalia                |
| 31/07/2022 | 0.7    | Adicionando o tópico de Visão Lógica                                 | Nathalia                |
| 31/07/2022 | 0.8    | Criando o tópico de Visão de Implementação e Adicionando Referências | Nathalia                |
| 31/07/2022 | 0.9    | Adicionando imagem no tópico de Visão de Implementação               | Nathalia                |
