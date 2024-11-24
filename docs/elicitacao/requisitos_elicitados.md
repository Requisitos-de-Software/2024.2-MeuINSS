# Requisitos Elicitados

## Introdução

Essa página tem como objetivo reunir e apresentar todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [encenação](encenacao.md), [entrevista](entrevista.md), [introspecção](introspeccao.md), [glossário](glossario.md) e [observação](observacao.md).

## Metodologia

Criou-se duas tabelas, uma apresentando os requisitos funcionais e outra com os requisitos não funcionais. 

As tabelas possuem o seguinte formato: cada linha contém um ID (junto com a indicação de se é funcional ou não funcional), sua respectiva descrição, se ele foi implementado ou não e a rastreabilidade, que indica qual(is) técnica(s) elicitou o requisito em questão. Além disso, requisitos que são similares e apresentam a mesma função agrupados e consolidados em um único requisito. Os identificadores (IDs) originais desses requisitos serão referenciados na tabela, garantindo rastreabilidade e transparência no processo.

Na tabela 1, encontra-se a legenda para cada sigla encontrada nas tabelas 2 e 3.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda para a tabela 2 e 3 </p></font>

<table>
  <thead>
    <tr>
        <th>Tipo</th>
        <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>RF</td>
        <td>Requisito Funcional</td>
    </tr>
    <tr>
        <td>RNF</td>
        <td>Requisito Não-Funcional</td>
    </tr>
    <tr>
        <td>ENC</td>
        <td>Requisito elicitado pela encenação</td>
    </tr>
    <tr>
        <td>ENT</td>
        <td>Requisito elicitado pela entrevista</td>
    </tr>
    <tr>
        <td>GLO</td>
        <td>Requisito elicitado pelo glossário</td>
    </tr>
    <tr>
        <td>INT</td>
        <td>Requisito elicitado pela introspecção</td>
    </tr>
    <tr>
        <td>OBS</td>
        <td>Requisito elicitado pela observação</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

## Tabela de requisitos funcionais elicitados

Na tabela 2, encontram-se os requisitos funcionais elicitados.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos funcionais elicitados do aplicativo Meu INSS</p></font>
</div >

| ID    | Descrição                                                                            | Implementado | Rastreabilidade |
| :---: | ------------------------------------------------------------------------------------ | :----------: | :-------------: |
| RF01  | O aplicativo emite e permite consulta a extratos e pagamentos.                        | Sim          | ENC01, ENT03, IS02, IS03   |
| RF02  | O aplicativo permite simular a aposentadoria.                                         | Sim          | ENC02, ENT01, GLO02   |
| RF03  | O aplicativo permite solicitar pedidos.                                              | Sim          | ENC03           |
| RF04  | O aplicativo deve ser integrado com outros sistemas, como o sistema jurídico.         | Não          | ENC04          |
| RF05  | O aplicativo permite solicitar auxílio doença.                                        | Sim          |    ENT02       |
| RF06 | O aplicativo permite verificar previsão de pagamento.                                    | Sim          | ENT04      |
| RF07 | O aplicativo deve possuir filtro de pesquisa assertivo.                                  | Não          | ENT05         |
| RF08 | O aplicativo deve possuir suporte adequado.                                            | Não          | ENT06              |
| RF09 | O aplicativo deve ser claro com relação a especificação para auxílios doenças e as modalidades de análise (online ou presencial).                                                | Não          | ENT07               |
| RF10 | O aplicativo deve avisar sobre mudanças e notícias sobre legislação previdenciária.                      | Não          | ENT08, IS07               |
| RF11 | O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício.| Não          | ENT09, IS06               |
| RF12 | O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).  | Sim          | GLO01, IS01             |
| RF13 | O aplicativo permite acessar comunidades para os próprios usuários se ajudarem.         | Não          | IS04               |
| RF14 | O aplicativo possui assistente virtual com simulações de diferentes cenários previdenciários.   | Não          | IS05              |

| INT15 | O aplicativo deverá mostrar os débitos pendentes do imóvel cadastrado pelo usuário   | Sim          | O               |
| INT16 | O aplicativo deverá mostrar os débitos pendentes de um parcelamento do usuário       | Sim          | O               |
| INT17 | O aplicativo deverá listar as dívidas ativas do usuário                              | Sim          | O               |
| INT18 | O usuário poderá imprimir o DAR de um débito pendente                                | Sim          | O               |
| INT19 | O aplicativo deverá listar os parcelamentos do usuário                               | Sim          | O               |
| INT20 | O aplicativo deverá ter um meio do usuário entrar em contato com o Economia DF       | Sim          | O               |
| INT21 | O aplicativo deverá ter um meio de fornecer ajuda ao usuário                         | Sim          | O               |
| INT22 | O aplicativo deverá mostrar o saldo do usuário no programa Nota Legal                | Não          | O, IS           |
| INT23 | O usuário poderá realizar a indicação do saldo do Nota Legal                         | Não          | O, IS, BS       |
| INT24 | Garantir que ao fechar o aplicativo o usuário seja deslogado                         | Não          | BS              |
| INT25 | O aplicativo deve possuir login com CPF e senha                                      | Sim          | O, IS, BS       |
| INT26 | Possibilitar que o usuário aumente a fonte                                           | Não          | BS              |
| INT27 | O usuário não deve conseguir colocar uma quantidade diferente de 7 caracteres ao cadastrar a placa de um veículo | Não | BS, O |
| INT28 | O usuário não deve conseguir colocar uma quantidade diferente de 11 números ao cadastrar o renavan de um veículo | Não | BS, O |
| INT29 | O usuário não deve conseguir colocar uma quantidade diferente de 8 números ao cadastrar a inscrição de um imóvel | Não | BS, O |
| INT30 | O usuário deve conseguir emitir a segunda via da dívida ativa                                                    | Não | BS, O |



<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >

## Tabela de requisitos não funcionais elicitados

Na tabela 3, encontram-se os requisitos não funcionais elicitados.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Requisitos não funcionais elicitados do aplicativo Meu INSS</p></font>
</div >

| ID    | Descrição                                                                            | Implementado | Rastreabilidade |
| :---: | ------------------------------------------------------------------------------------ | :----------: | :-------------: |
| RNF01  | O aplicativo deve ser intuitivo no uso.                                             | Não          | ENC05, ENT13           |
| RNF02  | O aplicativo deve possuir tutoriais explicativos de uso (por exemplo, vídeos).      | Não          | ENC06, ENT14           |
| RNF03  | O aplicativo deve possuir uma central de ajuda clara.                               | Não          | ENC07           |
| RNF04  | O aplicativo deve facilitar a execução de tarefas.                                  | Não          | ENC08, ENT11          |
| RNF05  | O aplicativo deve possuir, além de termos técnicos, nomenclaturas populares para as funcionalidades do INSS.  | Não          |    ENT10       |
| RNF06  | O aplicativo deve facilitar a busca de tarefas e funcionalidades.                   | Não          | ENT12      |
| RNF07 | O aplicativo deve ser acessível a todos os usuários.                                  | Não          | ENT15         |


| RNF08 | O aplicativo deve possuir suporte adequado.                                            | Não          | ENT06              |
| RNF09 | O aplicativo deve ser claro com relação a especificação para auxílios doenças e as modalidades de análise (online ou presencial).                                                | Não          | ENT07               |
| RNF10 | O aplicativo deve avisar sobre mudanças e notícias sobre legislação previdenciária.                      | Não          | ENT08, IS07               |
| RNF11 | O aplicativo deve mostrar o impacto que a contribuição do usuário está causando no seu benefício.| Não          | ENT09, IS06               |
| RNF12 | O usuário poderá ter acesso ao histórico completo de contribuições do segurado (CNIS).  | Sim          | GLO01, IS01             |
| RNF13 | O aplicativo permite acessar comunidades para os próprios usuários se ajudarem.         | Não          | IS04               |
| RNF14 | O aplicativo possui assistente virtual com simulações de diferentes cenários previdenciários.   | Não          | IS05              |



<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/julia-fortunato">Júlia Fortunato</a>, 2024</p></font>
</div >


## Histórico de versões 

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|23/11/2024|Criação do documento|[Júlia Fortunato](https://github.com/julia-fortunato)|[](https://github.com/)|