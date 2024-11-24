# Requisitos Elicitados

## Introdução
Seguem abaixo a lista de todos os requisitos não repetidos, elicitados durante através das metodologias de [análise de interface](./analise_interface.md), [entrevista](./entrevista.md) e [encenação](./encenacao.md):

## Todos os requisitos
### Legenda:

* ENT: Entrevista
* ENC: Encenação
* AN: Análise 'de interface


|Origem    | Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  |
|----------|---------|----------------------------|-------------------------|---------------------|
| 3ENT01   | 01      |  Requisito Funcional       | Sistema requer login do usuário para acessar | SIM | 
| 3ENT02   | 02      |  Requisito Funcional       | O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | SIM |
| 3ENT03   | 03      |  Requisito Funcional       | O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | SIM |  
| 5ENT21   | 04      |  Requisito Funcional       | O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | SIM |
| 5ENT16   | 05      |  Requisito Funcional       | O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | SIM |
| 5ENT17   | 06      |  Requisito Funcional       | O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | SIM |
| 5ENT18   | 07      |  Requisito Funcional       | O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | NÃO* |
| 3ENT08   | 08      |  Requisito Funcional       | O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| SIM | 
| 3AN06    | 09      |  Requisito Funcional       | O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO |
| 4AN09    | 10      |  Requisito Funcional       | O sistema disponibiliza as notas do usuário | SIM |
| 5ENT19   | 11      |  Requisito Funcional       | O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | SIM |
| 2AN05    | 12      |  Requisito Funcional       | O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |
| 1ENC05   | 13      |  Requisito não Funcional   | O sistema permite que o 'aluno' veja feedback de tarefas|  SIM |
| 3ENT04   | 14      |  Requisito Funcional       | O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. |  SIM |
| 5ENT14   | 15      |  Requisito Funcional       | O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | SIM |
| 5ENT20   | 16      |  Requisito Funcional       | O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | SIM |
| 2AN06    | 17      |  Requisito Funcional       | O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM |
| 4ENT10   | 18      |  Requisito Funcional       | O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | SIM |
| 3ENT05   | 19      |  Requisito Funcional       | O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | SIM |
| 3ENT06   | 20      |  Requisito Não Funcional   | A navegação do aplicativo mobile deve ser simples e intuitiva. | NÃO | 
| 3ENT07   | 21      |  Requisito Funcional       | O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| NÃO | 
| 4ENT09   | 22      |  Requisito Não Funcional   | O sistema deve ter um tempo de resposta admissível. | NÃO |
| 4ENT11   | 23      |  Requisito Funcional       | O sistema deve permitir que usuários possam responder formulários. | SIM |
| 4ENT12   | 24      |  Requisito Não Funcional   | Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | SIM |
| 4ENT13   | 25      |  Requisito Não Funcional   | O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| NÃO | 
| 5ENT15   | 26      |  Requisito Funcional       | O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| NÃO |
| 2AN07    | 27      |  Requisito Funcional       | O sistema permite que alunos façam upload de tarefas | SIM |
| 4AN02    | 28      |  Requisito Funcional       | O sistema permite a realização de aulas síncronas por chamas de vídeo | NÃO |
| 4AN10    | 29      |  Requisito Funcional       | O sistema integra outros aplicativos da mesma família para uso da turma | NÃO |
| 4AN12    | 30      |  Requisito Funcional       | O sistema permite que usuários conversem por chats privados | SIM |
| 1ENC03   | 31      |  Requisito não Funcional   | Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | NÃO |  
/// caption | < 
Tabela 1 — Todos os requisitos elicitados
///
/// caption
Fonte: autores
///

\* Observação: O requisito 07 é atualmente aplicável apenas para o tipo de usuário 'Professor', e não 'Monitor'.

---

## Histórico

| Versão | Descrição                  | Autor                   | Revisor                  |Revisado | Data       |
|--------|----------------------------|-------------------------|--------------------------|---------|------------|
| v1.0   | Requisitos reunidos        | Júlia Lopes             |  -                       |<input type="checkbox" onclick= "return false" disabled />  | 24/11/2024 |