# Requisitos Elicitados

## Introdução

Essa página tem como objetivo reunir e apresentar todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [encenação](encenacao.md), [entrevista](entrevista.md), [introspecção](introspeccao.md), [glossário](glossario.md) e [observação](observacao.md).

## Metodologia

Criou-se duas tabelas, uma apresentando os requisitos funcionais e outra com os requisitos não funcionais. 

As tabelas possuem o seguinte formato: cada linha contém um ID (junto com a indicação de se é funcional ou não funcional), sua respectiva descrição, se ele foi implementado ou não e a rastreabilidade, que indica qual(is) técnica(s) elicitou o requisito em questão. Além disso, requisitos que são similares e apresentam a mesma função agrupados e consolidados em um único requisito. Os identificadores (IDs) originais desses requisitos serão referenciados na tabela, garantindo rastreabilidade e transparência no processo.

Na tabela 1, encontra-se a legenda para cada sigla encontrada nas tabelas 2 e 3.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda para a tabela 2 e 3 </p></font>

<table>
  <thead>
    <tr>
        <th>Tipo</th>
        <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>RF</td>
        <td>Requisito Funcional</td>
    </tr>
    <tr>
        <td>RNF</td>
        <td>Requisito Não-Funcional</td>
    </tr>
    <tr>
        <td>ENC</td>
        <td>Requisito elicitado pela encenação</td>
    </tr>
    <tr>
        <td>ENT</td>
        <td>Requisito elicitado pela entrevista</td>
    </tr>
    <tr>
        <td>GLO</td>
        <td>Requisito elicitado pelo glossário</td>
    </tr>
    <tr>
        <td>INT</td>
        <td>Requisito elicitado pela introspecção</td>
    </tr>
    <tr>
        <td>OBS</td>
        <td>Requisito elicitado pela observação</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

## Tabela de requisitos funcionais elicitados

Na tabela 2, encontram-se os requisitos funcionais elicitados.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos funcionais elicitados do aplicativo Meu INSS</p></font>
</div >

| ID    | Descrição                                                                            | Implementado | Rastreabilidade |
| :---: | ------------------------------------------------------------------------------------ | :----------: | :-------------: |
| RF01  | O aplicativo emite e permite consulta a extratos e pagamentos.                        | Sim          | ENC01, ENT03, IS02, IS03, GLO07   |
| RF02  | O aplicativo permite simular a aposentadoria.                                         | Sim          | ENC02, ENT01, GLO02, OBS04   |
| RF03  | O aplicativo permite solicitar pedidos.                                              | Sim          | ENC03           |
| RF04  | O aplicativo deve ser integrado com outros sistemas, como o sistema jurídico.         | Não          | ENC04          |
| RF05  | O aplicativo permite solicitar auxílio doença.                                        | Sim          |    ENT02       |
| RF06 | O aplicativo permite verificar previsão de pagamento.                                    | Sim          | ENT04      |
| RF07 | O aplicativo deve possuir filtro de pesquisa assertivo.                                  | Não          | ENT05         |
| RF08 | O aplicativo deve possuir suporte adequado.                                            | Não          | ENT06              |
| RF09 | O aplicativo deve ser claro com relação a especificação para auxílios doenças e as modalidades de análise (online ou presencial).                                                | Não          | ENT07               |
| RF10 | O aplicativo deve avisar sobre mudanças e notícias sobre legislação previdenciária.                      | Não          | ENT08, IS07               |
| RF11 | O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício.| Não          | ENT09, IS06               |
| RF12 | O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).  | Sim          | GLO01, IS01             |
| RF13 | O aplicativo permite acessar comunidades para os próprios usuários se ajudarem.         | Não          | IS04               |
| RF14 | O aplicativo possui assistente virtual com simulações de diferentes cenários previdenciários.   | Não          | IS05              |
| RF15 | O aplicativo deve permitir agendamento de perícias e atendimentos.                                        | Sim          | GLO03               |
| RF16 | O aplicativo deve enviar notificações sobre pendências, prazos e novas regras.             | Sim          | GLO04, OBS05               |
| RF17 | O aplicativo deverá permitir bloqueio e desbloqueio de benefícios pelo aplicativo.         | Sim          | GLO08, OBS02               |
| RF18 | O aplicativo deverá mostrar critérios de carência de forma clara.                              | Sim          | GLO09               |
| RF19 | O usuário poderá enviar documentos digitalizados.                                          | Sim          | GLO11              |
| RF20 | O usuário poderá olicitar benefícios pelo aplicativo.                               | Sim          | GLO013               |
| RF21 | O aplicativo deve mostrar status de solicitações e benefícios em andamento.                         | Sim          | GLO14              |
| RF22 | O aplicativo deve permitir alteração de dados cadastrais, como endereço e telefone.                         | Sim          | GLO15               |
| RF23 | O aplicativo deverá mostrar emitir recibos digitais para transações realizadas.               | Sim          | GLO16           |
| RF24 | O aplicativo deverá integrar informações sobre FGTS para consulta de saldo e movimentações.   | Não          | GLO18       |
| RF25 | O aplicativo deve permitir consulta e pagamento de pensões.                         | Não          | GLO19              |
| RF26 | O aplicativo deve Usar autenticação pelo Gov.br para login.                                      | Sim          | GLO20       |
| RF27 | O sistema deve mascarar dados sensíveis, como CPF e número do benefício, exibindo apenas partes relevantes para preservar a privacidade do usuário.                                           | Não          | OBS01              |
| RF28 | O sistema deve permitir que o usuário agende um horário em uma agência do INSS, escolhendo o serviço, horário, data e local diretamente no aplicativo. | Não | OBS03 |
| RF29 | O aplicativo deve permitir a geração de declarações, como comprovantes de recebimento de benefício ou regularidade de contribuições. | Sim | OBS06 |
| RF30 | O usuário pode visualizar os benefícios com maiores detalhes.| Sim | OBS07 |
| RF31 | O usuário tem acesso a um calendário no aplicativo relacionado as suas atividades.                                        | Sim | OBS08 |


<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

## Tabela de requisitos não funcionais elicitados

Na tabela 3, encontram-se os requisitos não funcionais elicitados.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Requisitos não funcionais elicitados do aplicativo Meu INSS</p></font>
</div >

| ID    | Descrição                                                                            | Implementado | Rastreabilidade |
| :---: | ------------------------------------------------------------------------------------ | :----------: | :-------------: |
| RNF01  | O aplicativo deve ser intuitivo no uso.                                             | Não          | ENC05, ENT13, OBS13           |
| RNF02  | O aplicativo deve possuir tutoriais explicativos de uso (por exemplo, vídeos, FAQs).      | Não          | ENC06, ENT14, OBS12           |
| RNF03  | O aplicativo deve possuir uma central de ajuda clara.                               | Não          | ENC07           |
| RNF04  | O aplicativo deve facilitar a execução de tarefas.                                  | Não          | ENC08, ENT11          |
| RNF05  | O aplicativo deve possuir, além de termos técnicos, nomenclaturas populares para as funcionalidades do INSS.  | Não          |    ENT10       |
| RNF06  | O aplicativo deve facilitar a busca de tarefas e funcionalidades.                   | Não          | ENT12      |
| RNF07 | O aplicativo deve ser acessível a todos os usuários.                                  | Não          | ENT15, OBS10         |
| RNF08 | Garantir segurança dos dados com criptografia nas transações.                                           | Sim          | GLO05, OBS14              |
| RNF09 | Ser responsivo para uso em diferentes dispositivos.                                               | Sim          | GLO06, OBS11               |
| RNF10 | O aplicativo deve seguir normas de acessibilidade, como suporte a leitores de tela, para ser acessível a pessoas com deficiência                      | Não          | GLO12, OBS10               |
| RNF11 | O aplicativo deve armazenar dados em conformidade com a LGPD.| Sim          | GLO17               |
| RNF12 | O sistema deve estar disponível para o usuário por no mínimo 99% do tempo de um mês, exceto em momentos de manutenção programada.  | Sim          | OBS15             |


<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >


## Histórico de versões 

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|23/11/2024|Criação do documento|[Júlia Fortunato](https://github.com/julia-fortunato)|[](https://github.com/)|