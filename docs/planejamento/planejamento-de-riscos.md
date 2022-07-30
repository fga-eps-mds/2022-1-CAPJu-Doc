# Gerenciamento de Riscos

## Objetivos

O Gerenciamento dos riscos do projeto inclui os processos de planejamento, identificação, análise,
planejamento de respostas e controle de riscos de um projeto. Os objetivos do gerenciamento dos riscos do projeto são aumentar a probabilidade e o impacto dos eventos positivos e reduzir a probabilidade e o impacto dos eventos negativos no projeto.

### Planejar Gerenciamento de Riscos

O processo de planejar o gerenciamento de riscos é o processo que define como será feito a identificação, análise e as respostas aos riscos referentes ao projeto.

### Identificar Riscos

O PMBOK define esta fase como o processo de determinação dos riscos que podem afetar o projeto e de documentação das suas características.

#### Estrutura Análitica de Riscos

![ear](https://i.imgur.com/4v5CioV.png)

#### Categoria dos Riscos

**Gerência de projeto**

- **Planejamento:** São riscos relacionados a erros de planejamento, como tarefas grandes em períodos curtos.
- **Estimativa:** São erros que dizem respeito a erros de estimativa, como por exemplo erros de pontuação de histórias de usuário.
- **Comunicação:** São riscos os referentes a comunicação dos membros da equipe.
- **Execução:** São riscos relacionados a execução do projeto em si.

**Organizacional**

- **Recursos Humanos:** Corresponde aos riscos relacionados gerência de pessoas da equipe.
- **Priorização:** São riscos relacionados aos erros de priorização, gerando atrasos nas entregas, por existir dependências entre as tarefas.
- **Habilidades Individuais:** São os riscos referentes às capacidades e habilidades pessoais dos membros da equipe.

**Técnico**

- **Requisitos:** São riscos relacionados aos requisitos requisitos levantados.
- **Tecnologia:** São riscos relacionados com as tecnologias utilizadas no projeto.
- **Infraestrutura:** São riscos relacionados com a infraestrutura do projeto.
- **Escopo:** São riscos relacionados ao escopo definido.
- **Qualidade:** São os riscos relacionados as características de qualidade do produto (Funcionalidade, Usabilidade, Eficiência Manutenibilidade, Portabilidade).

**Externos**

- **Disciplinas:** São os riscos relacionados a ocupação dos membros com outras disciplinas e que podem influenciar no andamento do projeto.
- **Saúde/Fatores Pessoais:** São os riscos relacionados a algum problema de saúde ou problema pessoal que um dos membros ou stakerholder pode adquirir durante o semestre. Também está associado a transmissão da COVID-19 ou Varíola do Macaco e acontecer um possível retorno as atividades remotas.
- **Stakeholder:** São os riscos relacionados ao stakeholder do projeto.

### Realizar Análise dos Riscos

O PMBOK define a etapa em duas partes uma qualitativa que é o processo de priorização de riscos para análise ou ação adicional através da avaliação e combinação de sua probabilidade de ocorrência e impacto. E outra a quantitativa que analisa numericamente o efeito dos riscos identificados nos objetivos gerais do projeto.

Para isso é necessário classificar os riscos segundo sua probabilidade, impacto e tipos. Nas tabelas abaixo temos a classificação das probabilidade, impacto e uma descrição dos tipos de risco.

#### Probabilidade

| **Probabilidade** | **Intervalo(%)** | **Peso** |
| ----------------- | ---------------- | -------- |
| Muito Baixa       | De 0% a 20%      | 1        |
| Baixa             | De 21% a 40%     | 2        |
| Média             | De 41% a 60%     | 3        |
| Alta              | De 61% a 80%     | 4        |
| Muito Alta        | De 81% a 100%    | 5        |

#### Impacto

| **Impacto** | **Descrição**                                     | **Peso** |
| ----------- | ------------------------------------------------- | -------- |
| Muito Baixo | Quase imperceptível para o projeto                | 1        |
| Baixo       | Emite pouco impacto sobre o projeto               | 2        |
| Médio       | Existe um impacto considerável, mas é recuperável | 3        |
| Alto        | Existe grande impacto no projeto                  | 4        |
| Muito Alto  | Impede o prosseguimento do projeto                | 5        |

### Controlar Riscos

Segundo o PMBOK controlar os riscos é o processo de implementação de planos de respostas aos riscos, acompanhamento dos riscos identificados, monitoramento dos riscos residuais, identificação de novos riscos e avaliação da eficácia do processo de riscos durante todo o projeto.

## Documentação dos Riscos

O principal resultado do processo Identificar os riscos é a entrada inicial no registro dos riscos. O registro dos riscos é o documento em que os resultados da análise dos riscos e o planejamento das respostas aos riscos são registrados.

E para registrar um risco foi decidio utilizar o seguinte formato:

- **Identificador**: é um identificador único que está relacionado com o risco para que haja maior facilidade ao referenciar o risco.
- **Descrição**: especificação do risco.
- **Causa**: demonstra qual o motivo da provável ocorrência do risco.
- **Consequência**: projeta os prováveis impactos no desenvolvimento do projeto.
- **Probabilidade**: define, em porcentagem, a provável ocorrência do risco.
- **Impacto**: define qual o grau de impacto da ocorrência do risco no projeto.
- **Categoria**: é determinada pela categoria segundo os tipos definidos

## Levantamento dos Riscos

| ID  | Descrição                                       | Causa                                                        | Consequência                     | Categoria           | Impacto    | Probabilidade |
| --- | ----------------------------------------------- | ------------------------------------------------------------ | -------------------------------- | ------------------- | ---------- | ------------- |
| 1   | Membros abandonarem a disciplina                | Problemas Pessoais                                           | Sobrecarga da Equipe             | Externo             | Alto       | Média         |
| 2   | Fechamento da Universidade                      | Aumento da Transmissão de COVID-19/Varíola dos Macacos Greve | Cancelamento do Projeto          | Externo             | Muito Alto | Média         |
| 3   | Mudanças de Tecnologias                         | Inexperiência da Equipe                                      | Atraso do Projeto                | Tecnologia          | Alto       | Baixa         |
| 4   | Mudança de escopo                               | Entendimento Errado do Projeto                               | Atraso na Entrega das Atividades | Técnico             | Alto       | Média         |
| 5   | Má gerência da comunicação da equipe            | Inexperiência da Equipe                                      | Sobrecarga de Membros            | Gerência de projeto | Alto       | Alto          |
| 6   | Planejamento de tempo feito de forma equivocada | Inexperiência da Equipe                                      | Atraso do Projeto                | Gerência de projeto | Alto       | Média         |
| 7   | Falta de Compromisso dos Membros                | Baixa Produtividade dos Integrantes                          | Atraso no Cronograma             | Organizacional      | Alto       | Média         |
| 8   | Diferença de horários entre membro              | Problemas Pessoais                                           | Atraso na entrega das Atividades | Organizacional      | Alto       | Média         |
| 9   | Problemas com Estações de Trabalho              | Estação de Trabalho com Defeito                              | Atraso no Cronograma             | Externos            | Média      | Baixa         |

## Respostas aos Riscos

| ID  | Respostas                                                                                                                                                                                                                                                                           |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Adequação do Backlog com redução do escopo, compensar horas do membro entre o restante da equipe.                                                                                                                                                                                   |
| 2   | Se possível continuar, estruturar o desenvolvimento do projeto de maneira remota.                                                                                                                                                                                                   |
| 3   | Equipe de EPS deve intervir e realizar a migração do que foi desenvolvido até o momento para as tecnologias aderentes ao projeto a fim de minimizar o atraso no desenvolvimento.                                                                                                    |
| 4   | Reunir e alinhar a Visão do Produto com toda a equipe em conjunto, se necessário validar novamente com o cliente.                                                                                                                                                                   |
| 5   | Pedir para que o membro explique com suas palavras o seu entendimento a fim de confirmar a corretude da comunicação. Modificar estratégias de comunicação, realizar mais encontros presenciais, criar canais de comunicação anônimos para que todos possam se expressar livremente. |
| 6   | Estudar metodologias que auxiliem nas estimativas e buscar entender o ritmo de cada membro a fim de planejar o tempo mais próximo do real.                                                                                                                                          |
| 7   | Conversar constantemente com os membros da equipe, buscar estratégias de motivação, ou gamificação para aumentar o engajamento dos membros, buscar estratégias como quadros de humor para acompanhar o bem estar da equipe.                                                         |
| 8   | Adequa os horários de acordo com o horário estabelecido no mapa de horário criado no início do projeto.                                                                                                                                                                             |

**Histórico de Versão**

| Data       | Versão | Descrição               | Autor(es)                                    |
| ---------- | ------ | ----------------------- | -------------------------------------------- |
| 26/07/2022 | 0.1    | Criação do documento    | Francisco                                    |
| 27/07/2022 | 0.2    | Levantamento dos Riscos | Aquiles, Francsico, Nathalia, Maicon, Arthur |
| 28/07/2022 | 0.3    | Respostas aos Riscos    | Aquiles, Francsico, Nathalia, Maicon, Arthur |

## Referências

> PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.
