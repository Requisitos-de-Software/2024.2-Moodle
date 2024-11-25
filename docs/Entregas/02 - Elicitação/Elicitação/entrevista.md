# Entrevista

## Introdução - O que é a entrevista?

Um dos métodos escolhidos para a elicitação de requisitos foi a técnica de entrevista. Essa técnica, segundo Barbosa [Barbosa, et. al (2021)](https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf), consiste em 'uma conversa guiada por um roteiro de perguntas ou tópicos, na qual um entrevistador busca obter informação de um entrevistado'. O tipo de perguntas feitas em nossa entrevista foram **perguntas abertas**, que segundo a literatura têm uma natureza exploratória. Ademais, as perguntas abertas são usualmente utilizadas quando o entrevstador possui um baixo entendimento da situação e quando visam obter opiniões do entrevistado cerca do assunto, tanto para a elicitação de requisitos, quanto para mudanças em design. 


## Planejamento e Metodologia

A partir da reunião geral do dia 15/11/2024, foram planejadas as atividades referente à entrevista e o tipo de entrevista que seria
feito.

O tipo de entrevista escolhido foi **entrevista estruturada**, por sua natureza concisa e a obtenção de respostas objetivas, das quais
pode-se minimizar a ambiguidade na hora de elicitar requisitos.

Foi desenvolvida um tipo de entrevista com objetivo de ser respondida pelos três 
[perfis de usuário](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Elicita%C3%A7%C3%A3o/Perfil%20dos%20Usuarios/) do projeto: aluno, monitor e professor. Ao ter o mesmo conjunto de perguntas respondido por usuários diferentes, pode-se perceber diferentes prioridades ou até atividades realizadas, possibilitando a elicitação de diferentes requisitos.

Sobre as perguntas realizadas na entrevista, foram desenvolvidas perguntas pelos autores e foram reutilizadas perguntas realizadas por um grupo de 2022 da Engenharia de Requisitos, [Lichess](https://requisitos-de-software.github.io/2022.2-Lichess/). O principal objetivo durante a escolha das perguntas foi entender o aplicativo Moodle por meio das respostas dos entrevistados, podendo elicitar sem dúvida requisitos funcionais, não-funcionais e não implementados.

</br>

| Perguntas                  |
|----------------------------|
| Quantas vezes na semana você costuma utilizar o aplicativo? |
| Para que você utiliza o aplicativo? |
| Do que você mais gosta no aplicativo? |
| Onde você costuma usar esse aplicativo? |
| Que funcionalidade você mais utiliza no app? |
| Você costuma encontrar alguma dificuldade ao utilizar o aplicativo? |
| Existe algo que não goste a respeito do aplicativo? |
| O que poderia melhorar no aplicativo? |
| Você sente falta de alguma funcionalidade no app? | 
| Qual o benefício do aprender? |
/// caption | <
Tabela 1 — Perguntas realizadas na entrevista
///
/// caption
Fonte: Autores
///

</br>

Por fim, foi escrito um **termo de consentimento** desenvolvido com base no modelo apresentado por [Barbosa, et. al (2021)](https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf), apresentado na figura 1, a seguir. 

![Termo de Consetimento desenvolvido](../../../img/termo_consent.png) 
 **Figura 1**: Termo de consentimento do planejamento. **Fonte**: Autores. 

 </br>

Durante o encontro do dia 16/11, foram planejadas as datas principais das atividades na entrevista, descritas na tabela 2, a seguir:

| Dia     | Atividade                  | Participantes           | 
|---------|----------------------------|-------------------------|
| 16/11   | Planejamento de perguntas e dos entrevistados                   | Rodrigo Orlandi, João Paulo | 
| 19/11   | Dia da entrevista presencial com aluno - 14h30  | Rodrigo Orlandi, João Paulo     | 
| 19/11 - 20/11   | Estudo da entrevista e elaboração de requisitos | Rodrigo Orlandi, João Paulo   |  
| 20/11   | Elaboração do artefato de entrevista  | Rodrigo Orlandi, João Paulo     | 
| 22/11   | Dia da entrevista presencial com monitor - 11h30 | Rodrigo Orlandi, João Paulo     | 
/// caption | <
Tabela 2 — Cronograma planejado das atividades referentes à entrevista
///
/// caption
Fonte: Autores
///

## Execução 

A entrevista planejada para o dia 19/11 não ocorreu pelo participante com quem o grupo estava comunicando ter faltado. Foi então remarcada uma entrevista com urgência para o dia 21/11. 

Por consequência, foi entrevistado um membro de outro grupo da disciplina de Requisitos de Software, o que pode causar opiniões influenciadas na hora da entrevista. O grupo do Moodle considera que ainda assim, valeu à pena a realização da entrevista pela urgência, mas reconhece o problema com entrevistar um membro de outro grupo.

</br>

### Entrevista 1 (Aluno) - 21/11/2024, 10:30 - 11:00

<iframe width="500" height="285" src="https://www.youtube.com/embed/PvHUFPDSKIs" title="Grupo 02 - Moodle - Entrevista com usuário do aplicativo - Requisitos 2024/2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Entrevista 2 (Monitor) - 22/11/2024, 11:30 - 12:00

<iframe width="500" height="285" src="https://www.youtube.com/embed/92kF1vy1b30" title="Grupo 02 - Moodle - Entrevista com usuário Monitora do aplicativo - Requisitos 2024/2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</br>

## Requisitos Elicitados

Após as entrevistas, foi realizado seu estudo visando a elicitação de requisitos funcionais e não-funcionais, implementados e não implementados. Os requisitos de ambas foram organizados e compilados nas tabela 3, 4 e 5, a seguir. A tabela 5 representa requisitos indiretos que foram elicitados pelos requisitos elicitados da entrevista.

| Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  |
|---------|----------------------------|-------------------------|---------------------|
| 01   |  Requisito Funcional          |  Sistema requer login do usuário para acessar | SIM | 
| 02   |  Requisito Funcional          |  O sistema deve permitir que o Usuário 'Aluno' possa vizualizar o material disponibilizado pelo Usuário 'Professor'. | SIM |
| 03   |  Requisito Funcional          |  O sistema deve permitir que o Usuário 'Aluno' possa baixar arquivos. | SIM |  
| 04   |  Requisito Funcional          |  O conteúdo deve poder ser organizado pelo usuário 'Professor' em tópicos e índices de tópicos. |  SIM |
| 05   |  Requisito Funcional          |  O sistema deve possuir uma funcionalidade calendário, permitindo que o usuário 'Aluno' possa vizualizar atividades próximas. | SIM |
| 06   |  Requisito Não Funcional      |  A navegação do aplicativo mobile deve ser simples e intuitiva. | NÃO | 
| 07   |  Requisito Funcional          |  O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| NÃO | 
| 08   |  Requisito Funcional          |  O sistema deve avisar o usuário 'Aluno' quando ele tiver alguma atividade próxima.| SIM | 
/// caption | <
Tabela 3 — Requisitos elicitados a partir das entrevistas
///
/// caption
Fonte: Autores
///

| Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  |
|---------|----------------------------|-------------------------|---------------------|
| 09      | Requisito Não Funcional     | O sistema deve ter um tempo de resposta admissível. | NÃO |
| 10      | Requisito Funcional         | O sistema deve permitir que o usuário 'Monitor' possa acompanhar o conteúdo da mesma forma que o usuário 'Aluno' para poder ajudá-los no conteúdo. | SIM |
| 11      | Requisito Funcional         | O sistema deve permitir que usuários possam responder formulários. | SIM |
| 12      | Requisito Não Funcional     | Os arquivos enviados ao sistema devem possuir um limite máximo de tamanho. | SIM |
| 13      | Requisito Não Funcional     | O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| NÃO |
/// caption | <
Tabela 4 — Requisitos elicitados a partir da entrevista com o usuário 'Monitor'
///
/// caption
Fonte: Autores
///

| Número  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  |
|---------|----------------------------|-------------------------|---------------------|
| 14      | Requisito Funcional        | O sistema deve permitir que o usuário ‘Professor’ possa enviar conteúdos, que ficarão disponíveis ao tipo de usuário ‘Aluno’ e 'Monitor'. | SIM |
| 15      | Requisito Funcional        | O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| NÃO |
| 16      | Requisito Funcional        | O sistema deve possuir usuário do tipo 'Aluno', 'Professor' e 'Monitor'. | SIM |
| 17      | Requisito Funcional        | O sistema deve notificar o aluno de entregas se aproximando da deadline por meio do Calendário ou Painel/Dashboard. | SIM |
| 18      | Requisito Funcional        | O sistema deve permitir que os usuários 'Professor’ e 'Monitor’ possam corrigir atividades enviadas pelo usuário ‘Aluno'. | NÃO* |
| 19      | Requisito Funcional        | O usuário ‘Aluno’ deve poder consultar as notas das atividades já corrigidas. | SIM |
| 20      | Requisito Funcional        | O usuário 'Professor’ deve ser capaz de elegir um ou mais usuário(s) 'Monitor’ para a sua matéria. | SIM |
| 21      | Requisito Funcional        | O sistema deve permitir que ‘Alunos’ possam filtrar as suas matérias cursadas. | SIM |
/// caption | <
Tabela 5 — Requisitos indiretos elicitados a partir das entrevistas com os usuários
///
/// caption
Fonte: Autores
///

* Observação: O requisito 18 é atualmente aplicável apenas para o tipo de usuário 'Professor', e não 'Monitor'.

## Referência

[1] BARBOSA, S. et al. **Interação Humano-Computador e Experiência do Usuário**. [s.l.] Autopublicação - Leanpub, 2021. Capítulo 7, Página 142. Seção disponível em: [https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf](https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf). Acesso em: 21/11/2024. 

[2] MACHADO, Maurício, et. al. **Lichess (Wiki online de Requisitos de Software)**. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/](https://requisitos-de-software.github.io/2022.2-Lichess/). Acesso em: 21/11/2024.  

## Histórico

| Versão | Descrição                  | Autor                   | Revisor                  | Revisado | Data       |
|--------|----------------------------|-------------------------|--------------------------|-------|-----|
| v1.0   | Adição dos requisitos indiretos elicitados a partir da entrevista com o usuário 'Aluno' | João Paulo | Rodrigo Orlandi |<input type="checkbox" onclick="return false;" disabled/>| 22/11/2024 |
| v1.1   | Adição dos requisitos elicitados a partir da entrevista com o usuário 'Monitor' | João Paulo | Rodrigo Orlandi |<input type="checkbox" onclick="return false;" disabled/>| 23/11/2024 |