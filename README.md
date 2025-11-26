Análise de Performance e Perfil do Cliente para E-commerce

Este projeto de Business Intelligence consiste em um painel gerencial interativo desenvolvido no Power BI, focado na análise de performance de vendas e no detalhamento do perfil do cliente de um grande e-commerce brasileiro. O objetivo principal é fornecer à equipe de negócios dados claros e acionáveis para otimizar estratégias de vendas e marketing.

🎯 Objetivo do Projeto

O E-commerce Analisado buscava estruturar seus dados para:

Avaliar o desempenho histórico de vendas (quantidade e faturamento).

Identificar padrões de compra e canais de venda mais eficazes.

Compreender a demografia e o poder aquisitivo da sua base de clientes.

Estabelecer uma base analítica para previsões futuras (regressão linear) e recomendações estratégicas.

📊 Detalhamento das Páginas e Métricas

Página 1: Visão de Vendas (Performance e Canais)

Para a análise de performance, utilizei o seguinte dashboard, que detalha o volume, o valor das vendas e os canais de distribuição:

<img width="1269" height="869" alt="Screenshot 2025-11-25 234812" src="https://github.com/user-attachments/assets/5a5cda23-acc7-4bd1-82e0-b2f0c7dbecd9" />

Esta página foca nos resultados financeiros e operacionais do e-commerce.

Métrica Escolhida (Cartão)

Propósito da Escolha

Quantidade de Vendas (55,8 Mil)

Métrica de volume fundamental para medir a escala da operação. É crucial para entender a eficiência do funil de vendas, independentemente do valor unitário do produto.

Valor Total de Vendas sem Frete (R$ 72,6 Mi)

Indica o faturamento puro dos produtos. É essencial para calcular margem de lucro real e avaliar a performance de precificação e mix de produtos.

Valor Total de Vendas com Frete (R$ 72,9 Mi)

Representa o valor total pago pelo cliente. É a métrica mais próxima da Receita Bruta, importante para o controle financeiro geral.

Análise dos Gráficos:

Contagem de Vendas por Mês (Gráfico de Linha): Usado para rastrear a tendência temporal do volume de transações. Permite identificar sazonalidades (picos ou quedas em meses específicos) e avaliar o impacto de campanhas promocionais.

Valor Total de Vendas por Mês (Gráfico de Linha): Semelhante ao anterior, mas foca no faturamento. A comparação entre os gráficos de linha (Contagem vs. Valor) ajuda a discernir se as vendas estão aumentando por mais volume ou por tickets médios mais altos.

Quantidade e Valor de Vendas por Categoria (Gráficos de Barra): Permite a análise do Mix de Produtos. A visualização lado a lado é crucial para identificar se a maior quantidade vendida está gerando o maior faturamento, destacando categorias de alto e baixo valor agregado.

Média de Compras por Departamento (Gráfico de Área): Indica o Ticket Médio por segmento de produto. A inclinação da linha mostra onde o cliente investe mais dinheiro, sendo um guia para estratégias de cross-selling e alocação de estoque (ex: "TV e Vídeo" apresenta o maior ticket médio).

Total de Vendas por Estado (Mapa): Essencial para a logística e regionalização de marketing. O mapa geográfico mostra visualmente as áreas de maior concentração de vendas, permitindo à empresa otimizar a distribuição e focar em mercados com maior potencial ou menor penetração.

Página 2: Dashboard de Perfil do Cliente (Demografia e Renda)

Esta página é dedicada à construção da Persona ideal do cliente, utilizando o seguinte painel para análise:

<img width="1270" height="873" alt="Screenshot 2025-11-25 234832" src="https://github.com/user-attachments/assets/01b8bce2-53ec-41bc-9a8e-e8a71e58cb92" />

Esta página é dedicada à construção da Persona ideal do cliente.

Métrica Escolhida (Cartão)

Propósito da Escolha

Quantidade de Clientes (17 Mil)

Mede o tamanho da base de usuários ativos. Essencial para estratégias de retenção e aquisição (CAC - Custo de Aquisição de Clientes).

Média de Idade (53)

Fornece uma média demográfica simples. Ajuda a definir a linguagem, o design e as plataformas de comunicação mais adequadas para o público predominante.

Média de Renda dos Clientes (R$ 8,2 Mil)

Indica o poder aquisitivo. Métrica vital para segmentação de marketing, definição de faixas de preço de produtos e estratégias de upsell.

Análise dos Gráficos:

Distribuição de Idade dos Clientes (Historiograma): Permite uma análise granular da idade. Ao contrário da média simples, o historiograma revela se a base é concentrada em faixas etárias específicas ou se é uniformemente distribuída. Isso é vital para refinar a Persona.

Distribuição de Renda dos Clientes (Gráfico de Barra Agrupada): Permite a segmentação do público-alvo por poder aquisitivo. A clusterização por faixa de renda (como "Acima de R$ 10.000", "Até R$ 7.500", etc.) é crucial para direcionar campanhas de produtos premium ou de entrada.

Percentual de Clientes por Estado (Gráfico Treemap): O Treemap é ideal para mostrar a proporção das principais regiões. Identifica rapidamente os estados que mais contribuem para a base de clientes, confirmando ou refinando as descobertas do mapa da página de vendas.

🛠️ Tecnologias e Metodologia

Ferramenta: Power BI

Fontes de Dados: Planilhas de Vendas (com dados de compra, frete, canal, bandeira) e Clientes (com dados de idade, UF de nascimento e renda).

Metodologia: O relatório foi construído seguindo os princípios de Storytelling com Dados, garantindo que as métricas e os gráficos conduzam o leitor a insights claros e suportem as recomendações de negócio.

💡 Próximos Passos Sugeridos

Com esta base analítica, a empresa pode avançar para:

Desenvolvimento do Modelo de Regressão Linear para prever o faturamento mensal.

Cálculo do Lifetime Value (LTV) e Custo de Aquisição de Clientes (CAC).

Criação de estratégias de fidelização baseadas nas faixas de renda e departamentos de maior retorno.

👤 Autor

Relatório Desenvolvido por: Fábio R Soares

Conecte-se no LinkedIn: linkedin.com/in/fábio-soares-ti
