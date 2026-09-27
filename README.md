# Análise de Coorte e Otimização de ROI de Marketing

Este projeto de Inteligência de Negócios tem como objetivo analisar o comportamento de usuários e avaliar o desempenho de campanhas de marketing de uma plataforma. Através de Análise de Coorte, o projeto mapeia a jornada do cliente e calcula métricas financeiras essenciais para embasar a realocação estratégica de orçamentos.

## Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python
- **Manipulação de Dados:** Pandas, NumPy
- **Visualização:** Matplotlib, Seaborn

## 📋 Funcionalidades e Etapas da Análise
- **Otimização de Dados:** Padronização de colunas e conversão de tipos de dados (formato `category` e `datetime`) para otimização de memória.
- **Análise de Produto:** Cálculo de DAU, WAU, MAU, duração média das sessões (ASL) e Taxa de Retenção por Coorte.
- **Análise de Vendas (E-commerce):** Mapeamento do tempo até a conversão, evolução do Ticket Médio e cálculo do LTV (Lifetime Value) acumulado ao longo da vida da coorte.
- **Análise de Marketing:** Levantamento de custos operacionais e cálculo do CAC (Custo de Aquisição de Clientes) por origem de tráfego, finalizando com a apuração do ROI.

## Principais Insights de Negócio
- **Comportamento do Usuário:** A duração média da sessão é de apenas 60 segundos, e a grande maioria das conversões (compras) ocorre no exato dia do primeiro acesso, indicando decisões de compra rápidas e pontuais.
- **Identificação de Outliers e Heavy Users:** A coorte de Setembro/2017 apresentou um pico de ticket médio de $62,57 no 3º mês, coincidindo diretamente com o período de maior investimento em marketing da empresa.
- **Otimização de Orçamento (ROI):** A análise revelou que as origens de tráfego 2 e 3 possuem o maior custo de aquisição (com o canal 3 ultrapassando $18 de CAC), enquanto as fontes 9 e 10 se mostraram as mais baratas (CAC inferior a $4), orientando a empresa de forma clara sobre onde focar os próximos investimentos.
