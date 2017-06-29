# MPS parklot
Gestor de estacionamentos em Java do início ao fim

## Enunciado do Problema

Nos negócios, a automação comercial surge quando uma atividade deixa de ser desempenhada por uma pessoa e passa a ser efetuada por alguma ferramenta artificial. Essa necessidade nasce quando os processos executados manualmente extravasam a capacidade humana de executá-la com eficiência e eficácia.

O enunciado (fictício) abaixo demostra esse tipo de situação:

> Há 10 anos, Sr. M possui um estacionamento de veículos, em Mirzam. Quando herdou um terreno extenso escolheu entrar nesse ramo. O negócio deu certo! Ele pavimentou o local e criou um chamativo quiosque de atendimento.
> Sr. M recebe ajuda de seus dois filhos na gerência do empreendimento. O número de clientes está aumentando e o fluxo de veículos cresce a cada dia. Os funcionários estão tendo problemas em anotar em papel as informações sobre o veículo e sobre o serviço. A demora no atendimento está criando desconforto e irritação nos clientes. O atual método de gerência não está acompanhando a velocidade de crescimento do negócio. Uma solução é necessária!

Essa descrição foi criada através do relato do Sr. M. Sendo que, pela natureza da situação, verifica-se a **viabilidade** da criação de um software para a solução desse problema. Justifica-se, portanto, o desenvolvimento de um sistema para suprir as necessidades do solicitante.

## Levantamento de Requisitos

O levantamento de requisitos é a etapa de compreensão inicial do problema. A equipe busca enxergar o problema da mesma forma que o usuário o vê. O objetivo é levantar as necessidades dos usuários. Essas necessidades são chamadas **requisitos**, sendo que podem ser classificadas em 3 tipos: funcionais, não funcionais e de domínio.

Os requisitos são coletados através do contato com o usuário. Entrevistas, questionários e observação são os meios mais comuns. Os itens abaixo foram coletados através de uma reunião com o cliente, Sr. M.

Os **requisitos funcionais** definem as funcionalidades do sistema.

|  ID  | Descrição                                             |
|:----:|-------------------------------------------------------|
| RF01 | Registrar entrada de veículo                          |
| RF02 | Registrar saída de veículo                            |
| RF03 | Manter veículo (placa, modelo, cor)                   |
| RF04 | Imprimir ticket do serviço em andamento               |
| RF05 | Aplicar desconto e/ou promoção no total de um serviço |
| RF06 | Cadastrar funcionário usuário do sistema              |
| RF07 | Controlar permissões de acesso de usuários            |
| RF08 | Manter tabela de preços (eventualmente promoções)     |
| RF09 | Emitir relatório de faturamento (mensal)              |

Os **requisitos não funcionais** qualificam o software em relação a suas funcionalidades. Esses requisitos abrangem itens como: confiabilidade, desempenho, portabilidade, segurança e usabilidade.

|   ID  | Descrição                                           |
|:-----:|-----------------------------------------------------|
| RNF01 | Login obrigatório (autenticação por RG e senha)     |
| RNF02 | Compatibilidade com o sistema operacional Windows 7 |

Ainda existem os **requisitos de domínio**, que são responsáveis por representar as regras de negócio de seu domínio. Por enquanto, não foram listados esse tipo de requisito.

## Diagrama de Casos de Uso

Após o levantamento de requisitos, a equipe de desenvolvimento tem conhecimento sobre as necessidades do solicitante. O diagrama de casos de uso tem o objetivo de facilitar a comunicação com o cliente, sendo que descreve um cenário com todas as funcionalidades descritas a partir do ponto de vista do usuário.

[Diagrama de Casos de Uso do MPS Parklot]

As elipses são os casos de uso, cada um deles possui uma documentação escrita que descreve as etapas de sua execução.

## Linguagens, Ferramentas e Bibliotecas

- Java e SQL (MySQL)
- NetBeans IDE 8.1
- JDK 1.8
