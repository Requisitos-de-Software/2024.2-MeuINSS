# Planejamento da Verificação da Etapa 6 do Grupo 7 (2024.2) - Threads

## Introdução

A verificação e validação (V&V) são etapas essenciais no ciclo de desenvolvimento e de vida de um software, que efetivamente dá suporte para a qualidade e a confiabilidade dos artefatos construídos. A verificação consiste em uma análise criteriosa dos artefatos, assegurando que estejam em conformidade com os requisitos estabelecidos e os padrões técnicos necessários.   

Neste contexto, este documento tem como propósito realizar a verificação da entrega [Pós rastreabilidade](https://requisitos-de-software.github.io/2024.2-Threads/Rastreabilidade/backwardFrom/) do Grupo 7, que desenvolveu artefatos ligados ao aplicativo Threads na disciplina de Requisitos de Software, na Universidade de Brasília, no período do segundo semestre de 2024.

## Objetivos

O propósito deste documento é realizar uma verificação minuciosa dos artefatos desenvolvidos pelo Grupo 7 durante a etapa 4, que diz respeito a segunda etapa de Pós rastreabilidade. 

O objetivo é assegurar que esses artefatos estejam em plena conformidade com o conteúdo estabelecidos na disciplina de Requisitos de Software, bem como em alinhamento com os padrões consagrados na literatura utilizada e estudada pela equipe. 

Essa análise visa garantir a qualidade e a aderência às melhores práticas, o que contribui para o desenvolvimento de artefatos corretos para o projeto.

## Metodologia

A metodologia utilizada para a verificação dos artefatos é a desenvolvida por Michael E. Fagan [1], que prega uma abordagem de revisão de artefatos de software. Dessa forma, espera-se identificar e corrigir os eventuais problemas encontrados durante a verificação realizada. A inspeção de Fagan é nitidamente sistemática.

O foco desta inspeção é focar em:

  - Preparação: estudo sobre os artefatos a serem analisados; 
  - Inspeção Individual: criação e aplicação de lista de inspeção;
  - Correção e Reinspeção: correções de problemas encontrados;
  - Revisão da Inspeção: revisão dos resultados encontrados pela verificação (que será realizada por um membro do grupo, que não seja o responsável pela própria inspeção).

A inspeção será gravada e disponibilizada na página de documentação de cada artefato citado neste documento.

## Participantes

O integrante da equipe responsável pela verificação da Etapa 6 foi [Nicolas Bomfim](https://github.com/nickgehjk). Foi feita uma verificação por meio das listas de inspeção e verificação dos artefatos construídos na Entrega 6. A revisão da verificação da Entrega 4 foi realizada pelo integrante [Ana Catarina Santos](http://github.com/an4catarina).

## Objetos de verificação

Nesta etapa, serão verificados os artefatos construídos pela equipe presentes na Tabela 1

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1 - </b> Tabela de artefatos produzidos na Entrega 6 </p></font>

<table>

<thead>
    <tr>
        <th>Artefato</th>
        <th>Versão</th>
        <th>Data</th>
        <th>Autor</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td> <a href="https://requisitos-de-software.github.io/2024.2-Threads/Rastreabilidade/matrizdeRastreabilidade/">Matriz de rastreabilidade</a> </td>
        <td> 1.0 </td>
        <td> 19/01/2025</td>
        <td> Alana Gabriele </td>
    <tr>
        <td> <a href="https://requisitos-de-software.github.io/2024.2-Threads/Rastreabilidade/backwardFrom/">Backward-From</a> </td>
        <td> 1.4 </td>
        <td> 19/01/2025 </td>
        <td> Genilson Silva </td>
    </tr>
    <tr>
        <td> <a href="https://requisitos-de-software.github.io/2024.2-Threads/Rastreabilidade/forwardFrom/">Forward-From</a> </td>
        <td> 1.2 </td>
        <td> 19/01/2025 </td>
        <td> Alana Gabriele </td>
    </tr>
</tbody>
</table>

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2025</p></font>
</div>

## Listas de verificação

Nesta etapa, serão apresentadas listas de verificação para os artefatos construídos na Entrega 6, que deve ser aplicado a todos os artefatos, e um checklist específico para cada artefato. As questões disponíveis no checklist devem ser respondidas com "Sim", "Não", "Incompleto" ou "Não se aplica", que indica a confirmidade do item no artefato a ser analisado em questão. Os itens devem possuir referência, e uma foto dela sempre que possível.

Se forem feitas observações, elas aparecerão ao final da tabela ao qual se refere.

### Lista de verificação para itens de padronização e desenvolvimento do projeto

Na Tabela 2, estão listados os critérios gerais que devem ser verificados em todos os artefatos da Entrega 6 do Grupo 7.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2 -</b> Lista de verificação para itens de padronização e desenvolvimento do projeto</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui histórico de versão padronizado?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 03 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>2</td>
      <td>O(s) autor(es) e o(s) revisor(es) estão presentes para cada artefato?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 03 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>3</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 03 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>4</td>
      <td>As tabelas e imagens possuem legenda e fonte/autor e elas chamadas dentro dos texto?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 03 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>5</td>
      <td>O artefato possui um texto fazendo introdução dele?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf"> Plano de Ensino - REQ (2024.2)</a>. Acesso em: 01 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2025</p></font>
</div>

### Lista de verificação para Matriz de rastreabilidade

Na tabela 3, estão listados os critérios que devem ser verificados no artefato [Matriz de rastreabilidade](https://requisitos-de-software.github.io/2024.2-MeuINSS/rastreabilidade/matriz/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3 -</b> Lista de verificação para o artefato Matriz de rastreabilidade</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Estão identificados os artefatos gerados pelos requisitos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/M1.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Os elos estão corretamente associados aos requisitos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/M2.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>A matriz possui alguma legenda para identificação dos termos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Os requisitos estão rastreáveis?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Os requisitos estão ligados aos artefatos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/M5.png"></td>
      <td><a href="https://github.com/nickgehjk"> Nicolas Bomfim </a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>Hyperlinks para os elos de cada requisito?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td></td>
      <td><a href="https://github.com/mauricio-araujoo"> Maurício Ferreira </a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2025</p></font>
</div>

### Lista de verificação para Backward-From

Na Tabela 4, estão listados os critérios gerais que devem ser verificados no artefato de [Backward-From](https://requisitos-de-software.github.io/2024.2-MeuINSS/rastreabilidade/backward-from/) da Entrega 3 do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4 - </b> Lista de verificação para o artefato Backward-From</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O Backward-From está referenciando as fontes dos requisitos? </td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B1.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Estão identificados os tipos de elos dos requisitos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B2.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Existem descrições dos elos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B3.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Cada elo está identificado de alguma forma como, por exemplo, um ID?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B4.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Os requisitos estão vinculados corretamente à sua origem?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B5.png"></td>
      <td><a href="https://github.com/an4catarina"> Ana Catarina Santos </a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>A metodologia referencia o Meta-modelo proposto por Toranzo?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B6.png"></td>
      <td><a href="https://github.com/an4catarina"> Ana Catarina Santos </a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>As informações rastreadas estão classificadas nos níveis: ambiental, organizacional, gerencial e desenvolvimento?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/B7.png"></td>
      <td><a href="https://github.com/an4catarina"> Ana Catarina Santos </a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2025</p></font>
</div>

### Lista de verificação para Forward-From

Na Tabela 5, estão listados os critérios gerais que devem ser verificados no artefato de [Forward-From](https://requisitos-de-software.github.io/2024.2-MeuINSS/rastreabilidade/foward/) da Entrega 3 do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5 - </b> Lista de verificação para o artefato Forward-From</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Os artefatos e documentos produzidos a partir dos requisitos estão identificados?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/F1.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Estão identificados os tipos de elos dos requisitos?</td>
      <td>Slides da Aula 26 da Professora Milene Serrano. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf"> Aula 26 </a> Acesso em: 03 fevereiro 2025.</td>
      <td><img src="../imagens/F2.png"></td>
      <td><a href="https://github.com/CristianoMoraiss"> Cristiano Morais </a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/nickgehjk">Nicolas Bomfim</a>, 2025</p></font>
</div>

## Referências bibliográficas

> [1] FAGAN, Michael E. Design and Code Inspections to Reduce Errors in Program Development. 1976.

## Bibliografia

>
> Economia - DF. Planejamento da Verificação da Entrega 6 do Grupo 1. Grupo Economia DF da disciplina Requisitos de Software, disponível em: <https://requisitos-de-software.github.io/2023.2-Economia-DF/verificacao/Grupo-01/Entrega-06/planejamento-verificacao-e6-grupo1/>. Acesso em: 03 de fevereiro de 2025.
>
> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. s.d. Slide 8-11 de 35. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>. Acesso em:  03 de fevereiro de 2025.
>
> SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf>. Acesso em: 03 de fevereiro de 2025.

## Histórico de versões

| Versão | Data   | Descrição     | Autor     |  Revisor        |
| :----: | ------ | ------------- | --------- | :-------------: |
| `1.0`  | 03/02/2025 | Criação do documento  | [Nicolas Bomfim](http://github.com/nickgehjk) | [Ana Catarina Santos](https://github.com/an4catarina) |