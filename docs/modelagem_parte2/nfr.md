# NFR Framework

## Introdução

O NFR Framework (Framework de Requisitos Não Funcionais) é uma abordagem conceitual voltada para a modelagem e análise de requisitos não funcionais no contexto da Engenharia de Requisitos. Diferente dos requisitos funcionais, que descrevem o que o sistema faz, os requisitos não funcionais focam em características de qualidade como desempenho, segurança, usabilidade e confiabilidade, sendo considerados elementos fundamentais para o sucesso de um projeto.

O NFR Framework utiliza o Softgoal Interdependency Graph (SIG), um modelo que organiza os softgoals, ou seja, objetivos abstratos sem critérios rígidos de satisfação. No SIG, os softgoals são analisados e conectados por meio de decomposições e contribuições, que ajudam a entender como diferentes requisitos interagem e impactam o sistema.

Principais conceitos do NFR Framework:
- NFR Softgoal: Representa os requisitos não funcionais como atributos de qualidade do sistema.
- Operationalizing Softgoal: Refere-se às implementações concretas que atendem aos softgoals.
- Claim Softgoal: Argumentações que justificam decisões no modelo.
- Contribuições: Relacionamentos entre softgoals, podendo ser positivos (MAKE, HELP), negativos (HURT, BREAK) ou neutros (UNKNOWN).
- Labels: Indicadores de satisfação dos softgoals, como Satisficed (atendido) ou Denied (negado).

O NFR Framework é essencial para gerenciar conflitos e avaliar alternativas, permitindo uma visão estruturada dos objetivos de qualidade do sistema e facilitando a tomada de decisões ao longo do desenvolvimento​.

## Metodologia

## Cartões de especificação

Os cartões de especificação desempenham um papel fundamental na rastreabilidade e no desenvolvimento posterior do NFR, servindo como uma base estruturada. Os cartões apresentados nas Tabelas 1 a 5 foram utilizados para descrever os Requisitos Não-Funcionais necessários à elaboração dos NFR frameworks.

<font><p style="text-align: center">**Tabela 1** - Cartão de especificação: RNF02 - Usabilidade.</p></font>

<center>

| **Campo**               | **Detalhes**                                                                 |
|-----------------------|--------------------------------------------------------------------------|
|**ID**|[RNF02](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#:~:text=requisitos%20funcionais%20elicitados-,Tabela%20de%20requisitos%20n%C3%A3o%20funcionais%20elicitados,-Hist%C3%B3rico%20de%20vers%C3%B5es)|
| **Classificação**     | Usabilidade                                                             |
| **Descrição**         | O aplicativo deve possuir tutoriais explicativos de uso (por exemplo, vídeos, FAQs). |
| **Justificativa**     | Oferecer suporte imediato ao usuário, facilitando o entendimento das funcionalidades do sistema. |
| **Origem do Requisito** | [Encenação](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/encenacao/#nao-funcionais:~:text=Funcionais-,N%C3%A3o%20funcionais,-Refer%C3%AAncias%20Bibliogr%C3%A1ficas), [Entrevista](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/#nao-funcionais:~:text=Funcionais-,N%C3%A3o%20funcionais,-Bibliografia)    , [Observação](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/#:~:text=Requisitos%20Funcionais-,Requisitos%20N%C3%A3o%20Funcionais,-Refer%C3%AAncia%20bibliogr%C3%A1fica) |
| **Critério de Aceitação** | Disponibilização de tutoriais (vídeos ou FAQs) acessíveis na interface principal. |
| **Dependências**      | Nenhuma                                                   |
| **Prioridade**        | Alta                                                                  |
| **Conflitos**         | Nenhum identificado.                                                   |
| **História**          | 17/12/2024 |


<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

</center>

<font><p style="text-align: center">**Tabela 2** - Cartão de especificação: RNF03 - Usabilidade.</p></font>

<center>

| **Campo**               | **Detalhes**                                                                 |
|-----------------------|--------------------------------------------------------------------------|
|**ID**|[RNF03](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#:~:text=requisitos%20funcionais%20elicitados-,Tabela%20de%20requisitos%20n%C3%A3o%20funcionais%20elicitados,-Hist%C3%B3rico%20de%20vers%C3%B5es)|
| **Classificação**     | Usabilidade                                                             |
| **Descrição**         | O aplicativo deve possuir uma central de ajuda clara.                   |
| **Justificativa**     | Melhorar o suporte ao usuário e resolver dúvidas de forma prática e eficiente. |
| **Origem do Requisito** |[Encenação](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/encenacao/#nao-funcionais:~:text=Funcionais-,N%C3%A3o%20funcionais,-Refer%C3%AAncias%20Bibliogr%C3%A1ficas)      |
| **Critério de Aceitação** | Central de ajuda deve conter tópicos claros, organizados por categoria e ser fácil de navegar. |
| **Dependências**      | Nenhuma                                                                 |
| **Prioridade**        | Média                                                                  |
| **Conflitos**         | Nenhum identificado.                                                   |
| **História**          | Inserido após observação de dúvidas recorrentes nos testes com usuários. |


<font size="3"><p style="text-align: center">Autor: [](https://github.com/), 2024</p></font>

</center>

<font><p style="text-align: center">**Tabela 3** - Cartão de especificação: RNF05 - Usabilidade.</p></font>

<center>

| **Campo**                 | **Detalhes**                                                                                                                                                                                                                                       |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                        | [RNF05](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#:~:text=requisitos%20funcionais%20elicitados-,Tabela%20de%20requisitos%20n%C3%A3o%20funcionais%20elicitados,-Hist%C3%B3rico%20de%20vers%C3%B5es) |
| **Classificação**         | Usabilidade                                                                                                                                                                                                                                        |
| **Descrição**             | O aplicativo deve possuir, além de termos técnicos, nomenclaturas populares para as funcionalidades do INSS.                                                                                                                                       |
| **Justificativa**         | Facilitar o entendimento das funcionalidades por diferentes públicos.                                                                                                                                                                              |
| **Origem do Requisito**   | [Entrevista](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/#nao-funcionais:~:text=Funcionais-,N%C3%A3o%20funcionais,-Bibliografia)                                                                                                                                                                                           |
| **Critério de Aceitação** | Uso de termos populares nas descrições e labels das funcionalidades.                                                                                                                                                                               |
| **Dependências**          | Nenhuma                                                                                                                                                                                                                                              |
| **Prioridade**            | Alta                                                                                                                                                                                                                                              |
| **Conflitos**             | Possível conflito entre precisão técnica e clareza popular.                                                                                                                                                                                        |
| **História**              | 17/12/2024                                                                                                                                                                     |

<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

</center>

<font><p style="text-align: center">**Tabela 4** - Cartão de especificação: RNF11 - Segurança.</p></font>

<center>

| **Campo**                 | **Detalhes**                                                                                                                                                                                                                                       |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                    | [RNF11](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#:~:text=requisitos%20funcionais%20elicitados-,Tabela%20de%20requisitos%20n%C3%A3o%20funcionais%20elicitados,-Hist%C3%B3rico%20de%20vers%C3%B5es) |
| **Classificação**         | Segurança                                                                                                                                                                                                                                          |
| **Descrição**             | O aplicativo deve armazenar dados em conformidade com a LGPD (Lei Geral de Proteção de Dados).                                                                                                                                                     |
| **Justificativa**         | Garantir segurança e privacidade no tratamento e armazenamento dos dados dos usuários, cumprindo requisitos legais.                                                                                                                                |
| **Origem do Requisito**   | [Glossário](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/#requisitos-nao-funcionais-rnf:~:text=Requisitos%20Funcionais%20(RF)-,Requisitos%20N%C3%A3o%20Funcionais%20(RNF),-Bibliografia)                                                                                                                                                                                             |
| **Critério de Aceitação** | Realização de auditorias de conformidade com a LGPD e testes de segurança.                                                                                                                                                                         |
| **Dependências**          | Nenhuma                                                                                                                                                                                                                                            |
| **Prioridade**            | Média                                                                                                                                                                                                                                              |
| **Conflitos**             | Pode haver impactos em sistemas legados ou aumento de custos para implementação.                                                                                                                                                                   |
| **História**              | 17/12/2024                                                                                                                                                                                                                                         |

<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

</center>

<font><p style="text-align: center">**Tabela 5** - Cartão de especificação: RNF12 - Confiabilidade.</p></font>

<center>

| **Campo**                 | **Detalhes**                                                                                                                                                                                                                                       |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                    | [RNF12](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#:~:text=requisitos%20funcionais%20elicitados-,Tabela%20de%20requisitos%20n%C3%A3o%20funcionais%20elicitados,-Hist%C3%B3rico%20de%20vers%C3%B5es) |
| **Classificação**         | Confiabilidade                                                                                                                                                                                                                                     |
| **Descrição**             | O sistema deve estar disponível para o usuário por no mínimo 99% do tempo de um mês, exceto em momentos de manutenção programada.                                                                                                                  |
| **Justificativa**         | Garantir alta disponibilidade do sistema para atender às necessidades dos usuários de forma contínua.                                                                                                                                              |
| **Origem do Requisito**   | [Observação](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/#:~:text=Requisitos%20Funcionais-,Requisitos%20N%C3%A3o%20Funcionais,-Refer%C3%AAncia%20bibliogr%C3%A1fica)                                                                                                                                                       |
| **Critério de Aceitação** | Relatório de disponibilidade mensal comprovando um tempo de uptime igual ou superior a 99%, descontando as manutenções programadas.                                                                                                                |
| **Dependências**          | Nenhuma                                                                                                                                                                                                                                            |
| **Prioridade**            | Média                                                                                                                                                                                                                                              |
| **Conflitos**             | Manutenção programada pode impactar o uso durante janelas específicas.                                                                                                                                                                             |
| **História**              | 17/12/2024                                                                                                                                                                                                                                         |

<font size="3"><p style="text-align: center">Autor: [Ana Catarina Santos](https://github.com/an4catarina), 2024</p></font>

</center>

## NFR Framework

### NFR01 - Suportabilidade

### NFR02 - Confiabilidade

### NFR03 - Usabilidade

### NFR04 - Desempenho

### NFR05 - Manutenibilidade

## Referência bibliográfica

> [1] SAYÃO, M.; DE CARVALHO, G. Construção do léxico de aplicações. 4th Workshop in Information and Human Language Technology (TIL’2006). 2006. Disponível em: <http://www.nilc.icmc.usp.br/til/til2006/0030.pdf>. Acesso em: 03 dez. 2024.

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 17. s.d. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972516/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf>. Acesso em: 17 dez. 2024.

## Histórico de Versões

| Versão | Data       | Descrição            | Autor                   |         Revisor         |
| :----: | ---------- | -------------------- | ----------------------- | :---------------------: |
| `1.0`  | 11/12/2024 | Criação do documento e adição dos cartões de especificação | [Ana Catarina Santos](https://github.com/an4catarina) | [](https://github.com/) |
