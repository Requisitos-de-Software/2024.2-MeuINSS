## Introdução

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">Para a utilização da técnica conhecida como First Things First se faz necessário a observação e análise meticulosa do quão benéfico e custoso um determinado requisito será para o software, além disso também é considerado o custo de recursos e o risco para a produção do requisito, com isso é possível se ter uma dimensão dos impactos arquiteturais no sistema com sua implementação. Através da definição do benefício, penalidade, custo e risco se quantifica uma prioridade para cada um dos requisitos funcionais e não funcionais de um projeto afim de ordená-los em uma hierarquia de implementação, essa hierarquia maximiza o lucro e minimiza o risco.[1]</p>

## Metodologia

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">No dia 24/11, por volta de 13 horas da tarde, foi realizada uma reunião via Microsoft Teams, no qual o objetivo era quantificar os benefícios, penalidades, riscos e custos de todos os requisitos que haviam sido elicitados através das técnicas de elicitação escolhidas pelo grupo. Nessa reunião participaram três membros do grupo, são eles: <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a> (realizou o papel do desenvolvedor); <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira </a>(realizou o papel de persona); <a href="https://github.com/julia-fortunato">Julia Fortunato</a> (realizou o papel de mediadora). É possível observar a relação na tabela 1:</p>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Membros participantes</p></font>

<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Papel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
      <td>Desenvolvedor</td>
    </tr>
    <tr>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira </a></td>
      <td>Persona</td>
    </tr>
    <tr>
      <td><a href="https://github.com/julia-fortunato">Julia Fortunato</a></td>
      <td>Mediadora</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Autores:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, <a href="https://github.com/julia-fortunato">Julia Fortunato</a>, 2024</p></font>
</div>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">Nessa reunião a mediadora falou, de forma sequencial, os requisitos que haviam sido elicitados para o desenvolvedor e a persona. A cada requisito dito os dois últimos deveriam quantificar da seguinte maneira:</br></br>

• O desenvolvedor deveria associar valores de 1 até 9 em cada requisito para os critérios de custo (sendo 1 pouco custo e 9 muito custo para a produção), como também para risco (sendo 1 pouco risco e 9 muito risco).</br></br>

• A persona deveria fazer o mesmo processo que o desenvolvedor, porém em vez de avaliar os critérios de custo e risco ele avaliaria para os critérios de benefício (sendo 1 pouco benéfico e 9 muito benéfico de ser implementado), como também para a penalidade (sendo 1 pouca penalidade e 9 muita penalidade caso não seja implementado).</br></br>

Após esse processo e com os valores obtidos foi possível quantificar a prioridade para cada um dos requisitos julgados anteriormente, os cálculos foram feitos da seguinte forma:</br></br>
</p>

> <p align="center" style="font-size: 18px;">`valor total = (benefício * peso) + (penalidade * peso)`</p>
> <p align="center" style="font-size: 18px;">`Custo(%) = (Custo Relativo/Somatório dos custos)*100`</p>
> <p align="center" style="font-size: 18px;">`Risco(%) = (Risco relativo/Somatório dos Riscos)*100`</p>
> <p align="center" style="font-size: 18px;">`Valor(%) = (Valor relativo/Somatório dos valores)*100`</p>
> <p align="center" style="font-size: 18px;">`prioridade = valor(%)/(custo(%) * peso do custo + risco(%) * peso do risco)`</p>

<div align="center">
  <font size="4"><p style="text-align: center; margin-bottom: 50px;"><b>Figura 1: Tabela de resultados na priorização da técnica First Things First</b></p></font>
</div>

<div align="center">
    <img src="../../imagens/first.svg" alt="Foto de Maria das Dores" style=" max-width: 100%; height: auto; margin-bottom: 20px;">
</div>
<div align="center">
    <p style="text-align: center"><b>Autores:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, <a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, <a href="https://github.com/julia-fortunato">Julia Fortunato</a>, 2024</p></font>
</div> 

## Link da Gravação

No vídeo 1, encontra-se a gravação da técnica de priorização First Things First.

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/9w-MqIKbH5E?si=XkoNGeEM2h24SeqS" target="blanket"><b>Vídeo 1:</b> Grupo 06 - First Things First</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/9w-MqIKbH5E?si=XkoNGeEM2h24SeqS" title="Apresentação 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >


## Referência bibliográfica
> [1] FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

## Bibliografia

> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.
>
> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 37-40 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 24 nov. 2024.

## Histórico de versões 

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|24/11/2024|Criação do documento. |[](https://github.com/)|[](https://github.com/)|