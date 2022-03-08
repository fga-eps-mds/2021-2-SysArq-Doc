
# Product Backlog
## Introdução
O Backlog do Produto é um artefato que comporta a lista de requisitos elicitados do sistema até onde se tem conhecimento. Em um contexto de metologia ágil, trata-se de um documento que pode ser alterado ou incrementado conforme o projeto avança. Nele, os requisitos são descritos em Histórias de Usuários e são agrupados em Épicos. Nesse documento também é feito o mapeamento dos defeitos e melhorias identificados pelo cliente.

## Épicos
  
| Épico  | US's |
|--|--|
| Edição e exclusão dos metadados dos documento | [US01](#us01), [US02](#us02), [US03](#us03) |
| Cadastro de usuários no sistema | [US04](#us04), [US13](#us13)|
| Gerenciar credenciais de usuário (admin, alimentador, visualizador) | [US05](#us05)|
| Informar quando o documento atinge sua temporalidade | [US06](#us06)|
| Gerar relatórios | [US07](#us07)|
| Status do documento de Arquivamento de Caixas | [US08](#us08), [US09](#us09) |
| Impressão de etiquetas | [US10](#us10)|
| Cadastro de inventário (museu) | [US11](#us11), [US12](#us12) |


## Histórias de Usuário

### US01
| **Épico** |Edição e exclusão dos metadados dos documentos |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário alimentador, **quero** editar informações referentes aos documentos arquivados **para** atualizar o conteúdo quando necessário. |
| **Critérios de aceitação** | - Opção de edição em Processo Administrativo <br> - Opção de edição em Relação de Frequências <br> - Opção de edição em Folhas de Frequências <br> - Opção de edição em Arquivamento de Caixas <br> |

### US02
| **Épico** |Edição e exclusão dos metadados dos documentos |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário alimentador, **quero** editar informações referentes aos campos obrigatórios **para** atualizar o conteúdo quando necessário. |
| **Critérios de aceitação** | - Opção de edição em Assunto do Documento <br> - Opção de edição em Unidade <br> - Opção de edição em Caixa <br> - Opção de edição em Tipo de Documento <br> - Opção de edição em Estante e Prateleira <br> - Opção de edição em Servidor <br> - Garantir que seja atualizado nos locais aonde se utiliza do campo <br>|

### US03
| **Épico** | Edição e exclusão dos metadados dos documentos |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário alimentador, **quero** deletar as informações referentes aos documentos arquivados **para** remover o registro no sistema. |
| **Critérios de aceitação** | - Opção de deleção em Processo Administrativo <br> - Opção de deleção em Relação de Frequências <br> - Opção de deleção em Folhas de Frequências <br> - Opção de deleção em Arquivamento de Caixas <br> |

### US04
| **Épico** | Cadastro de usuários no sistema |
| ---: | :------- |
| **Descrição** | Eu, **como** administrador, **quero** cadastrar novos usuários **para** dar acesso a outras pessoas ao sistema. |
| **Critérios de aceitação** | - Tela para registro de novos usuários <br> - Formulário de cadastro <br> |

### US05
| **Épico** | Gerenciar credenciais de usuário (admin, alimentador, visualizador) |
| ---: | :------- |
| **Descrição** | Eu, **como** administrador, **quero** escolher o tipo de usuário no cadastro **para** definir quais permissões ele terá. |
| **Critérios de aceitação** | - Campo "tipo" no cadastro de usuário <br> - Visualizador com permissão a consumo de dados <br> - Alimentador com permissão a consumo e cadastro de dados (exceto usuários) <br> - Administrador com permissão total <br>|
| **Dependência** | [US04](#us04)|

### US06
| **Épico** | Informar quando o documento atinge sua temporalidade |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário, **quero** ser informado quando o documento atingir a sua temporalidade definida **para** que assim eu decida que fim ele terá. |
| **Critérios de aceitação** | - Informar quando o documento atingir a temporalidade definida <br> |

### US07
| **Épico** | Gerar relatórios |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário, **quero** requisitar relatórios com informações dos documentos cadastrados **para** que eu possa fazer analises em cima disso. |
| **Critérios de aceitação** | - Gerar relatório <br> - Customizar o conteúdo do relatório <br> |

### US08
| **Épico** | Status para encaminhamento de arquivos (arquivamento de caixa |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário alimentador, **quero** definir o status do arquivamento de caixas **para** ter conhecimento do estado do documento na seção. |
| **Critérios de aceitação** | - Campo de status com: arquivado, desarquivado e eliminado <br> |

### US09
| **Épico** | Status para encaminhamento de arquivos (arquivamento de caixa) |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário alimentador, **quero** adicionar informações sobre o desarquivamento de caixas **para** ter o registro de sua transitação. |
| **Critérios de aceitação** | - Campo para unidade de destino do desarquivamento <br> - Campo para número de processo do desarquivamento <br> - Campo para data do desarquivamento <br>|
| **Dependência** | [US08](#us08)|

### US10
| **Épico** | Impressão de etiquetas |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário, **quero** requisitar a impressão de etiquetas com dados do arquivamento **para** também ter o mapeamento no espaço físico. |
| **Critérios de aceitação** | - Botão que gera etiqueta referente ao documento arquivado <br> |

### US11
| **Épico** | Cadastro de inventário (museu) |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário alimentador, **quero** cadastrar informações sobre os itens do inventário do museu **para** ter o catálogo registrado no sistema. |
| **Critérios de aceitação** | - Botão na barra de navegação <br> - Tela de cadastro de item do inventário <br>|

### US12
| **Épico** | Cadastro de inventário (museu) |
| ---: | :------- |
| **Descrição** | Eu, **como** usuário visualizador, **quero** ter acesso aos itens do museu cadastrados **para** fazer eventuais consultas ao catalogo. |
| **Critérios de aceitação** | - Tela com listagem dos itens <br> - Botão na tela de pesquisa <br>|
| **Dependência** | [US11](#us11)|

### US13
| **Épico** | Cadastro de usuários no sistema |
| ---: | :------- |
| **Descrição** | Eu, **como** administrador, **quero** gerenciar os usuários cadastrados **para** editar e deletar quando necessário. |
| **Critérios de aceitação** | - Tela para gerenciamento de usuários cadastrados <br> - Lista de usuários <br> - Botão para edição <br> - Botão para deleção <br>|

## Defeitos e melhorias

Defeitos e melhorias informados pelo cliente:

* Após o cadastro de um campo obrigatório, retornar para a tela com a lista dos campos já cadastrados.
* Após o cadastro de um documento, retornar para a tela com a lista dos documentos já cadastrados.
*  Incluir possibilidade de dia e mês na definicação da temporalidade nos campos obrigatórios: Assunto do Documento e Tipo do Documento.
*  No cadastro de servidor (campo obrigatório), adicionar máscara no campo "CPF" (xxx.xxx.xxx-xx) e validar o CPF informado.
* No cadastro de um processo administrativo, adicionar máscara no campo "CPF" (xxx.xxx.xxx-xx).
* Nas tabelas com os documentos cadastrados (em todas categorias), expandir o elemento com todas as informações ao clicar em cima.
* Alterar ordem dos botões na barra de navegação para: 
<br>```[Cadastro - Pesquisa- Campos obrigatórios - Relatórios - Configurações]```
* Nova tela de pesquisa: divisão por categoria de documentos e campos obrigatórios (semelhante à tela de cadastro).
* Na tela de cadastro, adicionar a lista com todos os documentos (de mesma categoria) abaixo para eventuais consultas.
*  Adicionar filtro de busca em todas as tabelas de listagem.
* Mostrar botão configurações na barra de navegação apenas para administradores (depende da [US05](#us05)).

## Histórico de Versões
|Data|Versão|Alteração|Autor|
|----|------|---------|-----|
| 02/03/2022 | 0.1 | Criação do Product Backlog | João Baraky |
| 03/03/2022 | 0.2 | Atualização: remoção da US04 (já estava implementada) | João Baraky |
| 08/03/2022 | 0.3 | Atualização: adição da US13 | João Baraky |
