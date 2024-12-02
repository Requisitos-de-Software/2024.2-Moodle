# Requisitos Elicitados

Apresentados na tabela 1, a seguir, estão os requisitos elicitados não repetidos, adquiridos durante a ulilização das metodologias de [análise de interface](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/analise_interface/), [entrevista](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/entrevista/) e [encenação](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/encenacao/): 

| Código  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  | Origem |
|---------|----------------------------|-------------------------|---------------------|--------|
| RE01    |  Requisito Funcional       |  Sistema requer login do usuário para acessar | SIM | ANA01, ANA08, ANA16, ENC01, ENT01 |
| RE02    |  Requisito Funcional       |  O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | SIM | ANA02, ANA09, ANA21, ENC02, ENT02|
| RE03    |  Requisito Funcional       |  O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | SIM | ENT03, ANA03, ANA10, ANA22 |
| RE04    |  Requisito Funcional       |  O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | SIM |ENT21 |
| RE05    |  Requisito Funcional       |  O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | SIM |ENT16 |
| RE06    |  Requisito não Funcional   |  O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | SIM | ENT17, ANA04, ANA11, ANA18 |
| RE07    |  Requisito Funcional       |  O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | NÃO |ENT18 |
| RE08    |  Requisito Funcional       |  O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| SIM | ENT08 |
| RE09    |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO | ANA13, ANA19 |
| RE10    |  Requisito Funcional       |  O sistema disponibiliza as notas do usuário | SIM | ANA24 |
| RE11    |  Requisito Funcional       |  O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | SIM |ENT19 |
| RE12    |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |  ANA05, ANA12, ANA20 |
| RE13    |  Requisito não Funcional   |  O sistema permite que o 'aluno' veja feedback de tarefas|  SIM | ENC05 |
| RE14    |  Requisito Funcional       |  O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. |  SIM |ENT04 |
| RE15    |  Requisito Funcional       |  O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | SIM |ENT14 |
| RE16    |  Requisito Funcional       |  O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | SIM |ENT20 |
| RE17    |  Requisito Funcional       |  O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM | ANA06, ANA14, ANA26 |
| RE18    |  Requisito Funcional       |  O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | SIM |ENT10 |
| RE19    |  Requisito Funcional       |  O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | SIM | ENT05, ANA04, ANA11, ANA18 |
| RE20    |  Requisito Não Funcional   |  A navegação do aplicativo mobile deve ser simples e intuitiva. | NÃO | ANA15, ENT06 |
| RE21    |  Requisito Funcional       |  O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| NÃO | ENT07 |
| RE22    |  Requisito Não Funcional   |  O sistema deve ter um tempo de resposta admissível. | NÃO | ENT09 |
| RE23    |  Requisito Funcional       |  O sistema deve permitir que usuários possam responder formulários. | SIM |ENT11 |
| RE24    |  Requisito Não Funcional   |  Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | SIM |ENT12 |
| RE25    |  Requisito Não Funcional   |  O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| NÃO | ENT13 |
| RE26    |  Requisito Funcional       |  O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| NÃO |ENT15 |
| RE27    |  Requisito Funcional       |  O sistema permite que alunos façam upload de tarefas | SIM | ANA07, ANA16, ANA23, ENC04 |
| RE28    |  Requisito Funcional       |  O sistema permite a realização de aulas síncronas por chamas de vídeo | NÃO | ANA17 |
| RE29    |  Requisito Funcional       |  O sistema integra outros aplicativos da mesma família para uso da turma | NÃO | ANA25 |
| RE30    |  Requisito Funcional       |  O sistema permite que usuários conversem por chats privados | SIM | ANA27 |
| RE31    |  Requisito não Funcional          | Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | NÃO | ENC03 |
/// caption | <
Tabela 1 — Tabela com todos os requisitos elicitados e já priorizados
///
/// caption
Fonte: Autores
///


## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Página Criada              |Júlia Lopes e Rodrigo de Andrade| João Paulo Rodrigues                        | <input type="checkbox" onclick="return false;" disabled/> | 24/11/2024 |
| v1.1   | Adição da coluna de Origem |João Paulo Rodrigues| Júlia Lopes | <input type="checkbox" onclick="return false;" disabled/> | 24/11/2024 |
| v1.2   | Melhor rastreabilidade de duplicatas | Laís Cecília          | João Paulo Rodrigues     | <input type="checkbox" onclick="return false;" disabled/> | 02/12/2024 |
