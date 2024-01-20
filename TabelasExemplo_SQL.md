# Exemplo de Estrutura de Dados para Controle Financeiro de Pequena Empresa - SQL


Este é um exemplo de estrutura de dados em SQL para um sistema de controle financeiro de uma pequena empresa. Cada tabela representa uma entidade específica relacionada ao controle financeiro.

Os código estão escrito em T-SQL


## Tabelas

### OrcamentoMensal

```sql
CREATE TABLE OrcamentoMensal (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Categoria VARCHAR(255),
    Receitas DECIMAL(10, 2),
    Despesas DECIMAL(10, 2),
    SaldoMensal DECIMAL(10, 2),
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

### FluxoDeCaixa

```sql
CREATE TABLE FluxoDeCaixa (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Data DATE,
    Descricao VARCHAR(255),
    Entrada DECIMAL(10, 2),
    Saida DECIMAL(10, 2),
    SaldoAtual DECIMAL(10, 2),
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

### ControleEstoque

```sql
CREATE TABLE ControleEstoque (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Produto VARCHAR(255),
    QuantidadeInicial INT,
    VendasPeriodo INT,
    ComprasPeriodo INT,
    QuantidadeFinal INT,
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

### ContasPagar

```sql
CREATE TABLE ContasPagar (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Fornecedor VARCHAR(255),
    Valor DECIMAL(10, 2),
    DataVencimento DATE,
    Status VARCHAR(50),
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

### ContasReceber

```sql
CREATE TABLE ContasReceber (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Cliente VARCHAR(255),
    Valor DECIMAL(10, 2),
    DataVencimento DATE,
    Status VARCHAR(50),
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

### DRE

```sql
CREATE TABLE DRE (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Descricao VARCHAR(255),
    Receitas DECIMAL(10, 2),
    Custos DECIMAL(10, 2),
    Despesas DECIMAL(10, 2),
    LucroPrejuizo DECIMAL(10, 2),
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

### RelatorioDespesas

```sql
CREATE TABLE RelatorioDespesas (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Categoria VARCHAR(255),
    ValorGasto DECIMAL(10, 2),
    AnoMes VARCHAR(7) -- Formato: YYYY-MM
);
```

Essas tabelas formam a base de dados para um sistema de controle financeiro, permitindo o acompanhamento detalhado das finanças ao longo do tempo.
