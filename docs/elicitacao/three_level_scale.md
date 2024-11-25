## Introdução

A técnica de priorização de requisitos Three-Level Scale é uma abordagem simples e eficaz para classificar e priorizar requisitos em um projeto. Ela facilita a tomada de decisões e o planejamento das entregas e divide os requisitos em três categorias ou níveis de prioridade: alta, média e baixa. Nesse projeto, essa técnica foi utilizada por um desenvolvedor e uma persona, com o desenvolvedor sendo o mediador e guiando a persona.

## Metodologia

Os requisitos são classificados em três níveis principais:

- <b>Alta Prioridade</b>: Requisitos importantes e urgentes.

- <b>Média Prioridade</b>: Requisitos importantes, mas não urgentes.

- <b>Baixa Prioridade</b>: Requisitos nem importantes nem urgentes.

A importância define por sendo a necessidade de implementação e a urgência é a necessidade de ser lançada na próxima release.

## Desenvolvimento

### Participantes

A usuária Maria das Dores Silva interpretada pela integrante do grupo [Júlia Fortunato](https://github.com/julia-fortunato) foi convidada a participar de uma sessão de perguntas rápidas online a fim da priorização dos requisitos elicitados sobre o aplicativo "Meu INSS" com o desenvolvedor [Maurício Ferreira](https://github.com/mauricio-araujoo). Os resultados estão documentados nas tabelas 1 e 2.
A reunião aconteceu de forma guiada e o desenvolvedor tomou notas e, então analisou as respostas da usuária e priorizou-os de acordo com as categorizações.

## Resultado da priorização

Na tabela 1, se encontram as legendas para as tabelas 2 e 3.

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
</div>

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div>

#### Funcionais

Na tabela 2, encontram-se a o resultado da priorização dos requisitos funcionais de acordo com a técnica Three Level Scale.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos funcionais priorizados pela técnica Three Level Scale</p></font>
</div >

|  ID  | Descrição                                                                                                                                              | Rastreabilidade | Prioridade |
| :--: | ------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------------: | :--------: |
| RF01 | O aplicativo emite e permite consulta a extratos e pagamentos.                                                                                         |      ENC01      |    Alta    |
| RF02 | O aplicativo permite simular a aposentadoria.                                                                                                          |      ENC02      |   Media    |
| RF03 | O aplicativo permite solicitar pedidos.                                                                                                                |      ENC03      |    Alta    |
| RF04 | O aplicativo deve ser integrado com outros sistemas, como o sistema jurídico.                                                                          |      ENC04      |   Media    |
| RF05 | O aplicativo permite solicitar auxílio doença.                                                                                                         |      ENT02      |    Alta    |
| RF06 | O aplicativo permite verificar previsão de pagamento.                                                                                                  |      ENT04      |   Media    |
| RF07 | O aplicativo deve possuir filtro de pesquisa assertivo.                                                                                                |      ENT05      |    Alta    |
| RF08 | O aplicativo deve possuir suporte adequado.                                                                                                            |      ENT06      |   Media    |
| RF09 | O aplicativo deve ser claro com relação a especificação para auxílios doenças e as modalidades de análise (online ou presencial).                      |      ENT07      |    Alta    |
| RF10 | O aplicativo deve avisar sobre mudanças e notícias sobre legislação previdenciária.                                                                    |      ENT08      |   Baixa    |
| RF11 | O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício.                                                      |      ENT09      |   Media    |
| RF12 | O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).                                                                 |      GLO01      |    Alta    |
| RF13 | O aplicativo permite acessar comunidades para os próprios usuários se ajudarem.                                                                        |      IS04       |   Baixa    |
| RF14 | O aplicativo possui assistente virtual com simulações de diferentes cenários previdenciários.                                                          |      IS05       |   Media    |
| RF15 | O aplicativo deve permitir agendamento de perícias e atendimentos.                                                                                     |      GLO03      |   Media    |
| RF16 | O aplicativo deve enviar notificações sobre pendências, prazos e novas regras.                                                                         |      GLO04      |    Alta    |
| RF17 | O aplicativo deverá permitir bloqueio e desbloqueio de benefícios pelo aplicativo.                                                                     |      GLO08      |    Alta    |
| RF18 | O aplicativo deverá mostrar critérios de carência de forma clara.                                                                                      |      GLO09      |   Media    |
| RF19 | O usuário poderá enviar documentos digitalizados.                                                                                                      |      GLO11      |   Media    |
| RF20 | O usuário poderá solicitar benefícios pelo aplicativo.                                                                                                 |     GLO013      |   Media    |
| RF21 | O aplicativo deve mostrar status de solicitações e benefícios em andamento.                                                                            |      GLO14      |    Alta    |
| RF22 | O aplicativo deve permitir alteração de dados cadastrais, como endereço e telefone.                                                                    |      GLO15      |    Alta    |
| RF23 | O aplicativo deverá mostrar emitir recibos digitais para transações realizadas.                                                                        |      GLO16      |   Media    |
| RF24 | O aplicativo deverá integrar informações sobre FGTS para consulta de saldo e movimentações.                                                            |      GLO18      |   Media    |
| RF25 | O aplicativo deve permitir consulta e pagamento de pensões.                                                                                            |      GLO19      |    Alta    |
| RF26 | O aplicativo deve Usar autenticação pelo Gov.br para login.                                                                                            |      GLO20      |    Alta    |
| RF27 | O sistema deve mascarar dados sensíveis, como CPF e número do benefício, exibindo apenas partes relevantes para preservar a privacidade do usuário.    |      OBS01      |    Alta    |
| RF28 | O sistema deve permitir que o usuário agende um horário em uma agência do INSS, escolhendo o serviço, horário, data e local diretamente no aplicativo. |      OBS03      |   Media    |
| RF29 | O aplicativo deve permitir a geração de declarações, como comprovantes de recebimento de benefício ou regularidade de contribuições.                   |      OBS06      |   Media    |
| RF30 | O usuário pode visualizar os benefícios com maiores detalhes.                                                                                          |      OBS07      |    Alta    |
| RF31 | O usuário tem acesso a um calendário no aplicativo relacionado as suas atividades.                                                                     |      OBS08      |   Media    |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div>

#### Não funcionais

Na tabela 3, encontram-se a o resultado da priorização dos requisitos não funcionais de acordo com a técnica Three Level Scale.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b>Requisitos não funcionais priorizados pela técnica Three Level Scale</p></font>
</div >

|  ID   | Descrição                                                                                                                         | Rastreabilidade | Prioridade |
| :---: | --------------------------------------------------------------------------------------------------------------------------------- | :-------------: | :--------: |
| RNF01 | O aplicativo deve ser intuitivo no uso.                                                                                           |      ENC05      |    Alta    |
| RNF02 | O aplicativo deve possuir tutoriais explicativos de uso (por exemplo, vídeos, FAQs).                                              |      ENC06      |    Alta    |
| RNF03 | O aplicativo deve possuir uma central de ajuda clara.                                                                             |      ENC07      |   Media    |
| RNF04 | O aplicativo deve facilitar a execução de tarefas.                                                                                |      ENC08      |    Alta    |
| RNF05 | O aplicativo deve possuir, além de termos técnicos, nomenclaturas populares para as funcionalidades do INSS.                      |      ENT10      |    Alta    |
| RNF06 | O aplicativo deve facilitar a busca de tarefas e funcionalidades.                                                                 |      ENT12      |    Alta    |
| RNF07 | O aplicativo deve ser acessível a todos os usuários.                                                                              |      ENT15      |    Alta    |
| RNF08 | Garantir segurança dos dados com criptografia nas transações.                                                                     |      GLO05      |    Alta    |
| RNF09 | Ser responsivo para uso em diferentes dispositivos.                                                                               |      GLO06      |   Media    |
| RNF10 | O aplicativo deve seguir normas de acessibilidade, como suporte a leitores de tela, para ser acessível a pessoas com deficiência  |      GLO12      |    Alta    |
| RNF11 | O aplicativo deve armazenar dados em conformidade com a LGPD.                                                                     |      GLO17      |    Alta    |
| RNF12 | O sistema deve estar disponível para o usuário por no mínimo 99% do tempo de um mês, exceto em momentos de manutenção programada. |      OBS15      |    Alta    |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div>

## Link da Gravação

No vídeo 1, encontra-se a gravação da técnica de priorização Three Level Scale.

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/jje6FGhp0g0?si=Bi3vrcRjkqI0cmTA" target="blanket"><b>Vídeo 1:</b> Grupo 06 - Three Level Scale</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/jje6FGhp0g0?si=eZT3hVvhVE3Tamzt" title="Apresentação 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>

</div >

## Bibliografia

> WIEGERS, Karl; Beatty, Joy. (2013) Software Requirements (Developer Best Practices). p. 319-320. ISBN: 0735679665. Acesso em: 24 nov. 2024

## Histórico de versões

| Versão | Data       | Descrição                            | Autor                                                    |                         Revisor                          |
| :----: | ---------- | ------------------------------------ | -------------------------------------------------------- | :------------------------------------------------------: |
| `1.0`  | 23/11/2024 | Criação do documento.                | [Nicolas Bomfim](https://github.com/nickgehjk)           | [Maurício Ferreira](https://github.com/mauricio-araujoo) |
| `1.1`  | 24/11/2024 | Preenchimento dos dados das tabelas. | [Maurício Ferreira](https://github.com/mauricio-araujoo) |  [Júlia Fortunato](https://github.com/julia-fortunato)   |
| `1.2`  | 24/11/2024 | Adição da gravação                   | [Júlia Fortunato](https://github.com/julia-fortunato)    |  [Ana Catarina Santos](https://github.com/an4catarina)   |
