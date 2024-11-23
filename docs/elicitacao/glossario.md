# Glossário

## Introdução

O glossário é uma ferramenta importante no desenvolvimento de sistemas, principalmente para apps com termos específicos, como o Meu INSS. Ele serve para definir e esclarecer os termos utilizados dentro do contexto do sistema, garantindo que todos os envolvidos no processo de desenvolvimento e uso compreendam claramente a funcionalidade e o significado de cada termo.

Escolhemos usar essa técnica para o Meu INSS pela necessidade de formalizar a linguagem utilizada no aplicativo, considerando a diversidade dos usuários, como segurados buscando informações simples e profissionais que interagem com dados mais complexos. Ao elaborar um glossário, conseguimos alinhar as expectativas, melhorar a comunicação e, acima de tudo, garantir que os requisitos do sistema sejam bem compreendidos e atendidos de forma precisa.

## Definição do Glossário

A Tabela 1 lista os termos usados no sistema Meu INSS e suas definições. Esses termos foram documentados com base no uso do sistema, garantindo que todos os envolvidos entendam da mesma forma, contribuindo para uma comunicação clara, considerando os diferentes usuários e contextos do sistema.

<font size="3"><p style="text-align: center">Tabela 1: Termos rastreados e suas respectivas descrições.</p></font>

<center>

| Termo                      | Definição                                                                                       |
| -------------------------- | ----------------------------------------------------------------------------------------------- |
| Meu INSS                   | Aplicativo oficial da Previdência Social que oferece serviços e informações sobre benefícios.   |
| Segurado                   | Pessoa cadastrada no INSS que contribui para a Previdência e tem direito a benefícios.          |
| Contribuição               | Pagamento feito pelo segurado para garantir sua proteção previdenciária.                        |
| Aposentadoria              | Benefício concedido ao segurado ao cumprir os requisitos de idade ou tempo de contribuição.     |
| Benefício                  | Valor pago pelo INSS em situações previstas, como doença ou maternidade.                        |
| Extrato CNIS               | Registro do histórico de contribuições do segurado no Cadastro Nacional de Informações Sociais. |
| Salário-Maternidade        | Benefício pago à segurada durante a licença-maternidade.                                        |
| Perícia Médica             | Avaliação médica feita pelo INSS para verificar a condição de saúde do segurado.                |
| PIS/PASEP                  | Programas usados como identificadores do segurado no sistema previdenciário.                    |
| DIB                        | Data de Início do Benefício, quando o pagamento do benefício começa.                            |
| Carência                   | Número mínimo de contribuições exigidas para acessar um benefício.                              |
| INSS Digital               | Estratégia para modernizar e facilitar o atendimento por meios digitais.                        |
| Simulação de Aposentadoria | Ferramenta que calcula uma previsão de tempo para aposentadoria.                                |
| Bloqueio de Benefício      | Suspensão temporária do benefício para verificar informações.                                   |
| Agendamento Online         | Serviço para marcar atendimentos ou perícias pelo aplicativo.                                   |
| FGTS                       | Fundo de Garantia por Tempo de Serviço, acessado em casos específicos, como aposentadoria.      |
| Pensão                     | Benefício pago aos dependentes do segurado falecido.                                            |

</center>
<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

## Elicitação dos requisitos

Os requisitos do sistema foram elicitados a partir do glossário e divididos em duas categorias: requisitos funcionais e não funcionais. Esses requisitos definem as funcionalidades do sistema e os padrões de desempenho e qualidade que precisam ser cumpridos.

### Requisitos Funcionais (RF)

Os requisitos funcionais descrevem as funcionalidades que o sistema deve oferecer, detalhando as operações que ele precisa realizar para atender às necessidades dos usuários. A Tabela 1 lista os requisitos funcionais, elicitados a partir do glossário, do sistema Meu INSS:

<font size="3"><p style="text-align: center">Tabela 2: Requsiitos Funcionais</p></font>

<center>

| ID    | Descrição                                                               |
| ----- | ----------------------------------------------------------------------- |
| GLO01 | Exibir o histórico completo de contribuições do segurado (CNIS).        |
| GLO02 | Oferecer simulação de aposentadoria com base nas regras atuais.         |
| GLO03 | Permitir agendamento de perícias e atendimentos.                        |
| GLO04 | Enviar notificações sobre pendências, prazos e novas regras.            |
| GLO07 | Disponibilizar consulta e download de extratos de pagamento.            |
| GLO08 | Permitir bloqueio e desbloqueio de benefícios pelo aplicativo.          |
| GLO09 | Mostrar critérios de carência de forma clara.                           |
| GLO11 | Aceitar envio de documentos digitalizados.                              |
| GLO13 | Permitir solicitação de benefícios pelo aplicativo.                     |
| GLO14 | Mostrar status de solicitações e benefícios em andamento.               |
| GLO15 | Permitir alteração de dados cadastrais, como endereço e telefone.       |
| GLO16 | Emitir recibos digitais para transações realizadas.                     |
| GLO18 | Integrar informações sobre FGTS para consulta de saldo e movimentações. |
| GLO19 | Permitir consulta e pagamento de pensões.                               |
| GLO20 | Usar autenticação pelo Gov.br para login.                               |

</center>

<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

### Requisitos Não Funcionais (RNF)

Os requisitos não funcionais definem as qualidades e características do sistema, como segurança, acessibilidade e desempenho, que não estão diretamente relacionadas a uma função específica, mas são essenciais para garantir uma boa experiência ao usuário e o funcionamento eficiente da plataforma. A Tabela 2 lista os requisitos não funcionais, elicitados a partir do glossário, do sistema Meu INSS::

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não Funcionais</p></font>

<center>

| ID    | Descrição                                                         |
| ----- | ----------------------------------------------------------------- |
| GLO05 | Garantir segurança dos dados com criptografia nas transações.     |
| GLO06 | Ser responsivo para uso em diferentes dispositivos.               |
| GLO10 | Oferecer suporte em português, espanhol e inglês.                 |
| GLO12 | Seguir normas de acessibilidade, como suporte a leitores de tela. |
| GLO17 | Armazenar dados em conformidade com a LGPD.                       |

</center>
<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

## Bibliografia

> SOUZA, Nicolas. Glossário do Lichess. 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/glossario/]. Acesso em: 22 nov. 2024.
> VÁZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.

## Histórico de versões

| Versão | Data       | Descrição                    | Autor                                                 |                        Revisor                        |
| :----: | ---------- | ---------------------------- | ----------------------------------------------------- | :---------------------------------------------------: |
| `1.0`  | 22/11/2024 | Desenvolvimento do glossário | [Ana Catarina Santos](https://github.com/an4catarina) | [Júlia Fortunato](https://github.com/julia-fortunato) |
