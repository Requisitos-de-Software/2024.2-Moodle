# Cenários 

## Introdução

Cenários, de acordo com Barbosa et. al, são uma narrativa, textual ou pictórica, concreta, rica em detalhes
contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais [(BARBOSA, 2021)](https://aprender3.unb.br/pluginfile.php/2972437/mod_resource/content/2/ihc-ux-%20Personas.pdf).


Cenários são principalmente utilizados para ilustrar casos em que requisitos se tornam mais claros, ajudando a elicitação e no entendimento, tornando-os menos abstraros e mais concretos. Necessita-se dos [requisitos elicitados](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/arequisitos_elicitados/), ou pelo menos uma versão inicial, para que cenários possam ser implementados de maneira satisfatória. 


Usar cenários na especificação de requisitos "tem um forte impacto positivo na qualidade de requisitos, nomeadamente ao nível da adequação, completude parcial, habilidade de modificação e habilidade de verificação - desde que os cenários sejam usados de forma adequada" [(WIKIPEDIA, 2008)](https://pt.wikipedia.org/wiki/Cen%C3%A1rio_(software)).

## Metodologia e Execução

Dentro da especificação de requisitos, a utilização de cenários no projeto foi baseada em [requisitos não implementados](../areq_nao_imp) no Moodle.

Os cenários foram codificados na ordem dos requisitos não implementados. **C01** representa **R09**, com **R09** sendo o primeiro requisito não implementado do projeto. Além disso, o modelo utilizado para desenvoler os cenários pode ser visto na tabela 1, a seguir:

| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Objetivo         | Finalidade do cenário |
| Contexto         | Descrição de pré-condições, local (físico) e tempo | 
| Recursos         | Objetos passivos com os quais os atores interagem | 
| Ator             | Pessoa ou estrutura organizacional | 
| Episódios        | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos | 
| Restrições       | Imposição que restrinja um episódio de um cenário | 
| Exceções     | Tratamento para uma situação excepcional ou de erro |
/// caption | <
Tabela 1 — Template dos cenários
///
/// caption
Fonte: Lichess, 2024, *apud* Leite, 2003.
///

## Cenários Desenvolvidos

As tabelas 2-8, a seguir, representam os cenários desenvolvidos pela equipe acerca dos requisitos não implementados

=== "Revisitar Turma Anterior."

    | Categoria     | Descrição                  | 
    |---------------|----------------------------|
    | Código        | **C01** |
    | Título        | Revisitar Turma Anterior.   |
    | Objetivo      | Permitir que o usuário aluno visualize uma turma anterior. |
    | Contexto      | <ul><li> Usuário está logado em sua conta; <br><li> Dispositivo possui acesso a internet; <br> <li> A turma em questão foi encerrada.</ul> | 
    | Recursos      | <ul><li> Dispositivo celular; <br><li>  Conexão com a internet. <br></ul> | 
    | Ator          | Usuário Moodle | 
    | Episódios     | <ol><li> O usuário acessa a página "Meus Cursos" no aplicativo; <br> <li> O usuário clica no botão "Ver cursos arquivados"; <br> <li> O usuário seleciona a turma que deseja consultar.</ol>| 
    | Restrições    | <ul><li> O usuário deve já ter participado da turma como aluno; <br> <li> O usuário poderá somente visualizar o conteúdo.</ul> | 
    | Exceções      | Se a sessão estiver esgotada, o usuário será redirecionado à tela de login |
    /// caption | <
    Tabela 2 — Cenario referente ao [RE09](../areq_nao_imp/#requisitos): Revisitar turma anterior
    ///
    /// caption
    Fonte: Laís Cecília (Autora)
    ///

=== "Busca dentro da matéria."
    | Categoria     | Descrição                  | 
    |------------------|-----------------------------|
    | Código        | **C02** |
    | Título        | Busca dentro da matéria.   |
    | Objetivo       | Alunos devem poder buscar, dentro das disciplinas, por algum tópico específico.|
    | Contexto      | Aluno necessita achar um tópico específico dentro da página de uma matéria, então, para fazer de forma mais rápida usa um sistema de busca integrado para encontrar.| 
    | Recursos     | <ul><li> Smartphone com o conexão à internet; <br><li> Conta no Moodle.</ul> | 
    | Ator              | Aluno | 
    | Episódios     | <ol><li> Aluno acessa o Moodle; <br><li> Aluno entra na matéria de um professor; <br><li> Aluno busca por um conteúdo específico.</ol> | 
    | Restrições    | Não há um sistema de busca. | 
    | Exceções     | Falta de energia. |
    /// caption | <
    Tabela 3 — Cenário referente ao [RE21](../areq_nao_imp/#requisitos): O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.
    ///
    /// caption
    Fonte: João Paulo (Autor)
    ///

=== "Upload Rápido de Tarefa."

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Código        | **C03** |
    | Título        | Upload Rápido de Tarefa. |
    | Objetivo         | O usuário ‘Aluno’ tem de fazer upload de uma tarefa em um minuto. |
    | Contexto         | <ul><li> **Local**: Casa do usuário; <br> <li> **Tempo**: Noite, 23:58; <br> <li> **Pré-Condições**: Ter um dispositivo com um aplicativo que utilize o Moodle como base (Aprender3).</ul> | 
    | Recursos         | <ul><li> Smartphone/computador; <br><li> Aplicativo de framework Moodle. </ul>| 
    | Ator             | Usuário ‘Estudante’ de um aplicativo de framework Moodle  | 
    | Episódios        | <ol><li> O usuário faz login e acessa o aplicativo de framework Moodle; <br> <li> O usuário acessa a disciplina e encontra a entrega da tarefa; <br> <li> O usuário faz upload da tarefa e clica em enviar tarefa; <br> <li>A tarefa é considerada enviada com sucesso. </ol>| 
    | Restrições       | <ul><li>A tarefa será fechada em um minuto; <br><li> Tempo de espera entre clicar e carregar a página deve ser menor que dois segundos. </ul>| 
    | Exceções     |<ul><li> Smartphone/computador sem conexão à Internet;<br><li> Smartphone/computador sem bateria. </ul>|
    /// caption | <
    Tabela 4 — Cenário referente ao [RE22](../areq_nao_imp/#requisitos): O sistema deve ter um tempo de resposta menor ou igual a dois segundos para cada clique.
    ///
    /// caption
    Fonte: Rodrigo de Andrade (Autor)
    ///

=== "Auto-compactação de arquivos."

    | Categoria     | Descrição                  | 
    |------------------|-----------------------------|
    | Código        | **C04** |
    | Título        | Auto-compactação de arquivos.   |
    | Objetivo       | Compactar arquivos se excederem o tamanho máximo permitido. |
    | Contexto      | Alunos, ao enviarem a tarefa, se exceder o a quantidade de bytes máximos, ter um sistema que auto-compacta o arquivo enviado. | 
    | Recursos     | <ul><li> Smartphone com o conexão à internet; <br> <li> Conta no Moodle.</ul> | 
    | Ator              | Aluno | 
    | Episódios     | <ol><li> Aluno acessa o Moodle; <br> <li>Aluno entra na matéria de um professor; <br> <li>Aluno envia um arquivo; <br><li> O arquivo é compactado pelo sistema. </ol> | 
    | Restrições    | Não há um sistema de auto-compactação. | 
    | Exceções     | Falta de energia. |
    /// caption | <
    Tabela 5 — Cenário referente ao [RE25](../areq_nao_imp/#requisitos): O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.
    ///
    /// caption
    Fonte: João Paulo (Autor)
    ///

=== "Porcentagem de conclusão da disciplina." 

    | Categoria     | Descrição                  | 
    |------------------|-----------------------------|
    | Código        | **C05** |
    | Título        | Porcentagem de conclusão da disciplina.   |
    | Objetivo       | O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina. |
    | Contexto      | <ul><li> **Local**: Em casa; <br> <li> **Tempo**: No horário fora de aula; <br> <li> **Pré-condição**: Estar matriculado em uma disciplina e ter atividades feitas.</ul> | 
    | Recursos     | <ul><li> Dispositivo com acesso ao moodle; <br> <li> Ter conta no Moodle. </ul>| 
    | Ator              | Aluno | 
    | Episódios     | <ol><li> O aluno realiza uma atividade; <br> <li> Abre a seção de porcentagem de conclusão do curso; <br> <li> Visualiza a porcentagem que acabou de subir em relação a porcentagem anterior. </ol>| 
    | Restrições    | Quantidade de atividades disponíveis na disciplina. | 
    | Exceções     | <ul><li> Não estar em uma disciplina no Moodle; <br> <li> Não ter atividades </ul>|
    /// caption | <
    Tabela 6 — Cenário referente ao [RE26](../areq_nao_imp/#requisitos): O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.
    ///
    /// caption
    Fonte: Esther Sousa (Autora)
    ///

=== "Aulas síncronas por chamada de vídeo."

    | Categoria     | Descrição                  | 
    |------------------|-----------------------------|
    | Código        | **C06** |
    | Título        | Aulas síncronas por chamada de vídeo.   |
    | Objetivo       | O sistema permite a realização de aulas síncronas por chamada de vídeo. |
    | Contexto      | <ul><li> **Local**: Em casa; <br> <li> **Tempo**: Horário da aula; <br> <li> **Pré-condição**: Está cadastrado na disciplina no Moodle.</ul> | 
    | Recursos     | <ul><li> Dispositivo com acesso ao moodle; <br> <li> Ter conta no Moodle.</ul> | 
    | Atores              | <ul> <li> Aluno; <br> <li> Professor. </ul> | 
    | Episódios     | <ol><li>O professor faz login no Moodle; <br> <li> O professor em sua disciplina inicia uma chamada de vídeo disponível para os alunos da disciplina pelo Moodle; <br> <li> O aluno faz login no Moodle; <br> <li> O aluno entra na página da disciplina; <br> <li> O aluno entra na seção de aulas por chamada de vídeo; <br> <li> O aluno entra na chamada de vídeo criada pelo professor no momento. </ol>| 
    | Restrições    | Usuários terem câmera. | 
    | Exceções     | <ul><li> Não estar na disciplina no Moodle; <br> <li> Não ter uma câmera.</ul> |
    /// caption | <
    Tabela 7 — Cenário referente ao [RE28](../areq_nao_imp/#requisitos): O sistema permite a realização de aulas síncronas por chamas de vídeo
    ///
    /// caption
    Fonte: Esther Sousa (Autora)
    ///

=== "Pesquisa por turma"

    | Categoria        | Descrição                                                                                  |  
    |------------------|--------------------------------------------------------------------------------------------|
    | Código           | **C07** |
    | Título        | Pesquisa por turma   |
    | Objetivo         |  O usuário ‘Aluno’ tem de encontrar a turma na qual está matriculado e inserir a senha entregue para ingressar na disciplina. |
    | Contexto         | <ul><li>**Local**: Casa do usuário; <br><li>**Tempo**: Qualquer;<br><li> **Pré-Condições**: Ter um dispositivo com um aplicativo que utilize o Moodle como base (Aprender3)</ul> |
    | Recursos         | <ul><li> Smartphone/computador;<br><li> Aplicativo de framework Moodle</ul> |
    | Ator             | Usuário ‘Estudante’ de um aplicativo de framework Moodle  |
    | Episódios        | <ol><li> O usuário faz login e acessa o aplicativo de framework Moodle; <br><li>O usuário encontra a barra de busca e insere o código da matéria; <br><li> O usuário se inscreve na matéria ao utilizar a senha.</ol> |
    | Restrições       | A barra de busca de disciplina tem de estar facilmente localizável |
    | Exceções     | <ul><li>Smartphone sem conexão à Internet; <br><li> Smartphone sem bateria.</ul> |
    /// caption | <
    Tabela 8 — Cenário referente ao [RE31](../areq_nao_imp/#requisitos): Encontrar a barra de busca de turmas é facilmente localizável e intuitiva.
    ///
    /// caption
    Fonte: Júlia Lopes (Autor)
    ///

---

## Referências

| # | Fonte|
|---|:------|
| 1 | BARBOSA, S. et al. Interação Humano-Computador e Experiência do Usuário. [s.l.] Autopublicação - Leanpub, 2021. Capítulo 8, Página 172. Seção disponível em: [https://aprender3.unb.br/pluginfile.php/2972437/mod_resource/content/2/ihc-ux-%20Personas.pdf](https://aprender3.unb.br/pluginfile.php/2972437/mod_resource/content/2/ihc-ux-%20Personas.pdf). Acesso em: 07/12/2024|
| 2 | *In*: WIKIPÉDIA: a enciclopédia livre. [São Francisco, CA: Fundação Wikimedia], 2008. Disponível em: [https://pt.wikipedia.org/wiki/Cen%C3%A1rio_(software)](https://pt.wikipedia.org/wiki/Cen%C3%A1rio_(software)) . Acesso em: 07/12/2024 |  
| 3 | CENÁRIOS - Lichess. Lichess, 2022. Acessível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/cenarios/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/cenarios/)
| 4 | LEITE, Julio Cesar Sampaio do Prado. **Cenários:** Rastreamento de Cenários. PUC-Rio, 2003. Acessível em: [https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf)|

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Feito upload da página | Rodrigo de Andrade| João Paulo | <input type="checkbox" onclick="return false;" disabled/> | 07/12/2024 |
| v1.1   | RE09                       | Laís Cecília                    | João Paulo               | <input type="checkbox" onclick="return false;" disabled /> | 07/12/2024 |
| v1.2   | Cenários reunidos          | Laís Cecília                    | João Paulo               | <input type="checkbox" onclick="return false;" disabled /> | 08/12/2024 |

