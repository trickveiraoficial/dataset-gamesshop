# Características

- A empresa foca apenas em fabricação de consoles, deixando a distribuição e venda para terceiros
- Os produtos são vendidos globalmente

# Objetivos

- [x] Consolidar todas as bases de terceiros para realizar uma análise
- [x] Transformar dados de vendasem informações relevantes para a fabricante
- [x] Quais são os produtos mais populares em cada país
- [x] Como otimizar o processo de transporte e logística até o momento da venda



# Transformando Dados de Vendas em Informações Relevantes

O objetivo é transformar os dados de vendas em insights acionáveis para o fabricante de consoles, focando na identificação dos produtos mais populares em cada país e na otimização dos processos de transporte e logística até o ponto de venda.

Como a empresa se concentra apenas na fabricação e terceiriza a distribuição e vendas para terceiros, os insights serão adaptados para informar as estratégias de produção e fornecer recomendações baseadas em dados para seus parceiros.

## Conjunto de Dados

O conjunto de dados contém informações detalhadas de vendas, incluindo:

- SKU
- Produto vendido
- Data da venda
- Quantidade
- Preço unitário
- Preço total
- Moeda
- Local da venda
- Detalhes de desconto
- Demografia do comprador
- País de entrega
- ID da fatura

Ao analisar esses dados, podemos extrair insights para apoiar o planejamento da produção do fabricante e a coordenação logística com os distribuidores terceirizados.

## Objetivos Principais

1. **Identificar os produtos mais populares em cada país** para orientar as prioridades de produção.
2. **Otimizar os processos de transporte e logística até o ponto de venda** para melhorar a eficiência e reduzir custos para os parceiros de distribuição.

## 1. Produtos Mais Populares em Cada País

Para determinar os produtos mais populares, agregamos a quantidade total vendida para cada produto por país de entrega. A popularidade foi definida como o produto com o maior número total de unidades vendidas em cada país.

### Metodologia

1. Agrupar os dados: Agregação das vendas por "país de entrega" e "produto vendido".
2. Somar quantidades: Cálculo do total de "quantidade" vendida para cada produto em cada país.
3. Classificar produtos: Identificação do produto com o maior total de unidades vendidas por país.

### Resultados por País

#### Austrália:
- **NEW MEGANIUM RG CubeXX**: 15 unidades
- **NEW MEGANIUM RG35XX**: 2 unidades
- **NEW MEGANIUM RG28XX**: 11 unidades
- **MEGANIUM RG353M**: 5 unidades
- **Mais Popular**: NEW MEGANIUM RG CubeXX (15 unidades)

#### Reino Unido:
- **NEW MEGANIUM RG35XX**: 7 unidades
- **MEGANIUM RG353M**: 7 unidades
- **NEW MEGANIUM RG CubeXX**: 1 unidade
- **Mais Popular**: Empate entre NEW MEGANIUM RG35XX e MEGANIUM RG353M (7 unidades cada)

#### Alemanha:
- **NEW MEGANIUM RG 40XXV**: 8 unidades
- **NEW MEGANIUM RG28XX**: 12 unidades
- **NEW MEGANIUM RG CubeXX**: 10 unidades
- **MEGANIUM RG353M**: 3 unidades
- **Mais Popular**: NEW MEGANIUM RG28XX (12 unidades)

#### Canadá:
- **NEW MEGANIUM RG 40XXV**: 26 unidades
- **NEW MEGANIUM RG28XX**: 11 unidades
- **NEW MEGANIUM RG35XX**: 12 unidades
- **NEW MEGANIUM RG CubeXX**: 2 unidades
- **Mais Popular**: NEW MEGANIUM RG 40XXV (26 unidades)

#### EUA:
- **NEW MEGANIUM RG CubeXX**: 1 unidade
- **MEGANIUM RG353M**: 4 unidades
- **Mais Popular**: MEGANIUM RG353M (4 unidades)

#### França:
- **NEW MEGANIUM RG35XX**: 17 unidades
- **NEW MEGANIUM RG 40XXV**: 4 unidades
- **NEW MEGANIUM RG CubeXX**: 9 unidades
- **NEW MEGANIUM RG28XX**: 9 unidades
- **MEGANIUM RG353M**: 6 unidades
- **Mais Popular**: NEW MEGANIUM RG35XX (17 unidades)

#### Japão:
- **NEW MEGANIUM RG 40XXV**: 14 unidades
- **MEGANIUM RG353M**: 6 unidades
- **NEW MEGANIUM RG28XX**: 5 unidades
- **NEW MEGANIUM RG CubeXX**: 5 unidades
- **Mais Popular**: NEW MEGANIUM RG 40XXV (14 unidades)

### Insights e Recomendações

- **Austrália**: Priorizar a produção do NEW MEGANIUM RG CubeXX.
- **Reino Unido**: Equilibrar a produção de NEW MEGANIUM RG35XX e MEGANIUM RG353M.
- **Alemanha**: Focar na produção do NEW MEGANIUM RG28XX.
- **Canadá**: Priorizar o NEW MEGANIUM RG 40XXV.
- **EUA**: Necessidade de mais dados, mas MEGANIUM RG353M lidera.
- **França**: A maior demanda é por NEW MEGANIUM RG35XX.
- **Japão**: Focar no NEW MEGANIUM RG 40XXV.

## 2. Otimizando Transporte e Logística até o Ponto de Venda

### Metodologia

1. **Analisar o volume de envio**: Somar as unidades vendidas por país para entender a frequência e escala dos envios.
2. **Identificar regiões de alta demanda**: Destacar países com maior volume de vendas para sugerir hubs logísticos.
3. **Examinar o tempo das vendas**: Analisar padrões de "data da venda" para prever demanda e ajustar estoque.

### Total de Unidades Vendidas por País

- **Canadá**: 51 unidades
- **França**: 45 unidades
- **Austrália**: 33 unidades
- **Alemanha**: 34 unidades
- **Japão**: 30 unidades
- **Reino Unido**: 15 unidades
- **EUA**: 5 unidades

### Estratégias de Otimização

#### Hubs Regionais de Distribuição

- **América do Norte**: Estabelecer um hub no Canadá para atender Canadá e EUA.
- **Europa**: Criar um hub central na Alemanha ou França para consolidar envios para Europa.
- **Ásia-Pacífico**: Um hub na Austrália pode servir Austrália e Japão.

#### Consolidação de Envios

Para países com alto volume de vendas (Canadá e França), agrupar envios para reduzir o número de entregas individuais.

#### Previsão de Demanda

Usar datas de vendas para prever futuras necessidades de estoque e garantir disponibilidade de produtos.

### Recomendações

1. **Estratégia Logística**: Sugerir hubs no Canadá, Alemanha ou França, e Austrália para reduzir custos e prazos de entrega.
2. **Gestão de Estoque**: Compartilhar previsões de vendas com distribuidores para evitar excesso ou falta de produtos.
3. **Eficiência de Custos**: Negociar tarifas de frete em massa para países com alto volume de vendas.


---
