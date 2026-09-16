📊 Dashboard de Vendas — Excel
Dashboard de vendas construído em Excel, com foco em organizar dados brutos e transformá-los em indicadores e gráficos visuais para apoiar a análise de desempenho e a tomada de decisão.
🎯 Objetivo
Este projeto foi desenvolvido como desafio de organização e visualização de dados, com o objetivo de:
Estruturar uma base de dados de vendas;
Calcular indicadores-chave de desempenho (KPIs);
Construir visualizações claras (gráficos) que facilitem a leitura dos resultados;
Permitir que o dashboard seja atualizado automaticamente ao inserir novos dados.
🗂️ Estrutura do arquivo
O arquivo contém 3 abas:
Aba	Descrição
Dashboard	Painel principal com KPIs e gráficos
Análise	Tabelas auxiliares com fórmulas (`SUMIF`, `COUNTIF`) que alimentam os gráficos
Dados	Base de dados bruta (fictícia) com os pedidos de vendas
Aba "Dados"
Contém os registros de venda, com as colunas:
`ID Pedido | Data | Vendedor | Região | Categoria | Produto | Quantidade | Preço Unitário | Valor Total | Mês`
> Os dados desta versão são **fictícios**, gerados apenas para fins de demonstração (período de jan/2024 a dez/2024).
Aba "Dashboard"
KPIs: Receita Total, Pedidos, Ticket Médio, Unidades Vendidas
Gráficos:
Receita Mensal (linha)
Receita por Região (colunas)
Receita por Categoria (pizza)
Receita por Vendedor (barras)
⚙️ Como usar
Baixe o arquivo.
Abra no Excel (ou Google Sheets/LibreOffice Calc).
Substitua os dados da aba Dados pelos seus dados reais de vendas, mantendo as mesmas colunas.
O Dashboard e as tabelas da aba Análise são recalculados automaticamente, pois usam fórmulas (não valores fixos).
🛠️ Tecnologias e recursos utilizados
Microsoft Excel
Fórmulas: `SUMIF`, `COUNTIF`, `IFERROR`, `YEAR`, `MONTH`
Gráficos nativos do Excel (linha, colunas, pizza e barras)
Formatação condicional e KPIs em cartões
📌 Próximos passos (possíveis melhorias)
[ ] Adicionar filtros interativos (segmentação de dados / slicers)
[ ] Incluir comparação entre metas e realizado
[ ] Adicionar análise de tendência ano a ano
