# Priorização por Tabelas

Em uma aplicação da técnica de valor custo e risco, de acordo com [Wiegers et. al (2013)](https://aprender3.unb.br/pluginfile.php/2972454/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf), na página 326 , a equipe de requisitos pode medir os requisitos elicitados de acordo com o benefício, custo, risco e penalidade, estruturados na tabela 1, a seguir. Isso ajuda a decidir as prioridades relativas dos requisitos para o projeto.  

|Código | Requisito    | Benefício    | Penalidade  | Custo     |  Risco       |
|-------|--------------|--------------|-------------|-----------|--------------|
| RE01  | Sistema requer login do usuário para acessar. |  10    |   10          |   3       |     1      |
/// caption | <
Tabela 1 — Exemplo de medição da priorização por Wiegers
///
/// caption
Fonte: Júlia Lopes, Rodrigo de Andrade
///
 
O grupo decidiu adaptar a priorização dos requisitos em uma escala de 1 a 10, julgando cada um de acordo com sua utilidade geral, pela maior facilidade em julgar os requisitos. Cada categoria é julgada da seguinte maneira:

* **Benefício**: Este é o benefício em implementar o requisito, para o sistema. 0 representa nenhum benefício, 10 representa necessário para o sistema;
* **Penalidade**: Esta é a penalidade em não implementar o requisito no sistema. 0 representa nenhuma penalidade, e 10 representa a penalidade mais grave possível.
* **Custo**: Esta é uma aproximação generalizada de quantidade de tempo e trabalho para implementação do requisito. Custo 0 representa um custo mínimo para a implementação, enquanto 10 representa um altíssimo investimento de tempo e trabalho em sua implementação.
* **Risco**: Esta é uma representação da possibilidade de surgimento de problemas, um risco que aumenta quanto maior a quantia de trabalho relacionada à proximidade de uma deadline, por exemplo. Um valor de 0 representa uma ausência de risco dado as competências dos desenvolvedores, e 10 representa o maior risco possível relativo à sua implementação na próxima entrega.  

Para comparar, o grupo fez uma média do benefício/penalidade e outra média do custo e risco, julgando a importância da ordem dos requisitos após a priorização.

A tabela 2, a seguir, demonstra a priorização por tabelas realizada pelo grupo.

## Gravação da Priorização por Tabelas

https://youtu.be/5gVOp78b3B4

<iframe width="500" height="285" src="https://www.youtube.com/embed/5gVOp78b3B4" title="[2024-2] Requisitos - Grupo 2 - Priorização de Requisitos - Por Tabela" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

|Código | Requisito    | Benefício    | Penalidade  | Custo     |  Risco       |
|-------|--------------|--------------|-------------|-----------|--------------|
| RE01 | Sistema requer login do usuário para acessar. |  10    |   10          |   3       |     1      | 
| RE02 | O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | 10 | 10 | 7 | 2 |
| RE03 | O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | 9 | 5 | 4 | 1 | 
| RE04 | O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | 4 | 3 | 4 | 1 | 
| RE05 | O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | 10 | 10 | 5 | 7 | 
| RE06 | O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | 6 | 5 | 7 | 3 | 
| RE07 | O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | 9 | 7 | 3 | 3 | 
| RE08 | O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| 6 | 5  | 5 | 3 |  
| RE09 | O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | 4 | 2 | 8 | 9 | 
| RE10 | O sistema disponibiliza as notas do usuário | 9 | 7 | 3 | 2 | 
| RE11 | O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | 9 | 7 | 3 | 2 | 
| RE12 | O sistema permite que alunos visualizem as turmas em que estão cadastrados | 10 | 10 | 6 | 4 | 
| RE13 | O sistema permite que o 'aluno' veja feedback de tarefas| 5 | 0 | 3 | 2 | 
| RE14 | O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. | 5 | 3 | 3 | 2 | 
| RE15 | O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | 10 | 10 | 7 | 7 | 
| RE16 | O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | 3 | 1 | 4 | 3 | 
| RE17 | O sistema disponibiliza um fórum para conversa entre alunos e professores | 3 | 1 | 6 | 4 | 
| RE18 | O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | 5 | 5 | 1 | 1 | 
| RE19 | O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | 7 | 5 | 7 | 8 | 
| RE20 | A navegação do aplicativo mobile deve ser simples e intuitiva. | 8 | 9 | 7 | 3 | 
| RE21 | O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| 5 | 0 | 3 | 2 | 
| RE22 | O sistema deve ter um tempo de resposta admissível. | 9 | 9 | 10 | 9 | 
| RE23 | O sistema deve permitir que usuários possam responder formulários. | 7 | 4 | 5 | 4 | 
| RE24 | Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | 8 | 10 | 3 | 8 | 
| RE25 | O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| 4 | 0 | 6 | 1 | 
| RE26 | O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| 3 | 1 | 3 | 1 | 
| RE27 | O sistema permite que alunos façam upload de tarefas | 9 | 9 | 7 | 8 | 
| RE28 |  O sistema permite a realização de aulas síncronas por chamadas de vídeo | 2 | 0 | 9 | 8 | 
| RE29 | O sistema integra outros aplicativos, que são necessários para a disciplina, da mesma família, como pacotes Microsoft para uso de uma turma | 5 | 0 | 8 | 5 | 
| RE30 | O sistema permite que usuários conversem por chats privados | 4 | 1 | 5 | 6 | 
| RE31 | Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | 4 | 3 | 0 | 1 |  
/// caption | <
Tabela 2 — Priorização dos requisitos mediante técnica de priorização por tabelas
///
/// caption
Fonte: Júlia Lopes, Rodrigo de Andrade
///

---

## Referências

| # | Fonte|
|---|:------|
| 1 | WIEGERS, Karl; BEATTY, Joy. **Software Requirements**. Pearson Education. 3 ed. 2013. 326p. Seção disponível em:(https://aprender3.unb.br/pluginfile.php/2972454/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf)[https://aprender3.unb.br/pluginfile.php/2972454/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf]. Acesso em: 23/11/2024|  

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Página Criada              | Júlia Lopes, Rodrigo de Andrade| João Paulo | <input type="checkbox" onclick="return false;" disabled checked/> | 24/11/2024 |
| v1.1   | Alteração do código dos requisitos        | Laís Cecília | João Paulo | <input type="checkbox" onclick="return false;" disabled checked/> | 02/12/2024 |

