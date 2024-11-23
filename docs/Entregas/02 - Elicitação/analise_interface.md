# Análise de Interface de Usuário

## Introdução

Análise de interface de usuário (*User interface analysis*), de acordo com [Wiegers et. al (2013)](https://aprender3.unb.br/pluginfile.php/2972451/mod_resource/content/1/Elicitacao%20de%20Req.pdf), é uma técnica de elicitação independente na qual se estuda sistemas existentes para descobrir requisitos de usuário e requisitos funcionais. Pode se usar *prints* para seu estudo. A análise da interface de usuário (IU) pode ajudar a identificar uma lista completa de telas para descobrir potenciais funcionalidades.

## Planejamento e Metodologia

Tendo em vista os [perfis de usuários](link_perfil_usuarios) elaborados pela equipe para o sistema Moodle, foi definido que, para realizar a técnica de análise de interface, buscaríamos ao menos um aluno e um monitor para ver como o app se diferencia entre eles, considerando também, se possível, a análise de interface de um tipo de usuário no Moodle equivalente ao 'Professor' definido nos [perfis de usuários](link_perfil_usuarios) deste projeto. O cronograma de atividades referentes à análise de interfaces pode ser visto na tabela 1, a seguir. 

### Tabela 1 - Cronograma planejado das atividades referentes à análise de interfaces.
| Dia     | Atividade                  | Participantes           | 
|---------|----------------------------|-------------------------|
| 18/11   | Planejamento da realização da análise de interfaces | Laís Cecília, Rodrigo Orlandi | 
| 20/11   | Realização da análise de interface - Aluno  | Laís Cecília, Rodrigo Orlandi | 
| 22/11   | Realização da análise de interface - Monitor  | Laís Cecília, Rodrigo Orlandi | 
| 23/11   | Revisão e correção do artefato  | Laís Cecília, Rodrigo Orlandi | 


## Execução - Análise de Interface

Durante a execução da análise de interface, houve dois contratempos notáveis:
* A equipe tentou entrar em contato com um professor, porém, devido a imprevistos em outras partes do projeto, não foi possível realizar a análise de interface do tipo de usuário 'Professor';
* Infelizmente, dentro das turmas do Moodle na FCTE ao qual tivemos acesso, nenhum instrutor fazia uso das funcionalidades especiais do Moodle para monitores, com o sistema apresentando funcionalidades equivalentes ao utilizado pelo usuário do tipo 'Aluno'. 

## Requisitos Elicitados

=== "Moodle"

    Como interface de estudo para o Moodle, foi utilizada a ferramenta Aprender3.

    | Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  |
    |---------|----------------------------|-------------------------|---------------------|
    | 01      |  Requisito Funcional       |  O sistema requer login do usuário para acessar | SIM |
    | 02      |  Requisito Funcional       |  O sistema permite que alunos visualizem os materiais da turma| SIM |
    | 03      |  Requisito Funcional       |  O sistema permite que alunos baixem os materiais da turma| SIM |
    | 04      |  Requisito Funcional       |  O sistema permite que alunos visualizem a agenda de atividades | SIM |
    | 05      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |
    | 06      |  Requisito Funcional       |  O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM |
    | 07      |  Requisito Funcional       |  O sistema permite que alunos façam upload de tarefas | SIM |

    /// caption | <
    Tabela 1 — Requisitos extraídos do Moodle.
    ///
    /// caption
    Fonte: autores
    ///

=== "Google Classroom"

    Foi feita uma análise do Google Classroom como competidor do moodle. Essa análise foi feita a partir da interface de usuário aluno.

    | Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado no Moodle?  |
    |---------|----------------------------|-------------------------|---------------------|
    | 01      |  Requisito Funcional       |  O sistema requer login do usuário para acessar | SIM |
    | 02      |  Requisito Funcional       |  O sistema permite que alunos visualizem os materiais da turma| SIM |
    | 03      |  Requisito Funcional       |  O sistema permite que alunos baixem os materiais da turma| SIM |
    | 04      |  Requisito Funcional       |  O sistema permite que alunos visualizem a agenda de atividades | SIM |
    | 05      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |
    | 06      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO |
    | 07      |  Requisito Funcional       |  O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM |
    | 08      |  Requisito Não Funcional   |  A navegação deve ser símples e centralizada | NÃO |
    | 09      |  Requisito Funcional       |  O sistema permite que alunos façam upload de tarefas | SIM |
    /// caption | <
    Tabela 2 — Requisitos extraídos do Google Classroom
    ///
    /// caption
    Fonte: autores
    ///
=== "Microsoft Teams"

    Foi feita uma análise do Microsoft Teams como competidor do moodle. Essa análise foi feita a partir da interface de usuário aluno.

    | Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado no Moodle?  |
    |---------|----------------------------|-------------------------|---------------------|
    | 01      |  Requisito Funcional       |  O sistema requer login do usuário para acessar | SIM |
    | 02      |  Requisito Funcional       |  O sistema permite a realização de aulas síncronas por chamas de vídeo | NÃO |
    | 03      |  Requisito Funcional       |  O sistema permite que alunos visualizem a agenda de atividades | SIM |
    | 04      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO |
    | 05      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |
    | 06      |  Requisito Funcional       |  O sistema permite que alunos visualizem os materiais da turma| SIM |
    | 07      |  Requisito Funcional       |  O sistema permite que alunos baixem os materiais da turma| SIM |
    | 08      |  Requisito Funcional       |  O sistema permite que alunos façam upload de tarefas | SIM |
    | 09      |  Requisito Funcional       |  O sistema disponibiliza as notas do usuário | SIM |
    | 10      |  Requisito Funcional       |  O sistema integra outros aplicativos da mesma família para uso da turma | NÃO |
    | 11      |  Requisito Funcional       |  O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM |
    | 12      |  Requisito Funcional       |  O sistema permite que usuários conversem por chats privados | SIM |
    /// caption | <
    Tabela 3 — Requisitos extraídos do Microsoft Teams
    ///
    /// caption
    Fonte: autores
    ///


---

## Referências

| # | Fonte |
|---|:------|
| 1 | WIEGERS, Karl; BEATTY, Joy. **Software Requirements**. Pearson Education. 3 ed. 2013. 121p - 129p. Seção disponível em:(https://aprender3.unb.br/pluginfile.php/2972451/mod_resource/content/1/Elicitacao%20de%20Req.pdf)[https://aprender3.unb.br/pluginfile.php/2972451/mod_resource/content/1/Elicitacao%20de%20Req.pdf]. Acesso em: 22/11/2024|  

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Página Criada              | Laís Cecília, Rodrigo de Andrade| -                        | <input type="checkbox" onclick="return false;" disabled/> | 22/11/2024 |



<iframe width="500" height="285" src="https://www.youtube.com/embed/halkn1XoD2o?list=PLGRXxCmBB-YhV9OsHUsSMyU3LCnAUelIQ" title="Puppy Struggles to Use the Stairs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>