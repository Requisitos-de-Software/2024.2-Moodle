# Requisitos Não Implementados e Cenários 

## Introdução

Cenários, de acordo com Barbosa et. al, são uma narrativa, textual ou pictórica, concreta, rica em detalhes
contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais [(BARBOSA, 2021)](https://aprender3.unb.br/pluginfile.php/2972437/mod_resource/content/2/ihc-ux-%20Personas.pdf)".

Cenários são principalmente utilizados para ilustrar casos em que requisitos se tornam mais claros, ajudando a elicitação e no entendimento, tornando-os menos abstraros e mais concretos. Necessita-se dos [requisitos elicitados](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Prioriza%C3%A7%C3%A3o/arequisitos_elicitados/), ou pelo menos uma versão inicial, para que cenários possam ser implementados de maneira satisfatória. 

Usar cenários na especificação de requisitos "tem um forte impacto positivo na qualidade de requisitos, nomeadamente ao nível da adequação, completude parcial, habilidade de modificação e habilidade de verificação - desde que os cenários sejam usados de forma adequada" [(WIKIPEDIA, 2008)](https://pt.wikipedia.org/wiki/Cen%C3%A1rio_(software)).

## Metodologia e Execução

Dentro da especificação de requisitos, a utilização de cenários no projeto foi baseada em requisitos não implementados no aplicativo analisado, Moodle. A aproximação justifica-se pelo intuito do projeto de analisar pontos que podem ser implementados ou melhorados no aplicativo, visando apresentar sugestões efetivas sobre sua performance como resultado do esforço contínuo, aplicado ao longo da disciplina de Requisitos de Software. 

A lista de requisitos elicitados não implementados no aplicativo foi definida com base nos [requisitos elicitados do projeto](https://requisitos-de-software.github.io/2024.2-Moodle/Entregas/02%20-%20Elicita%C3%A7%C3%A3o/Prioriza%C3%A7%C3%A3o/arequisitos_elicitados/), e está disponível na tabela 1, a seguir:

 | Código  | Tipo de Requisito          | Descrição do Requisito  |  Foi implementado?  | Origem |
|---------|----------------------------|-------------------------|---------------------|--------|
| RE09    |  Requisito Funcional       |  O sistema permite que alunos visualizem as turmas em que já foram cadastrados (arquivadas) | NÃO | ANA13, ANA19 |
| RE20    |  Requisito Não Funcional   |  A navegação do aplicativo mobile deve ter símbolos grandes e posicionados de maneira a tornar a navegação mais simples, com presença de diversos atalhos. | NÃO | ANA15, ENT06 |
| RE21    |  Requisito Funcional       |  O sistema deve possuir um sistema de busca, dentro das disciplinas, para facilitar e simplificar a navegação dos usuários.| NÃO | ENT07 |
| RE22    |  Requisito Não Funcional   |  O sistema deve ter um tempo de resposta menor ou igual a dois segundos para cada clique. | NÃO | ENT09 |
| RE25    |  Requisito Não Funcional   |  O sistema deve possuir uma auto-compactação de arquivos se recebê-los exceder o tamanho máximo do arquivo.| NÃO | ENT13 |
| RE26    |  Requisito Funcional       |  O sistema deve automaticamente considerar conteúdos dados, atividades corrigidas, notas de prova e de projetos, resumindo-os em uma porcentagem de conclusão da disciplina.| NÃO |ENT15 |
| RE28    |  Requisito Funcional       |  O sistema permite a realização de aulas síncronas por chamas de vídeo | NÃO | ANA17 |
| RE29    |  Requisito Funcional       |  O sistema integra outros aplicativos da mesma família para uso da turma | NÃO | ANA25 |
| RE31    |  Requisito não Funcional          | Encontrar a barra de busca de turmas é facilmente localizável e intuitiva | NÃO | ENC03 |
/// caption | <
Tabela 1 — Tabela com todos os requisitos elicitados não implementados.
///
/// caption
Fonte: Autores
///

Após separar os requisitos não implementados, estes foram divididos entre a equipe para que todos possam passar pelo processo de elaborar cenários, léxicos e um caso de uso referente aos requisitos escolhidos. O resultado da divisão de requisitos não implementados foi realizado e pode ser visto na tabela 2, a seguir:

Laís: RE09
Esther RE26, RE28
Wonz: RE31 
João RE21, RE25, Ata 07 (03/12)
Rodrigo: RE22, RE31

| Membro da Equipe | Requisitos Não Implementados |  
|------------------|------------------------------|
| Laís Cecília     | RE09 |
| Esther Sousa     | RE26, RE28 |
| Júlia Lopes      | RE31 |
| João Paulo       | RE21, RE25 |
| Rodrigo Orlandi  | RE22, RE31 |
/// caption | <
Tabela 2 — Cenário referente ao RE22, que não foi implementado no projeto.
///
/// caption
Fonte: Rodrigo de Andrade
///

Dada a escolha dos requisitos, o processo de desenvolvimento dos itens referentes à entrega três se deu na ordem de desenvolvimento de cenários, léxico e casos de uso, respectivamente. 

Os cenários foram codificados na ordem dos requisitos não implementados. **C01** representa **R09**, com **R09** sendo o primeiro requisito não implementado do projeto.

## Cenários Desenvolvidos

### C04 - Upload Rápido de Tarefa

| Categoria        | Descrição                                                                                  |  
|------------------|--------------------------------------------------------------------------------------------|
| Objetivo         | O usuário ‘Aluno’ tem de fazer upload de uma tarefa em um minuto. |
| Contexto         | - **Local**: Casa do usuário; **Tempo**: Noite, 23:58; **Pré-Condições**: Ter um dispositivo com um aplicativo que utilize o Moodle como base (Aprender3) | 
| Recursos         | - Smartphone; Aplicativo de framework Moodle | 
| Ator             | - Usuário ‘Estudante’ de um aplicativo de framework Moodle  | 
| Episódios        | **1**. O usuário faz login acessa o aplicativo de framework Moodle; **2**. O usuário acessa a disciplina e encontra a entrega da tarefa; **3**. O usuário faz upload da tarefa e clica em enviar tarefa; **4**. A tarefa é considerada enviada com sucesso. | 
| Restrições       | A tarefa será fechada em um minuto</br>; Tempo de espera entre clicar e carregar a página deve ser menor que dois segundos | 
| Exceções     | Smartphone sem conexão à Internet; Smartphone sem bateria. |
/// caption | <
Tabela 3 — Cenário referente ao RE22, que não foi implementado no projeto.
///
/// caption
Fonte: Rodrigo de Andrade
///

## Referências

| # | Fonte|
|---|:------|
| 1 | BARBOSA, S. et al. Interação Humano-Computador e Experiência do Usuário. [s.l.] Autopublicação - Leanpub, 2021. Capítulo 8, Página 172. Seção disponível em: [https://aprender3.unb.br/pluginfile.php/2972437/mod_resource/content/2/ihc-ux-%20Personas.pdf](https://aprender3.unb.br/pluginfile.php/2972437/mod_resource/content/2/ihc-ux-%20Personas.pdf). Acesso em: 07/12/2024|
| 2 | *In*: WIKIPÉDIA: a enciclopédia livre. [São Francisco, CA: Fundação Wikimedia], 2008. Disponível em: [https://pt.wikipedia.org/wiki/Cen%C3%A1rio_(software)](https://pt.wikipedia.org/wiki/Cen%C3%A1rio_(software)) . Acesso em: 07/12/2024 |  

## Histórico
| Versão | Descrição                  | Autor                           | Revisor                  |                 Revisado          | Data       |
|--------|----------------------------|---------------------------------|--------------------------|-----------------------------------|------------|
| v1.0   | Feito upload da página | Rodrigo de Andrade| João Paulo | <input type="checkbox" onclick="return false;" disabled/> | 07/12/2024 |

