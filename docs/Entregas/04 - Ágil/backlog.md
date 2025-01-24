# Backlog de Produto

## Introdução

O *Backlog* de produto(regisitro pendente de trabalhos) é uma lista que reune os requisitos do projeto que fornecem valor comercial ao cliente e suas prioridades, sendo constantemente atualizada (PRESSMAN, 2021). O backlog serve como ponto de partida do desenvolvimento das funcionalidades do projeto, e as categoriza em diversos níveis de abstração.

## Metodologia

A partir dos [Requisitos](../02%20-%20Elicitação/arequisitos_elicitados.md#requisitos) funcionais elicitados anteriormente, foi feita uma análise que os categorizou em diversos épicos, os mesmo sendo categorizados em temas. Além disso, para cada requisito foi desenvolvida uma [História de Usuário](./a_us.md) que o caracteriza, foi também atribuida a [Prioridade](../02%20-%20Elicitação/Priorização/index.md) determinada a ele. A tabela 1, a seguir, mostra o template seguido ao montar a tabela de Backlog.

<table>
    <tr>
        <td style="text-align: center">Tema</td>
        <td style="text-align: center">Épico</td>
        <td style="text-align: center">História de Usuário</td>
        <td style="text-align: center">Código</td>
        <td style="text-align: center">Prioridade</td>
        <td style="text-align: center">Requisito de Origem</td>
    </tr>
    <tr>
        <!-- Tema -->
        <td style="vertical-align: middle" rowspan=4>Tema 1</td>
        <!-- Épico -->
        <td style="vertical-align: middle" rowspan=2>Épico 1</td>
        <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>USXXX</td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>US001</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- Épico -->
         <td style="vertical-align: middle" rowspan=2>Épico 2</td>
         <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>USXXX</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>USXXX</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- Tema -->
        <td style="vertical-align: middle" rowspan=4>Tema 2</td>
        <!-- Épico -->
        <td style="vertical-align: middle" rowspan=2>Épico 3</td>
        <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>USXXX</td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>US001</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- Épico -->
         <td style="vertical-align: middle" rowspan=2>Épico 4</td>
         <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>USXXX</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário...</td>
        <!-- Código -->
        <td>USXXX</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>REXX</td>
    <tr>
</table>

/// caption | <
Tabela 1 — Template de Backlog de produto
///
/// caption
Fonte: Laís Cecília(Autora)
///

## Backlog

Segue, na tabela 2, o backlog formulado para o Moodle.

<table>
    <tr>
        <td style="text-align: center">Tema</td>
        <td style="text-align: center">Épico</td>
        <td style="text-align: center">História de Usuário</td>
        <td style="text-align: center">Código</td>
        <td style="text-align: center">Prioridade</td>
        <td style="text-align: center">Requisito de Origem</td>
    </tr>
    <tr>
        <!-- Tema -->
        <td style="vertical-align: middle" rowspan=6>Sistema</td>
        <!-- Épico -->
        <td style="vertical-align: middle" rowspan=2>Login</td>
        <!-- História de Usuário-->
        <td>Eu, como professor, quero realizar o login para acessar minhas turmas.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US01</a></td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE01</a></td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu, como aluno, quero entrar na turma e visualizar o conteúdo que o professor disponibilizou, para poder estudar.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US02</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE02</a></td>
    </tr>
    <tr>
        <!-- Épico -->
         <td style="vertical-align: middle" rowspan=4>Filtragem</td>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero pesquisar por palavras-chave dentro de uma disciplina, para encontrar rapidamente materiais, atividades ou informações relacionadas ao que estou estudando.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US20</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE21</a></td>
    </tr>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero utilizar filtros na busca dentro de uma disciplina, para refinar os resultados e encontrar rapidamente o que procuro.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US21</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE21</a></td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero filtrar pelas minhas matérias para achar o que tenho que estudar mais facilmente.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US03</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE04</a></td>
        </tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário, desejo poder ver as notas que obtive para poder estar ciente da minha situação na matéria.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US08</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE10</a></td>
    </tr>
          <!-- Tema -->
        <td style="vertical-align: middle" rowspan=12>Turmas</td>
        <!-- Épico -->
        <td style="vertical-align: middle" rowspan=4>Tarefas</td>
        <!-- História de Usuário-->
        <td>Eu, como aluno, gostaria de poder baixar arquivos do moodle, para facilitar meu acesso a esses arquivos sem a necessidade de acessar o site toda vez.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US10</a></td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE03</a></td>
    </tr>
        <tr>
        <!-- História de Usuário-->
        <td>Eu, como aluno, quero poder enviar o arquivo pedido na tarefa  para poder ser avaliado pelo professor.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US27</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE27</a></td>
    </tr>
            <!-- Épico -->
        <tr>
        <!-- História de Usuário-->
        <td>Eu, como professor, quero poder corrigir as atividades enviadas por alunos para poder acompanhar a evolução do aprendizado.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US04</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE08</a></td>
    </tr>
        </tr>
            <!-- Épico -->
        <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário, desejo poder realizar atividades e testes no formato de questionário pelo Moodle, para poder ter a flexibilidade de um ensino híbrido ou remoto.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US07</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE23</a></td>
    </tr>
    <tr>
     <!-- Épico -->
        <td style="vertical-align: middle" rowspan=5>Organização</td>
        <!-- História de Usuário-->
        <td>Eu, como aluno, quero visualizar a porcentagem restante para concluir a disciplina para poder me organizar no andamento do semestre.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US24</a></td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE28</a></td>
    </tr>
     <tr>
        <!-- História de Usuário-->
        <td>Eu, como professor, quero organizar o conteúdo a ser dado em tópicos para deixar as turmas mais organizadas, deixando-o mais legível para mim e para os alunos.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US05</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE14</a></td>
    </tr>
         <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário, desejo ser capaz de revisitar turmas anteriores para poder ver quem foram os meus colegas e professores.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US06</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE09</a></td>
    </tr>
         <tr>
        <!-- História de Usuário-->
        <td> Eu como aluno, quero ser notificado com antecedência personalizável (por exemplo, 1, 3 ou 7 dias antes) sobre as deadlines, para que eu tenha tempo suficiente para concluir as tarefas.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US17</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE06</a></td>
    </tr>
         <tr>
        <!-- História de Usuário-->
        <td> Eu, como aluno, quero poder assistir aula síncronas a distância na plataforma, sem precisar de terceiros para ter a praticidade de acompanhar as aulas mesmo a distância.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US25</a></td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE28</a></td>
    </tr>
    <tr>
        <!-- Épico -->
         <td style="vertical-align: middle" rowspan=3>Fórum e chat</td>
         <!-- História de Usuário-->
        <td>Eu como aluno gostaria de fazer utilização de chats de conversa privado para tirar dúvidas com monitores/professores</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US13</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE30</a></td>
    </tr>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero acessar um fórum para conversar com meus professores e colegas, para esclarecer dúvidas e discutir temas relacionados à disciplina.</td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US18</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE17</a></td>
    </tr>
     <!-- História de Usuário-->
        <td>Eu como aluno, quero receber notificações quando alguém responder a meus tópicos ou comentários no fórum, para acompanhar as discussões em tempo </td>
        <!-- Código -->
        <td><a href="../a_us#historias-de-usuarios-us">US19</a></td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td><a href="../../02 - Elicitação/arequisitos_elicitados#requisitos">RE17</a></td>
    </tr>
</table>

/// caption | <
Tabela 2 — Tabela de Backlog de produto
///
/// caption
Fonte: Júlia Lopes
///

## Gravação

<iframe width="500" height="285" src="https://www.youtube.com/embed/_dWPeMfJdwI" title="[2024-2] Requisitos - Grupo 2 - Gravação de Backlog" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

## Referências

| # | Fonte |
|---|-------|
| 1 | PRESSMAN, Roger S.; MAXIM, Bruce R. **Engenharia de software**. McGraw Hill Brasil, 9ª ed, Porto Alegre, 2021. |

## Histórico

| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Página Criada              | Laís Cecília, Júlia Lopes  |  Esther Sousa                        | <input type="checkbox" onclick="return false;" disabled checked/> | 14/12/2024 |
| v1.1 | Pendência entrega passada (referência à tabela) | Laís Cecília | Rodrigo de Andrade | <input type="checkbox" onclick="return false;" disabled checked/> | 19/01/2025 |