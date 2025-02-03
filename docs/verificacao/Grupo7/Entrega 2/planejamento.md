# Planejamento da Verificação da Etapa 2 do Grupo 6 (2024.2) - Meu INSS

## Introdução

A verificação e validação (V&V) são etapas essenciais no ciclo de desenvolvimento e de vida de um software, que efetivamente dá suporte para a qualidade e a confiabilidade dos artefatos construídos. A verificação consiste em uma análise criteriosa dos artefatos, assegurando que estejam em conformidade com os requisitos estabelecidos e os padrões técnicos necessários.

Neste contexto, este documento tem como propósito realizar a verificação da [segunda entrega](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/Perfil_Do_Usuario/) do Grupo 6, que desenvolveu artefatos ligados ao aplicativo do Meu INSS na disciplina de Requisitos de Software, na Universidade de Brasília, no período do segundo semestre de 2024.

## Objetivos

O propósito deste documento é realizar uma verificação minuciosa dos artefatos desenvolvidos pelo Grupo 6 durante a etapa 2, que diz respeito a etapa de elicitação de Requisitos. 

O objetivo é assegurar que esses artefatos estejam em plena conformidade com o conteúdo estabelecidos na disciplina de Requisitos de Software, bem como em alinhamento com os padrões consagrados na literatura utilizada e estudada pela equipe. 

Essa análise visa garantir a qualidade e a aderência às melhores práticas, o que contribui para o desenvolvimento de artefatos corretos para o projeto.

## Metodologia

A metodologia utilizada para a verificação dos artefatos é a desenvolvida por Michael E. Fagan [1], que prega uma abordagem de revisão de artefatos de software. Dessa forma, espera-se identificar e corrigir os eventuais problemas encontrados durante a verificação realizada. A inspeção de Fagan é nitidamente sistemática.

O foco desta inspeção é focar em:

  - Preparação: estudo sobre os artefatos a serem analisados; 
  - Inspeção Individual: criação e aplicação de lista de inspeção;
  - Correção e Reinspeção: correções de problemas encontrados;
  - Revisão da Inspeção: revisão dos resultados encontrados pela verificação (que será realizada por um membro do grupo, que não seja o responsável pela própria inspeção).

A inspeção será disponibilizada em paginas dessa documentação com links abaixo.

## Participantes

A integrante da equipe responsável pela verificação da Etapa 2 foi [Maurício Ferreira](https://github.com/mauricio-araujoo). Foi feita uma verificação por meio das listas de inspeção e verificação dos artefatos construídos na Entrega 2. A revisão da verificação da Entrega 2 foi realizada pelo integrante [Júlia Fortunato](https://github.com/julia-fortunato).

## Objetos de verificação

Nesta etapa, serão verificados os artefatos construídos pela equipe presentes na Tabela 1

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1 - </b> Tabela de artefatos produzidos na Entrega 2 </p></font>
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
                <td>Perfil de usuário</td>
                <td>1.0</td>
                <td>23/11/2024</td>
                <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
            </tr>
            <tr>
                <td>Personas</td>
                <td>1.0</td>
                <td>20/11/2024</td>
                <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
            </tr>
            <tr>
                <td>Encenação</td>
                <td>1.0</td>
                <td>22/11/2024</td>
                <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
            </tr>
            <tr>
                <td>Entrevista</td>
                <td>1.1</td>
                <td>23/11/2024</td>
                <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a></td>
            </tr>
            <tr>
                <td>Introspecção</td>
                <td>1.0</td>
                <td>23/11/2024</td>
                <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a></td>
            </tr>
            <tr>
                <td>Observação</td>
                <td>1.0</td>
                <td>23/11/2024</td>
                <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
            </tr>
            <tr>
                <td>Glosário</td>
                <td>1.1</td>
                <td>22/11/2024</td>
                <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
            </tr>
            <tr>
                <td>First Things First</td>
                <td>1.0</td>
                <td>24/11/2024</td>
                <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
            </tr>
            <tr>
                <td>Three Level Scale</td>
                <td>1.0</td>
                <td>24/11/2024</td>
                <td><a href="https://github.com/mauricio-araujoo">Maurício Ferreira</a></td>
            </tr>
            <tr>
                <td>$100</td>
                <td>1.0</td>
                <td>24/11/2024</td>
                <td><a href="https://github.com/nickgehjk">Nicolas Bomfim</a></td>
            </tr>
        </tbody>
    </table>
    <font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

## Listas de verificação

### Lista de verificação para itens de padronização e desenvolvimento do projeto

Na Tabela 2, estão listados os critérios gerais que devem ser verificados em todos os artefatos da Entrega 2 do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2 -</b> Lista de verificação para itens de padronização e desenvolvimento do projeto</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui histórico de versão padronizado?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 01 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>2</td>
      <td>O(s) autor(es) e o(s) revisor(es) estão presentes para cada artefato?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 01 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>3</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 01 de fevereiro de 2025. </td>
      <td><img src="../imagens/planoensino.png"></td>
    </tr>
    <tr>
      <td>4</td>
      <td>As tabelas e imagens possuem legenda e fonte/autor e elas chamadas dentro dos texto?</td>
      <td>SALES, André. Plano de Ensino de Requisitos de Software (UnB) 2024.2. 2024. Disponível em: <a href="https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/53/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf">Plano de Ensino - REQ (2024.2)</a>. Acesso em: 01 de fevereiro de 2025. </td>
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

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para Perfil de Usuarios

Na tabela 3, estão listados os critérios que devem ser verificados no artefato [Perfil de usuário](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/Perfil_Do_Usuario/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3 -</b> Lista de verificação para o artefato Casos de Uso</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>uma descrição detalhada das características dos usuários cujos objetivos serão apoiados pelo sistema a ser projetado? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>faixa etária dos usuários? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>a experiência dos usuários? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>nível de instrução dos usuários? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>frequência de uso/afinidade com a tecnologia? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para personas

Na tabela 4, estão listados os critérios que devem ser verificados no artefato [Personas](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/personas/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4 -</b> Lista de verificação para o artefato Personas</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>nome, sobrenome e dados demográficos que são importantes para o domínio da aplicação? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>o seu status (como primária, secundária, stakeholder ou antipersona)? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td> seus objetivos (que também pode incluir objetivos fora do domínio da aplicação)? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td> habilidades, especialidades? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>o grau de afinidade com tecnologia? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/julia-fortunato"> Júlia Fortunato</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para encenação

Na tabela 5, estão listados os critérios que devem ser verificados no artefato [Encenação](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/encenacao/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5 -</b> Lista de verificação para o artefato Encenação</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>personas bem definidas? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>uso de roteiro bem estruturado de entrevista? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>roteiro previamente pensado? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Objetivo da encenação bem apresentado? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>papeis bem definidos(persona, entrevistador e revisor)? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para entrevista

Na tabela 6, estão listados os critérios que devem ser verificados no artefato [Entrevista](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/entrevista/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6 -</b> Lista de verificação para o artefato Entrevista</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Na entrevista , caso seja estruturada ou semiestruturada, havia um roteiro com perguntas/tópicos previamente pensados? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Existiu uma análise posterior em relação ao objetivo da entrevista? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Houve uma apresentação e explicação em relação ao objetivo da entrevista? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>A terminologia utilizada na entrevista permitiu a plena compreensão por parte do entrevistado? </td>
      <td>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 8.1 Perfil do usuário, p. 165-167. Autopublicação. ISBN: 978-65-00-19677-1.</td>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para introspecção

Na tabela 7, estão listados os critérios que devem ser verificados no artefato [Introspecção](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/introspeccao/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 7 -</b> Lista de verificação para o artefato Introspecção</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Metas/tarefas a serem executadas no contexto do sistema? </td>
      <td>Slide 25 da Aula 07 da Professora Milene Serrano. Disponível em:
https://aprender3.unb.br/mod/resource/view.php?id=1305268 - Acesso em 23 de janeiro de 2025.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Utilização de personas para melhor cenário? </td>
      <td>Slide 25 da Aula 07 da Professora Milene Serrano. Disponível em:
https://aprender3.unb.br/mod/resource/view.php?id=1305268 - Acesso em 23 de janeiro de 2025.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Cenário hipotético para execução das metas? </td>
      <td>Slide 25 da Aula 07 da Professora Milene Serrano. Disponível em:
https://aprender3.unb.br/mod/resource/view.php?id=1305268 - Acesso em 23 de janeiro de 2025.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para observação

Na tabela 8, estão listados os critérios que devem ser verificados no artefato [Observação](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/observacao/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8 -</b> Lista de verificação para o artefato Observação</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>a tarefa/aplicação a ser observada está bem definida? </td>
      <td> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 24 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>realização sem a interferência dos observadores no ambiente? </td>
      <td> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 24 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>registro dos requisitos de acordo com a observação das tarefas realizadas? </td>
      <td> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 24 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td> conclusões claras sobre os resultados alcançados pela técnica? </td>
      <td> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 24 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>papel (responsabilidade) dos participantes foram devidamente identificados? </td>
      <td> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 24 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para glossario

Na tabela 9, estão listados os critérios que devem ser verificados no artefato [Glossario](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/glossario/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 9 -</b> Lista de verificação para o artefato Glossario</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>termos bem claros e definidos? </td>
      <td> SOUZA, Nicolas. Glossário do Lichess. 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/glossario/]. Acesso em: 02 jan. 2025. VÁZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>possui participação de usuários/personas? </td>
      <td> SOUZA, Nicolas. Glossário do Lichess. 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/glossario/]. Acesso em: 02 jan. 2025. VÁZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>estruturação para facil consulta? </td>
      <td> SOUZA, Nicolas. Glossário do Lichess. 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/glossario/]. Acesso em: 02 jan. 2025. VÁZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>uso de linguagem acessível e padronizada? </td>
      <td> SOUZA, Nicolas. Glossário do Lichess. 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/glossario/]. Acesso em: 02 jan. 2025. VÁZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Integração com outras técnicas de elicitação? </td>
      <td> SOUZA, Nicolas. Glossário do Lichess. 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/glossario/]. Acesso em: 02 jan. 2025. VÁZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para First Things First

Na tabela 10, estão listados os critérios que devem ser verificados no artefato [First Things First](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/first_things_first/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 10 -</b> Lista de verificação para o artefato First Things First</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>a consideração de requisitos funcionais e não funcionais, ou seja, ambos estão sendo priorizados?  </td>
      <td>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 38 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>a utilização da escala de 1 a 9 para benefício?  </td>
      <td>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 38 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>a utilização da escala de 1 a 9 para penalidade?  </td>
      <td>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 38 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>a utilização da escala de 1 a 9 para risco?  </td>
      <td>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 38 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>a utilização da escala de 1 a 9 para custo?  </td>
      <td>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 38 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>o valor total calculado e apresentado da forma correta?  </td>
      <td>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. s.d. Slide 38 de 50. Disponível em:https://aprender3.unb.br/pluginfile.php/2972455/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23 jan. 2025.</td>
      <td><a href="https://github.com/julia-fortunato">Júlia Fortunato</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para Three Level Scale

Na tabela 11, estão listados os critérios que devem ser verificados no artefato [Three Level Scale](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/three_level_scale/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 11 -</b> Lista de verificação para o artefato Three Level Scale</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>A priorização considerou o risco de sobrecarga com requisitos de alta prioridade?  </td>
      <td>WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.</td>
      <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Houve uma revisão para dividir esses requisitos em subcategorias, garantindo que apenas os mais urgentes fossem destacados para seguir com a sua produção?  </td>
      <td>WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.</td>
      <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Os stakeholders estão alinhados quanto ao que significa "importante" e "urgente" no contexto dos requisitos do projeto?  </td>
      <td>WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.</td>
      <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>As dependências entre os requisitos foram analisadas para evitar que requisitos de alta prioridade sejam adiados devido a dependências de menor prioridade?  </td>
      <td>WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.</td>
      <td><a href="https://github.com/an4catarina">Ana Catarina</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

### Lista de verificação para $100

Na tabela 12, estão listados os critérios que devem ser verificados no artefato [$100](https://requisitos-de-software.github.io/2024.2-MeuINSS/elicitacao/100dol/) do Grupo 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 12 -</b> Lista de verificação para o artefato $100</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>tecnica realizada com um usuario/persona?  </td>
      <td>WIEGERS, Karl; Beatty, Joy. (2013) Software Requirements (Developer Best Practices). p. 319-320. ISBN: 0735679665.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>entendimento dos limites de 100 dolares bem definido?  </td>
      <td>WIEGERS, Karl; Beatty, Joy. (2013) Software Requirements (Developer Best Practices). p. 319-320. ISBN: 0735679665.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>quantia de acordo com a quantidade de requisitos elicitados?  </td>
      <td>WIEGERS, Karl; Beatty, Joy. (2013) Software Requirements (Developer Best Practices). p. 319-320. ISBN: 0735679665.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>importancia dos requisitos definida sem interferencia dos desenvolvedores?  </td>
      <td>WIEGERS, Karl; Beatty, Joy. (2013) Software Requirements (Developer Best Practices). p. 319-320. ISBN: 0735679665.</td>
      <td><a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Autor:<a href="https://github.com/mauricio-araujoo">Mauricio Ferreira</a>, 2025</p></font>
</div>

## Bibliografia

> ZARANZA, Gabriel; ROSA, Gabriel. Perfil de usuário - Economia DF. 2023. Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/perfil_usuario/]. Acesso em: 23 nov. 2024.

## Histórico de versões

| Versão | Data   | Descrição     | Autor     |  Revisor        |
| :----: | ------ | ------------- | --------- | :-------------: |
| `1.0`  | 02/02/2025 | Criação do documento  | [Maurício Ferreira](https://github.com/mauricio-araujoo) | [Júlia Fortunato](https://github.com/julia-fortunato) |