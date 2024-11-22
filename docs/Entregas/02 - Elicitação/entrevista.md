# Entrevista

## Introdução - O que é a entrevista?
Um dos métodos escolhidos para a elicitação de requisitos foi a técnica de entrevista. Essa técnica, segundo Barbosa [Barbosa, et. al (2021)](https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf), consiste em 'uma conversa guiada por um roteiro de perguntas ou tópicos, na qual um entrevistador busca obter informação de um entrevistado'. O tipo de perguntas feitas em nossa entrevista foram **perguntas abertas**, que segundo a literatura têm uma natureza exploratória. Ademais, as perguntas abertas são usualmente utilizadas quando o entrevstador possui um baixo entendimento da situação e quando visam obter opiniões do entrevistado cerca do assunto, tanto para a elicitação de requisitos, quanto para mudanças em design. 


## Planejamento e Metodologia

A partir da reunião geral do dia 15/11/2024, foram planejadas as atividades referente à entrevista e o tipo de entrevista que seria
feito.

O tipo de entrevista escolhido foi **entrevista estruturada**, por sua natureza concisa e a obtenção de respostas objetivas, das quais
pode-se minimizar a ambiguidade na hora de elicitar requisitos.

Foi desenvolvida um tipo de entrevista com objetivo de ser respondida pelos três 
[perfis de usuário](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicitação/Perfil%20de%20Usuário) do projeto: aluno, monitor e professor. Ao ter o mesmo conjunto de perguntas respondido por usuários diferentes, pode-se perceber diferentes prioridades ou até atividades realizadas, possibilitando a elicitação de diferentes requisitos.

Sobre as perguntas realizadas na entrevista, foram desenvolvidas perguntas pelos autores e foram reutilizadas perguntas realizadas por um grupo de 2022 da Engenharia de Requisitos, [Lichess](https://requisitos-de-software.github.io/2022.2-Lichess/). O principal objetivo durante a escolha das perguntas foi entender o aplicativo Moodle por meio das respostas dos entrevistados, podendo elicitar sem dúvida requisitos funcionais, não-funcionais e não implementados.

</br>

### Tabela 1 - Perguntas realizadas na entrevista
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

</br>

Por fim, foi escrito um **termo de consentimento** desenvolvido com base no modelo apresentado por [Barbosa, et. al (2021)](https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf), apresentado na figura 1, a seguir. 

![Termo de Consetimento desenvolvido](../../img/termo_consent.png) 
 **Figura 1**: Termo de consentimento do planejamento. **Fonte**: Autores. 

 </br>

Durante o encontro do dia 16/11, foram planejadas as datas principais das atividades na entrevista, descritas na tabela 2, a seguir:

### Tabela 2 - Cronograma planejado das atividades referentes à entrevista.
| Dia     | Atividade                  | Participantes           | 
|---------|----------------------------|-------------------------|
| 16/11   | Planejamento de perguntas e dos entrevistados                   | Rodrigo Orlandi, João Paulo | 
| 19/11   | Dia da entrevista presencial com aluno - 14h30  | Rodrigo Orlandi, João Paulo     | 
| 19/11 - 20/11   | Estudo da entrevista e elaboração de requisitos | Rodrigo Orlandi, João Paulo   |  
| 20/11   | Elaboração do artefato de entrevista  | Rodrigo Orlandi, João Paulo     | 
| 22/11   | Dia da entrevista presencial com monitor - 11h30 | Rodrigo Orlandi, João Paulo     | 

## Execução 

A entrevista planejada para o dia 19/11 não ocorreu pelo participante com quem o grupo estava comunicando ter faltado. Foi então remarcada uma entrevista com urgência para o dia 21/11. 

Por consequência, foi entrevistado um membro de outro grupo da disciplina de Requisitos de Software, o que pode causar opiniões influenciadas na hora da entrevista. O grupo do Moodle considera que ainda assim, valeu à pena a realização da entrevista pela urgência, mas reconhece o problema com entrevistar um membro de outro grupo.

</br>

### Entrevista 1 - 21/11/2024

<iframe width="500" height="285" src="https://www.youtube.com/embed/PvHUFPDSKIs" title="Grupo 02 - Moodle - Entrevista com usuário do aplicativo - Requisitos 2024/2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Entrevista 2 - 22/11/2024

[INSERIR VÍDEO]

</br>

## Requisitos Elicitados

Após as entrevistas, foi realizado seu estudo visando a elicitação de requisitos funcionais e não-funcionais, implementados e não implementados. Os requisitos de ambas foram organizados e compilados na tabela 3, a seguir.

### Tabela 3 - Requisitos elicitados a partir das entrevistas.
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



## Referência

[1]

[2] BARBOSA, S. et al. **Interação Humano-Computador e Experiência do Usuário**. [s.l.] Autopublicação - Leanpub, 2021. Capítulo 7, Página 142. Seção disponível em: [https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf](https://aprender3.unb.br/pluginfile.php/2972450/mod_resource/content/4/ihc-ux%20cap%207.pdf). Acesso em: 21/11/2024. 

[3] MACHADO, Maurício, et. al. **Lichess (Wiki online de Requisitos de Software)**. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/](https://requisitos-de-software.github.io/2022.2-Lichess/). Acesso em: 21/11/2024.  

## Histórico

| Versão | Descrição                  | Autor                   | Revisor                  | Data       |
|--------|----------------------------|-------------------------|--------------------------|------------|
| v1.0   | Criação do Artefato        | Rodrigo Orlandi, João Paulo      |  Laís Cecília   | 21/11/2024 |
| v1.0   | Adição dos requisitos elicitados a partir da entrevista       | João Paulo | Rodrigo Orlandi | 22/11/2024 |
