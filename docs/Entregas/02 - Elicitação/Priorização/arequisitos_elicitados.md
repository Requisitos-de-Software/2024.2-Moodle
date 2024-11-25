# Requisitos Elicitados

Apresentados na tabela 1, a seguir, estão os requisitos elicitados não repetidos, adquiridos durante a ulilização das metodologias de [análise de interface](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/analise_interface/), [entrevista](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/entrevista/) e [encenação](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/encenacao/): 

### Tabela 1 - Tabela com todos os requisitos elicitados e já priorizados
| Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  | Origem |
|---------|----------------------------|-------------------------|---------------------|--------|
| 01   |  Requisito Funcional          |  Sistema requer login do usuário para acessar | SIM | Entrevista |
| 02   |  Requisito Funcional          |  O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | SIM | Entrevista |
| 03   |  Requisito Funcional          |  O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | SIM | Entrevista |
| 04      | Requisito Funcional        | O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | SIM |Entrevista |
| 05      | Requisito Funcional        | O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | SIM |Entrevista |
| 06      | Requisito não Funcional        | O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | SIM | Entrevista |
| 07      | Requisito Funcional        | O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | NÃO* |Entrevista |
| 08   |  Requisito Funcional          |  O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| SIM | Entrevista |
| 09      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO | Análise de Interface |
| 10      |  Requisito Funcional       |  O sistema disponibiliza as notas do usuário | SIM | Análise de Interface |
| 11      | Requisito Funcional        | O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | SIM |Entrevista |
| 12      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |  Análise de Interface |
| 13   |  Requisito não Funcional          |O sistema permite que o 'aluno' veja feedback de tarefas|  SIM | Encenação |
| 14   |  Requisito Funcional          |  O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. |  SIM |Entrevista |
| 15      | Requisito Funcional        | O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | SIM |Entrevista |
| 16      | Requisito Funcional        | O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | SIM |Entrevista |
| 17      |  Requisito Funcional       |  O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM | Análise de Interface |
| 18      | Requisito Funcional         | O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | SIM |Entrevista |
| 19   |  Requisito Funcional          |  O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | SIM |Entrevista |
| 20   |  Requisito Não Funcional      |  A navegação do aplicativo mobile deve ser simples e intuitiva. | NÃO | Entrevista |
| 21   |  Requisito Funcional          |  O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| NÃO | Entrevista |
| 22      | Requisito Não Funcional     | O sistema deve ter um tempo de resposta admissível. | NÃO |Entrevista |
| 23      | Requisito Funcional         | O sistema deve permitir que usuários possam responder formulários. | SIM |Entrevista |
| 24      | Requisito Não Funcional     | Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | SIM |Entrevista |
| 25      | Requisito Não Funcional     | O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| NÃO | Entrevista |
| 26      | Requisito Funcional        | O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| NÃO |Entrevista |
| 27      |  Requisito Funcional       |  O sistema permite que alunos façam upload de tarefas | SIM | Análise de Interface |
| 28      |  Requisito Funcional       |  O sistema permite a realização de aulas síncronas por chamas de vídeo | NÃO | Análise de Interface |
| 29      |  Requisito Funcional       |  O sistema integra outros aplicativos da mesma família para uso da turma | NÃO | Análise de Interface |
| 30      |  Requisito Funcional       |  O sistema permite que usuários conversem por chats privados | SIM | Análise de Interface |
| 31   |  Requisito não Funcional          | Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | NÃO | Encenação |


## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Página Criada              |Júlia Lopes e Rodrigo de Andrade| João Paulo Rodrigues                        | <input type="checkbox" onclick="return false;" disabled/> | 24/11/2024 |
| v1.1   | Adição da coluna de Origem |João Paulo Rodrigues| Júlia Lopes | <input type="checkbox" onclick="return false;" disabled/> | 24/11/2024 |
