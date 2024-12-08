# Especificação Suplementar

## <p style="margin-bottom: 50px;">Introdução </p> 

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">A especificação suplementar se trata de uma documentação produzida no âmbito de se descrever os requisitos não-funcionais presentes no sistema, tais requisitos são os que não estão diretamente envolvidos com funcionalidades específicas do software mas que ao invés disso possuem certas características como a confiabilidade do sistema, suportabilidade, usabilidade, desempenho, qualidade entre outras coisas. O documento é redigido em linguagem natural e acaba por ser um complementar aos <b><a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/modelagem_parte1/casosdeuso/">casos de uso</a> </b> pois captura os requisitos que não foram utilizados no método anterior, tais requisitos são de grande importância para se ter a satisfação do usuário e qualidade no sistema.[1]</p>

## <p style="margin-bottom: 50px;">Metodologia</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">Para a confecção do documento optou-se por utilizar de base a metodologia descrita pelo modelo FURPS+, se tratando de uma técnica para a realização da coleta e organização dos requisitos não-funcionais de forma eficiente. Vale ressaltar que o termo FURPS+ é um acrônimo para: Functionality (Funcionalidade); Usability (Usabilidade); Reliability (Confiabilidade); Performance (Desempenho); Supportability (Suporte). Além desses citados o modelo também prevê os requisitos voltados para questões de design, implementação, interface entre outros. A página está categorizada de acordo com os tópicos abordados pelo modelo e cada categoria apresenta os requisitos relacionados ao "Meu INSS" que se enquadram em cada uma delas.  </p>

## <p style="margin-bottom: 50px;">Funcionalidades</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">No que se refere aos requisitos elicitados em relação as funcionalidades do sistema, eles podem ser observados na página dedicada a elicitção de requisitos presentes no link <b><a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/">elicitação de requisitos </a></b>.</p>



## <p style="margin-bottom: 50px;">Suportabilidade</p>

Na categoria de soportabilidade, tem-se os requisitos que estão relacionados ao suporte e manutenção do sistema, que inevitavelmente, garantem a facilidade de manutenção e evolução do sistema ao longo do tempo, tornando-o mais robusto.


Além de tratar de atualizações e correções, também possui requisitos relacionados a diagnóstico de problemas, monitoramento contínuo e rastreabilidade de alterações.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Suportabilidade</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  | Rastreabilidade  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |---------------------------------  |
| SUP01 | O sistema deve possuir documentação detalhada e estruturada, que pode ser testada por meio de auditorias e revisão de sua clareza, abrangência e atualização.                                                                                                                         | - |
| SUP02 | O sistema deve ter uma arquitetura modular que permita a modificação de componentes de forma independente, o que pode ser validado por testes de integração para garantir que modificações não afetem outras partes do sistema.                                                                                                                                                              | - |
| SUP03 | O sistema deve possibilitar a realização de atualizações automáticas, que devem ser testadas para garantir que ocorram sem interrupções no serviço, com um tempo de inatividade inferior a 1 segundo.                                                                                                                                                           | - |
| SUP04 | O sistema deve fornecer suporte em tempo real ao usuário, que não apresentem latência superior a 2 segundos durante o uso.                                                                                                                                                          | [RNF03](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| SUP05 | O sistema deve manter a rastreabilidade das mudanças, o que pode ser validado por meio de logs de alterações e controle de versão, permitindo rastrear qualquer modificação e verificar se está documentada corretamente.                                                                                                                                                                      | - |
| SUP06 | O sistema deve possuir suporte testável para tecnologias assistivas, que responda bem a testes.                                                                                                                              | [RNF07](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| SUP07 | O sistema deve permitir a personalização de configurações de preferências pelo usuário, sendo validado por meio de testes que simulem alterações nas preferências de usabilidade e verifiquem a aplicação das modificações sejam efetivadas em até no máximo 100ms.                                                                                        | - |
| SUP08 | O sistema deve ser compatível e oferecer suporte pleno tanto para dispositivos Android quanto iOS| -  |
| SUP09 | O sistema deve ser capaz de detectar falhas automaticamente e fornecer um mecanismo de recuperação sem perda de dados ou interrupção significativa, fazendo um backup completo (uma vez por dia) e backups incrementais (a cada 2-4 horas durante o dia, dependendo da quantidade de transações no banco de dados)| -  |


<font size="3"><p style="text-align: center">Autor: [Júlia Fortunato](https://github.com/julia-fortunato).</p></font>



## <p style="margin-bottom: 50px;">Confiabilidade</p>

Na questão de confiabilidade, existem os requisitos que correspondem a confiabilidade que o sistema possui, o que pode incluir itens como qualidade e validação assim como também manutenção e gerenciamento.
Inclui os diversos requisitos que tem relaçao a qualidade e confiabilidade, isso inclui requisitos relacionados à disponibilidade e tolerância a falhas como mantenibilidade. 

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  | Rastreabilidade  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |-------------------  |
| CON01 | Garantir a segurança dos dados com criptografia nas transações.           |         [RNF08](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados)           |
| CON02 | O aplicativo deve armazenar dados em conformidade com a LGPD.             |         [RNF011](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)          |
| CON03 | 	O sistema deve estar disponível para o usuário por no mínimo 99% do tempo de um mês, exceto em momentos de manutenção programada.|       [RNF012](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)         |

<font size="3"><p style="text-align: center">Autor: [Cristiano Morais](https://github.com/CristianoMoraiss).</p></font>

## Usabilidade

Diz respeito a facilidade de uso da interface e das funcionalidades do sistema, permitindo que os usuários realizem suas tarefas de forma eficaz, eficiente e com clareza.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Usabilidade.</p></font>

<center>

| ID    | Descrição | Rastreabilidade |
| --- | --- | --- |
| USA01 | O aplicativo deve concluir tarefas em no maximo 5 cliques. | [RNF01](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) [RNF04](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| USA02 | O aplicativo deve oferecer pelo menos 2 tipos de tutoriais explicativos de uso, como vídeos, FAQs e guias escritos. | [RNF02](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| USA03 | O aplicativo deve possuir uma central de ajuda com tutoriais para pelo menos 80% das funcionalidades existentes. | [RNF03](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| USA04 | O aplicativo deve possuir um local explicandos os termos técnicos do Meu INSS. | [RNF05](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| USA05 | O aplicativo deve oferecer uma funcionalidade de busca que permita ao usuário localizar tarefas e funcionalidades após a escrita da primeira palavra da busca desejada. | [RNF06](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| USA06 | O aplicativo deve possuir alternativas para pessoas com deficiencia como por exemplo audio-descrição. | [RNF07](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) [RNF10](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/#tabela-de-requisitos-nao-funcionais-elicitados) |
| USA07 | O aplicativo deve possuir retorno a todas as ações do usuário para confirmação de ação bem sucedida. | - |

</center>

<font size="3"><p style="text-align: center">Autor: [Maurício Ferreira](https://github.com/mauricio-araujoo).</p></font>




## <p style="margin-bottom: 50px;">Referências bibliográficas</p>

> [1] SERRANO, Milene; SERRANO, Maurício. Elicitação, Modelagem e Análise - Aula 13. s.d. Slide 8 de 40. Disponível em: <a>https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf</a>. Acesso em: 05 Dez. 2024. </br>


## <p style="margin-bottom: 50px;">Histórico de Versões</p> 


| Versão | Data       | Descrição                   | Autor                                                 | Revisor                                               |
| :----: | ---------- | --------------------------- | ----------------------------------------------------- | ----------------------------------------------------- |
|  1.0   | 05/12/2024 | Criação do documento        |          [Cristiano Moraes](http://github.com/CristianoMoraiss)                                              |                                    [Júlia Fortunato](http://github.com/julia-fortunato)                      |
|  1.1   | 06/12/2024 | Adição de requisitos de confiabilidade e suportabilidade      |          [Cristiano Moraes](http://github.com/CristianoMoraiss)                                    [Júlia Fortunato](http://github.com/julia-fortunato)             |                                               |