# Especificação Suplementar

## <p style="margin-bottom: 50px;">Introdução </p> 

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">A especificação suplementar se trata de uma documentação produzida no âmbito de se descrever os requisitos não-funcionais presentes no sistema, tais requisitos são os que não estão diretamente envolvidos com funcionalidades específicas do software mas que ao invés disso possuem certas características como a confiabilidade do sistema, suportabilidade, usabilidade, desempenho, qualidade entre outras coisas. O documento é redigido em linguagem natural e acaba por ser um complementar aos <b><a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/modelagem_parte1/casosdeuso/">casos de uso</a> </b> pois captura os requisitos que não foram utilizados no método anterior, tais requisitos são de grande importância para se ter a satisfação do usuário e qualidade no sistema.[1]</p>

## <p style="margin-bottom: 50px;">Metodologia</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">Para a confecção do documento optou-se por utilizar de base a metodologia descrita pelo modelo FURPS+, se tratando de uma técnica para a realização da coleta e organização dos requisitos não-funcionais de forma eficiente. Vale ressaltar que o termo FURPS+ é um acrônimo para: Functionality (Funcionalidade); Usability (Usabilidade); Reliability (Confiabilidade); Performance (Desempenho); Supportability (Suporte). Além desses citados o modelo também prevê os requisitos voltados para questões de design, implementação, interface entre outros. A página está categorizada de acordo com os tópicos abordados pelo modelo e cada categoria apresenta os requisitos relacionados ao "Meu INSS" que se enquadram em cada uma delas.  </p>

## <p style="margin-bottom: 50px;">Funcionalidades</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">No que se refere aos requisitos elicitados em relação as funcionalidades do sistema, eles podem ser observados na página dedicada a elicitção de requisitos presentes no link <b><a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/">elicitação de requisitos </a></b>.</p>


## <p style="margin-bottom: 50px;">Suportabilidade</p>

Na categoria de soportabilidade, tem-se os requisitos que estão relacionados ao suporte e manutenção do sistema, que inevitavelmente, garantem a facil
eunam e edad

Envolve os requisitos relacionados ao suporte e manutenção do sistema. Isso inclui requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado, documentação adequada, facilidade de teste e diagnóstico de problemas.

Para essa categoria os requisitos identificados estão representados na tabela ? a seguir.

<font><p style="text-align: center">Tabela ? - Requisitos de Suportabilidade</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  | Rastreabilidade  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |-------------------  |
| SUP01 | O sistema deve possuir uma documentação separada em tópicos (ao menos 10 tópicos principais) e que apresente grande parte das dúvidas mais frequentes.                                                                                                                     |  |
| SUP02 | O sistema deve possuir uma facilidade de manutenção através de uma estrutura modular e código bem organizado.                                                                                                                                                              |  |
| SUP03 | O sistema deve possuir uma capacidade de extensão para adicionar novas funcionalidades e acompanhar as mudanças.                                                                                                                                                           |  |
| SUP04 | O sistema deve possuir uma facilidade de atualização com processos eficientes (de até 200ms) e sem interrupções significativas, que ultrapassem o tempo limite de resposta.                                                                                                |  |
| SUP05 | O sistema deve possuir um suporte ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) com canais adequados de suporte e equipe  |  |disponível.                                                                                                                                                                          |  |
| SUP06 | O sistema deve possuir uma testabilidade, com facilidade de realização de testes durante o desenvolvimento e a manutenção.                                                                                                                                                 |  |
| SUP07 | O sistema deve possuir uma rastreabilidade com mecanismos para registrar e rastrear mudanças e correções ao longo do tempo, incluindo controle de versão e registros de alterações.                                                                                        |  |
| SUP08 | O sistema deve possuir uma tolerância a falhas para garantir que o sistema possa lidar com falhas adequadamente, por meio de mecanismos de recuperação, detecção de falhas, manutenção da integridade dos dados, backups regulares e restauração rápida em caso de falhas. |  |

<font size="3"><p style="text-align: center">Autora: [Júlia Fortunato, 2024](https://github.com/julia-fortunato).</p></font>




## <p style="margin-bottom: 50px;">Confiabilidade</p>

Na questão de confiabilidade, existem os requisitos que correspondem a confiabilidade que o sistema possui, o que pode incluir itens como qualidade e validação assim como também manutenção e gerenciamento.
Inclui os diversos requisitos que tem relaçao a qualidade e confiab Isso inclui requisitos relacionados à disponibilidade, tolerância a falhas como mantenibilidade. 

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<p style="text-align: center">Tabela 2 - Requisitos de Confiabilidade.</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  | Rastreabilidade  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |-------------------  |
| SUP01 | O sistema deve possuir uma documentação separada em tópicos (ao menos 10 tópicos principais) e que apresente grande parte das dúvidas mais frequentes.                                                                                                                     |  |
| SUP02 | O sistema deve possuir uma facilidade de manutenção através de uma estrutura modular e código bem organizado.                                                                                                                                                              |  |
| SUP03 | O sistema deve possuir uma capacidade de extensão para adicionar novas funcionalidades e acompanhar as mudanças.                                                                                                                                                           |  |
| SUP04 | O sistema deve possuir uma facilidade de atualização com processos eficientes (de até 200ms) e sem interrupções significativas, que ultrapassem o tempo limite de resposta.                                                                                                |  |
| SUP05 | O sistema deve possuir um suporte ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) com canais adequados de suporte e equipe  |  |disponível.                                                                                                                                                                          |  |
| SUP06 | O sistema deve possuir uma testabilidade, com facilidade de realização de testes durante o desenvolvimento e a manutenção.                                                                                                                                                 |  |
| SUP07 | O sistema deve possuir uma rastreabilidade com mecanismos para registrar e rastrear mudanças e correções ao longo do tempo, incluindo controle de versão e registros de alterações.                                                                                        |  |
| SUP08 | O sistema deve possuir uma tolerância a falhas para garantir que o sistema possa lidar com falhas adequadamente, por meio de mecanismos de recuperação, detecção de falhas, manutenção da integridade dos dados, backups regulares e restauração rápida em caso de falhas. |  |

<font size="3"><p style="text-align: center">Autor: [Cristiano Morais, 2024](https://github.com/CristianoMoraiss).</p></font>





## <p style="margin-bottom: 50px;">Referências bibliográficas</p>

> [1] SERRANO, Milene; SERRANO, Maurício. Elicitação, Modelagem e Análise - Aula 13. s.d. Slide 8 de 40. Disponível em: <a>https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf</a>. Acesso em: 05 Dez. 2024. </br>


## <p style="margin-bottom: 50px;">Histórico de Versões</p> 


| Versão | Data       | Descrição                   | Autor                                                 | Revisor                                               |
| :----: | ---------- | --------------------------- | ----------------------------------------------------- | ----------------------------------------------------- |
|  1.0   | 05/12/2024 | Criação do documento        |                                                       |                                                       |