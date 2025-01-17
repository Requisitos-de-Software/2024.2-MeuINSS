# Casos de Uso 

## <p style="margin-bottom: 50px;">Introdução </p> 

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;"> Os casos de uso, também conhecidos dentro da notação UML como diagramas comportamentais, são uma importante ferramenta a medida que ajudam a entender as ações que um sistema/subsistema deve desempenhar em conjunto com agentes externos que geralmente são chamados de atores.
 Essa representação mostra de maneira simplificada como ocorrem as interações e quais são caminhos que os atores percorrem afim de atingir seus objetivos no sistema e são normalmente utilizados para demonstrar os requisitos funcionais deste.[1]
 </p>

## <p style="margin-bottom: 50px;">Metodologia </p> 

 <p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;"> Para ser realizada a montagem do diagrama dos casos de uso para o aplicativo "Meu INSS" optou-se pela utilização de uma das personas que haviam sido criadas anteriormente no projeto para a entrega da elicitação de requisitos, foi escolhida a persona <b><a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/personas/#persona-primaria-1-maria-das-dores-silva-aposentada"> Maria das Dores Silva </a> 
  </b>para se ter uma melhor compreensão das tarefas que o usuário pode realizar dentro do sistema. No que se refere ao diagrama, foram definidos e inseridos os atores que participam assim como outros elementos ilustrativos para demonstrar o funcionamento e fluxo das funcionalidades dentro do "Meu INSS". Para a produção do diagrama dos casos de uso foi utilizada a ferramenta <b><a href="https://www.lucidchart.com/pages/pt">Lucidchart</a> 
  </b> [2], é possível observar a simbologia utilizada e seus significados a partir da tabela 1: </p>


<p><font size="3"><p style="text-align: center"><b>Tabela 1</b>: Simbologia utilizada no Diagrama dos casos de uso</p></font></p>
<table>
<thead>
<tr>
<th>Nome</th>
<th>Função</th>
<th style="text-align: center;">Elemento</th>
</tr>
</thead>
<tbody>
<tr>
<td>Atores do Sistema</td>
<td>Servem como uma representação dos atores que participam de alguma forma do sistema, podem ser desde usuários até componentes e subsistemas.</td>
<td style="text-align: center;"><figure class="usecaseElement" style="width: 50%; display: flex;"><img alt="actor" src="../../imagens/casoDeUso/ator.svg" /></figure></td>
</tr>
<tr>
<td>Elipse (Caso de Uso)</td>
<td>Símbolo usado dentro do diagrama para representar efetivamente os casos de uso. O caso de uso se trata de uma determinada ação e/ou também funcionalidade que o sistema executará de acordo com as decisões dos atores, esse elemento (Elipse) possui em si o nome do caso de uso específico. </td>
<td style="text-align: center;"><figure class="usecaseElement" style="width: 60%; display: flex;"><img alt="elipse" src="../../imagens/casoDeUso/casoDeUso.svg" /></figure></td>
</tr>
<tr>
<td>Retângulo (Sistema)</td>
<td>Usado no diagrama para representar o sistema ou também o bloco em análise. Ele engloba tanto os casos de uso como também os atores relacionados.</td>
<td style="text-align: center;"><figure class="usecaseElement" style="width: 60%; display: flex;"><img alt="retangulo" src="../../imagens/casoDeUso/sistema.svg" /></figure></td>
</tr>
<tr>
<td>Flecha (Relações)</td>
<td>São usadas com a finalidade de mostrar as relações ou interações que existem entre atores e os casos de uso.</td>
<td style="text-align: center;"><figure class="usecaseElement" style="width: 80%; display: flex;"><img alt="flechas" src="../../imagens/casoDeUso/relacionamento.svg" /></figure></td>
</tr>
</tbody>
</table>
<p><font size="4"><p style="text-align: center"><b>Autor: <a href="https://github.com/CristianoMoraiss">Cristiano Morais, 2024</a></b></p></font></p>

## <p style="margin-bottom: 50px;">Diagrama dos Casos de Uso</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;"> A partir da figura 1, é possível observar o diagrama dos casos de uso elaborado pela equipe. </p>

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama de caso de uso do aplicativo Meu INSS</p></font>

<img src="../../imagens/casoDeUso/Diagrama de caso de uso - Meu INSS.svg" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/#equipe">Autores</a>, 2024</p></font>

</div>

Diagrama de caso de uso - Meu INSS


## <p style="margin-bottom: 50px;">Especificação dos Casos de Uso </p>

### UC01. Agendar atendimento em uma agência do INSS

A tabela 2 demonstra a especificação do caso de uso UC01 - Agendar atendimento em uma agência do INSS.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Especificação do caso de uso UC01</p></font>
</div>

| UC01 |  Agendar atendimento em uma agência do INSS |
| --- | --- |
| **Atores** | Usuário trabalhador <br> Usuário aposentado |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01: Possuir uma conexão com a internet <br>  PRE02: Possuir o aplicativo Meu INSS instalado. <br> PRE03. Estar logado no aplicativo Meu INSS.|
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa o aplicativo Meu INSS e seleciona a opção "Agendar horário em uma agência do INSS". <li> O sistema solicita que o usuário informe seu CEP. <li> O usuário informa o CEP. <li> O sistema apresenta uma lista de agências próximas ao endereço informado. <li> O usuário seleciona uma agência desejada. <li> O sistema exibe as datas e horários disponíveis. <li> O usuário escolhe a data e horário e confirma o agendamento. <li> O sistema registra o agendamento. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | FA01: O usuário cancela o agendamento antes de confirmar <ol> <li> O usuário decide não prosseguir e clica na opção "Cancelar". <li> O sistema não registra o agendamento e retorna ao menu inicial. <li> Fim do caso de uso. </ol> FA02: Alterar agência após selecionar uma <ol> <li> O usuário seleciona uma agência e prossegue para escolher uma data e horário. <li> O usuário decide alterar a agência selecionada. <li> O sistema retorna à lista de agências próximas ao CEP informado. <li> O usuário escolhe outra agência e prossegue com o fluxo principal (escolhendo data e horário). <li> Fim do caso de uso. </ol> FA03: O usuário não encontra a agência desejada na lista <ol> <li> O usuário informa seu CEP e o sistema exibe a lista de agências próximas.</li> <li> O usuário não encontra a agência de sua preferência na lista.</li> <li> O sistema oferece ao usuário a opção de tentar com um CEP diferente ou visualizar agências em cidades vizinhas.</li> <li> O usuário opta por tentar um novo CEP ou pesquisar por agências em outra cidade.</li> <li> O sistema exibe a nova lista de agências e o fluxo continua conforme o fluxo básico a partir da escolha da agência.</li> <li> Fim do caso de uso.</li> </ol>|
| **Fluxos de exceção** | FE01: Sem conexão à internet <ol> <li> O sistema detecta que não há conexão com a internet. <li> O sistema exibe uma mensagem de erro informando que é necessário estar conectado à internet para agendar. <li> Fim do caso de uso. </ol> FE02: Sem datas ou horários disponíveis <ol> <li> O sistema informa que não há datas e horários disponíveis para a agência selecionada. <li> O usuário pode tentar outra agência ou encerrar o caso de uso. <li> Fim do caso de uso. </ol> |
| **Pós-condições** |POS01. O agendamento é registrado com sucesso no sistema e uma notificação é enviada ao usuário. |
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC02. Informar CEP para localizar uma agência

Na tabela 3, tem-se a especificação do caso de uso UC02 - Informar CEP para localizar uma agência.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Especificação do caso de uso UC02</p></font>
</div>

| UC02 |  Informar CEP para localizar uma agência |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Alta (acionado em qualquer tentativa de agendamento em uma agência do INSS). |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br> PRE03. Ter iniciado o processo de agendamento em uma agência do INSS no aplicativo Meu INSS.|
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa a funcionalidade "Agendar horário em uma agência do INSS". <li> O sistema solicita que o usuário informe o CEP para localizar as agências próximas. <li> O usuário insere o CEP e confirma. <li> O sistema verifica o CEP informado e retorna as agências disponíveis na região. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | FA01: CEP informado digitado incorretamente <ol> <li> O usuário insere um CEP inválido ou com erro de digitação. <li> O sistema informa que o CEP é inválido e solicita que o usuário insira novamente. <li> O usuário corrige o CEP e confirma. <li> O fluxo retorna ao ponto em que o sistema valida o novo CEP. </ol> FA02: CEP informado não possui agências cadastradas <ol> <li> O usuário insere um CEP válido, mas sem agências cadastradas na região. <li> O sistema exibe uma mensagem indicando que não há agências próximas. <li> O usuário pode inserir outro CEP ou encerrar o caso de uso. <li> Fim do caso de uso. </ol>|
| **Fluxos de exceção** | FE01: Sem conexão à internet <ol> <li> O sistema detecta que não há conexão à internet. <li> O sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente quando estiver conectado. <li> Fim do caso de uso. </ol> FE02: Serviço de busca de CEP indisponível <ol> <li> O sistema não consegue processar a busca devido a problemas técnicos. <li> O sistema informa que a funcionalidade está temporariamente indisponível e sugere tentar novamente mais tarde. <li> Fim do caso de uso. </ol> |
| **Pós-condições** | POS01. O sistema exibe uma lista de agências próximas ao CEP informado (caso existam). |
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC03. Selecionar uma agência próxima

Na tabela 4, está documentada a especificação do caso de uso UC03 - Selecionar uma agência próxima.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Especificação do caso de uso UC03</p></font>
</div>

| UC03 |  Selecionar uma agência próxima |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado <br> INSS |
| **Frequência de uso** | Alta (acionado sempre que o usuário deseja escolher uma agência para o atendimento). |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br> PRE03. Ter iniciado o processo de agendamento em uma agência do INSS no aplicativo Meu INSS. <br> PRE04. Ter informado um CEP válido no informá-lo.|
| **Fluxo básico** | FB01. <ol> <li> O sistema apresenta uma lista de agências próximas ao CEP informado. <li> O usuário visualiza as opções de agências disponíveis na região. <li> O usuário seleciona uma agência para o atendimento. <li> O sistema registra a seleção da agência. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | FA01: O usuário decide alterar o CEP <ol> <li> O usuário percebe que as agências apresentadas não são convenientes. <li> O usuário opta por alterar o CEP e insere um novo endereço. <li> O fluxo retorna ao caso de uso UC02 - Informar CEP para localizar agência. </ol> FA02: Lista de agências excede a tela do dispositivo <ol> <li> O sistema exibe a lista com opções de rolagem caso existam muitas agências disponíveis. <li> O usuário utiliza a rolagem para visualizar todas as opções antes de fazer sua seleção. <li> O fluxo retorna ao ponto onde o usuário seleciona a agência. </ol>|
| **Fluxos de exceção** | FE01: Agência escolhida não possui vagas disponíveis <ol> <li> O sistema informa que a agência selecionada não possui horários disponíveis para agendamento. <li> O usuário pode escolher outra agência ou encerrar o caso de uso. <li> Fim do caso de uso. </ol> FE02: Erro ao carregar a lista de agências <ol> <li> O sistema não consegue carregar a lista de agências devido a uma falha técnica. <li> O sistema exibe uma mensagem de erro e sugere tentar novamente mais tarde. <li> Fim do caso de uso. </ol> |
| **Pós-condições** |POS01. A agência escolhida é registrada no sistema, e o fluxo de agendamento segue para a próxima etapa (escolha de data e horário).|
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC04. Escolher data e horário disponíveis

Na tabela 5, é apresentada a especificação do caso de uso UC04 - Escolher data e horário disponíveis.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Especificação do caso de uso UC04</p></font>
</div>

| UC04 | Escolher data e horário disponíveis |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Alta (acionado toda vez que o usuário precisa agendar um horário em uma agência). |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br> PRE03. Ter selecionado uma agência no processo de agendamento.|
| **Fluxo básico** | FB01. <ol> <li> O sistema apresenta uma lista de datas disponíveis para atendimento na agência selecionada. <li> O usuário escolhe uma data. <li> O sistema exibe os horários disponíveis para a data escolhida. <li> O usuário escolhe um horário. <li> O sistema registra a data e o horário selecionados. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | FA01: O usuário deseja alterar a data escolhida <ol> <li> O usuário decide alterar a data inicialmente selecionada. <li> O usuário retorna à lista de datas e escolhe uma nova data. <li> O fluxo retorna ao ponto em que o sistema exibe os horários disponíveis para a nova data. </ol> FA02: Datas disponíveis não atendem à necessidade do usuário <ol> <li> O usuário verifica as opções de datas e não encontra uma data conveniente. <li> O sistema oferece a possibilidade de retornar à escolha de agência (acionando o caso de uso UC03). <li> O usuário pode selecionar outra agência e recomeçar o fluxo de escolha de data e horário. <li> Fim do caso de uso. </ol>|
| **Fluxos de exceção** | FE01: Nenhuma data disponível para agendamento <ol> <li> O sistema informa que não há nenhuma data disponível para a agência selecionada.</li> <li> O usuário pode optar por retornar à escolha de agência (acionando o caso de uso UC03) ou encerrar o caso de uso.</li> <li> Fim do caso de uso.</li> </ol> FE02: Nenhum horário disponível na data selecionada <ol> <li> O sistema informa que não há horários disponíveis para a data escolhida. <li> O usuário pode selecionar outra data ou encerrar o caso de uso. <li> Fim do caso de uso. </ol> FE03: Erro ao carregar as opções de datas e horários <ol> <li> O sistema não consegue carregar as datas ou horários devido a uma falha técnica. <li> O sistema exibe uma mensagem de erro e sugere tentar novamente mais tarde. <li> Fim do caso de uso. </ol> |
| **Pós-condições** |POS01. A data e o horário escolhidos são registrados no sistema, permitindo a confirmação do agendamento.|
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC05. Confirmar agendamento de horário em uma agência

Na tabela 6, pode-se encontrar a especificação do caso de uso UC05 - Confirmar agendamento de horário em uma agência.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Especificação do caso de uso UC05</p></font>
</div>

| UC05 | Confirmar agendamento de horário em uma agência |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado <br> INSS |
| **Frequência de uso** | Alta (acionado sempre que o agendamento de um horário é concluído).|
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br> PRE03. Ter escolhido uma data e um horário disponíveis no processo de agendamento.|
| **Fluxo básico** | FB01. <ol> <li> O sistema exibe um resumo do agendamento com os dados da agência, data e horário selecionados. </li> <li> O usuário revisa as informações e confirma o agendamento.</li> <li> O sistema registra o agendamento. </li> <li> O sistema exibe a confirmação do agendamento. </li> <li> Fim do caso de uso.</li> </ol> |
| **Fluxos alternativos** | FA01: O usuário decide alterar as informações do agendamento antes de confirmar <ol> <li> O usuário percebe que deseja alterar a data, horário ou agência. </li> <li> O usuário opta por retornar às etapas anteriores (acionando o caso de uso UC03 ou UC04).</li> <li> O fluxo básico é retomado após a nova seleção de dados.</li> </ol>|
| **Fluxos de exceção** | FE01: Falha no registro do agendamento <ol> <li> O sistema tenta registrar o agendamento, mas ocorre uma falha técnica. </li> <li> O sistema informa que o agendamento não foi concluído e orienta o usuário a tentar novamente mais tarde. </li> <li> Fim do caso de uso. </li> </ol> FE02: Nenhuma opção confirmada pelo usuário <ol> <li> O usuário revisa o resumo, mas decide não confirmar o agendamento.</li> <li> O caso de uso é encerrado sem registrar o agendamento. </li> <li> Fim do caso de uso. </li> </ol> |
| **Pós-condições** |POS01. O agendamento é confirmado, e o protocolo de atendimento é gerado e exibido ao usuário.|
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC06. Cancelar ou alterar agendamento 

Na tabela 7, encontra-se a especificação do caso de uso UC06 - Cancelar ou alterar agendamento. 
<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Especificação do caso de uso UC06</p></font>
</div>

| UC06 | Cancelar ou alterar agendamento |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado <br> INSS |
| **Frequência de uso** | Média (acionado quando o usuário precisa modificar ou cancelar o agendamento).|
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br> PRE03. Ter realizado um agendamento previamente (em qualquer etapa anterior).|
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa a funcionalidade de agendamentos no aplicativo. </li> <li> O sistema exibe os agendamentos ativos do usuário. </li> <li> O usuário escolhe um agendamento para cancelar ou alterar. </li> <li> O sistema exibe as opções de cancelar ou alterar o agendamento (incluindo datas, horários e agência). </li> <li> O usuário escolhe a opção desejada: <ul> <li> Para cancelar, o sistema solicita a confirmação do cancelamento. </li> <li> Para alterar, o sistema leva o usuário de volta para a tela de escolha de data e horário (UC04). </li> </ul> </li> <li> O sistema processa a ação escolhida e confirma a operação. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos alternativos** | FA01: O usuário deseja apenas consultar os agendamentos sem alterar ou cancelar <ol> <li> O usuário acessa os agendamentos e decide não realizar nenhuma alteração ou cancelamento. </li> <li> O sistema exibe os detalhes do agendamento sem permitir alterações. </li> <li> O usuário pode sair da tela de agendamento sem confirmar nenhuma ação. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos de exceção** | FE01: Erro ao tentar cancelar o agendamento <ol> <li> O sistema não consegue processar o cancelamento devido a uma falha técnica. </li> <li> O sistema informa que houve um erro e sugere que o usuário tente novamente mais tarde. </li> <li> Fim do caso de uso. </li> </ol> FE02: Erro ao tentar alterar o agendamento <ol> <li> O sistema não consegue processar a alteração do agendamento devido a uma falha técnica. </li> <li> O sistema informa que houve um erro e sugere que o usuário tente novamente mais tarde. </li> <li> Fim do caso de uso. </li> </ol> |
| **Pós-condições** |POS01. O agendamento é alterado ou cancelado conforme a escolha do usuário. Caso alterado, o sistema registra as novas informações. Caso cancelado, o agendamento é removido do sistema.|
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC07. Notificar indisponibilidade de vagas

Na tabela 8, encontra-se a especificação do caso de uso UC07 - Notificar indisponibilidade de vagas. 
<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8:</b> Especificação do caso de uso UC07</p></font>
</div>

| UC07 | Notificar indisponibilidade de vagas |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado <br> INSS|
| **Frequência de uso** | Alta (acionado quando o sistema identifica que não há vagas disponíveis para o agendamento).|
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br> PRE03. Ter iniciado o processo de agendamento.|
| **Fluxo básico** | FB01. <ol> <li> O usuário inicia o processo de agendamento e escolhe uma agência, data e horário. </li> <li> O sistema verifica a disponibilidade de vagas na agência e para o horário escolhido. </li> <li> O sistema detecta que não há vagas disponíveis. </li> <li> O sistema notifica o usuário informando que não há vagas disponíveis para o horário ou agência selecionada. </li> <li> O usuário é convidado a selecionar outra agência, data ou horário. </li> <li> Fim do caso de uso. </li> </ol>|
| **Fluxos alternativos** | FA01: O usuário escolhe alterar a agência <ol> <li> O usuário decide mudar a agência escolhida após a notificação de indisponibilidade. </li> <li> O sistema exibe as agências disponíveis, e o fluxo retorna ao UC03 para seleção de nova agência. </li> </ol> FA02: O usuário escolhe outra data ou horário <ol> <li> O usuário decide selecionar uma nova data ou horário após ser notificado sobre a indisponibilidade.</li> <li> O fluxo retorna ao UC04, onde o usuário pode escolher uma nova data e horário disponíveis. </li> </ol> |
| **Fluxos de exceção** | FE01: Falha na notificação ao usuário <ol> <li> O sistema detecta a indisponibilidade de vagas, mas não consegue notificar o usuário devido a uma falha técnica.</li> <li> O sistema informa que houve uma falha e sugere que o usuário tente novamente mais tarde. </li> <li> Fim do caso de uso. </li> </ol> FE02: Sistema falha ao verificar a disponibilidade de vagas <ol> <li> O sistema tenta verificar a disponibilidade de vagas, mas ocorre uma falha na comunicação de informações.</li> <li> O sistema exibe uma mensagem de erro e sugere que o usuário tente novamente mais tarde. </li> <li> Fim do caso de uso. </li> </ol> |
| **Pós-condições** |POS01. O usuário é notificado da indisponibilidade de vagas e, caso deseje, pode tentar selecionar outra opção de agendamento.|
| **Data da criação** | 06/12/2024 |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

### UC08. Consultar Benefícios

Na tabela 9, encontra-se a especificação do caso de uso UC08 - Consultar Benefícios. 

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 9:</b> Especificação do caso de uso UC08</p></font>
</div>

| UC08 | Consultar Benefícios |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Alta |
| **Pré-condições** | PRE01. Possuir uma conexão com a internet. <br> PRE02. Possuir o aplicativo Meu INSS instalado. <br> PRE03. Estar logado no aplicativo Meu INSS. |
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa o aplicativo Meu INSS e seleciona a opção "Consultar Benefícios". </li> <li> O sistema exibe uma lista dos benefícios vinculados ao CPF do usuário. </li> <li> O usuário seleciona um benefício desejado para mais detalhes. </li> <li> O sistema apresenta as informações detalhadas do benefício, incluindo: <ul><li>Nome do benefício</li><li>Status atual (ativo, inativo, pendente)</li><li>Valor mensal</li><li>Próxima data de pagamento</li><li>Histórico de pagamentos recentes</li></ul></li> <li> O usuário encerra a consulta ou retorna ao menu principal. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos alternativos** | FA01: O usuário não possui benefícios cadastrados <ol> <li> O usuário acessa a opção "Consultar Benefícios". </li> <li> O sistema exibe uma mensagem informando que não há benefícios vinculados ao CPF do usuário. </li> <li> O usuário retorna ao menu principal. </li> <li> Fim do caso de uso. </li> </ol> FA02: O usuário deseja buscar por outro benefício <ol> <li> Após visualizar os detalhes de um benefício, o usuário retorna à lista de benefícios. </li> <li> O usuário seleciona outro benefício para consulta. </li> <li> O sistema exibe os detalhes do novo benefício. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos de exceção** | FE01: Sem conexão à internet <ol> <li> O sistema detecta que não há conexão com a internet. </li> <li> O sistema exibe uma mensagem de erro informando que é necessário estar conectado à internet para consultar os benefícios. </li> <li> Fim do caso de uso. </li> </ol> FE02: Erro ao carregar os benefícios <ol> <li> O sistema encontra problemas ao carregar a lista de benefícios. </li> <li> O sistema exibe uma mensagem informando que não foi possível concluir a operação e sugere tentar novamente mais tarde. </li> <li> Fim do caso de uso. </li> </ol> |
| **Pós-condições** | POS01. O usuário visualiza as informações detalhadas do benefício consultado, se houver. |
| **Data da criação** | 07/12/2024 |
| **Rastreabilidade** | [RF11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) |


<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

### UC09. Exibir impacto da contribuição no benefício

Na tabela 10, encontra-se a especificação do caso de uso UC09 - Exibir impacto da contribuição no benefício. 

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 10:</b> Especificação do caso de uso UC09</p></font>
</div>

| UC09 | Exibir impacto da contribuição no benefício |
| --- | --- |
| **Atores** | Trabalhador |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. Possuir uma conexão com a internet. <br> PRE02. Possuir o aplicativo Meu INSS instalado. <br> PRE03. Estar logado no aplicativo Meu INSS. |
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa o aplicativo Meu INSS e seleciona a opção "Consultar Benefícios". </li> <li> O sistema exibe uma lista dos benefícios vinculados ao CPF do usuário. </li> <li> O usuário seleciona um benefício desejado para mais detalhes. </li> <li> O sistema apresenta as informações detalhadas do benefício. </li> <li> O usuário seleciona a opção "Exibir impacto da contribuição no benefício". </li> <li> O sistema solicita ao usuário que informe o valor da contribuição. </li> <li> O usuário insere o valor da contribuição desejada. </li> <li> O sistema calcula o impacto da contribuição no benefício futuro, considerando o histórico contributivo do usuário e a legislação vigente. </li> <li> O sistema exibe os resultados, incluindo: <ul><li>Benefício estimado com base na contribuição informada.</li><li>Comparativo com o valor do benefício atual, se aplicável.</li><li>Sugestões para otimizar a contribuição.</li></ul></li> <li> O usuário encerra a consulta ou retorna ao menu principal. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos alternativos** | FA01: O usuário deseja simular um novo valor de contribuição <ol> <li> Após visualizar os resultados, o usuário retorna à tela de simulação e informa um novo valor de contribuição. </li> <li> O sistema recalcula o impacto e exibe os novos resultados. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos de exceção** | FE01: Valor de contribuição inválido <ol> <li> O usuário insere um valor inválido (ex.: texto em vez de números ou valor fora do permitido). </li> <li> O sistema exibe uma mensagem de erro e solicita um valor válido. </li> <li> O usuário corrige o valor e continua o fluxo básico. </li> <li> Fim do caso de uso. </li> </ol> FE02: Sem conexão à internet <ol> <li> O sistema detecta que não há conexão com a internet. </li> <li> O sistema exibe uma mensagem de erro informando que é necessário estar conectado à internet para realizar a simulação. </li> <li> Fim do caso de uso. </li> </ol> |
| **Pós-condições** | POS01. O usuário obtém uma estimativa detalhada sobre o impacto da contribuição no benefício futuro. |
| **Data da criação** | 07/12/2024 |
| **Rastreabilidade** | [RF11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

### UC10. Exibir projeção de benefício futuro

Na tabela 11, encontra-se a especificação do caso de uso UC10 - Exibir projeção de benefício futuro. 

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 11:</b> Especificação do caso de uso UC10</p></font>
</div>

| UC10 | Exibir projeção de benefício futuro |
| --- | --- |
| **Atores** | Trabalhador |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. Possuir uma conexão com a internet. <br> PRE02. Possuir o aplicativo Meu INSS instalado. <br> PRE03. Estar logado no aplicativo Meu INSS. <br> PRE04. O usuário deve ter acessado a funcionalidade "Consultar Benefícios" (UC08). |
| **Fluxo básico** | FB01. <ol> <li> Durante a consulta de um benefício (UC08), o usuário seleciona a opção "Exibir projeção de benefício futuro". </li> <li> O sistema solicita ao usuário que informe: <ul><li>Tempo adicional de contribuição desejado (em meses ou anos).</li><li>Valor médio da contribuição futura.</li></ul></li> <li> O usuário insere os valores solicitados. </li> <li> O sistema calcula a projeção do benefício futuro, considerando: <ul><li>O histórico contributivo do usuário.</li><li>As regras da legislação vigente.</li><li>Os valores e tempo adicional informados.</li></ul></li> <li> O sistema exibe os resultados da projeção, incluindo: <ul><li>Valor estimado do benefício com base na projeção.</li><li>Tempo necessário para alcançar o valor projetado (se aplicável).</li><li>Recomendações adicionais para melhorar o benefício futuro.</li></ul></li> <li> O usuário encerra a consulta ou retorna ao menu principal. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos alternativos** | FA01: O usuário deseja ajustar os valores da projeção <ol> <li> Após visualizar os resultados, o usuário retorna à tela de ajuste e informa novos valores para a projeção. </li> <li> O sistema recalcula a projeção e exibe os novos resultados. </li> <li> Fim do caso de uso. </li> </ol> |
| **Fluxos de exceção** | FE01: Valor de entrada inválido <ol> <li> O usuário insere valores inválidos (ex.: texto em vez de números, ou valores fora do permitido). </li> <li> O sistema exibe uma mensagem de erro e solicita valores válidos. </li> <li> O usuário corrige os valores e continua o fluxo básico. </li> <li> Fim do caso de uso. </li> </ol> FE02: Sem conexão à internet <ol> <li> O sistema detecta que não há conexão com a internet. </li> <li> O sistema exibe uma mensagem de erro informando que é necessário estar conectado à internet para realizar a projeção. </li> <li> Fim do caso de uso. </li> </ol> |
| **Pós-condições** | POS01. O usuário obtém uma projeção detalhada sobre o valor futuro do benefício com base nos dados inseridos. |
| **Data da criação** | 07/12/2024 |
| **Rastreabilidade** | [RF12](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >


### UC11. Consultar Pensão

Na tabela 12, encontra-se a especificação do caso de uso UC11 - Consultar Pensão. 
<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 12:</b> Especificação do caso de uso UC11</p></font>
</div>

| UC11 | Consultar Pensão |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br>|
| **Fluxo básico** | FB01. <ol> <li> O usuário inicia o processo de consultar pensões.</li> <li>O sistema retorna o historico de pagamentos de pensões </li> </ol>|
| **Fluxos alternativos** | FA01: O usuário escolhe cancelar a consulta <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li> </ol> |
| **Fluxos de exceção** | FE01: Falha na consulta do historico de pagamento <ol><li>O sistema notifica o erro</li> <li>O sistema da a opção de tentar novamente ou sair</li> </ol> |
| **Pós-condições** |POS01. O usuário consegue consultar a pensão.|
| **Data da criação** | 07/12/2024 |
| **Rastreabilidade** | [RF25](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a>, 2024</p></font>
</div >

### UC12. Consultar historico de pagamentos

Na tabela 13, encontra-se a especificação do caso de uso UC12 - Consultar historico de pagamentos. 
<div align="center">
<font size="3">
<p style="text-align: center">
<b>Tabela 13:</b> 
Especificação do caso de uso UC12
</p>
</font>
</div>

| UC12 | Consultar historico de pagamentos |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Alta(Acionado quando o usuário deseja realizar um pagamento de pensão ou consultar suas pensões) |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br>|
| **Fluxo básico** | FB01. <ol> <li> O usuário inicia o processo de consultar pensões.</li> <li>O sistema consulta o historico de pagamentos de pensões. </li> </ol> FB02. <ol><li>O usuário inicia o processo de realizar pagamento de pensão.</li> <li>O sistema consulta o historico de pagamentos de pensões.</li></ol>|
| **Fluxos alternativos** | FA01: O usuário escolhe cancelar a consulta <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li> </ol> FA02: O usuário escolhe cancelar a realização de pagamento <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li> </ol>|
| **Fluxos de exceção** | FE01: Falha na consulta do historico de pagamento <ol><li>O sistema notifica o erro</li> <li>O sistema da a opção de tentar novamente ou sair</li> </ol> |
| **Pós-condições** |POS01. O sistema recolhe as informações da consulta e executa a tarefa escolhida pelo usuário.|
| **Data da criação** | 07/12/2024 |
| **Rastreabilidade** | [RF25](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a>, 2024</p></font>
</div >


### UC13. Realizar pagamento de pensão

Na tabela 14, encontra-se a especificação do caso de uso UC13 - Realizar pagamento de pensão. 
<div align="center">
<font size="3">
<p style="text-align: center">
<b>Tabela 14:</b> 
Especificação do caso de uso UC13
</p>
</font>
</div>

| UC13 | Realizar pagamento de pensão |
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS. <br>PRE03. Dispor de fundos necessarios para realizar pagamento. |
| **Fluxo básico** | FB01. <ol> <li> O usuário inicia o processo de pagar pensão.</li> <li>O sistema consulta o historico de pagamentos de pensões.</li> <li>O usuário confirma seus dados.</li> <li>O sistema redireciona para o pagamento.</li> <li>O usuário recebe um boleto com o valor a ser pago da pensão.</li></ol>|
| **Fluxos alternativos** | FA01: O usuário escolhe cancelar o pagamento <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li> </ol>|
| **Fluxos de exceção** |FE01: Falha na consulta do historico de pagamento<ol><li>O sistema notifica o erro.</li><li>O sistema da a opção de tentar novamente ou sair.</li></ol> FE02: Falha no pagamento da pensão <ol><li>O sistema notifica o usuário.</li> <li>O usuário é redirecionado ao inicio do processo de pagamento.</li></ol>|
| **Pós-condições** |POS01. O sistema retorna o comprovante de pagamento para o usuário.|
| **Data da criação** | 08/12/2024 |
| **Rastreabilidade** | [RF25](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a>, 2024</p></font>
</div >



### UC14. Acessar Comunidades de ajuda

Na tabela 15, pode ser vista a especificação do caso de uso UC14 - Acessar comunidades. 
<div align="center">
<font size="3">
<p style="text-align: center">
<b>Tabela 15:</b> 
Especificação do caso de uso UC14
</p>
</font>
</div>

| UC14 |Acessar comunidades de ajuda|
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Média (Usado quando o usuário possui alguma dúvida e deseja interagir com outros usuários) |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS.<br>|
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa a aba de comunidades/fóruns </li> <li> Após entrar no espaço ele terá acesso a diversos fóruns onde poderá participar das discussões </li> </ol>
| **Fluxos alternativos** | FA01: O usuário escolhe sair da parte de comunidades <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li>
| **Fluxos de exceção** | FE01: Falha no acesso a aba de comunidade <ol><li>O sistema notifica o erro</li> <li>O sistema da a opção de tentar novamente ou sair</li> </ol> |
| **Pós-condições** |POS01. Permite ao usuário ter acesso aos fóruns presentes no aplicativo|
| **Data da criação** | 08/12/2024 |
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div >



### UC15. Pesquisar fóruns na comunidade

Na tabela 16, pode ser vista a especificação do caso de uso UC15 - Pesquisar fóruns.
<div align="center">
<font size="3">
<p style="text-align: center">
<b>Tabela 16:</b> 
Especificação do caso de uso UC15
</p>
</font>
</div>

| UC15 |Pesquisar fóruns na comunidade|
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Baixa (Usado quando o usuário possui alguma dúvida e deseja interagir com outros usuários) |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS.<br>|
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa a aba de comunidades/fóruns </li> <li> Após acessar ele pode, através de filtros, procurar fóruns relacionados aos assuntos que sejam interessantes para ele </li> </ol>
| **Fluxos alternativos** | FA01: O usuário escolhe sair da parte de comunidades <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li>
| **Fluxos de exceção** | FE01: Falha no acesso a aba de comunidade <ol><li>O sistema notifica o erro</li> <li>O sistema da a opção de tentar novamente ou sair</li> </ol> |
| **Pós-condições** |POS01. Permite ao usuário realizar buscas precisas sobre os assuntos que sejam do seu interesse dentre os criados.|
| **Data da criação** | 08/12/2024 |
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div >

### UC16. Entrar em fóruns e interagir

Na tabela 17, pode ser vista a especificação do caso de uso UC16 - Acessar fóruns e publicar/excluir mensagens.
<div align="center">
<font size="3">
<p style="text-align: center">
<b>Tabela 17:</b> 
Especificação do caso de uso UC16
</p>
</font>
</div>

| UC15 |Pesquisar fóruns na comunidade|
| --- | --- |
| **Atores** | Trabalhador <br> Aposentado |
| **Frequência de uso** | Baixa (Usado quando o usuário possui alguma dúvida e deseja interagir com outros usuários) |
| **Pré-condições** | PRE01. Dispor de conexão à internet. <br> PRE02. Estar logado no aplicativo Meu INSS.<br>|
| **Fluxo básico** | FB01. <ol> <li> O usuário acessa a aba de comunidades/fóruns </li> <li> Após acessar ele pode, através de filtros, procurar fóruns relacionados aos assuntos que sejam interessantes para ele assim como criar um.</li> <li> Após ele entrar ou criar fóruns ele pode publicar as informações que desejar.</li>  </ol>
| **Fluxos alternativos** | FA01: O usuário escolhe sair da parte de comunidades <ol> <li>O sistema retorna para a pagina inicial do aplicativo.</li>
| **Fluxos de exceção** | FE01: Falha no acesso a aba de comunidade <ol><li>O sistema notifica o erro</li> <li>O sistema da a opção de tentar novamente ou sair</li> </ol> |
| **Pós-condições** |POS01. Permite ao usuário efetivamente interagir com a comunidade.|
| **Data da criação** | 08/12/2024 |
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div >



## <p style="margin-bottom: 50px;">Referências bibliográficas</p>

> [1] SERRANO, Milene; SERRANO, Maurício. Elicitação, Modelagem e Análise - Aula 13. s.d. Slide 8 de 40. Disponível em: <a>https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf</a>. Acesso em: 05 Dez. 2024. </br>

> [2] Lucid Software Português. Tutorial de Caso de Uso UML [Recurso eletrônico: vídeo], 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 05 Dez. 2024.


## <p style="margin-bottom: 50px;">Histórico de Versões</p> 


| Versão | Data       | Descrição                   | Autor                                                 | Revisor                                               |
| :----: | ---------- | --------------------------- | ----------------------------------------------------- | ----------------------------------------------------- |
|  1.0   | 05/12/2024 | Criação do documento        |     [Cristiano Moraes](http://github.com/CristianoMoraiss)   |                                    [Júlia Fortunato](http://github.com/julia-fortunato)                   |
|  1.1   | 06/12/2024 | Adição dos UC01 até UC07       |     [Júlia Fortunato](http://github.com/julia-fortunato) |  [Ana Catarina Santos](http://github.com/an4catarina)                                  |
|  1.2   | 06/12/2024 | Adição dos UC08 até UC10       |     [Ana Catarina Santos](http://github.com/an4catarina) |                [Júlia Fortunato](http://github.com/julia-fortunato)                    |
|  1.3   | 08/12/2024 | Adição dos UC15 até UC17       |     [Cristiano Morais](http://github.com/CristianoMoraiss) | [Júlia Fortunato](http://github.com/julia-fortunato)
|  1.4   | 08/12/2024 | Adição dos UC11 até UC14       |     [Mauricio Ferreira](http://github.com/mauricio-araujoo) |                 [Júlia Fortunato](http://github.com/julia-fortunato)                   |
