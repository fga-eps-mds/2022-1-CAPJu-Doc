# Planejamento de Qualidade

## Objetivo

De acordo com a definição do guia PMBOK, a qualidade seria “o grau até o qual um conjunto de características inerentes satisfaz as necessidades”. Dessa forma, com o objetivo de detectar não conformidades dentro do projeto e estabelecer ações corretivas e preventivas para que seja possível entregar um produto que possua um grau elevado de satisfação para o usuário final, serão abordadas neste Planejamento de Qualidade, práticas, recursos e parâmetros que permitam ao time atingir esse objetivo.

Para isso faremos o uso da abordagem **GQM** (Goal Question Metrics) que é uma abordagem de cima para baixo (top-down) que estabelece um sistema de medição  direcionado a metas para desenvolvimento de software em que a equipe inicia com metas organizacionais, define a medição das metas, levanta questões a abordar os objetivos e identifica as métricas que proporcionem as respostas. O modelo GQM está dividido em três níveis: Nível Conceitual, nível operacional e nível quantitativo.

Essa abordagem possui 3 níveis hierárquicos, são eles:

**Conceitual (Objetivos):** Uma meta é definida para algum objeto de medição, esse objeto pode ser produtos, processos ou recursos
**Operacional (Questões):** Elaborar perguntas que nos ajudam a caracterizar o objeto de medição e nos ajuda a escolher o ponto de vista da análise de qualidade que será feita.
**Quantitativo (Métricas):** Conjunto de dados que está associado às perguntas a fim de respondê-las.

 

## Goals

### Objetivo 1 - Qualidade a Nível Organizacional

Para que seja possível medir a qualidade organizacional é necessário primeiramente definir os aspectos que serão avaliados dentro desse contexto. Pretende-se avaliar, por exemplo, a produtividade do time, capacitação do time, e padronização de processos dentro da equipe. A medição da qualidade a nível organizacional permite ao próprio time uma autonomia para tomar decisões e gerar uma melhoria contínua nas entregas de releases.

Conforme propõe a ISO/IEC 14598-1 que está direcionada ao ponto de vista de desenvolvedores que pretendem desenvolver um novo produto ou melhorar um produto existente e pretendam executar avaliação de produto utilizando pessoas de seu próprio corpo técnico pode-se fazer o uso de indicadores que ajudam a prever a qualidade do produto final através da medição de produtos intermediários desenvolvidos durante o ciclo de vida.

Para obtermos métricas de qualidade a nível organizacional, foram escolhidos os seguintes aspectos para serem avaliados:

| Goal | Questions | Metrics |
| -------- | -------- | -------- |
| 1     |  O time realiza treinamentos? Existe progresso de conhecimento das tecnologias? Os membros participam das reuniões?| Quadro de conhecimentos, Burndown,  Velocity, Frequência de participação nas cerimonias do Scrum|


### Objetivo 2 - Qualidade a Nível de Projeto

Para avaliar a qualidade a nível de projeto serão coletadas métricas utilizando o SonarCloud em cada release, e estão divididas conforme os aspectos de qualidade abaixo:

* Manutenibilidade do código,
* confiabilidade
* segurança

| Goal |  Questions |  Metrics |
| -------- | -------- | -------- |
| 2     |  O código é reaproveitado? O código é legível? Após inserir novas funcionalidades é fácil identificar bugs? |  files,functions, complexity, comment_lines_density, duplicated_lines_density, coverage, ncloc, tests, test_errors, test_failures, test_execution_time, security_rating |


**MANUTENIBILIDADE**

O conjunto de métricas abaixo será coletado para avaliar a manutenabilidade do código do projeto. Tal aspecto é importante por nos permitir avaliar o quão fácil será para que manutenção seja feita no código.


1. **Complexidade**

Será avaliada utilizando as seguintes métricas:

**functions;
complexity;
files;
ncloc;**

* Functions mede a quantidade de funções;
* Files mede a quantidade de arquivos do projeto;
* Complexity calcula a complexidade ciclomática do codigo a partir das branchs;
* Ncloc retorna o número físico de linhas que contém, no mínimo, um caracter que não seja tabulação ou espaço em branco;

2. **Comentários**

Será avaliado utilizando a seguinte métrica:

**comment_lines_density;**

3. **Duplicidade**

Será avaliado utilizando a seguinte métrica:

**duplicated_lines_density;**

**CONFIABILIDADE**

A métrica abaixo será utilizada para calcular a confiabilidade do projeto. Esse aspecto é importante para avaliar o quão confiável o código é em realizar aquilo que propõe.

1. **Testes**

Será avaliado utilizando as seguintes métricas:

**coverage;
tests;
test_execution_time;
test_errors;
test_failures;
reliability_rating;**

Coverage avalia a cobertura utilizando um mix de cobertura de linhas e cobertura condicional para retornar um resultado com maior acurácia do que utilizar apenas um ou outro.

**SEGURANÇA**

A métrica abaixo será utilizada para calcular a segurança do projeto baseado nas vulnerabilidades encontradas no mesmo.

Será avaliado utilizando a seguinte métrica:

**security_rating;**


### Objetivo 3 - Qualidade na Visão do Usuário

É importante considerar que o cliente é quem está à frente. Ele tem o direito de participar e opinar durante o processo de construção do software. Neste contexto, a experiência do usuário, além das qualidades técnicas do software, é um fator determinante para a construção de sistemas de maior qualidade. Sua participação pode facilitar a compreensão dos seus desejos quanto ao software que está sendo desenvolvido. Esse aspecto da qualidade do software é chamado usabilidade. 

Dessa forma, para medirmos a usabilidade será desenvolvido e disponibilizado um formulário para o cliente e conforme ele for testando as novas funcionalidades implementadas será possível ele avaliar em uma escala de 0 a 10 questões qualitativas do quão intuitivo e prático foi sua experiência ao utilizar a aplicação.

| Goal  | Questions | Metrics |
| -------- | -------- | -------- |
| 3     |  As funcionalidades estão disponíveis e são executadas eficientemente? O aplicativo funciona corretamente sem imprevistos? O software é seguro, ou seja, evita que pessoas ou sistemas não autorizados tenham acesso às informações? É fácil de usar ou requer muito treinamento?| Respostas do forms que serão analisadas conforme o cliente usar a aplicação  |


**Histórico de Versão**

| Data | Versão | Descrição | Autor(es) |
| ---- | ------ | --------- | --------- |
|  15/07/2022    | 0.1       |     Criação do plano de qualidade e adição do tópico de introdução       |      Nathalia, Luciano e Pedro    | 
| 15/07/2022 | 0.2 | Adição do tópico de objetivos | Nathalia, Luciano e Pedro|
| 18/07/2022 | 0.3 | Adição do tópico de Abordagens e metodologias | Nathalia, Luciano e Pedro|
| 18/07/2022 | 0.4 | Atualização do tópico de Abordagens e metodologias | Nathalia, Luciano e Pedro|
| 18/07/2022 | 0.5 | Adição do tópico de Qualidade a Nível Organizacional | Nathalia, Luciano e Pedro|
| 18/07/2022 | 0.6 | Adição do tópico de Qualidade a Nível de Projeto | Nathalia, Luciano e Pedro|
| 18/07/2022 | 0.7 | Adição do tópico de Qualidade na Visão de Usuário | Nathalia, Luciano e Pedro|
| 18/07/2022 | 0.8 | Adição de Referências | Nathalia, Luciano e Pedro|
| 31/07/2022 | 0.9 | Refatorando o documento| Nathalia |

## Referências

RODRIGUES, Claudia. A importância de um plano de qualidade de software e a estratégia de testes. Linkedin, 2017. Disponível em: <https://www.linkedin.com/pulse/import%C3%A2ncia-de-um-plano-qualidade-software-e-testes-farias-ctfl/?originalSubdomain=pt>. Acesso em: 30 de jul. de 2022.

ARIAS, Raphael. Como criar um plano de gerenciamento da qualidade. Excellence Blog, 2020. Disponível em: <https://blog.softexpert.com/plano-gerenciamento-qualidade/>. Acesso em: 30 de jul. de 2022.

SILVA, C. V. P.  GQM - Goal Question Metric. Ago 2009. Disponível em: <https://www.cin.ufpe.br/~scbs/metricas/seminarios/GQM_texto.pdf> Acesso em: 30 jul. 2022.

CAMPOS, Fábio. Qualidade, Qualidade de Software e Garantia da Qualidade de Software são as mesmas coisas?. Linha de Código, 2022. Disponível em: <http://www.linhadecodigo.com.br/artigo/1712/qualidade-qualidade-de-software-e-garantia-da-qualidade-de-software-sao-as-mesmas-coisas.aspx>. Acesso em: 30 jul. 2022.

LENILDO. Qualidade de Software - Engenharia de Software 29. DEVMEDIA, 2010. Disponível em: <https://www.devmedia.com.br/qualidade-de-software-engenharia-de-software-29/18209>. Acesso em: 30 jul. 2022.

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. NBR ISO/IEC 14598-1: Tecnologia de informação: Avaliação de produto de software. Rio de Janeiro, p. 07. 2001.
