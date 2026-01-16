📊 Análise de Teste ABC: Desempenho de Funcionalidades
Este repositório contém a análise técnica de um Teste ABC realizado para avaliar o impacto de novas funcionalidades em uma base de clientes de e-commerce. O objetivo principal é selecionar a funcionalidade com melhor performance para implementação definitiva.


📋 Objetivo do Projeto
O teste dividiu os clientes em três grupos:


Grupo A (Controle): Clientes não expostos às novas funcionalidades.


Grupo B (Variante 1): Clientes expostos à funcionalidade "B".


Grupo C (Variante 2): Clientes expostos à funcionalidade "C".

🛠️ Tecnologias Utilizadas
Python: Linguagem base para manipulação de dados.

Pandas: Biblioteca para análise e limpeza de dados.


SQL (pandasql): Utilizado para consultas complexas e manipulação de tabelas relacionais.

Matplotlib & Seaborn: Criação de visualizações e gráficos estatísticos.

📈 Principais Insights e Resultados
1. Seleção da Melhor Funcionalidade
O Grupo B foi selecionado como o vencedor. Embora tenha um número de clientes ligeiramente menor, ele gerou a maior receita total (R$ 11.070.687) e o maior Ticket Médio por cliente (R$ 27.815), superando o controle em aproximadamente 13,6%.

2. Influência Geográfica
A análise confirmou que o estado do usuário influencia o valor das vendas. Estados como RR e MG lideram em volume total, enquanto o CE apresenta um dos maiores Tickets Médios por pedido.

3. Comportamento e Status do Pedido
Identificou-se que a quantidade de itens por pedido (média de 2 unidades) não afeta o status de cancelamento. Categorias como Roupas e Eletrônicos possuem maior volume, mas mantêm taxas de conversão proporcionais às demais.

4. Eficiência Operacional
Apesar de todos os clientes da base serem compradores (conversão de 100%), o diferencial do Grupo B foi o aumento do Ticket Médio, provando que a funcionalidade incentiva o consumo de produtos de maior valor.
