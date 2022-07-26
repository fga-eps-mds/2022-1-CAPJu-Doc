# Treinamentos
## Contexto

Visando preparar a equipe de desenvolvimento pra a execução do projeto, preparamos treinamentos sobre os principais conceitos a serem abordados no projeto para garantir o conhecimento da equipe sobre o mesmo.


## Desenvolvimento-Web

**Responsáveis**: [Maicon Mares](https://github.com/MaiconMares)

**Data Realizada**: 28/06/2022

**Membros Participante na Vídeo Chamada**: Maicon Lucas Mares de Souza, Lucas Lopes Rocha, Gabriel Araujo Souza,
Hellen Fernanda Mendonca De Faria, Francisco Heronildo Sousa Santos, Pablo Christianno Silva Guedes, Philipe de Sousa Barros, Pedro Henrique Ferreira Nunes

## Formato do Treinamento
O treinamento teve como foco o ensinamento dos principais conceitos de HTML, incluindo as `tags` mais utilizadas, a separação de camadas da web (HTML, CSS e JS em arquivos separados) na composição de um documento HTML, principais seletores e regras CSS, principais recursos do Javascript e recursos modernos do ECMAScript6. Também foram mencionados sites úteis para a busca de conteúdo para estudo ([W3 Schools](https://www.w3schools.com/)).

## Material Utilizado
O vídeo completo do treinamento pode ser encontrado em: [Assistir](https://drive.google.com/drive/folders/19Btkgstw_1epIhfzV_vxxebFAB7DiWnW?usp=sharing).

## Principais tags HTML abordadas
```bash
- Listas: <ul></ul> e <ol></ol>
- Títulos: <h1> a <h6>
- Textos: <p>, <span>, <strong>, etc
- Mídia/recursos externos: <img>, <link>, <script>
- Formulário: <form>, <input>, <label>
- Botões de ação/link: <button>, <a>, <submit>
- Seletores: class e id
```

## CSS
- border
- display
- Flexbox/posicionamento/responsividade
- color
- background
- font-family, font-size, etc
- seletores
- margin
- padding

## Javascript
- Tipos de dados
- Funções
- Como fazer requisições 
- async e await (assincronicidade de eventos)
- Promises
- Template Literals
- Objetos
- Principais métodos para lidar com arrays (reduce, map, filter, forEach, etc)
---

## Git

**Responsáveis**: [Francisco Heronildo](https://github.com/FranciscoHeronildo)

**Data Realizada**: 25/06/2022

**Membros Participante na Vídeo Chamada**: Hellen Fernanda, Luciano Alves, Philipe de Sousa, Pedro Henrique, Gabriel Araújo, José Aquiles


## Formato do Treinamento

Para melhor compreensão dos participantes do treinameto criamos um [repositório](https://github.com/FranciscoHeronildo/Treinamento-GIT-GITHUB) para executar os comandos ao mesmo tempo que cada um era explicado.

O Treinamento foi realizado via Microsoft Team e para os membros que não participaram foi disponibilizado a gravação da [chamava](https://drive.google.com/file/d/1c_pnLXBxgMqygQxqeAER0HN6f1jDSVk0/view?usp=sharing)
para que todos tenham acesso.

Além disso, foi proposto um desafio para fixaxão do conteúdo apresentado, desafio esse que encontra-se no repositório criado para o treinamento.

## Material Utilizado

### Apresentação

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTeIX7WsM4dDkb1NRWs_SA0XwCl5JayuRPYDC0hQE69zWoSA8Y23w4Ite1LsU5qQw/embed?start=false&loop=false&delayms=3000" frameborder="0" width="1920" height="1109" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

E a seguir estão algum dos comandos apresentados e uma breve descrição de cada.

### Git

---

#### Iniciar um projeto

Para iniciar o git no seu projeto utilize o comando:

> git init

#### Obter um repositório

Para criar uma cópia de um trabalho em repositório remoto

> git clone usuário@servidor:/caminho/para/o/repositório

#### Adicionar arquivos alterados

> git add <arquivo>

Para inserir todos os arquivos modificados

> git add \*

#### Confirmar mudanças

> git commit -m "comentario"

> git commit -s

##### inserir Co-authored-by

> Co-authored-by: another-name <Coauther-name@example.com>"

#### Enviando alterações

> git push origin <branch>

#### Inserindo repositórorio remoto

> git remote add origin <path>

#### Ramificando

##### Para criar uma nova branch

> git checkout -b <branch_name>

##### Para alterar de branch

> git checkout <branch_name>

##### Para remover uma branch (LOCAL)

> git branch -d <branch_name>

#### Atualizar repositório local

> git pull

> git pull origin <branch_name>

#### Visualizar diferenças entre branch

> Git diff <branch1> <branch2>

#### Visualizar commits

> git log

#### Sobrescrever alterações locais

> git checkout -- <file>

#### Remover todas alterações locais

> git stash

---

## Ágil
### Descrição

Apresentação dos principais conceitos sobre metodologia ágil. Conceitos de Scrum, Kanban e XP, e como podem ser utilizados neste projeto.

### Responsável
[Nathalia Lorena](https://github.com/Natilorens)

**Data Realizada**: 24/06/2022

**Membros Participante na Vídeo Chamada**: Hellen Fernanda, Lucas Lopes, Philipe de Sousa,
Gabriel Araujo, Pedro Henrique, Pablo Christianno, Jose Aquiles, Francisco Heronildo.

## Formato do Treinamento

Foi desenvolvida uma apresentação em slides na plataforma Prezi com o objetivo de disseminar conhecimentos téoricos e alguns exemplos práticos sobre a metodologia ágil para serem aplicados no contexto do projeto CAPJu da disciplica de Engenharia e Produto de Software. Foram citadas como exemplo as metodologias Scrum, Kanban e XP.

O Treinamento foi realizado via Microsoft Teams e para os membros que não participaram foi disponibilizada a gravação da [reunião](https://drive.google.com/file/d/1St119JLCkBhQrl8OYFspmLC3O_f7EsXh/view?usp=sharing)
para que todos tenham acesso.


## Material Utilizado

### Apresentação

A apresentação completa em slides encontra-se disponível [aqui](https://drive.google.com/file/d/1t4oLNMVneKTDTBfy85dYx4vMhywjSkkX/view?usp=sharingusp=sharing).


---
## Docker
### Descrição

Treinamento dos conceitos básicos sobre como rodar uma aplicação através de contêineres pelo docker

### Responsável
@aquiles23

### Participação sincrona
@Hellen159, @PhilipeSousa, @PedroHhenriq, @FranciscoHeronildo

### Material
#### Repositório: 
https://github.com/aquiles23/treinamento_mds
#### Gravação:
 <iframe src="https://drive.google.com/file/d/1uW6LbZxVvFZR8m4lChFCQIf_EAOonLO7/preview" width="640" height="480" allow="autoplay"></iframe>

---
## NodeJs
### Descrição
Treinamento sobre os principais conceitos sobre API REST usando nodeJS + express.

### Responsavel:
@aquiles23

### Participação sincrona:
@GabrielGaba, @PedroHhenriq .

### Material
#### Repositório: 
https://github.com/aquiles23/treinamento_mds
#### Gravação: 
<iframe src="https://drive.google.com/file/d/1ZR1dZcS4Vw6lhcdbrZ1Ha923My2mjdZG/preview" width="640" height="480" allow="autoplay"></iframe>

#### Slides: 
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSyW7VhQhmnrhJ2KRlMJ3ctulzv9rmT-G8haa1oLjGrh8OSPg5Ji3c45Hj44gB7JHocm9mscSTvA_97/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

---
## ReactJs

---

**Histórico de Versão**

| Data       | Versão | Descrição                        | Autor(es) |
| ---------- | ------ | -------------------------------- | --------- |
| 19/07/2022 | 0.1    | Adicionando o treinamento de Git | Francisco |
| 22/07/2022 | 0.2    | Adicionando o treinamento de docker e nodeJS | Aquiles |
| 23/07/2022 | 0.3    | Adicionando o treinamento de Desenvolvimento Web | Maicon Mares |
| 26/07/2022 | 0.4    | Adicionando o treinamento de Metodologia Agil | Nathalia Lorena |
