# Planejamento de Tempo

## Introdução

O presente documento tem por objetivo a documentação do Plano de Tempo, incluindo as atividades definidas, como as estimativas de tempo foram mensuradas para as mesmas e outros atributos dessas.

## Heatmap e Mapa de Horários

O Mapa de Calor é um artefato que permite visualizar a disponibilidade da equipe como um todo, tornando possível otimizar o tempo disponível da equipe para atividades que exigem execução em conjunto.
As cores auxiliam visualmente a identificação da quantidade de pessoas disponíveis para determinado horário, quanto mais o tom da cor tender para o vermelho significam menos pessoas disponíveis e quanto mais para o verde mais pessoas disponíveis.
Abaixo também é possível visualizar a grade horária de cada membro da equipe individualmente.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS5zvnJXYsxBicjAnp8kvuYqIAXbjp3NH9XhyIeWkwiP25NjQd-E0mOIIc8ow4t4A7szm_TjvS-dIpz/pubhtml?widget=true&amp;headers=false" width="100%" height="480px" style="min-width: 640px; min-height: 480px; background-color: #f4f4f4; border: 1px solid #efefef;"></iframe>

## Definição das atividades

Para definição e planejamento das atividades decidimos pela utilização da técnica de _Rolling Wave Planning_ (RWP). Essa técnica foca em trabalho iterativo e permite atualizações do plano ao longo do projeto, foi escolhida justamente por nos permitir termos espaço para ajustar o nosso plano e se adequar ao nosso tipo de projeto, onde não temos todos os dados necessários para o planejamento já no início do projeto. Atributos utilizados no planejamento das atividades:

- ID: número de identificação da atividade.
- Atividade: nome da atividade.
- Inicial: data de início.
- Final: data de finalização.
- Estimativa: estimativa da tarefa em minutos.
- Esforço gasto: tempo em minutos realmente gasto para realização da tarefa.
- Custo adicional: custo fora do previsto.
- Nº de integrantes: membros participantes da atividade.
- Responsável(eis): pessoa(s) que se comprometem a fazer o necessário para a entrega da tarefa.
- Dependência: número da atividade ao qual esta depende.
- Tipo dependência: define a sequência entre a atividade atual e a atividade a qual esta depende, podendo ser: Finish-to-start (FS), Finish-to-finish (FF), Start-to-start (SS) e Start-to-finish (SF).
- Individual: se pode ser feita por somente uma pessoa.
- Realizada: se foi entregue.
- Custo total (planejado): custo que leva em conta o custo da hora estimado por pessoa, o número de integrantes envolvidos e total de horas planejadas.
- Custo total (real): custo que leva em conta o custo da hora estimado por pessoa, o número de integrantes envolvidos e total de horas realmente gastos.

## Histórico de Versão

| Data       | Versão | Descrição                                       | Autor(es/as)                                                                   |
| ---------- | ------ | ----------------------------------------------- | ------------------------------------------------------------------------------ |
| 18/07/2022 | 0.1    | Documentação inicial e definição das atividades | Maicon Mares, Francisco Heronildo, José Aquiles, Arthur Paiva, Nathalia Lorena |

## Referências

> PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.
