## Introdução

A introspecção é uma técnica que envolve o engenheiro de requisitos ou a
pessoa que está alocada para a tarefa de elicitação de requisitos. Dessa forma, ela
consiste em uma imaginação do que o sistema deve possuir, em questão de
propriedades, para que ele seja consistente e completo, ou seja, que atinja o
sucesso, de acordo com uma necessidade. Porém, é uma técnica complicada, pois
realmente demanda discernimento com relação aos interesses do sistema.

Nesta documentação iremos mostrar os resultados da aplicação da tecnica de introspecção no aplicativo "Meu INSS", este aplicativo visa ajudar os seu publico alvo com questões previdenciarias.

## Metodologia

A técnica para a elicitação de requisitos foi utilizada de forma que um membro da equipe, no caso [Maurício Ferreira](https://github.com/mauricio-araujoo),  se imaginou executando tarefas e assim elicitou requisitos que o ajudariam a cumprir essas tarefas de acordo com o contexto do aplicativo "Meu INSS", a situação hipotetica esta listada abaixo e os resultados estão na sessão "Desenvolvimento".

- <b>Situação Hipotetica</b>

Eu sou um cidadão que deseja acessar o Meu INSS para garantir que minhas contribuições estejam atualizadas, evitar atrasos que possam prejudicar meu auxílio previdenciário, desejo previsibilidade sobre quanto tempo eu recebo e quanto eu recebi de meu auxílio e acompanhar alguns beneficios que posso utilizar em possíveis emergências com minha família.


## Desenvolvimento

Nesta seção, apresentamos os requisitos que foram elicitados ao utilizar a técnica de elicitação de introspecção.

Legenda da Tabela 1:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela introspecção.


<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Requisitos Elicitados</p></font>

<center>

| Tipo | Descrição                                                                                                             | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RF12 | O aplicativo permite verificar historico de contribuições.  | IS01 | Sim |
| RF13 | O aplicativo permite emitir extratos de pagamentos de beneficios.| IS02 | Sim |
| RF14 | O aplicativo permite simular o tempo de contribuição.| IS03 | Sim |
| RF15 | O aplicativo permite acessar comunidades para os proprios usuarios se ajudarem.| IS04  | Não  |
| RF16 | O aplicativo possui assistente virtual com simulações de diferentes cenários previdenciarios. | IS05  | Não |
| RF17 | O aplicativo possui relatórios personalizados com informações sobre os impactos das contribuições nos beneficios futuros.| IS06 | Não|
| RF18 | O aplicativo possui notificações sobre mudanças que ocorreram ou que irão ocorrer na legislação previdenciaria. | IS07 | Não |

</center>

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2024</p></font>
</div>




## Bibliografia

>[1] SERRANO, Milene; SERRANO, Maurício. Elicitação, Modelagem e Análise - Aula 7. s.d. Slide 25 de 50. Disponível em: <a>https://aprender3.unb.br/pluginfile.php/2972449/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf</a>. Acesso em: 22 nov. 2024. 

## Histórico de versões


| Versão | Data       | Descrição                            | Autor                                                 | Revisor                                               |
| :----: | ---------- | ------------------------------------ | ----------------------------------------------------- | ----------------------------------------------------- |
| `1.0`  | 23/11/2024 | Criação do documento                 | [Maurício Ferreira](https://github.com/mauricio-araujoo)        |         |

