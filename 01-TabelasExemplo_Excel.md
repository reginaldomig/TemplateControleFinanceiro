# Exemplo de Estrutura de Dados para Controle Financeiro em Excel

Este é um exemplo de estrutura de dados para o controle financeiro de uma pequena empresa, modelado para ser utilizado em planilhas do Excel. As tabelas abaixo representam diferentes aspectos do controle financeiro, como orçamento mensal, fluxo de caixa, controle de estoques, contas a pagar e receber, demonstrativo de resultados (DRE) e relatório de despesas por categoria.

## Orçamento Mensal

| ID | Categoria        | Receitas | Despesas | SaldoMensal | AnoMes  |
|----|------------------|----------|----------|--------------|---------|
| 1  | Vendas           |          |          |              | 2024-01 |
| 2  | Salários         |          |          |              | 2024-01 |
| 3  | Aluguel          |          |          |              | 2024-01 |
| 4  | Contas de Luz    |          |          |              | 2024-01 |
| 5  | Fornecedores     |          |          |              | 2024-01 |
| 6  | Outros Gastos    |          |          |              | 2024-01 |

## Fluxo de Caixa

| ID | Data       | Descrição           | Entrada | Saída | SaldoAtual | AnoMes  |
|----|------------|---------------------|---------|-------|------------|---------|
| 1  | 2024-01-01 | Venda de Produto A  | 500     |       | 500        | 2024-01 |
| 2  | 2024-01-03 | Pagamento Fornecedor |         | 200   | 300        | 2024-01 |
| 3  | 2024-01-05 | Salário Funcionário  | 800     |       | 1100       | 2024-01 |

## Controle de Estoques

| ID | Produto      | QuantidadeInicial | VendasPeriodo | ComprasPeriodo | QuantidadeFinal | AnoMes  |
|----|--------------|--------------------|---------------|----------------|------------------|---------|
| 1  | Produto A    | 100                | 20            | 30             | 50               | 2024-01 |
| 2  | Produto B    | 50                 | 15            | 20             | 45               | 2024-01 |

## Contas a Pagar

| ID | Fornecedor        | Valor | DataVencimento | Status   | AnoMes  |
|----|-------------------|-------|----------------|----------|---------|
| 1  | Fornecedor X      | 200   | 2024-02-10     | Pendente | 2024-01 |
| 2  | Aluguel           | 800   | 2024-01-31     | Pago     | 2024-01 |

## Contas a Receber

| ID | Cliente           | Valor | DataVencimento | Status   | AnoMes  |
|----|-------------------|-------|----------------|----------|---------|
| 1  | Cliente A         | 500   | 2024-02-15     | Pendente | 2024-01 |
| 2  | Cliente B         | 300   | 2024-02-05     | Recebido | 2024-01 |

## Demonstrativo de Resultados (DRE)

| ID | Descrição            | Receitas | Custos | Despesas | LucroPrejuizo | AnoMes  |
|----|----------------------|----------|--------|----------|---------------|---------|
| 1  | Vendas de Produtos   | X        | Y      | Z        | X - (Y + Z)   | 2024-01 |

## Relatório de Despesas por Categoria

| ID | Categoria        | ValorGasto | AnoMes  |
|----|------------------|------------|---------|
| 1  | Salários         | X          | 2024-01 |
| 2  | Aluguel          | Y          | 2024-01 |
| 3  | Contas de Luz    | Z          | 2024-01 |
| 4  | Fornecedores     | W          | 2024-01 |
| 5  | Outros Gastos    | Q          | 2024-01 |

Essas tabelas representam uma estrutura de dados simples que pode ser utilizada em planilhas do Excel para realizar o controle financeiro de uma pequena empresa. A coluna `AnoMes` é incluída para facilitar a análise ao longo do tempo.
