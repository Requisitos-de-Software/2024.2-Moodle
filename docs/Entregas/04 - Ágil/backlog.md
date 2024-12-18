# Backlog de Produto

## Introdução

O *Backlog* de produto(regisitro pendente de trabalhos) é uma lista que reune os requisitos do projeto que fornecem valor comercial ao cliente e suas prioridades, sendo constantemente atualizada (PRESSMAN, 2021). O backlog serve como ponto de partida do desenvolvimento das funcionalidades do projeto, e as categoriza em diversos níveis de abstração.

## Metodologia

A partir dos [Requisitos](../02%20-%20Elicitação/arequisitos_elicitados.md#requisitos) funcionais elicitados anteriormente, foi feita uma análise que os categorizou em diversos épicos, os mesmo sendo categorizados em temas. Além disso, para cada requisito foi desenvolvida uma [História de Usuário] que o caracteriza, foi também atribuida a [Prioridade] determinada a ele. A tabela 1, a seguir, mostra o template seguido ao montar a tabela de Backlog.

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
        <td>US01</td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td>RE01</td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu, como aluno, quero entrar na turma e visualizar o conteúdo que o professor disponibilizou, para poder estudar.</td>
        <!-- Código -->
        <td>US02</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE02</td>
    </tr>
    <tr>
        <!-- Épico -->
         <td style="vertical-align: middle" rowspan=4>Filtragem</td>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero pesquisar por palavras-chave dentro de uma disciplina, para encontrar rapidamente materiais, atividades ou informações relacionadas ao que estou estudando.</td>
        <!-- Código -->
        <td>US20</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE21</td>
    </tr>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero utilizar filtros na busca dentro de uma disciplina, para refinar os resultados e encontrar rapidamente o que procuro.</td>
        <!-- Código -->
        <td>US21</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE21</td>
    </tr>
    <tr>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero filtrar pelas minhas matérias para achar o que tenho que estudar mais facilmente.</td>
        <!-- Código -->
        <td>US03</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE04</td>
        </tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário, desejo poder ver as notas que obtive para poder estar ciente da minha situação na matéria.</td>
        <!-- Código -->
        <td>US08</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE10</td>
    </tr>
          <!-- Tema -->
        <td style="vertical-align: middle" rowspan=12>Turmas</td>
        <!-- Épico -->
        <td style="vertical-align: middle" rowspan=4>Tarefas</td>
        <!-- História de Usuário-->
        <td>Eu, como aluno, gostaria de poder baixar arquivos do moodle, para facilitar meu acesso a esses arquivos sem a necessidade de acessar o site toda vez.</td>
        <!-- Código -->
        <td>US10</td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td>RE03</td>
    </tr>
        <tr>
        <!-- História de Usuário-->
        <td>Eu, como aluno, quero poder enviar o arquivo pedido na tarefa  para poder ser avaliado pelo professor.</td>
        <!-- Código -->
        <td>US27</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE27</td>
    </tr>
            <!-- Épico -->
        <tr>
        <!-- História de Usuário-->
        <td>Eu, como professor, quero poder corrigir as atividades enviadas por alunos para poder acompanhar a evolução do aprendizado.</td>
        <!-- Código -->
        <td>US04</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE08</td>
    </tr>
        </tr>
            <!-- Épico -->
        <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário, desejo poder realizar atividades e testes no formato de questionário pelo Moodle, para poder ter a flexibilidade de um ensino híbrido ou remoto.</td>
        <!-- Código -->
        <td>US07</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE23</td>
    </tr>
    <tr>
     <!-- Épico -->
        <td style="vertical-align: middle" rowspan=5>Organização</td>
        <!-- História de Usuário-->
        <td>Eu, como aluno, quero visualizar a porcentagem restante para concluir a disciplina para poder me organizar no andamento do semestre.</td>
        <!-- Código -->
        <td>US24</td>
        <!-- Prioridade -->
        <td>Alta</td>
        <!-- Rastreabilidade -->
        <td>RE28</td>
    </tr>
     <tr>
        <!-- História de Usuário-->
        <td>Eu, como professor, quero organizar o conteúdo a ser dado em tópicos para deixar as turmas mais organizadas, deixando-o mais legível para mim e para os alunos.</td>
        <!-- Código -->
        <td>US05</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE14</td>
    </tr>
         <tr>
        <!-- História de Usuário-->
        <td>Eu, como usuário, desejo ser capaz de revisitar turmas anteriores para poder ver quem foram os meus colegas e professores.</td>
        <!-- Código -->
        <td>US06</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE09</td>
    </tr>
         <tr>
        <!-- História de Usuário-->
        <td> Eu como aluno, quero ser notificado com antecedência personalizável (por exemplo, 1, 3 ou 7 dias antes) sobre as deadlines, para que eu tenha tempo suficiente para concluir as tarefas.</td>
        <!-- Código -->
        <td>US17</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE06</td>
    </tr>
         <tr>
        <!-- História de Usuário-->
        <td> Eu, como aluno, quero poder assistir aula síncronas a distância na plataforma, sem precisar de terceiros para ter a praticidade de acompanhar as aulas mesmo a distância.</td>
        <!-- Código -->
        <td>US25</td>
        <!-- Prioridade -->
        <td>Média</td>
        <!-- Rastreabilidade -->
        <td>RE28</td>
    </tr>
    <tr>
        <!-- Épico -->
         <td style="vertical-align: middle" rowspan=3>Fórum e chat</td>
         <!-- História de Usuário-->
        <td>Eu como aluno gostaria de fazer utilização de chats de conversa privado para tirar dúvidas com monitores/professores</td>
        <!-- Código -->
        <td>US13</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE30</td>
    </tr>
        <!-- História de Usuário-->
        <td>Eu como aluno, quero acessar um fórum para conversar com meus professores e colegas, para esclarecer dúvidas e discutir temas relacionados à disciplina.</td>
        <!-- Código -->
        <td>US18</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE17</td>
    </tr>
     <!-- História de Usuário-->
        <td>Eu como aluno, quero receber notificações quando alguém responder a meus tópicos ou comentários no fórum, para acompanhar as discussões em tempo </td>
        <!-- Código -->
        <td>US19</td>
        <!-- Prioridade -->
        <td>Baixa</td>
        <!-- Rastreabilidade -->
        <td>RE17</td>
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
| v1.0   | Página Criada              | Laís Cecília, Júlia Lopes  |  Esther Sousa                        | <input type="checkbox" onclick="return false;" disabled/> | 14/12/2024 |