
# Projeto: Análise de Receita dos Planos Telefonicos da Megaline:

## Descrição do Projeto
Olá a todos! Estou empolgado para compartilhar o projeto de análise de receita dos planos Megaline que realizei recentemente pelo curso de análise de dados da escola Tripleten. 
Fui encarregado de determinar qual dos nossos dois planos pré-pagos - Surf ou Ultimate - gera mais receita. Essa análise foi crucial para o departamento comercial ajustar o orçamento de publicidade de forma mais eficaz. Para isso, trabalhei com dados de 500 clientes da Megaline, analisando seu comportamento de uso de chamadas, mensagens e internet ao longo do ano de 2018.

## Descrição dos Planos
Vamos dar uma olhada nos planos que oferecemos:

## Surf
Preço Mensal: $20
Inclusões Mensais: 500 minutos, 50 mensagens de texto, 15 GB de dados
Após Exceder os Limites:
1 minuto extra: 3 centavos
1 mensagem de texto extra: 3 centavos
1 GB de dados extra: $10

## Ultimate
Preço Mensal: $70
Inclusões Mensais: 3000 minutos, 1000 mensagens de texto, 30 GB de dados
Após Exceder os Limites:
1 minuto extra: 1 centavo
1 mensagem de texto extra: 1 centavo
1 GB de dados extra: $7


# Instruções para Completar o Projeto
## Passo 1: Exploração Inicial dos Dados
Estudei as informações gerais contidas nos conjuntos de dados fornecidos.

## Passo 2: Preparação dos Dados
Converti os dados para os tipos necessários.
Encontrei e eliminei erros nos dados, explicando quais erros foram encontrados e como foram tratados.

## Passo 3: Análise dos Dados
Descrevi o comportamento dos clientes, calculando métricas como minutos, mensagens e volume de dados usados por mês.
Construi histogramas e descrevi as distribuições das métricas analisadas.

## Passo 4: Teste de Hipóteses
Testei as hipóteses de que a receita média dos usuários dos planos Ultimate e Surf são diferentes, e que a receita média dos usuários na área de NY-NJ é diferente dos usuários em outras regiões.
Expliquei como formulei as hipóteses e qual critério utilizei para testá-las.

## Passo 5: Conclusão Geral
Escrevi uma conclusão geral com base nos resultados obtidos ao longo do projeto.



## Descrição dos Dados
Os conjuntos de dados fornecidos incluem informações sobre os usuários, chamadas, mensagens de texto e sessões web. Os dados estão estruturados nas seguintes tabelas:

users: informações sobre os usuários, como identificação, nome, idade, data de inscrição, data de encerramento, cidade e plano.
calls: dados sobre chamadas, incluindo identificador, data, duração e identificação do usuário.
messages: dados sobre mensagens de texto, incluindo identificador, data e identificação do usuário.
internet: dados sobre sessões web, incluindo identificador, volume de dados gasto e identificação do usuário.
plans: informações sobre os planos, incluindo nome, preço mensal, pacote de minutos, mensagens e volume de dados, e os preços adicionais por minuto, mensagem e GB de dados extra.
