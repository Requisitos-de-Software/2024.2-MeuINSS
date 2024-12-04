# Cenários

## Introdução

O cenário, para modelagem de requisitos, é uma estratégia utilizada para a compreensão das interações entre ambientes e sistemas da aplicação, como elicitar a parte comportamental do software para determinadas ações, com sua dinâmica e fluxo. Também auxiliam na relação que é, eventualmente, estabelecida entre requisitos funcionais e não funcionais em uma aplicação de software [1].

## Metodologia

A elaboração dos cenários foi realizada a partir de requisitos que foram [elicitados](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/) pela equipe anteriormente. Como foi solicitado na disciplina, cada integrante do grupo trabalhou com um requisito funcional não implementado e desenvolveu os artefatos para ele. A relação entre os integrantes e os cenários trabalhados/desenvolvidos pode ser encontrada na Tabela 1.

A estrutura para a eloração dos cenários foi feita de acordo com as abstrações específicas que esse artefato deve possuir [1]. São elas:

- título: o título do cenário;
- objetivo: o objetivo, uma meta, a ser alcançado pela tarefa;
- contexto: descreve a localização geográfica e o estado inicial da tarefa;
- recursos: recursos, bem como meios de apoio e dispositivos, que necessitam estar disponíveis para o cenário ser efetivado;
- atores: pessoa que realiza a tarefa descrita no cenário;
- episódios: frases que descrevem como o cenário acontece e seu comportamento, ações;
- restrição: características que o cenário deve seguir;
- exceção: situações que impedem a realização do cenário.
<br>


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Definição do integrante da equipe que desenvolveu determinado cenário</p></font>

<table>
  <thead>
    <tr>
      <th>Membro da Equipe</th>
      <th>Cenário</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
      <td><a href="https://">-</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
      <td><a href="https://github.com/">-</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
      <td><a href="https://requisitos-de-software.github.io/2024.2-MeuINSS/modelagem_parte1/cenarios/#cen01-agendar-horario-em-uma-agencia-do-inss">Agendar horário em uma agência do INSS</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a></td>
      <td><a href="https://github.com/">-</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/nickgehjk">Nicolas Bonfim</a></td>
      <td><a href="https://github.com/">-</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div>

## Cenários

### CEN01 - Agendar horário de atendimento em uma agência do INSS

O cenário a seguir diz respeito ao objetivo "Agendar horário de atendimento em uma agência do INSS", sua descrição detalhada pode ser encontrada na tabela 2, com todas as abstrações específicas necessárias para o entendimento da tarefa em questão.

Rastreabilidade: [RF28](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/requisitos_elicitados/)

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Cenário referente ao objetivo "Agendar horário em uma agência do INSS" </p></font>
</div>

| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Agendar um horário em uma agência do INSS através do aplicativo Meu INSS            |
| Contexto    | Local: em casa, por meio do aplicativo Meu INSS<br>Tempo: Aproximadamente 3 minutos<br> Pré-condições: existir uma agência do INSS próxima ao CEP informado |
| Recursos    | Internet<br>Smartphone<br>Aplicativo do Meu INSS instalado                           |
| Atores      | Usuário brasileiro com CPF ativo que contribui, ou contribuia (durante o tempo de trabalho ativo) com o INSS                                                 |
| Episódios   | O *usuário* seleciona a opção Agendar um horário de atendimento em uma agência do INSS no menu lateral<br>O aplicativo exibe uma tela na qual o usuário pode informar o seu CEP<br>O *usuário* informa o seu CEP<br> O aplicativo informa agências pŕoximas aquele endereço<br>O *usuário* seleciona a agência em que deseja ser atendido <br> O aplicativo mostra as datas e horários disponíveis para atendimento <br> O *usuário* escolhe a data e horário e confirma o agendamento |
| Restrição   |      O agendamento deve ser realizado com pelo menos 24 horas de antecedência em relação à data do atendimento desejado                  |
| Exceção     | Erro de conexão com a internet <br> Todas as datas e horários disponíveis para a agência selecionada estão indisponíveis       (agência lotada)  |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div>

### CEN02 - 



### CEN03 - 



### CEN04 - 



### CEN05 - 



## Referência Bibliográfica
> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. s.d. Slide 8-11 de 35. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 02 dez. 2024.

## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. s.d. Slide 8-11 de 35. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 02 dez. 2024.
>
> Bilheteria Digital. Cenários. Grupo Bilheteria Digital da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em: 03 de dezembro de 2024.
>
> Economia - DF. Cenários. Grupo Economia DF da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em: 03 de dezembro de 2024.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|03/12/2024|Criação de documento e adição do cenário sobre "agendar horário em uma agência do INSS"|[Júlia Fortunato](https://github.com/julia-fortunato)|[](https://github.com/)|