# Histórias de Usuário

## Introdução

As histórias de usuário são uma técnica essencial nas metodologias de desenvolvimento ágil, sendo fundamentais para a definição de requisitos de maneira clara e objetiva. Elas consistem em descrições curtas e diretas de funcionalidades desejadas, sempre considerando a perspectiva do cliente. Para garantir a eficácia de sua implementação, cada história de usuário deve ser acompanhada de critérios de aceitação bem definidos, que permitem avaliar com precisão se a funcionalidade foi desenvolvida com sucesso. Essa abordagem facilita a comunicação entre as partes interessadas e assegura que o produto final atenda às expectativas do cliente.

## Objetivo

O objetivo é verificar por meio das histórais de usuário se cada funcionalidade presente e cada requisito condiz com o esperado.

## Metodologia

Foram utilizados os [requisitos elicitados](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) anteriormente e feito uma história de usuário pra cada um deles com o seguinte padrão:

### USXX - "Nome da história".
Na tabela Y, pode ser encontrada a USX - "Nome da história".

<div style="text-align: center">

<p><b>Tabela Y:</b> História de Usuário X</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| "Descrição da história" | "Tema da história" | "Critérios de aceitação" | "Prioridade de implementação" | "Dificuldade de implementação" |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a>"Autor"</a>, 2024</p></font>
</div >

Rastreabilidade: [RFx - "Nome do requisito"]()


## Histórias de Usuário


### US01 - Emissão e consulta a extratos e pagamentos.
Na tabela 1, pode ser encontrada a US01 - O aplicativo emite e permite consulta a extratos e pagamentos.

<div style="text-align: center">

<p><b>Tabela 1:</b> História de Usuário 1</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo poder realizar a emissão de extratos assim como também ter a permissão para consultar posteriormente esses extratos e  os pagamentos.| Emissão de extratos e consulta de extratos e pagamentos | - O sistema deve permitir que o usuário possa realizar a emissão de extratos . </br> - O sistema deve permitir que o usuário possa consultar o histórico de extratos que tenha realizado anteriormente se for o caso. </br> - Deve também ser possível dentro do aplicativo a consulta de pagamentos realizados. | Alta | Média |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div >

Rastreabilidade: [RF01 - O aplicativo emite e permite consulta a extratos e pagamentos.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US02 - 	Simulação de aposentadoria
Na tabela 2, pode ser encontrada a US02 - O aplicativo permite simular a aposentadoria.

<div style="text-align: center">

<p><b>Tabela 2:</b> História de Usuário 2</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo poder realizar simulações da minha aposentadoria baseado no meu tempo de contribuição e pagamentos já realizados| Realizar simulações de aposentadoria.| - O sistema deve permitir ao usuário fornecer quanto irá pagar de previdência a cada mês para o cálculo do benefício final. </br> - O sistema deve considerar a contribuição previdenciária realizada pelo usuário até o momento da simulação para prever quanto tempo de contribuição com o valor especificado será necessário.  | Média | Média |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div > 

Rastreabilidade: [RF02 - O aplicativo permite simular a aposentadoria.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US03 - 	Solicitação de pedidos
Na tabela 3, pode ser encontrada a US03 - O aplicativo permite solicitar pedidos.

<div style="text-align: center">

<p><b>Tabela 3:</b> História de Usuário 3</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo poder realizar pedidos como por exemplo solicitação de benefícios (aposentadoria, auxilio-doença, pensão por morte, salário-maternidade, seguro desemprego), atualização de dados, agendamento de perícia médica.| Realizar pedidos dentro do aplicativo.| - O sistema deve permitir ao usuário realizar os pedidos relativos ao que se refere os serviços do INSS. </br> - O sistema deve ser capaz de mostrar ao usuário o histórico de pedidos realizados pelo mesmo identificando os detalhes de cada pedido. </br> - Caso o usuário não tenha conseguido solicitar um pedido o sistema deve informá-lo.| Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div > 

Rastreabilidade: [RF03 - O aplicativo permite solicitar pedidos.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US04 - 	Integrção com outros sistemas
Na tabela 4, pode ser encontrada a US04 - O aplicativo deve ser integrado com outros sistemas, como o sistema jurídico.

<div style="text-align: center">

<p><b>Tabela 4:</b> História de Usuário 4</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo que o aplicativo do "Meu INSS" esteja integrado com outros sistemas como, por exemplo, o sistema jurídico.| Integralização com outros sistemas. |- O sistema deve estar integralizado com outros sistemas além do próprio INSS. </br> - O usuário deve ter acesso a interações/informações de outros sistemas dentro do aplicativo do "Meu INSS".| Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div > 

Rastreabilidade: [RF04 - O aplicativo deve ser integrado com outros sistemas, como o sistema jurídico.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US05 - 	Solicitação de auxílio-doença
Na tabela 5, pode ser encontrada a US05 - O aplicativo permite solicitar auxílio doença.

<div style="text-align: center">

<p><b>Tabela 5:</b> História de Usuário 5</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo poder solicitar o auxílio doença através do sistema.| Solicitação de auxílio doença.|- O sistema deve permitir que seja possível solicitar o auxílio doença. </br> - O usuário deve poder acompanhar o seu pedido de auxílio doença no aplicativo.| Alta | Médio|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div > 

Rastreabilidade: [RF05 - O aplicativo permite solicitar auxílio doença.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados) 


### US06 - Verificação da previsão de pagamento

Na tabela 6, pode ser encontrada a US06 - O aplicativo permite verificar previsão de pagamento.

<div style="text-align: center">

<p><b>Tabela 6:</b> História de Usuário 6</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo poder verificar as minhas previsões de pagamento| Previsões de pagamento|- O sistema deve permitir que seja possível realizar verificações de eventuais pagamentos. </br> - O usuário deve poder acompanhar o seu pedido de auxílio doença no aplicativo.| Médio | Baixo|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, 2024</p></font>
</div > 

Rastreabilidade: [RF06 - O aplicativo permite verificar pagamentos](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados) 

### US07 - Realizar pesquisa assertiva
Na tabela 7, pode ser encontrada a US07 - Realizar pesquisa assertiva.

<div style="text-align: center">

<p><b>Tabela 7:</b> História de Usuário 7</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo realizar uma pesquisa assertiva para que eu possa encontrar informações relevantes de forma rápida e eficiente| Filtro de pesquisa assertivo | - O filtro deve permitir a busca por diversos critérios (ex: tipo de serviço, categoria de benefício, etc.); </br> - O filtro deve retornar resultados relevantes baseados na pesquisa realizada; </br>- O filtro deve permitir a combinação de até 5 critérios de pesquisa simultaneamente; </br> - Deve ser possível navegar no filtro e atingir um objetivo de pesquisa em no máximo, 5 cliques.| Alta | Média |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

Rastreabilidade: [RF07 - O aplicativo deve possuir filtro de pesquisa assertivo.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

### US08 - Receber suporte adequado
Na tabela 8, é possível visualizar a US08 - Receber suporte adequado.

<div style="text-align: center">

<p><b>Tabela 8:</b> História de Usuário 8</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo ter acesso a um suporte adequado para que eu possa resolver minhas dúvidas ou problemas de forma eficiente e sem frustrações| Suporte adequado | - O aplicativo deve fornecer acesso fácil a canais de suporte (chat, telefone, e-mail, etc.); </br>- O suporte deve ser acessível a qualquer momento durante o uso do aplicativo; </br> - O suporte deve ser capaz de oferecer respostas claras e precisas, com tempo de resposta de no máximo 250ms; </br> - O aplicativo deve oferecer uma seção de FAQ com as dúvidas mais frequentes.| Média | Média |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

Rastreabilidade: [RF08 - O aplicativo deve possuir suporte adequado.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US09 - Especificar de forma adequada informações de auxílio doença
Na tabela 9, está especificada a US09 - Especificar de forma adequada informações de auxílio doença.

<div style="text-align: center">

<p><b>Tabela 9:</b> História de Usuário 9</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo que o aplicativo seja claro sobre as especificações para auxílios doenças e as modalidades de análise (online ou presencial) para que eu possa entender claramente como solicitar e acompanhar meu auxílio| Especificação para auxílios doenças e modalidades de análise | - O aplicativo deve informar as modalidades de análise disponíveis (online ou presencial), com as vantagens e requisitos de cada uma; </br>- O aplicativo deve direcionar o usuário para o processo de solicitação adequado, com etapas detalhadas; </br> - O usuário deve receber uma explicação sobre os critérios para escolha entre análise online ou presencial, com base no seu caso específico. | Alta | Baixa |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

Rastreabilidade: [RF09 - O aplicativo deve ser claro com relação a especificação para auxílios doenças e as modalidades de análise (online ou presencial).](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US10 - Acessar notícias sobre legislação previdenciária
Na tabela 10, a US10 - Acessar notícias sobre legislação previdenciária pode ser visualizada.

<div style="text-align: center">

<p><b>Tabela 10:</b> História de Usuário 10</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo ser avisado sobre mudanças e notícias relacionadas à legislação previdenciária para que eu possa estar sempre atualizado sobre as regras e direitos que afetam meus benefícios| Aviso sobre mudanças e notícias da legislação previdenciária | - O aplicativo deve fornecer notificações sobre mudanças na legislação previdenciária que possam impactar os benefícios dos usuários; </br>- O usuário deve ser capaz de personalizar o tipo de notificação que deseja receber (por exemplo, mudanças na aposentadoria, auxílio-doença, etc.); </br> - O aplicativo deve ter uma seção dedicada às notícias e atualizações sobre a legislação previdenciária, com acesso fácil e organizado; </br> - As notícias e mudanças devem ser enviadas em tempo hábil, para que os usuários possam agir de acordo com as novas regras, ou seja, no mínimo com uma semana de antecedência. | Baixa | Baixa |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

Rastreabilidade: [RF10 - O aplicativo deve avisar sobre mudanças e notícias sobre legislação previdenciária.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US11 - Acessar impacto de contribuição
Na tabela 11, está especificada a US11 - Acessar impacto de contribuição.

<div style="text-align: center">

<p><b>Tabela 11:</b> História de Usuário 11</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo visualizar o impacto das minhas contribuições no meu benefício para que eu possa entender como elas influenciam no valor ou nas condições do meu benefício| Impacto da contribuição no benefício | - O usuário deve poder visualizar uma projeção de como as contribuições afetam o valor do benefício, levando em consideração o tipo de benefício (aposentadoria, auxílio-doença, etc.); </br>- O aplicativo deve mostrar uma estimativa de futuro impacto das contribuições adicionais no benefício, como o aumento de valor do benefício com mais contribuições; </br> - O impacto das contribuições deve ser exibido de forma fácil de entender, com gráficos ou tabelas simples e intuitivas; </br> - O aplicativo deve fornecer uma explicação sobre como as contribuições são calculadas e como elas afetam os benefícios do usuário. | Média| Média |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

Rastreabilidade: [RF11 - O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US12 - Acessar histórico de contribuição CNIS.
Na tabela 12, está descrita a US12 - Acessar histórico de contribuição CNIS.

<div style="text-align: center">

<p><b>Tabela 12:</b> História de Usuário 12</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo ter acesso ao meu histórico completo de contribuições (CNIS) para que eu possa verificar e acompanhar todas as contribuições realizadas ao longo do tempo| Impacto da contribuição no benefício / Acesso ao histórico de contribuições (CNIS) | - O CNIS deve ser exibido de forma organizada, mostrando as contribuições realizadas por período, valor e tipo de contribuição; </br>- O aplicativo deve permitir ao usuário visualizar detalhes de cada contribuição (data, valor, competência, etc.); </br> - O histórico deve ser acessível a qualquer momento e de forma segura (com autenticação adequada, pedindo a senha do gov.br do usuário); </br> - O usuário deve poder gerar e baixar o histórico de contribuições em formato PDF ou outro formato útil para consultas externas.| Alta| Alta|

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

Rastreabilidade: [RF12 - O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)
 

### US13 - Comunidades de Usuários

Na tabela 13, está descrita a US13 - Comunidades de Usuários.

<div style="text-align: center">

<p><b>Tabela 13:</b> História de Usuário 13</p>

</div>

| **História de Usuário**                                                                                       | **Tema**                   | **Critérios de Aceitação**                                                                                                                                                                                                                                                                                                         | **Prioridade** | **DI** |
|---------------------------------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|--------|
| Eu, como usuário do Meu INSS, desejo acessar comunidades no aplicativo para trocar experiências e informações com outros usuários.                 | Comunidades de usuários    | - O aplicativo deve possuir uma seção específica chamada "Comunidades" acessível a partir do menu principal;<br>- O usuário deve poder criar tópicos de discussão com título e descrição;<br>- O sistema deve permitir interação com outros usuários por meio de comentários;<br>- As interações devem ser moderadas para evitar abusos. | Baixa          | Alta  |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

Rastreabilidade: [RF13 - O aplicativo permite acessar comunidades para os próprios usuários se ajudarem.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

### US14 - Assistente Virtual

Na tabela 14, está descrita a US14 - Assistente Virtual.

<div style="text-align: center">

<p><b>Tabela 14:</b> História de Usuário 14</p>

</div>

| **História de Usuário**                                                                                       | **Tema**                   | **Critérios de Aceitação**                                                                                                                                                                                                                                             | **Prioridade** | **DI** |
|---------------------------------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|--------|
| Eu, como usuário do Meu INSS, desejo utilizar um assistente virtual para simular diferentes cenários previdenciários. |Assistência virtual ao usuário| - O assistente deve estar disponível no menu principal;<br>- O usuário deve poder simular cenários. <br>- Os dados devem ser preenchidos pelo usuário ou recuperados do perfil;<br>- O resultado deve apresentar: requisitos necessários, tempo restante e valores estimados. <br>-O assistente deve suportar perguntas frequentes e explicações simples sobre regras previdenciárias. | Média          | Alta   |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

Rastreabilidade: [RF14 - O aplicativo possui assistente virtual com simulações de diferentes cenários previdenciários.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

### US15 - Agendamento de perícias e atendimentos

Na tabela 15, está descrita a US15 - Agendamento de perícias e atendimentos.

<div style="text-align: center">

<p><b>Tabela 15:</b> História de Usuário 15</p>

</div>

| **História de Usuário**                                                                                       | **Tema**                             | **Critérios de Aceitação**                                                                                                                                                                                                                                     | **Prioridade** | **DI**  |
|---------------------------------------------------------------------------------------------------------------|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|---------|
| Eu, como usuário do Meu INSS, desejo agendar perícias e atendimentos diretamente pelo aplicativo, para facilitar o acesso aos serviços e reduzir a necessidade de deslocamentos até as agências.                                                 | Agendamento de perícias e atendimentos | - O aplicativo deve listar tipos de agendamento disponíveis;<br>-O sistema deve listar datas e horários disponíveis com base na localidade do usuário;<br>- O sistema deve permitir confirmar, cancelar ou reagendar;<br>- Notificações devem lembrar o usuário 24 horas antes. | Média          | Média   |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

Rastreabilidade: [RF15 - 	O aplicativo deve permitir agendamento de perícias e atendimentos.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

### US16 - Notificações sobre pendências e prazos

Na tabela 16, está descrita a US16 - Notificações sobre pendências e prazos.

<div style="text-align: center">

<p><b>Tabela 16:</b> História de Usuário 16</p>

</div>

| **História de Usuário**                                                                                       | **Tema**                             | **Critérios de Aceitação**                                                                                                                                                                                                                                            | **Prioridade** | **DI**        |
|---------------------------------------------------------------------------------------------------------------|--------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|---------------|
| Eu, como usuário do Meu INSS, desejo receber notificações sobre pendências, prazos e novas regras relevantes para meus benefícios, afim de melhor organizá-los e lembrar-me sempre de coisas importantes relacionadas a previdência social.                | Notificações sobre pendências e prazos | - O aplicativo deve permitir filtrar as notificações recebidas;<br>- As notificações devem ser claras, indicando ação necessária e prazos;<br>-As mensagens devem ser exibidas no aplicativo e enviadas por push, com opção para envio por e-mail;<br>- Deve haver um histórico de notificações acessível;<br>- As notificações devem ser enviadas com pelo menos 7 dias de antecedência quando aplicável. | Alta           | Baixa  |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

Rastreabilidade: [RF16 - 	O aplicativo deve enviar notificações sobre pendências, prazos e novas regras.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

### US17 - Gerenciamento de benefícios

Na tabela 17, está descrita a US17 - Gerenciamento de benefícios.

<div style="text-align: center">

<p><b>Tabela 17:</b> História de Usuário 17</p>

</div>

| **História de Usuário**                                                                                       | **Tema**                      | **Critérios de Aceitação**                                                                                                                                                                                                                                                 | **Prioridade** | **DI**        |
|---------------------------------------------------------------------------------------------------------------|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|---------------|
| Eu, como usuário do Meu INSS, desejo ter a possibilidade de bloquear e desbloquear meus benefícios diretamente pelo aplicativo, para garantir maior segurança e praticidade no gerenciamento dos meus direitos.                  | Gerenciamento de benefícios   | - A funcionalidade deve ser acessível no perfil do usuário;<br>- A funcionalidade de bloqueio/desbloqueio deve estar disponível no perfil do usuário, com acesso seguro por autenticação de usuário;<br>- O sistema deve apresentar um aviso claro sobre as implicações de bloquear ou desbloquear o benefício;<br>- O usuário deve receber uma mensagem de confirmação ao final da ação;<br>- O tempo para a efetivação do bloqueio/desbloqueio deve ser de no máximo 48 horas úteis.                         | Alta           | Baixa  |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

Rastreabilidade: [RF17 - 	O aplicativo deverá permitir bloqueio e desbloqueio de benefícios pelo aplicativo.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

### US18 - Exibição de critérios de carência

Na tabela 18, está descrita a US18 - Exibição de critérios de carência.

<div style="text-align: center">

<p><b>Tabela 18:</b> História de Usuário 18</p>

</div>

| **História de Usuário**                                                                                       | **Tema**                 | **Critérios de Aceitação**                                                                                                                                                                                                                                                         | **Prioridade** | **DI**  |
|---------------------------------------------------------------------------------------------------------------|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|---------|
| Eu, como usuário do Meu INSS, desejo visualizar os critérios de carência de forma clara e compreensível, para entender melhor os requisitos necessários ao acesso aos benefícios.                                          | Exibição de critérios de carência | - Deve haver uma seção específica chamada "Critérios de Carência";<br>- A apresentação deve incluir um resumo visual para facilitar o entendimento do status atual do usuário;<br>- A explicação deve detalhar requisitos específicos e como o usuário se enquadra neles;<br>- Deve incluir links para mais informações e suporte à acessibilidade. | Média           | Média  |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/an4catarina">Ana Catarina Santos</a>, 2024</p></font>
</div >

Rastreabilidade: [RF18 - 	O aplicativo deverá mostrar critérios de carência de forma clara.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US19 - Enviar Documentos Digitalizados
Na tabela 19, está descrita a US19 - Enviar Documentos Digitalizados.

<div style="text-align: center">

<p><b>Tabela 19:</b> História de Usuário 19</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo enviar documentos digitalizados para complementar informações ou solicitar benefícios, a fim de agilizar o processo e evitar a necessidade de envio físico de documentos. | Documentos digitalizados / Solicitação de benefícios | - O usuário poderá selecionar um ou mais arquivos do seu dispositivo (celular, tablet ou computador);</br> - Os formatos de arquivos aceitos serão especificados (ex: PDF, JPG, PNG);</br> - Haverá um limite de tamanho para cada arquivo e para o total de arquivos enviados;</br> - O sistema deverá validar os tipos de arquivos enviados e informar o usuário em caso de erro;</br> - O usuário receberá uma confirmação de envio dos documentos;</br> - Os documentos enviados serão armazenados de forma segura e confidencial. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div >

Rastreabilidade: [RF19 - O usuário poderá enviar documentos digitalizados.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US20 - Solicitar Benefícios
Na tabela 20, está descrita a US20 - Solicitar Benefícios.

<div style="text-align: center">

<p><b>Tabela 20:</b> História de Usuário 20</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo solicitar um benefício previdenciário, a fim de agilizar o processo e acompanhar o status da minha solicitação. | Solicitação de benefícios | - O sistema deve oferecer uma lista completa dos benefícios disponíveis (aposentadoria, pensão, auxílio-doença, etc.);</br> - O usuário deverá selecionar o tipo de benefício desejado;</br> - O sistema deverá apresentar os requisitos e documentos necessários para cada tipo de benefício;</br> - O usuário poderá preencher um formulário online com as informações solicitadas;</br> - O sistema deverá validar as informações inseridas pelo usuário;</br> - O usuário poderá anexar os documentos digitalizados necessários para a solicitação;</br> - O sistema deverá gerar um protocolo de atendimento para acompanhamento da solicitação;</br> - O usuário receberá uma confirmação da solicitação por e-mail ou notificação no aplicativo. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div >

Rastreabilidade: [RF20 - O usuário poderá solicitar benefícios pelo aplicativo.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US21 - Acompanhar Status de Solicitações e Benefícios
Na tabela 21, está descrita a US21 - Acompanhar Status de Solicitações e Benefícios.

<div style="text-align: center">

<p><b>Tabela 21:</b> História de Usuário 21</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo acompanhar o status das minhas solicitações e benefícios em andamento, a fim de ter informações atualizadas sobre o processo. | Acompanhamento de solicitações | - O sistema deve apresentar um painel com todas as solicitações e benefícios em andamento do usuário;</br> - Para cada solicitação, o sistema deve exibir o tipo de benefício, data de solicitação, status atual e a próxima etapa do processo;</br> - O usuário deve poder visualizar os detalhes de cada solicitação, incluindo os documentos enviados e as mensagens trocadas com o INSS;</br> - O sistema deve enviar notificações para o usuário quando houver alguma atualização no status da sua solicitação;</br> - O usuário deve poder imprimir ou salvar um relatório com o histórico da sua solicitação. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div >

Rastreabilidade: [RF21 - O aplicativo deve mostrar status de solicitações e benefícios em andamento.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US22 - Alterar Dados Cadastrais
Na tabela 22, está descrita a US22 - Alterar Dados Cadastrais.

<div style="text-align: center">

<p><b>Tabela 22:</b> História de Usuário 22</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo alterar meus dados cadastrais, como endereço e telefone, a fim de manter minhas informações atualizadas. | Dados cadastrais | - O sistema deve permitir que o usuário acesse e edite seus dados cadastrais pessoais (nome, data de nascimento, etc.);</br> - O sistema deve permitir a alteração de dados de contato (endereço, telefone, e-mail);</br> - O sistema deve validar as informações inseridas pelo usuário para garantir a sua integridade;</br> - O sistema deve solicitar a confirmação da senha do usuário antes de realizar qualquer alteração;</br> - O sistema deve gerar um comprovante da alteração realizada;</br> - O sistema deve permitir a inclusão de um endereço secundário (opcional). | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div >

Rastreabilidade: [RF22 - O aplicativo deve permitir alteração de dados cadastrais, como endereço e telefone.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US23 - Emitir Recibos Digitais
Na tabela 23, está descrita a US23 - Emitir Recibos Digitais.

<div style="text-align: center">

<p><b>Tabela 23:</b> História de Usuário 23</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo emitir recibos digitais das minhas transações, a fim de ter um comprovante eletrônico das minhas operações. | Recibos digitais | - O sistema deve gerar um recibo digital para cada transação realizada pelo usuário (pagamentos, solicitações, etc.);</br> - O recibo digital deve conter informações como data da transação, valor, descrição da transação e dados do usuário;</br> - O usuário deve poder visualizar, baixar e compartilhar o recibo digital;</br> - O recibo digital deve ser gerado em formato PDF ou outro formato padrão;</br> - O sistema deve armazenar os recibos digitais em um histórico acessível pelo usuário;</br> - O usuário deve poder filtrar e buscar recibos digitais por data, tipo de transação ou outros critérios. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div >

Rastreabilidade: [RF23 - O aplicativo deverá mostrar emitir recibos digitais para transações realizadas.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US24 - Consultar Informações do FGTS
Na tabela 24, está descrita a US24 - Consultar Informações do FGTS.

<div style="text-align: center">

<p><b>Tabela 24:</b> História de Usuário 24</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário do aplicativo do INSS, desejo consultar informações sobre o meu FGTS, como saldo e extrato, a fim de ter um controle sobre meus recursos. | Consulta ao FGTS | - O sistema deve permitir que o usuário consulte o saldo atual do seu FGTS;</br> - O sistema deve apresentar um extrato detalhado das movimentações do FGTS, incluindo depósitos, saques e rendimentos;</br> - O sistema deve permitir que o usuário filtre o extrato por períodos;</br> - O sistema deve informar a data de aniversário da conta do FGTS;</br> - O sistema deve indicar se há alguma pendência ou restrição na conta do FGTS;</br> - O sistema deve permitir que o usuário simule um saque do FGTS (opcional). | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2024</p></font>
</div >

Rastreabilidade: [RF24 - O aplicativo deverá integrar informações sobre FGTS para consulta de saldo e movimentações.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US25 - Consulta e pagamento de pensões

Na tabela 25, está descrita a US25 - Consulta e pagamento de pensões.

<div style="text-align: center">

<p><b>Tabela 25:</b> História de Usuário 25</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo fazer consultas e pagamentos por meio do aplicativo do Meu INSS. | Pensões | – O sistema deve permitir consulta do histórico de pagamento de pensões<br>– O sistema deve permitir o pagamento de parcelas pendentes das pensões<br>– O sistema deve possuir maneira de emitir boleto bancário | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF25 - O aplicativo deve permitir consulta e pagamento de pensões.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US26 - Usar autenticação pelo Gov.br para login

Na tabela 26, está descrita a US26 - Usar autenticação pelo Gov.br para login.

<div style="text-align: center">

<p><b>Tabela 26:</b> História de Usuário 26</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo realizar login no aplicativo do Meu INSS por meio da autenticação do gov.br. | Login |– O sistema deve permitir que o aposentado/trabalhador possa ser autenticado no aplicativo do Meu INSS por meio da autenticação do gov.br.<br>– O sistema deve redirecionar o aposentado/trabalhador para a interface do gov.br para que a autenticação seja feita por meio dele. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF26 - O aplicativo deve Usar autenticação pelo Gov.br para login.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US27 - Mascarar dados sensíveis

Na tabela 27, está descrita a US27 - Mascarar dados sensíveis.

<div style="text-align: center">

<p><b>Tabela 27:</b> História de Usuário 27</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo ter privacidade em relação aos meus dados sensíveis no uso do aplicativo do Meu INSS. | Privacidade |– O sistema deve mascarar qualquer dado sensível como CPF, RG, endereço e etc. Para poder preservar a privacidade do aposentado/trabalhador. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF27 - O sistema deve mascarar dados sensíveis, como CPF e número do benefício, exibindo apenas partes relevantes para preservar a privacidade do usuário.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US28 - Agendamento de horário

Na tabela 28, está descrita a US28 - Agendamento de horário.

<div style="text-align: center">

<p><b>Tabela 28:</b> História de Usuário 28</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo agendar horário em uma agência do INSS mais próxima a minha residência e com serviço já marcado. | Agendamento |– O sistema deve mostrar uma lista com as agências do INSS mais próximas do aposentado/trabalhador com base no seu CEP.<br>– O sistema deve mostrar todos os horários disponíveis para a agência selecionada para que o aposentado/trabalhador consiga agendar o horário.<br>– O sistema deve permitir que o aposentado/trabalhador escreva o assunto a ser abordado no agendamento. | Media | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF28 - O sistema deve permitir que o usuário agende um horário em uma agência do INSS, escolhendo o serviço, horário, data e local diretamente no aplicativo.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US29 - Gerir declarações

Na tabela 29, está descrita a US29 - Gerir declarações.

<div style="text-align: center">

<p><b>Tabela 29:</b> História de Usuário 29</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo emitir declarações sobre minhas contribuições para que eu possa comprovar meus benefícios e contribuições ao INSS. | Declarações |– O sistema deve emitir declarações sobre pagamentos de benefícios.<br>– O sistema deve emitir declarações sobre recebimento de benefícios. | Media | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF29 - O aplicativo deve permitir a geração de declarações, como comprovantes de recebimento de benefício ou regularidade de contribuições.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US30 - Visualização de benefícios

Na tabela 30, está descrita a US30 - visualização de benefícios.

<div style="text-align: center">

<p><b>Tabela 30:</b> História de Usuário 30</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo visualizar meus benefícios a serem recebidos com um detalhamento maior. | Benefícios |– O sistema deve permitir a consulta de dados mais específicos sobre os benefícios a serem recebidos. | Alta | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF30 - O usuário pode visualizar os benefícios com maiores detalhes.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)


### US31 - Calendario de atividades

Na tabela 31, está descrita a US31 - calendario de atividades.

<div style="text-align: center">

<p><b>Tabela 31:</b> História de Usuário 31</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como aposentado/trabalhador, desejo ter acesso a um calendário para que possa me organizar de acordo com as datas dos pagamentos pendentes. | Organização |– O sistema deve fornecer um calendário com as datas dos pagamentos pendentes em evidencia. | Media | Alta |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div >

Rastreabilidade: [RF31 - O usuário tem acesso a um calendário no aplicativo relacionado as suas atividades.](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-funcionais-elicitados)

## Referência bibliográfica 

> [1] SAYÃO, M.; DE CARVALHO, G. Construção do léxico de aplicações. 4th Workshop in Information and Human Language Technology (TIL’2006). 2006. Disponível em: <http://www.nilc.icmc.usp.br/til/til2006/0030.pdf>. Acesso em: 03 dez. 2024.


## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. s.d. Slide 13-20 de 35. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 02 dez. 2024.


## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|11/12/2024|Criação do documento|[Nicolas Bomfim](https://github.com/nickgehjk)|[Júlia Fortunato](https://github.com/julia-fortunato)|
|`1.1`|11/12/2024|Adição de histórias 7 a 12|[Júlia Fortunato](https://github.com/julia-fortunato)|[Ana Catarina Santos](https://github.com/an4catarina)|
|`1.2`|11/12/2024|Adição de histórias 19 a 24|[Nicolas Bomfim](https://github.com/nickgehjk)|[Mauricio Ferreira](https://github.com/mauricio-araujoo)|
|`1.3`|13/12/2024|Adição de histórias 25 a 31|[Mauricio Ferreira](https://github.com/mauricio-araujoo)||
|`1.4`|15/12/2024|Adição de histórias 13 a 18|[Ana Catarina Santos](https://github.com/an4catarina)|[Júlia Fortunato](https://github.com/julia-fortunato)|
|`1.5`|17/12/2024|Adição de histórias 1 a 6|[Cristiano Morais](https://github.com/CristianoMoraiss)||