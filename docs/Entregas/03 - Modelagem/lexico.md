# Léxico

## Introdução

Léxico é uma técnica que busca descrever os símbolos de uma linguagem, sendo representada pela notação LAL - Léxico Ampliado da Linguagem [(SERRANO, 2017)](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). 

A definição de léxicos auxilia na especificação de requisitos ao definir termos que serão utilizados ao longo do projeto, auxiliando a compreensão da equipe acerca dos requisitos do projeto.

## Metodologia

De acordo com a [divisão dos requisitos não implementados](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/03%20-%20Casos%20de%20Uso/cenarios/) realizada, após a execução dos cenários, foram definidos léxicos relacionados aos requisitos e cenários desenvolvidos.

Os léxicos serão apresentados de acordo com a estrutura da tabela 1, a seguir. Léxicos estão codificados na notação **LX**, onde **X** representa o número do léxico. Léxicos não estão ordenados de acordo com os requisitos como os cenários, considerando que são de utilidade mais geral ao projeto, fazendo com que uma ordenação de acordo com os requisitos não seja tão necessária. 

### L00 - Exemplo
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             |  |
| Noção            |  |
| Classificação    |  |
| Impacto          |  |
| Sinônimo         |  |
| Requisito        |  |
/// caption | <
Tabela 01 — Estrutura do Léxico
///
/// caption
Fonte: Rodrigo de Andrade
///

## Léxicos Desenvolvidos

As tabelas 02-18, a seguir, representam os léxicos desenvolvidos pela equipe acerca dos requisitos não implementados.

### L01 - Tempo de Resposta
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Tempo de Resposta  |
| Noção            | Tempo em que o sistema responde a requisições de usuários |
| Classificação    | Objeto |
| Impacto          | Quanto menor, mais fluída é a navegação pelo sistema |
| Sinônimo         | Duração |
| Requisito        | RE22 |
/// caption | <
Tabela 02 — Léxico de ‘tempo de resposta’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L02 - Requisição
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Requisição  |
| Noção            | Ação realizada pelo usuário que o permite navegar pelo sistema. |
| Classificação    | Objeto |
| Impacto          | Permite que usuários naveguem pelo sistema |
| Sinônimo         | Solicitação |
| Requisito        | RE22 |
/// caption | <
Tabela 03 — Léxico de ‘requisição’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L02 - Buscar
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Buscar |
| Noção            | Ato de pesquisar um conteúdo por palavras chaves ou títulos. Busca de turmas em que o usuário ‘Aluno’ esteja matriculado no sistema |
| Classificação    | Verbo |
| Impacto          | Permite que usuário ‘Aluno’ encontre suas turmas matriculadas. Permite que usuários busquem conteúdo desejado. |
| Sinônimo         | Pesquisar |
| Requisito        | RE31, RE21 |
/// caption | <
Tabela 04 — Léxico referente a ‘buscar’
///
/// caption
Fonte: Rodrigo de Andrade, João Paulo
///


### L03 - Turma
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Turma |
| Noção            | Ministrada pelo usuário ‘Professor’. Usuários ‘Aluno’ podem se inscrever nela para acessar conteúdos e realizar tarefas. Usuários ‘Monitor’ podem receber o acesso para estudar o conteúdo. |
| Classificação    | Objeto |
| Impacto          | Organiza e disponibiliza conteúdos para ‘Aluno’ e ‘Monitor’, permite que professor monitore ‘Aluno’ |
| Sinônimo         | Disciplina |
| Requisito        | RE31 |
/// caption | <
Tabela 05 — Léxico referente a ‘turma’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L04 - Usuário
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Usuário  |
| Noção            | Quem acessa qualquer funcionalidade da plataforma Moodle |
| Classificação    | Estado |
| Impacto          | Possui acesso à diversas funcionalidades do aplicativo, dependendo de sua classificação |
| Sinônimo         | Aluno, Professor, Monitor |
| Requisito        | RE22 |
/// caption | <
Tabela 06 — Léxico de ‘usuário’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L05 - Aluno
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Aluno  |
| Noção            | Tipo de usuário que pode: se matricular em turmas, acessar conteúdo de turmas, realizar tarefas. |
| Classificação    | Estado |
| Impacto          | Permite que alunos possam usufruir de conteúdos e realizar tarefas. Permite que professores e monitores possam corrigir tarefas. |
| Sinônimo         | Aprendiz |
| Requisito        | RE22 |
/// caption | <
Tabela 07 — Léxico de ‘aluno’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L06 - Professor
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Professor  |
| Noção            | Tipo de usuário que pode: criar turmas, corrigir tarefas, fazer upload de conteúdo |
| Classificação    |Estado |
| Impacto          | Permite que professores possam criar turmas, matricular alunos, corrigir tarefas. Permite que monitores possam corrigir tarefas, se matricularem em turmas. Permite que alunos possam acessar conteúdo, realizar tarefas. |
| Sinônimo         | Duração |
| Requisito        | RE22 |
/// caption | <
Tabela 08 — Léxico de ‘professor’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L07 - Monitor
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Monitor  |
| Noção            | Tipo de usuário que pode: corrigir tarefas, acessar turmas, acessar conteúdo |
| Classificação    | Estado |
| Impacto          | Permite que alunos possam ter suas tarefas corrigidas |
| Sinônimo         | Fiscal |
| Requisito        | RE22 |
/// caption | <
Tabela 09 — Léxico de ‘monitor’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L08 - Realizar
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Realizar  |
| Noção            | Um usuário ‘aluno’ pode realizar tarefas e enviá-las para correção |
| Classificação    | Verbo |
| Impacto          | Professores e monitores possam corrigir tarefas. Alunos podem visualizar correções. |
| Sinônimo         | Fazer |
| Requisito        | RE22 |
/// caption | <
Tabela 10 — Léxico de ‘realizar’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L09 - Tarefa
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Tarefa  |
| Noção            | Tipo de conteúdo que fica na turma como atividade para o usuário ‘Aluno’. Necessita ser realizada pelo aluno. Enviada pelo professor. |
| Classificação    | Objeto |
| Impacto          | Pode ser realizada pelo aluno e enviada para que o professor ou monitor possam corrigir |
| Sinônimo         | Dever |
| Requisito        | RE22 |
/// caption | <
Tabela 11 — Léxico de ‘tarefa’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L10 - Enviar
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Enviar  |
| Noção            | Um usuário ‘aluno’ pode enviar tarefas realizadas para correção. Um usuário ‘professor’ pode enviar tarefas não realizadas para o aluno realizar |
| Classificação    | Verbo |
| Impacto          | Aluno pode visualizar e realizar tarefa. Professor pode enviar tarefa para a turma. |
| Sinônimo         | Encaminhar |
| Requisito        | RE22 |
/// caption | <
Tabela 12 — Léxico de ‘enviar’
///
/// caption
Fonte: Rodrigo de Andrade
///

### L11 - Conteúdo
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Conteúdo  |
| Noção            | Unidade de informação digital que pode ser anexada, enviada ou armazenada no Moodle. Adicionado no Moodle pelo professor. Pode incluir arquivos, links, vídeos, etc |
| Classificação    | Objeto |
| Impacto          |  Permite que o aluno e monitor acessme os materiais necessários para acompanhar o curso |
| Sinônimo         | Tópico, Material didático, Tarefa, Arquivo, Documento |
| Requisito        | RE22, RE26 |
/// caption | <
Tabela 13 — Léxico de ‘conteúdo’
///
/// caption
Fonte: João Paulo, Rodrigo Orlandi, Esther Sousa
///


### L12 - Auto-compactação
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Auto-compactação  |
| Noção            | Ato de compactar os arquivos, se excederam o limite máximo de tamanho permitido no envio da tarefa |
| Classificação    | Verbo |
| Impacto          | Facilita e diminui o tempo de envio de tarefa do usuário ‘aluno’|
| Sinônimo         | Compressão |
| Requisito        | RE25 |
/// caption | <
Tabela 14 — Léxico de ‘auto-compactação’
///
/// caption
Fonte: João Paulo
///

### L13 - Limite de tamanho
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Limite de tamanho  |
| Noção            | Limite estabelecido pelo sistema sobre o envio de conteúdo e tarefas |
| Classificação    | Objeto |
| Impacto          | Evita que o sistema possa ser sobrecarregado de dados pelo envio de tarefas e conteúdos de peso excessivo |
| Sinônimo         | Compressão |
| Requisito        | RE25 |
/// caption | <
Tabela 15 — Léxico de ‘limite de tamanho’
///
/// caption
Fonte: João Paulo, Rodrigo Orlandi

### L14 - Corrigir
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Corrigir  |
| Noção            | Ato de verificar as respostas da tarefa enviada com o intuito de classificar como correto, incompleto ou errado. Pode ser realizado pelos usuários ‘professor’ e ‘monitor’. |
| Classificação    | Verbo |
| Impacto          | Permite que usuários ‘professor’ e ‘monitor’ possam verificar as tarefas enviadas do aluno. Permite que o aluno possa verificar o feedback das tarefas. |
| Sinônimo         | Verificar |
| Requisito        | RE26 |
/// caption | <
Tabela 16 — Léxico de ‘corrigir’
///
/// caption
Fonte: Esther Sousa, Rodrigo Orlandi

### L15 - Sistema
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Sistema  |
| Noção            | Representa o software analisado, Moodle, como um conjunto universal denominado sistema. |
| Classificação    | Objeto |
| Impacto          | Permite que todos os requisitos funcionais e não funcionais sejam implementados, permite usuários navegarem pelo sistema |
| Sinônimo         | Ordenação, Software |
| Requisito        | RE28 |
/// caption | <
Tabela 17 — Léxico de ‘sistema’
///
/// caption
Fonte: Esther Sousa, Rodrigo Orlandi

### L16 - Chamada de vídeo
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Chamada de vídeo  |
| Noção            | Funcionalidade do sistema que permite usuários se encontrarem em uma sala virtual, realizando uma chamada virtual em que se assemelhe a uma aula. Todos podem falar e ser escutados. |
| Classificação    | Estado |
| Impacto          | Permite a realização de aulas remotas |
| Sinônimo         | Videochamada, *videocall*, *call* |
| Requisito        | RE28 |
/// caption | <
Tabela 18 — Léxico de ‘sistema’
///
/// caption
Fonte: Esther Sousa, Rodrigo Orlandi

### L17 - Curso
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Curso  |
| Noção            | Seções no moodle nas quais professores ministram suas disciplinas. |
| Classificação    | Objeto|
| Impacto          | Agrega tarefas, conteúdos, questionários, participantes e notas|
| Sinônimo         | Turma, Matéria |
| Requisito        | RE09|
/// caption | <
Tabela 19 — Léxico de ‘curso’
///
/// caption
Fonte: Laís Cecília

### L18 - Curso arquivado
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             | Curso arquivado  |
| Noção            | Cursos encerrados pelo professor podem ser acessados como arquivados |
| Classificação    | Estado |
| Impacto          | Acesso à esses curso é limitado à modo leitura|
| Sinônimo         | Curso fechado |
| Requisito        | RE09|
/// caption | <
Tabela 20 — Léxico de ‘curso arquivado’
///
/// caption
Fonte: Laís Cecília

------------

## Referência

| # | Fonte|
|---|:------|
| 1 | SERRANO, Milene. SERRANO, Maurício. Requisitos - Aula 10. 2017. UnB Gama (FCTE). Disponível em: [https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). Acesso em: 08/12/2024. |

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Feito upload da página | Rodrigo de Andrade| Esther Sousa| <input type="checkbox" onclick="return false;" disabled/> | 08/12/2024 |