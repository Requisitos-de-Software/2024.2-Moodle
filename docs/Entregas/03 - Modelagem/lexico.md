# Léxico

## Introdução

Léxico é uma técnica que "busca descrever os símbolos de uma linguagem, sendo representada pela notação LAL - Léxico Ampliado da Linguagem" [(SERRANO, 2017)](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). 

A definição de léxicos auxilia na especificação de requisitos ao definir termos que serão utilizados ao longo do projeto, auxiliando a compreensão da equipe acerca dos requisitos do projeto.

## Metodologia

De acordo com a [divisão dos requisitos não implementados](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/03%20-%20Casos%20de%20Uso/cenarios/) realizada, após a execução dos cenários, foram definidos léxicos relacionados aos requisitos e cenários desenvolvidos.

Os léxicos serão apresentados de acordo com a estrutura da tabela 1, a seguir. Léxicos estão codificados na notação **LX**, onde **X** representa o número do léxico. Léxicos não estão ordenados de acordo com os requisitos como os cenários, considerando que são de utilidade mais geral ao projeto, fazendo com que uma ordenação de acordo com os requisitos não seja tão necessária. 

Os requisitos nos léxicos representam de onde originaram. Os léxicos podem ser aplicáveis em diversos requisitos diferentes, não limitados pela sua origem.

### L00 - Exemplo
| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Nome             |  |
| Noção            |  |
| Classificação    |  |
| Impacto          |  |
| Sinônimo         |  |
| Léxicos Relacionados |  |
| Requisito        |  |
/// caption | <
Tabela 01 — Estrutura do Léxico
///
/// caption
Fonte: Rodrigo de Andrade
///

## Léxicos Desenvolvidos

As tabelas 02-20, a seguir, representam os léxicos desenvolvidos pela equipe acerca dos requisitos não implementados.

=== "L01"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Tempo de Resposta  |
    | Noção            | Tempo em que o [sistema](#__tabbed_1_16) responde a [requisições](#__tabbed_1_2) de [usuários](#__tabbed_1_5) |
    | Classificação    | Objeto |
    | Impacto          | Quanto menor, mais fluída é a navegação pelo [sistema](#__tabbed_1_16) |
    | Sinônimo         | Duração |
    | Léxicos Relacionados | [Requisição](#__tabbed_1_2) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 02 — Léxico de ‘tempo de resposta’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L02"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Requisição  |
    | Noção            | Ação realizada pelo [usuário](#__tabbed_1_5) que o permite navegar pelo [sistema](#__tabbed_1_16). |
    | Classificação    | Objeto |
    | Impacto          | Permite que [usuários](#__tabbed_1_5) naveguem pelo [sistema](#__tabbed_1_16) |
    | Sinônimo         | Solicitação |
    | Léxicos Relacionados |  |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 03 — Léxico de ‘requisição’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L03"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Buscar |
    | Noção            | Ato de pesquisar um [conteúdo](#__tabbed_1_12) por palavras chaves ou títulos. Busca de [turmas](#__tabbed_1_4) em que o [usuário ‘Aluno’](#__tabbed_1_6) esteja matriculado no [sistema](#__tabbed_1_16) |
    | Classificação    | Verbo |
    | Impacto          | Permite que [usuário ‘Aluno’](#__tabbed_1_6) encontre suas [turmas](#__tabbed_1_4) matriculadas. Permite que [usuários](#__tabbed_1_5) busquem [conteúdo](#__tabbed_1_12) desejado. |
    | Sinônimo         | Pesquisar |
    | Léxicos Relacionados | [Conteúdo](#__tabbed_1_12) |
    | Requisito        | RE31, RE21 |
    /// caption | <
    Tabela 04 — Léxico referente a ‘buscar’
    ///
    /// caption
    Fonte: Rodrigo de Andrade, João Paulo
    ///

=== "L04"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Curso |
    | Noção            | Ministrado pelo [usuário ‘Professor’](#__tabbed_1_7). [Usuários ‘Aluno’](#__tabbed_1_6) podem se inscrever nele para acessar [conteúdos](#__tabbed_1_12) e realizar [tarefas](#__tabbed_1_10). [Usuários ‘Monitor’](#__tabbed_1_8) podem receber o acesso para estudar o [conteúdo](#__tabbed_1_12). |
    | Classificação    | Objeto |
    | Impacto          | Organiza e disponibiliza [conteúdos](#__tabbed_1_12) para [‘Aluno’](#__tabbed_1_6) e [‘Monitor’](#__tabbed_1_8), permite que [professor](#__tabbed_1_7) monitore [‘Aluno’](#__tabbed_1_6) |
    | Sinônimo         | Disciplina, turma |
    | Léxicos Relacionados | [Tarefa](#__tabbed_1_10), [Conteúdo](#__tabbed_1_12) |
    | Requisito        | RE31 |
    /// caption | <
    Tabela 05 — Léxico referente a 'curso'
    ///
    /// caption
    Fonte: Rodrigo de Andrade, Laís Cecília
    ///

=== "L05"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Usuário  |
    | Noção            | Quem acessa qualquer funcionalidade da [Plataforma Moodle](#__tabbed_1_16)|
    | Classificação    | Estado |
    | Impacto          | Possui acesso à diversas funcionalidades do [Aplicativo Moodle](#__tabbed_1_16), dependendo de sua classificação |
    | Sinônimo         |  |
    | Léxicos Relacionados | [Aluno](#__tabbed_1_6), [Professor](#__tabbed_1_7), [Monitor](#__tabbed_1_8)  |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 06 — Léxico de ‘usuário’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L06"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Aluno  |
    | Noção            | Tipo de [usuário](#__tabbed_1_5) que pode: se matricular em [turmas](#__tabbed_1_4), acessar [conteúdo](#__tabbed_1_12) de [turmas](#__tabbed_1_4), [realizar](#__tabbed_1_9) [tarefas](#__tabbed_1_10). |
    | Classificação    | Estado |
    | Impacto          | Permite que alunos possam usufruir de [conteúdos](#__tabbed_1_12) e [realizar](#__tabbed_1_9) [tarefas](#__tabbed_1_10). Permite que [professores](#__tabbed_1_7) e [monitores](#__tabbed_1_8) possam [corrigir](#__tabbed_1_15) [tarefas](#__tabbed_1_10). |
    | Sinônimo         | Aprendiz |
    | Léxicos Relacionados | [Usuário](#__tabbed_1_5) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 07 — Léxico de ‘aluno’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L07"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Professor  |
    | Noção            | Tipo de [usuário](#__tabbed_1_5) que pode: criar [turmas](#__tabbed_1_4), [corrigir](#__tabbed_1_15) [tarefas](#__tabbed_1_10), [fazer upload](#__tabbed_1_11) de [conteúdo](#__tabbed_1_12) |
    | Classificação    |Estado |
    | Impacto          | Professores podem criar [turmas](#__tabbed_1_4), matricular [alunos](#__tabbed_1_6), [corrigir](#__tabbed_1_15) [tarefas](#__tabbed_1_10). Permite que [monitores](#__tabbed_1_8) possam [corrigir](#__tabbed_1_15) [tarefas](#__tabbed_1_10), se matricularem em [turmas](#__tabbed_1_4). Permite que [alunos](#__tabbed_1_6) possam acessar [conteúdo](#__tabbed_1_12), [realizar](#__tabbed_1_9) [tarefas](#__tabbed_1_10). |
    | Sinônimo         | Reitor |
    | Léxicos Relacionados | [Usuário](#__tabbed_1_5), [Monitor](#__tabbed_1_8) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 08 — Léxico de ‘professor’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L08"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Monitor  |
    | Noção            | Tipo de [usuário](#__tabbed_1_5) que pode: [corrigir](#__tabbed_1_15) [tarefas](#__tabbed_1_10), acessar [turmas](#__tabbed_1_4), acessar [conteúdo](#__tabbed_1_12) |
    | Classificação    | Estado |
    | Impacto          | Permite que [alunos](#__tabbed_1_6) possam ter suas [tarefas](#__tabbed_1_10) [corrigidas](#__tabbed_1_15) |
    | Sinônimo         | Fiscal |
    | Léxicos Relacionados | [Usuário](#__tabbed_1_5), [Professor](#__tabbed_1_7) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 09 — Léxico de ‘monitor’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L09"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Realizar  |
    | Noção            | Um usuário [‘aluno’](#__tabbed_1_6) pode realizar [tarefas](#__tabbed_1_10) e [enviá-las](#__tabbed_1_11) para [correção](#__tabbed_1_19) |
    | Classificação    | Verbo |
    | Impacto          | [Professores](#__tabbed_1_7) e [monitores](#__tabbed_1_8) possam [corrigir](#__tabbed_1_15) [tarefas](#__tabbed_1_10). [Alunos](#__tabbed_1_6) podem visualizar [correções](#__tabbed_1_19). |
    | Sinônimo         | Fazer |
    | Léxicos Relacionados | [Tarefa](#__tabbed_1_10), [Enviar](#__tabbed_1_11) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 10 — Léxico de ‘realizar’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L10"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Tarefa  |
    | Noção            | Tipo de [conteúdo](#__tabbed_1_12) que fica na [turma](#__tabbed_1_4) como atividade para o [usuário ‘Aluno’](#__tabbed_1_6). Necessita ser [realizada](#__tabbed_1_9) pelo [aluno](#__tabbed_1_6). [Enviada](#__tabbed_1_11) pelo [professor](#__tabbed_1_7). |
    | Classificação    | Objeto |
    | Impacto          | Pode ser [realizada](#__tabbed_1_9) pelo [aluno](#__tabbed_1_6) e [enviada](#__tabbed_1_11) para que o [professor](#__tabbed_1_7) ou [monitor](#__tabbed_1_8) possam [corrigir](#__tabbed_1_15) |
    | Sinônimo         | Dever |
    | Léxicos Relacionados | [Conteúdo](#__tabbed_1_12) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 11 — Léxico de ‘tarefa’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L11"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Enviar  |
    | Noção            | Um [usuário ‘aluno’](#__tabbed_1_6) pode enviar [tarefas](#__tabbed_1_10) [realizadas](#__tabbed_1_9) para [correção](#__tabbed_1_15). Um [usuário ‘professor’](#__tabbed_1_7) pode enviar [tarefas](#__tabbed_1_10) não [realizadas](#__tabbed_1_9) para o [aluno](#__tabbed_1_6) [realizar](#__tabbed_1_9) |
    | Classificação    | Verbo |
    | Impacto          | [Aluno](#__tabbed_1_6) pode visualizar e [realizar](#__tabbed_1_9) [tarefa](#__tabbed_1_10). [Professor](#__tabbed_1_7) pode enviar [tarefa](#__tabbed_1_10) para a [turma](#__tabbed_1_4). |
    | Sinônimo         | Encaminhar, Fazer Upload, Adicionado |
    | Léxicos Relacionados | [Realizar](#__tabbed_1_9) |
    | Requisito        | RE22 |
    /// caption | <
    Tabela 12 — Léxico de ‘enviar’
    ///
    /// caption
    Fonte: Rodrigo de Andrade
    ///

=== "L12"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Conteúdo  |
    | Noção            | Unidade de informação digital que pode ser anexada, [enviada](#__tabbed_1_11) ou armazenada no [Moodle](#__tabbed_1_16). [Adicionado](#__tabbed_1_11) no [Moodle](#__tabbed_1_16) pelo [professor](#__tabbed_1_7). Pode incluir arquivos, links, vídeos, etc |
    | Classificação    | Objeto |
    | Impacto          |  Permite que o [aluno](#__tabbed_1_6) e [monitor](#__tabbed_1_8) acesse os materiais necessários para acompanhar o [curso](#__tabbed_1_4) |
    | Sinônimo         | Tópico, Material didático, Tarefa, Arquivo, Documento |
    | Léxicos Relacionados | [Tarefa](#__tabbed_1_10) |
    | Requisito        | RE22, RE26 |
    /// caption | <
    Tabela 13 — Léxico de ‘conteúdo’
    ///
    /// caption
    Fonte: João Paulo, Rodrigo Orlandi, Esther Sousa
    ///

=== "L13"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Auto-compactação  |
    | Noção            | Ato de compactar os arquivos, se excederam o limite máximo de tamanho permitido no [envio](#__tabbed_1_9) da [tarefa](#__tabbed_1_10) |
    | Classificação    | Verbo |
    | Impacto          | Facilita e diminui o tempo de [envio](#__tabbed_1_11) de [tarefa](#__tabbed_1_10) do [usuário ‘aluno’](#__tabbed_1_6)|
    | Sinônimo         | Compressão |
    | Léxicos Relacionados | [Enviar](#__tabbed_1_11), [Limite de tamanho](#__tabbed_1_14) |
    | Requisito        | RE25 |
    /// caption | <
    Tabela 14 — Léxico de ‘auto-compactação’
    ///
    /// caption
    Fonte: João Paulo
    ///

=== "L14"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Limite de tamanho  |
    | Noção            | Limite estabelecido pelo [sistema](#__tabbed_1_16) sobre o [envio](#__tabbed_1_11) de [conteúdo](#__tabbed_1_12) e [tarefas](#__tabbed_1_10) |
    | Classificação    | Objeto |
    | Impacto          | Evita que o [sistema](#__tabbed_1_16) possa ser sobrecarregado de dados pelo [envio](#__tabbed_1_11) de [tarefas](#__tabbed_1_10) e [conteúdos](#__tabbed_1_12) de peso excessivo |
    | Sinônimo         | Tamanho máximo |
    | Léxicos Relacionados | [Auto-compactação](#__tabbed_1_13), [Enviar](#__tabbed_1_11), [Tarefa](#__tabbed_1_10) |
    | Requisito        | RE25 |
    /// caption | <
    Tabela 15 — Léxico de ‘limite de tamanho’
    ///
    /// caption
    Fonte: João Paulo, Rodrigo Orlandi
    ///

=== "L15"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Corrigir  |
    | Noção            | Ato de verificar as respostas da [tarefa](#__tabbed_1_10) [enviada](#__tabbed_1_11) com o intuito de classificar como correto, incompleto ou errado. Pode ser realizado pelos [usuários](#__tabbed_1_5) [‘professor’](#__tabbed_1_7) e [‘monitor’](#__tabbed_1_8). |
    | Classificação    | Verbo |
    | Impacto          | Permite que [usuários](#__tabbed_1_5) [‘professor’](#__tabbed_1_7) e [‘monitor’](#__tabbed_1_8) possam verificar as [tarefas](#__tabbed_1_10) [enviadas](#__tabbed_1_11) do [aluno](#__tabbed_1_6). Permite que o [aluno](#__tabbed_1_6) possa verificar o [feedback](#__tabbed_1_19) das [tarefas](#__tabbed_1_10). |
    | Sinônimo         | Verificar |
    | Léxicos Relacionados | [Feedback](#__tabbed_1_19), [Tarefa](#__tabbed_1_10), [Professor](#__tabbed_1_7), [Monitor](#__tabbed_1_8) |
    | Requisito        | RE26 |
    /// caption | <
    Tabela 16 — Léxico de ‘corrigir’
    ///
    /// caption
    Fonte: Esther Sousa, Rodrigo Orlandi
    ///

=== "L16"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Sistema  |
    | Noção            | Representa o software analisado, Moodle, como um conjunto universal denominado sistema. |
    | Classificação    | Objeto |
    | Impacto          | Permite que todos os requisitos funcionais e não funcionais sejam implementados, permite [usuários](#__tabbed_1_5) navegarem pelo sistema |
    | Sinônimo         | Ordenação, Software, Plataforma Moodle, Aplicativo Moodle |
    | Léxicos Relacionados |  |
    | Requisito        | RE28 |
    /// caption | <
    Tabela 17 — Léxico de ‘sistema’
    ///
    /// caption
    Fonte: Esther Sousa, Rodrigo Orlandi
    ///

=== "L17"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Chamada de vídeo  |
    | Noção            | Funcionalidade do [sistema](#__tabbed_1_16) que permite [usuários](#__tabbed_1_5) se encontrarem em uma sala virtual, realizando uma chamada virtual em que se assemelhe a uma aula. Todos podem falar e ser escutados. |
    | Classificação    | Estado |
    | Impacto          | Permite a realização de aulas remotas |
    | Sinônimo         | Videochamada, *videocall*, *call* |
    | Léxicos Relacionados | [Curso](#__tabbed_1_4) |
    | Requisito        | RE28 |
    /// caption | <
    Tabela 18 — Léxico de ‘chamada de vídeo’
    ///
    /// caption
    Fonte: Esther Sousa, Rodrigo Orlandi
    ///

=== "L18"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Curso arquivado  |
    | Noção            | [Cursos](#__tabbed_1_4) encerrados pelo [professor](#__tabbed_1_7) podem ser acessados como arquivados |
    | Classificação    | Estado |
    | Impacto          | Acesso à esses [cursos](#__tabbed_1_4) é limitado ao modo leitura|
    | Sinônimo         | Curso fechado |
    | Léxicos Relacionados | [Curso](#__tabbed_1_4) |
    | Requisito        | RE09|
    /// caption | <
    Tabela 19 — Léxico de ‘curso arquivado’
    ///
    /// caption
    Fonte: Laís Cecília
    ///

=== "L19"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Nome             | Feedback |
    | Noção            | Correção e sugestões de melhoria de uma [tarefa](#__tabbed_1_10) [enviada](#__tabbed_1_11). Criado pelo [professor](#__tabbed_1_7) ou [monitor](#__tabbed_1_8) ao [corrigir](#__tabbed_1_15) uma [tarefa](#__tabbed_1_10) |
    | Classificação    | Objeto |
    | Impacto          | Oferece ao [aluno](#__tabbed_1_6) um retorno sobre as [tarefas](#__tabbed_1_10) [enviadas](#__tabbed_1_11)|
    | Sinônimo         | Retorno, Correção |
    | Léxicos Relacionados | [Corrigir](#__tabbed_1_15) |
    | Requisito        | RE26|
    /// caption | <
    Tabela 20 — Léxico de ‘feedback’
    ///
    /// caption
    Fonte: Laís Cecília
    ///

------------

## Referência

| # | Fonte|
|---|:------|
| 1 | SERRANO, Milene. SERRANO, Maurício. Requisitos - Aula 10. 2017. UnB Gama (FCTE). Disponível em: [https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). Acesso em: 08/12/2024. |

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Feito upload da página | Rodrigo de Andrade| Esther Sousa| <input type="checkbox" onclick="return false;" disabled/> | 08/12/2024 |
| v1.1   | Hyperlinks entre léxicos | Laís Cecília | Julia Lopes| <input type="checkbox" onclick="return false;" disabled/> | 08/12/2024 |