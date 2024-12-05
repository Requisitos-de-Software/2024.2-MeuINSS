# Observação

## <p style="margin-bottom: 50px;">Introdução</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 10px;">A técnica da observação é uma poderosa ferramenta para se realizar a elicitação de requisitos, se trata da obtenção de requisitos a partir de uma análise do comportamento do usuário realizando tarefas no ambiente do sistema. A partir dessa técnica é possível se compreender o contexto social e organizacional no qual determinado software está/será inserido.[1]</p>

## <p style="margin-bottom: 50px;">Metodologia</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 50px;">Para o aplicativo "Meu INSS" não foi possível realizar a observação com usuários externos ao grupo de desenvolvimento, entretanto foi executada a observação através de uma simulação com a persona Maria das Dores Silva de uso feita e gravada pela <a href="https://github.com/julia-fortunato">Julia Fortunato </a> tendo sido realizada no dia 23/11, posteriormente divulgou o vídeo que foi analisado pela <a href="https://github.com/an4catarina">Ana Catarina </a> como também pelo <a href="https://github.com/CristianoMoraiss">Cristiano Morais</a>, a análise do vídeo também foi realizada no dia 23/11. Os participantes e suas respectivas funções podem ser encontrados na tabela 1 enquanto que os requisitos que foram elicitados a partir dessa técnica podem ser encontrados nas tabelas 2 e 3.</p>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Membros participantes</p></font>

<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Função Realizada</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/an4catarina">Ana Catarina </a></td>
      <td>Observadora</td>
    </tr>
    <tr>
      <td><a href="https://github.com/CristianoMoraiss">Cristiano Morais</a></td>
      <td>Observador</td>
    </tr>
    <tr>
      <td><a href="https://github.com/julia-fortunato">Julia Fortunato </a></td>
      <td>Persona</td>
    </tr>
  </tbody>
</table>
<font size="3"><p style="text-align: center"><b>Autores:</b> <a href="https://github.com/CristianoMoraiss">Cristiano Morais, </a><a href="https://github.com/an4catarina">Ana Catarina, </a>2024</p></font>
</div>

## <p style="margin-bottom: 50px;">Gravação do uso do aplicativo</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/cpq_lHohonw?si=Z9uGCGZPEgtMUq6Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## <p style="margin-bottom: 50px;">Requisitos elicitados</p>

<p style="text-align: justify; text-indent: 50px; margin-bottom: 10px;">Legendas para as tabelas 2 e 3:</br></br>
• RFx: Requisito Funcional nºx </br> 
• RNFx: Requisito Não-Funcional nºx </br>
• OBSx: Requisito nºx elicitado pela observação.</br></p>

### <p style="margin-bottom: 50px;">Requisitos Funcionais</p>

Na tabela 2, encontram-se os requisitos funcionais elicitados pela técnica de observação.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais</p></font>

<center>

| Tipo | Descrição| <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RF21 | O sistema deve mascarar dados sensíveis, como CPF e número do benefício, exibindo apenas partes relevantes para preservar a privacidade do usuário. |OBS01|Não|
| RF22 | É possível o usuário verificar se está bloqueado para empréstimo.| OBS02 |Sim|
| RF23 | O sistema deve permitir que o usuário agende um horário em uma agência do INSS, escolhendo o serviço, horário, data e local diretamente no aplicativo. | OBS03 | Não |
| RF24 | O sistema deve calcular o valor das contribuições necessárias para atingir a aposentadoria ou outros benefícios.| OBS04 | Sim |
| RF25 | O usuário pode receber notificações relacionadas as tarefas que ele realizou no aplicativo.| OBS05|Sim|
| RF26 | O aplicativo deve permitir a geração de declarações, como comprovantes de recebimento de benefício ou regularidade de contribuições.| OBS06 | Sim|
| RF27 | O usuário pode visualizar os benefícios com maiores detalhes.|OBS07|Sim|
| RF28 | O usuário tem acesso a um calendário no aplicativo relacionado as suas atividades.| OBS08|Sim|


</center>

<font size="3"><p style="text-align: center"><b>Autor:</b><a href="https://github.com/CristianoMoraiss"> Cristiano Morais, </a><a href="https://github.com/an4catarina">Ana Catarina, </a>2024 </p></font>


### <p style="margin-bottom: 50px;">Requisitos Não Funcionais</p>

Na tabela 3, encontram-se os requisitos não funcionais elicitados pela técnica de observação.

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais</p></font>

<center>

| Tipo | Descrição| <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RNF11 | Garantir que o aplicativo seja acessível para pessoas com deficiência, com suporte a leitores de tela e navegação por teclado. |OBS10 |Não|
| RNF12 | O aplicativo possui compatibilidade para diversas plataformas.| OBS11 |Sim|
| RNF13 | O usuário tem recursos de ajuda como tutoriais/FAQ para a utilização do aplicativo .| OBS12 | Não |
| RNF14 | O aplicativo deve possuir interface intuitiva. |OBS13| Não |
| RNF15 | O aplicativo é criptografado.|OBS14| Sim|
| RNF16 | O sistema deve estar disponível para o usuário por no mínimo 99% do tempo de um mês, exceto em momentos de manutenção programada|OBS15| Sim|



</center>   

<font size="3"><p style="text-align: center"><b>Autor:</b><a href="https://github.com/CristianoMoraiss"> Cristiano Morais, </a><a href="https://github.com/an4catarina">Ana Catarina, </a>2024 </p></font>



## <p style="margin-bottom: 50px;">Referência bibliográfica</p>

> [1] SERRANO, Milene; SERRANO, Maurício. Elicitação, Modelagem e Análise - Aula 7. s.d. Slide 23 de 50. Disponível em: <a>https://aprender3.unb.br/pluginfile.php/2972449/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf</a>. Acesso em: 22 nov. 2024.

## <p style="margin-bottom: 50px;">Histórico de Versões</p>

| Versão | Data       | Descrição                            | Autor                                                 | Revisor                                               |
| :----: | ---------- | ------------------------------------ | ----------------------------------------------------- | ----------------------------------------------------- |
| `1.0`  | 23/11/2024 | Criação do documento                 | [Cristiano Morais](https://github.com/CristianoMoraiss) </br> [Ana Catarina](https://github.com/an4catarina)|       [Júlia Fortunato](https://github.com/julia-fortunato)       |







