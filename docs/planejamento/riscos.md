# Gerenciamento de Riscos
## Introdução
O Gerenciamento de Riscos é uma etapa responsável por levantar, analisar e propor soluções para eventuais riscos que possam ocorrer durante o andamento do projeto.
## Estrutura Analítica dos Riscos

![](https://i.imgur.com/OYncwJJ.jpg)

### Risco Técnico
| Tipo| Descrição |
|:-:|:-:|
| Tecnologia | Risco referente às escolhas tecnológicas anteriores e atuais |
| Arquitetura | Risco referente às decisões arquiteturais anteriores e atuais |
| Código implementado| Risco referente ao código implementado pelo time anterior |
| Definições dos Requisitos| Risco referente ao desafio de definir corretamente os requisitos |
### Risco de Gerência
| Tipo| Descrição |
|:-:|:-:|
| Planejamento | Risco referente ao planejamento do projeto |
| Estimativa | Risco referente às estimativas definidas para o projeto|
| Comunicação | Risco referente à comunicação entre os membros|
| Experiência| Risco referente à falta de experiência do time de gerência|
### Risco Externo  
| Tipo| Descrição |
|:-:|:-:|
| Clientes| Risco referente aos clientes|
| Universidade | Risco referente às decisões da universidade|
| Problemas pessoais| Risco referente à ocorrência de problemas pessoais de algum membro|

## Análise de Probabilidade e Impactos
A análise tem como o objetivo de estabelecer a probabilidade de um risco definir a descontinuidade do projeto, evidenciando sua estimativa de impacto no tempo.
| Escala | Probabilidade | Impacto no tempo | Descrição |
|:-:|:-:|:-:|--|
| Muito alto | > 75% | >= 3 sprints | Impacto muito significativo |
| Alto | 51-75% | 1-2 sprint | Impacto significativo|
| Médio | 26-50% | 3-5 dias | Impacto chamativo |
| Baixo | 11-25% | 2 dias |Impacto pontual |
| Muito baixo | 1-10% |1 dia|Impacto discreto |
| Nulo | < 1% | < 1 dia | Impacto imperceptível |

## Riscos
Segue abaixo os riscos levantados, identificando seu tipo, escala, mitigação e proposta de solução:
### Técnico
| ID | Tipo | Risco  | Escala | Mitigação| Solução |
|:-:|:-:|:-:|:-:|:-:|:-:
| T01 | Tecnologia | Tecnologia adotada limitar o desenvolvimento da solução | Muito alto  | - | Trocar de tecnologia ou resolver pontualmente de uma maneira não convencional |
| T02 | Tecnologia | Escolha do banco de dados não ser habitual para os clientes | Médio  | - | Trocar para um banco de dados de conforto |
| T03 | Arquitetura | Decisões arquiteturas que comprometam o bom desenvolvimento | Médio | - | Organizar uma nova arquitetura |
| T04 | Código implementado | Desicões no desenvolvimento do código que gere retrabalho | Médio | - | Refatorar o código |
| T05 | Definições de Requisitos | Definir requisitos que não atendam as necessidades do cliente | Médio | Identificar os requisitos com os clientes e validar | Alterar os requisitos |

### Gerência
| ID | Tipo | Risco  | Escala | Mitigação| Resolução |
|:-:|:-:|:-:|:-:|:-:|:-:
| G01 | Planejamento | Planejamento das atividades semanais mal feito | Médio  | Validar as atividades com os clientes | Ajustar o escopo da atividade e o planejamento de tempo |
| G02 | Estimativa| Estimar com bastante imprecisão as atividades do projeto | Alto | Definir critérios de aceitação para ter uma noção mais clara da atividade | Reajustar o planejamento de tempo |
| G03 | Comunicação | Comunicação ineficiente entre os membros  | Baixo  | Definir padrões de comunicação | Estimular boas práticas de comunicação |
| G04 | Experiência | Falta de experiência da gerência dificultar o bom desenvolvimento | Baixo | Estudar Scrum, PMBOK e livros da disciplina | Ajustar para as boas práticas de gerência |

### Externo
| ID | Tipo | Risco  | Escala | Mitigação| Resolução |
|:-:|:-:|:-:|:-:|:-:|:-:
| E01 | Clientes | Descontinuidade do projeto | Muito alto | Constante alinhamento com os clientes e oferecer confiança | - |
| E02 | Universidade | Saida de um membro do projeto | Alto | - | Seguir com as atividades planejadas considerando a perda |
| E03 | Problemas pessoais | Ocorrência de problemas pessoais com algum integrante  | Médio | - | Seguir com as atividades considerando a perda momentânea |

## Histórico de Versões
|Data|Versão|Alteração|Autor|
|----|------|---------|-----|
| 16/03/2022 | 0.1 |Criação do documento de Gerenciamento de Riscos| João Baraky |
