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
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="http://www.nilc.icmc.usp.br/til/til2006/0030.pdf">Miriam Sayão e Gustavo R. de Carvalho</a>, 2006</p></font>
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

| L01 - Agendar atendimento | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Noção | Tarefa realizada pelo usuário <br>Ação de selecionar um horário específico para atendimento presencial em uma unidade do INSS, através do aplicativo Meu INSS | 
| Impacto | Permite ao usuário organizar seu atendimento de forma eficiente, ao garantir que o mesmo seja realizado em um horário previamente marcado <br>A sua ausência pode gerar insatisfação, filas excessivas e problemas logísticos nas agências no INSS  |
| Sinônimo(s) | Marcar horário, reservar horário |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div>



## Referência bibliográfica 

> [1] SAYÃO, M.; DE CARVALHO, G. Construção do léxico de aplicações. 4th Workshop in Information and Human Language Technology (TIL’2006). 2006. Disponível em: <http://www.nilc.icmc.usp.br/til/til2006/0030.pdf>. Acesso em: 03 dez. 2024.


## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. s.d. Slide 13-20 de 35. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 02 dez. 2024.

>
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|03/12/2024|Criação do documento e adição dos léxicos agendar|[Júlia Fortunato](https://github.com/julia-fortunato)|[](https://github.com/)|
