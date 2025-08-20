<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *FIBONACCI MANAGEMENT SYSTEM*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Marcilei Alves|Gerente de Projeto|a.marcilei@estudante.ifro.edu.br|
|Wellington Jardel Silva Barros|Projetor|wellingtonjardel37@gmail.com|
|Izais Gomes de Oliveira Neto|Analista de projeto|izaiasgomesdeoliveiraneto@gmail.com|
|Ailla Odorizzi da Costa Teixeira|Designer|ailla.odorizzi@estudante.ifro.edu.br|
|Arthur Santos Ribeiro Barboza Mathias|Programador|imrealmaybe@gmail.com|


# Sumário

* [RESUMO DO PROJETO](#Fabricação-de-Website)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Click Fishing |
| GERENTE DO PROJETO | Marcilei Alves |
| PRINCIPAL OBJETIVO | Criar um site de venda de produtos de pesca Web. |
| BENEFÍCIOS ESPERADOS |* Ganhar porcentagem em cima do site ;<br/>* 
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2024 - 07/12/2025 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Pesc Fishing_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e fazer encomendas. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Poder ter acesso aos usuário cadastrado, poder ter controle a função que usuário padrão não teria|

[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento

[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais do sistema.

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Login no site: página inicial |O usuario devera realizar o login na página principal do site de pesca,logando ele podera ter acesso a seus dados. |
|RF-002 |O sistema deve exibir preços na aba abaixo do produto que está a venda.|Sera um código que mostrará o valor do produto abaixo da expecificação.|
|RF-003 |O sistema deve exibir os produtos || os produtos estarão cadastrado no banco de dados.||
|RF-004 |O fornecedor deve cadastrar os produtos para venda || os produtos estarão cadastrado no banco de dados.||
|RF-006 |O sistema deve cadastrar cliente || os cliente serão cadastrado no banco de dados.||
|RF-007 |O sistema podera mudar a função de cada usuário || Ex: de usuário padrão para adiministrador.||
|RF-008 |O sistema deve mostrar quantidade  de estoque disponível. || Quantidade de produto estára cadastrado no banco de dados.||
|RF-009 |O sistema terá a guia suporte de produtos e informação ao usuário || os suporte usuário podera conversar e fornecer informação do sistema pela a aba do site.
|RF-0010 |Mostrar as promoções do dia. || o sitema podera mostrar as promoção do dia.
|RF-0011 |Classificar os items a venda como mulinete,Iscas artificiais etc. || Ele classifica os items em separadas formas.
|RF-0012 |Adicionar um carrinho para ver quais items e o total da compra || Mostrar os items para compra
|RF-0013 |O sistema tera uma tela onde o usuário poderá apagar, atualizar, e editar o produto, marca,fornecedor|| Métodos do sistema.
|RF-0014 |O sistema deve mostrar a notificação de sucesso quando o usuário cadastrar,editar e excluir, atualizar produto, marca, fornecedor || Métodos do sistema.
|RF-0015 |Atravez de uma API poder localizar todo o endereço quando ele digitar o cep no site || Função do backend
|RF-0016 |O Usuário podera redefinir sua senha dando foi esquecido ||redefinição de senha.




## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001|O programa deve ser intuitivo com sua interface gráfica|O Website deve ser fácil de usar e intuitivo, permitindo que os usuários executem tarefas de forma eficiente.|
|RNF-002 |o programa deve ter uma boa proteção de dados com implementação de segurança cibernetica  |Analisar formas de invasão basica no website |
|RNF-003 |O sistema deve ser capaz de lidar com um aumento no número de usuários e no volume de dados sem perda de desempenho.| |

[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Classes

![Diagrama de Classes](/img/CDModelo.png)

[ [INÍCIO](#fibonacci-management-system) ]


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que foram disponibilizado pelo os professores do institutos Federais.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
