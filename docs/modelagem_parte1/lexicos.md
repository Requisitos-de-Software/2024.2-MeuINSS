# Léxicos

## Introdução

Léxicos, no contexto de modelagem de requisitos de software, têm como principal objetivo a identificação de palavras ou frases no meio social da aplicação, por meio de sua definição. Ajudam, principalmente na descrição de requisitos funcionais e não funcionais de forma acurada. 


## Metodologia

Os léxicos do Meu INSS foram identificados a partir dos [requisitos elicitados](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) na etapa anterior do projeto. Como foi solicitado na disciplina, cada integrante do grupo trabalhou com um requisito funcional não implementado e desenvolveu os artefatos para ele. A equipe também adicionou léxicos que achou relevante para o domínio da aplicação estudada.


Além disso, foram construídos léxicos seguindo a seguinte classificação e estrutura utilizada em LAL (Léxico Ampliado de Linguagem) [1]. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Modelo dos léxicos (LAL)</p></font>
</div>


| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Sujeito | Quem é o sujeito | Ações que executa |
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="http://www.nilc.icmc.usp.br/til/til2006/0030.pdf">Contrução do léxico de aplicações</a>, 2006</p></font>
</div>

Os léxicos deveriam possuir os seguintes tópicos/características:

- Nome;
- Classificação: que tipo de símbolo é aquele que está sendo descrito (verbo, objeto, estado);
- Noção: significado do símbolo, denotação;
- Impacto: efeito/uso do símbolo, conotação;
- Sinônimos: termos alternativos para o léxico trabalhado em questão.

## Léxicos

### L01 - Agendar atendimento 

O primeiro léxico formulado pela equipe, presente na Tabela 2, faz o uso dos seguintes requisitos não implementados: o sistema deve permitir que o usuário agende um horário em uma agência do INSS, escolhendo o serviço, horário, data e local diretamente no aplicativo - [OBS03](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/#requisitos-funcionais), [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/).

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Descrição do léxico 01 - Agendar atendimento</p></font>
</div>

| *L01 - Agendar atendimento* | *Descrição* |
|-----------------|-------|
| *Classificação* | Verbo |
| *Noção* | Tarefa realizada pelo usuário <br>Ação de selecionar um horário específico para atendimento presencial em uma unidade do INSS, através do aplicativo Meu INSS | 
| *Impacto* | Permite ao usuário organizar seu atendimento de forma eficiente, ao garantir que o mesmo seja realizado em um horário previamente marcado <br>A sua ausência pode gerar insatisfação, filas excessivas e problemas logísticos nas agências no INSS  |
| *Sinônimo(s)* | Marcar horário, reservar horário |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div>


### L02 - Acessar comunidades

O segundo léxico observado pela equipe, presente na Tabela 3, utiliza os seguintes requisitos funcionais não implementados: o sistema possui comunidades onde os usuários podem interagir afim de se ajudarem e sanarem dúvidas relacionadas ao INSS - [IS04](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/introspeccao/), [RF13](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/).

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Descrição do léxico 02 - Acessar comunidades</p></font>
</div>

| L02 - Acessar comunidades | Descrição |
|-----------------|-------|
| *Classificação* | Verbo |
| *Noção* | Tarefa realizada pelo usuário <br>Realizar a ação de participar de comunidades relacionadas ao INSS| 
| *Impacto* |Traz a possibilidades de uma maior interação entre usuários do INSS, além de ser uma alternativa de suporte com a possibilidade de pesquisa e acesso a fóruns de acordo com seus objetivos.|
| *Sinônimo(s)* | Fórum, comunidade, interação|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div>

### L03 - Contribuição Previdenciária

O terceiro cenário léxico, presente na Tabela 4, utiliza o seguinte requisitos funcionais não implementados: O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício. - [RF11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/). Também os seguintes não implementados: 'O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).' e 'O aplicativo deve mostrar status de solicitações e benefícios em andamento.' - [RF12](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) e [RF21](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Descrição do léxico 03 - Contribuição Previdenciária</p></font>
</div>

| *L3 - Contribuição Previdenciária* | *Descrição*                                                                                                       |
|--------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| *Classificação*                    | Objeto                                                                                                             |
| *Noção*                            | Representa o valor financeiro pago pelo segurado ao INSS, que impacta diretamente no cálculo e concessão dos benefícios previdenciários. |
| *Impacto*                          | A apresentação clara e detalhada das contribuições realizadas ao longo do tempo permite que o usuário entenda sua influência no benefício final. A ausência de uma visão consolidada pode gerar falta de transparência e dificultar o planejamento previdenciário. |
| *Sinônimo(s)*                      | Pagamento previdenciário, aporte ao INSS, contribuição ao benefício                   |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autores:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div>

### L04 - Notificação Pendente

O quarto cenário léxico, presente na Tabela 3, utiliza o seguinte requisito funcional não implementado: O aplicativo deve enviar notificações sobre pendências, prazos e novas regras.- [GLO04](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/), [OBS05](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) e [RF11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Descrição do léxico 04 - Notificação Pendente</p></font>
</div>

| *L04 - Notificação Pendente* | *Descrição*                                                                                      |
|------------------------------|--------------------------------------------------------------------------------------------------|
| *Classificação*              | Estado                                                                                          |
| *Noção*                      | Refere-se a um alerta ou mensagem enviada ao usuário sobre pendências, prazos ou mudanças importantes relacionadas ao seu benefício. |
| *Impacto*                    | Mantém o usuário informado e engajado com suas obrigações ou direitos. Sem isso, ele pode perder prazos ou atualizações importantes. |
| *Sinônimo(s)*                | Alerta não lido, mensagem pendente                                                              |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div>

### L05 - Filtro de Pesquisa

O quinto cenário léxico, presente na Tabela 6, utiliza o seguinte requisito funcional não implementado: O aplicativo deve possuir filtro de pesquisa assertivo. - [RF07](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Descrição do léxico 05 - Filtro de Pesquisa</p></font>
</div>

| *L05 - Filtro de Pesquisa*     | *Descrição*                                                                                                       |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------|
| *Classificação*                | Objeto                                                                                                            |
| *Noção*                        | Ferramenta que permite ao usuário realizar buscas detalhadas e assertivas dentro do aplicativo Meu INSS, facilitando a localização de informações e funcionalidades. |
| *Impacto*                      | A ausência de um filtro de pesquisa eficiente pode resultar em uma experiência ruim para o usuário, dificultando a navegação e aumentando a frustração. |
| *Sinônimo(s)*                  | Pesquisa avançada, Filtro de busca                                                                                |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div>

### L6 - Acessibilidade

O sexto cenário léxico, presente na Tabela 7, utiliza os seguintes requisitos não-funcionais não implementados: 'O  aplicativo deve ser acessível a todos os usuário.' - [ENT15](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/), [OBS10](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) e [RNF07](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), e 'O aplicativo deve seguir normas de acessibilidade, como suporte a leitores de tela, para ser acessível a pessoas com deficiência.' - [GLO12](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/), [OBS10](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Descrição do léxico 6 - Acessibilidade</p></font>
</div>


| *L6 - Acessibilidade*         | *Descrição*                                                                                                         |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| *Classificação*                | Estado                                                                                                               |
| *Noção*                        | Representa a capacidade do aplicativo de ser utilizado por pessoas com diferentes necessidades, como deficiência visual, auditiva ou motora. |
| *Impacto*                      | Garante a inclusão de todos os usuários, independentemente de suas limitações, promovendo equidade no acesso. A falta de acessibilidade pode excluir pessoas, gerando barreiras ao acesso aos serviços do INSS. |
| *Sinônimo(s)*                  | Inclusão digital, suporte a necessidades especiais, acessibilidade universal                                          |


<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div>

### L7 - Intuitividade do aplicativo

O sétimo cenário léxico, presente na Tabela 8, utiliza os seguintes requisitos não-funcionais não implementados: 'O aplicativo deve ser intuitivo no uso.' - [ENC05](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/encenacao/), [ENT13](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/), [OBS13](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) e [RNF01](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados), e 'O aplicativo deve facilitar a execução de tarefas.'- [ENC08](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/encenacao/), [ENT11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/) e [RNF04](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8:</b> Descrição do léxico 7 - Intuitividade do aplicativo</p></font>
</div>


| *L7 - Intuitividade do aplicativo* | *Descrição*                                                                                                               |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| *Classificação*                    | Estado                                                                                                                     |
| *Noção*                            | Refere-se à capacidade do aplicativo de ser facilmente compreendido e utilizado pelo usuário sem necessidade de esforço ou treinamento adicional. |
| *Impacto*                          | Um aplicativo intuitivo melhora a experiência do usuário e reduz a necessidade de suporte técnico. A ausência de intuitividade pode causar frustração, aumentar o tempo gasto para realizar tarefas e reduzir a adesão dos usuários. |
| *Sinônimo(s)*                      | Facilidade de uso, usabilidade, simplicidade, interação fluida                                                              |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div>

### L8 - Usuário

O oitavo cenário léxico, presente na Tabela 9, utiliza os seguintes requisitos funcionais implementados e não implementados: 'O aplicativo emite e permite consulta a extratos e pagamentos.' - [ENC01](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/encenacao/), [ENT03](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/), [IS02](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/introspeccao/), [GLO07](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/) e [RF01](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), 'O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).' - [GLO01](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/). [IS01](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/introspeccao/) e [RF12](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), 'O  aplicativo deve enviar notificações sobre pendências, prazos e novas regras' - [GLO04](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/), [OBS05](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) e [RF16](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), 'O  usuário poderá enviar documentos digitalizados.' - [GLO11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/) e [RF19](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), O usuário poderá solicitar benefícios pelo aplicativo. - [GLO013](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/) e [RF20](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), 'O aplicativo deve permitir alteração de dados cadastrais, como endereço e telefone.' - [GLO15](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/) e [RF22](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), 'O usuário pode visualizar os benefícios com maiores detalhes.' - [OBS07](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) e [RF30](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/), 'O usuário tem acesso a um calendário no aplicativo relacionado as suas atividades' - [OBS08](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) e [RF31](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 9:</b> Descrição do léxico 8 - Usuário</p></font>
</div>

| *L8 - Usuário*                  | *Descrição*                                                                                                       |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| *Classificação*                  | Estado                                                                                                             |
| *Noção*                          | Representa o indivíduo que interage com o aplicativo Meu INSS, podendo ser um segurado, beneficiário, ou qualquer pessoa que precise de serviços previdenciários. Ele está em um estado de interação com o sistema, seja para [consulta](https://requisitos-de-software.github.io/2024.2-MeuINSS/modelagem_parte1/lexicos/#l03-contribuicao-previdenciaria), [solicitação](https://requisitos-de-software.github.io/2024.2-MeuINSS/modelagem_parte1/lexicos/#l01-agendar-atendimento) ou acompanhamento de serviços e benefícios. |
| *Impacto*                        | O estado do "Usuário" afeta diretamente como o sistema deverá responder, oferecendo informações e funcionalidades específicas. Dependendo do estado de interação (consultando, solicitando, aguardando aprovação, etc.), a aplicação se comportará de maneira diferente para fornecer um serviço adequado. A ausência de um controle adequado sobre o estado do usuário pode gerar falhas na experiência e insegurança quanto aos serviços acessados. |
| *Sinônimo(s)*                    | Segurado, beneficiário, cliente, cidadão                                                                            |


<div align="center">
<font size="3"><p style="text-align: center"><b>Autores:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div>


## Referência bibliográfica 

> [1] SAYÃO, M.; DE CARVALHO, G. Construção do léxico de aplicações. 4th Workshop in Information and Human Language Technology (TIL’2006). 2006. Disponível em: <http://www.nilc.icmc.usp.br/til/til2006/0030.pdf>. Acesso em: 03 dez. 2024.


## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. s.d. Slide 13-20 de 35. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 02 dez. 2024.


## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|03/12/2024|Criação do documento e adição dos léxicos agendar|[Júlia Fortunato](https://github.com/julia-fortunato)|[Nicolas Bomfim](https://github.com/nickgehjk)|
|`1.1`|07/12/2024|Adição do léxico de impacto da contribuição previdenciária|[Ana Catarina Santos](https://github.com/an4catarina)|[Nicolas Bomfim](https://github.com/nickgehjk)|
|`1.2`|08/12/2024|Adição do léxico de acesso a comunidades|[Cristiano Morais](https://github.com/CristianoMoraiss)|[Nicolas Bomfim](https://github.com/nickgehjk)|
|`1.3`|08/12/2024|Adição dos léxicos notificação pendente, filtro de pesquisa, acessibilidade e usuário|[Nicolas Bomfim](https://github.com/nickgehjk) e [Ana Catarina Santos](https://github.com/an4catarina)|[Júlia Fortunato](https://github.com/julia-fortunato)|