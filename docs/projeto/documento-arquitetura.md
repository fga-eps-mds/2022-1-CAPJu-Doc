# Documento de Arquitetura

# 1. Introdução

## 1.1 Objetivo 

<p>O documento apresentado tem como finalidade oferecer uma visão abrangente da arquitetura do projeto. Dessa forma, utilizou-se visões arquiteturais que ilustram o desenvolvimento do sistema, contendo informações que compreendem as tecnologias envolvidas e suas interações. Logo, por intermédio deste documento busca-se esclarecer as decisões arquiteturais estabelecidas pela equipe durante o desenvolvimento do projeto.<p>

## 1.2 Escopo

CAPJu é uma aplicação web que propõe a gerência de processos jurídicos e automatizar tarefas repetidas realizadas via planilha. Os processos passam por etapas, e a proposta da aplicação consiste em proporcionar ao usuário um controle e acompanhamento de cada processo, como por exemplo, movimentar processos de acordo com sua categoria e etapa. Este documento tratará dos padrões de arquitetura, tecnologias, frameworks e a integração entre esses mecanismos para o desenvolvimento dessa aplicação.

## 1.3 Definições, acrônimos e abreviações 

|Sigla |Significado |
--|--
|**CAPJu**| Controle e Acompanhamento de Processos da Justiça
|**HTTP**| Hypertext Transfer Protocol
|**API**| Application Programming Interface
|**CSS**| Cascading Style Sheets 
|**JSON**| JavaScript Object Notation

## 1.4 Visão Geral

Este documento detalha os padrões arquiteturais do CAPJu, como também aborda as tecnologias utilizadas para o desenvolvimento. Para isso, os documento foi estruturado da seguinte forma: 


| |Tópico |Descrição |
|-|-|-|
|**1**|**Introdução**| Fornece ao leitor uma visão geral do conteúdo abordado no documento
|**2**|**Representação da Arquitetura**| Detalha a arquitetura utilizada no projeto e como ela está organizada
|**3**|**Metas e Restrições da Arquitetura**| Descreve os objetivos do projeto, como também suas restrições, do ponto de vista arquitetural
|**4**|**Visão Lógica**| Fornece ao leitor uma base para compreender a estrutura e a organização do design do sistema
|**5**|**Visão de Implementação**| Fornece ao leitor uma base que permitirá compreender a distribuição física do sistema em um conjunto de nós de processamento
|**6**|**Referências**| Fornece ao leitor um conhecimento das referências utilizadas durante a criação deste documento


# Histórico de versões 

|Data|Versão|Descrição|Autor|
|-|-|-|-|
| 26/07/2022  | 0.1| Adicionando o tópico de Introdução e Objetivo| Pedro, Pablo e Nathalia |
| 26/07/2022  | 0.2| Adicionando o tópico de Escopo| Pedro, Pablo e Nathalia |
| 31/07/2022  | 0.3| Adicionando o tópico de Definições, acrônimos e abreviações| Nathalia |
| 31/07/2022  | 0.4| Adicionando o tópico de Visão Geral| Nathalia |