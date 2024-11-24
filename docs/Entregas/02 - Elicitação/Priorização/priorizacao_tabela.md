Segue abaixo todos os requisitos elicitados não repitidos, que foram adquiridos durante a ulilização das metodologias análise de interface, entrevista e encenação: 

| Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  |
|---------|----------------------------|-------------------------|---------------------|
| 01   |  Requisito Funcional          |  Sistema requer login do usuário para acessar | SIM | 
| 02   |  Requisito Funcional          |  O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | SIM |
| 03   |  Requisito Funcional          |  O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | SIM |  
| 04      | Requisito Funcional        | O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | SIM |
| 05      | Requisito Funcional        | O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | SIM |
| 06      | Requisito não Funcional        | O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | SIM | 
| 07      | Requisito Funcional        | O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | NÃO* |
| 08   |  Requisito Funcional          |  O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| SIM | 
| 09      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO |
| 10      |  Requisito Funcional       |  O sistema disponibiliza as notas do usuário | SIM |
| 11      | Requisito Funcional        | O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | SIM |
| 12      |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que estão cadastrados| SIM |
| 13   |  Requisito não Funcional          |O sistema permite que o 'aluno' veja feedback de tarefas|  SIM |
| 14   |  Requisito Funcional          |  O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. |  SIM |
| 15      | Requisito Funcional        | O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | SIM |
| 16      | Requisito Funcional        | O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | SIM |
| 17      |  Requisito Funcional       |  O sistema disponibiliza um fórum para conversa entre alunos e professores | SIM |
| 18      | Requisito Funcional         | O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | SIM |
| 19   |  Requisito Funcional          |  O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | SIM |
| 20   |  Requisito Não Funcional      |  A navegação do aplicativo mobile deve ser simples e intuitiva. | NÃO | 
| 21   |  Requisito Funcional          |  O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| NÃO | 
| 22      | Requisito Não Funcional     | O sistema deve ter um tempo de resposta admissível. | NÃO |
| 23      | Requisito Funcional         | O sistema deve permitir que usuários possam responder formulários. | SIM |
| 24      | Requisito Não Funcional     | Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | SIM |
| 25      | Requisito Não Funcional     | O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| NÃO | 
| 26      | Requisito Funcional        | O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| NÃO |
| 27      |  Requisito Funcional       |  O sistema permite que alunos façam upload de tarefas | SIM |
| 28      |  Requisito Funcional       |  O sistema permite a realização de aulas síncronas por chamas de vídeo | NÃO |
| 29      |  Requisito Funcional       |  O sistema integra outros aplicativos da mesma família para uso da turma | NÃO |
| 30      |  Requisito Funcional       |  O sistema permite que usuários conversem por chats privados | SIM |
| 31   |  Requisito não Funcional          | Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | NÃO |  

## Priorização por Tabelas

Em uma aplicação da técnica de valor custo e risco, de acordo com [Wiegers et. al (2013)](https://aprender3.unb.br/pluginfile.php/2972454/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf), na página 326 , a equipe de requisitos pode medir os requisitos elicitados de acordo com o benefício, custo, risco e penalidade, estruturados na tabela 1, a seguir. Isso ajuda a decidir as prioridades relativas dos requisitos para o projeto.  

### Tabela 1 - Exemplo de medição da priorização por Wiegers.
| Requisito    | Benefício    | Penalidade  | Custo     |  Risco       |
|--------------|--------------|-------------|-----------|--------------|
| 01 - Sistema requer login do usuário para acessar. |  10    |   10          |   3       |     1      |
 
O grupo decidiu adaptar a priorização dos requisitos em uma escala de 1 a 10, julgando cada um de acordo com sua utilidade geral, pela maior facilidade em julgar os requisitos. Cada categoria é julgada da seguinte maneira:

* **Benefício**: Este é o benefício em implementar o requisito, para o sistema. 0 representa nenhum benefício, 10 representa necessário para o sistema;
* **Penalidade**: Esta é a penalidade em não implementar o requisito no sistema. 0 representa nenhuma penalidade, e 10 representa a penalidade mais grave possível.
* **Custo**: Esta é uma aproximação generalizada de quantidade de tempo e trabalho para implementação do requisito. Custo 0 representa um custo mínimo para a implementação, enquanto 10 representa um altíssimo investimento de tempo e trabalho em sua implementação.
* **Risco**: Esta é uma representação da possibilidade de surgimento de problemas, um risco que aumenta quanto maior a quantia de trabalho relacionada à proximidade de uma deadline, por exemplo. Um valor de 0 representa uma ausência de risco dado as competências dos desenvolvedores, e 10 representa o maior risco possível relativo à sua implementação na próxima entrega.  

Para comparar, o grupo fez uma média do benefício/penalidade e outra média do custo e risco, julgando a importância da ordem dos requisitos após a priorização.

A tabela 2, a seguir, demonstra a priorização por tabelas realizada pelo grupo.

### Tabela 2 - Priorização dos requisitos mediante técnica de priorização por tabelas.
| Requisito    | Benefício    | Penalidade  | Custo     |  Risco       |
|--------------|--------------|-------------|-----------|--------------|
| 01 - Sistema requer login do usuário para acessar. |  10    |   10          |   3       |     1      | 
| 02 - O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | 10 | 10 | 7 | 2 |
| 03 - O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | 9 | 5 | 4 | 1 | 
| 04 - O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | 4 | 3 | 4 | 1 | 
| 05 - O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | 10 | 10 | 5 | 7 | 
| 06 - O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | 6 | 5 | 7 | 3 | 
| 07 - O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | 9 | 7 | 3 | 3 | 
| 08 - O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| 6 | 5  | 5 | 3 |  
| 09 - O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | 4 | 2 | 8 | 9 | 
| 10 - O sistema disponibiliza as notas do usuário | 9 | 7 | 3 | 2 | 
| 11 - O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | 9 | 7 | 3 | 2 | 
| 12 - O sistema permite que alunos visualizem as turmas em que estão cadastrados | 10 | 10 | 6 | 4 | 
| 13 - O sistema permite que o 'aluno' veja feedback de tarefas| 5 | 0 | 3 | 2 | 
| 14 - O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. | 5 | 3 | 3 | 2 | 
| 15 - O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | 10 | 10 | 7 | 7 | 
| 16 - O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | 3 | 1 | 4 | 3 | 
| 17 - O sistema disponibiliza um fórum para conversa entre alunos e professores | 3 | 1 | 6 | 4 | 
| 18 - O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | 5 | 5 | 1 | 1 | 
| 19 - O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | 7 | 5 | 7 | 8 | 
| 20 - A navegação do aplicativo mobile deve ser simples e intuitiva. | 8 | 9 | 7 | 3 | 
| 21 - O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| 5 | 0 | 3 | 2 | 
| 22 - O sistema deve ter um tempo de resposta admissível. | 9 | 9 | 10 | 9 | 
| 23 - O sistema deve permitir que usuários possam responder formulários. | 7 | 4 | 5 | 4 | 
| 24 - Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | 8 | 10 | 3 | 8 | 
| 25 - O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| 4 | 0 | 6 | 1 | 
| 26 - O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| 3 | 1 | 3 | 1 | 
| 27 - O sistema permite que alunos façam upload de tarefas | 9 | 9 | 7 | 8 | 
| 28 -  O sistema permite a realização de aulas síncronas por chamadas de vídeo | 2 | 0 | 9 | 8 | 
| 29 - O sistema integra outros aplicativos, que são necessários para a disciplina, da mesma família, como pacotes Microsoft para uso de uma turma | 5 | 0 | 8 | 5 | 
| 30 - O sistema permite que usuários conversem por chats privados | 4 | 1 | 5 | 6 | 
| 31 - Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | 4 | 3 | 0 | 1 |  

| # | Referência|
|---|:------|
| 1 | WIEGERS, Karl; BEATTY, Joy. **Software Requirements**. Pearson Education. 3 ed. 2013. 326p. Seção disponível em:(https://aprender3.unb.br/pluginfile.php/2972454/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf)[https://aprender3.unb.br/pluginfile.php/2972454/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf]. Acesso em: 23/11/2024|  

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Página Criada              | Júlia Lopes, Rodrigo de Andrade| João Paulo | <input type="checkbox" onclick="return false;" disabled/> | 24/11/2024 |

