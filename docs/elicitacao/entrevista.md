## Introdução

A entrevista é uma das técnicas de elicitação mais utilizadas. Nesse quesito,
participam os stakeholders e a equipe responsável pela produção do produto de
software. Então, são formuladas questões que podem trazer requisitos do sistema.
As entrevistas podem ser fechadas, no qual as perguntas já são bem
definidas e as possibilidades de respostas já são especificadas, ou podem ser
abertas, ou seja, existe um roteiro pré-definido de questões, mas que pode sofrer
alterações e também compreende uma ampla maior de respostas. Isso aproxima o
engenheiro de requisitos dos stakeholders, o que tem impacto positivo no
desenvolvimento do sistema.


## Metodologia

A técnica para a elicitação de requisitos foi utilizada de forma que um membro da equipe, no caso [Maurício Ferreira](https://github.com/mauricio-araujoo) entrevistou uma usuária do app do Meu INSS. É importante frizar que o usuário a ser entrevistado não deveria ser alguém próximo ao entrevistador, como um parente.
A entrevista primeira ocorreu de forma presencial, no dia 21/11/2024 por volta das 20:10. A segunda também ocorreu presencialmente, no dia 23/11/2024 por volta das 16:30. Na tabela 1, encontram-se as informações sobre os participantes. 

## Roteiro da entrevista 

**Modelo: semi-estruturado**

**Primeiro momento:** Apresentação e explicação da entrevista

**Segundo momento:** Perguntas
1. Quem você imagina que usa este aplicativo?

2. Quais são os cenários, situações, mais comuns que você acredita que este app é usado no dia a dia?
3. Qual é a sua maior dificuldade usando o app atualmente?
4. Existe alguma funcionalidade que te frustra ou que você acha que deva melhorar?
5. Acha que falta algo no funcionamento atual do app?
6. O que acha que iria melhorar a experiência do usuário se fosse adicionado?

PERGUNTAS DINÂMICAS

7. Desses usuários, quem você imagina que teriam uma maior dificuldade no uso?

8. Eles possuem necessidades diferentes ao seu ver?
9. Você acha que tem uma funcionalidade que é menos usada no aplicativo?
10. Se você pudesse melhorar somente uma área do aplicativo, qual seria?

**Terceiro momento:** Finalização e despedida

O autor do roteiro da entrevista foi o membro [Maurício Ferreira](https://github.com/mauricio-araujoo).

## Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
| [Maurício Ferreira](https://github.com/mauricio-araujoo)  | Entrevistador              |
| [Júlia Fortunato](https://github.com/julia-fortunato) | Secretária (de forma remota) |

</center>

<font size="3"><p style="text-align: center">Autor: [Júlia Fortunato](https://github.com/julia-fortunato), 2024</p></font>

## Link da Gravação

No vídeo 1, encontra-se a gravação da entrevista 1.

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/HTQTsxcaGAQ?si=cQFV-A5DwJRkLltP" target="blanket"><b>Vídeo 1:</b> Grupo 06 - Entrevista 1</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/HTQTsxcaGAQ?si=cQFV-A5DwJRkLltP" title="Apresentação 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

No vídeo 2, encontra-se a gravação da entrevista 2.

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/t2IvAXEtFlQ?si=nAJLZX_nRyrAFRB1" target="blanket"><b>Vídeo 2:</b> Grupo 06 - Entrevista 2</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/t2IvAXEtFlQ?si=nAJLZX_nRyrAFRB1" title="Apresentação 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

## Requisitos elicitados

Nesta seção, apresentamos os requisitos que foram elicitados ao utilizar a técnica de elicitação de entrevista.

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ENTx: Requisito nºx elicitado pela entrevista.

### Funcionais

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais</p></font>

<center>

| Tipo | Descrição                                                                                                             | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RF05 | O aplicativo permite simular aposentadoria.                                                                            | ENT01                                                  | Sim          |
| RF06 | O aplicativo permite solicitar auxílio doença.                                                                             | ENT02                                                  | Sim          |
| RF07 | O aplicativo permite verificar extratos e comprovantes de pagamentos.                                                | ENT03                                                  | Sim          |
| RF08 | O aplicativo permite verificar previsão de pagamento.                                 | ENT04                                                  | Sim          |
| RF09 | O aplicativo deve possuir filtro de pesquisa assertivo.                                 | ENT05                                                  | Não          |
| RF10 | O aplicativo deve possuir suporte adequado.                                 | ENT06                                                 | Não          |
| RF11 | O aplicativo deve ser claro com relação a especificação para auxílios doenças e as modalidades de análise (online ou presencial).                                 | ENT07                                                 | Não          |
| RF12 | O aplicativo deve avisar sobre mudanças e notícias sobre legislação previdenciária.                                | ENT08                                                 | Não          |
| RF13 | O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício.                                | ENT09                                                 | Não          |

</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>

### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais</p></font>

<center>

| Tipo  | Descrição                                                                                                                                                                       | <a id="anchor_OBSNF" style="visibility: hidden;"></a>ID | Implementado |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------ |
| RNF05 | O aplicativo deve possuir, além de termos técnicos, nomenclaturas populares para as funcionalidades do INSS.                                                                  | ENT10                                                   | Não          |
| RNF06 | O aplicativo deve facilitar a realização de tarefas e funcionalidades.                                                                 | ENT11                                                   | Não          | 
| RNF07 | O aplicativo deve facilitar a busca de tarefas e funcionalidades.                                                               | ENT12    | Não          | 
| RNF08 | O aplicativo deve possuir interface intuitiva.                                                               | ENT13 | Não          | 
| RNF09 | O aplicativo deve possuir tutoriais de uso (vídeos explicativos).                                                             | ENT14                                                 | Não          |
| RNF10 | O aplicativo deve ser acessível a todos os usuários.                                                            | ENT15                                                 | Não          |


</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>


## Bibliografia

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 7.5.1 Entrevistas, p 144-148. Autopublicação. ISBN: 978-65-00-19677-1.

>  SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 22 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 20 nov. 2024.

## Histórico de versões 

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|22/11/2024|Criação do documento|[Júlia Fortunato](https://github.com/julia-fortunato)|[Nicolas Bomfim](https://github.com/nickgehjk)|
|`1.1`|23/11/2024|Adição da segunda entrevista|[Júlia Fortunato](https://github.com/julia-fortunato)|[Nicolas Bomfim](https://github.com/nickgehjk)|