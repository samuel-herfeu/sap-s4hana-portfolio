# Stock Audit Dashboard

Aplicação SAP Fiori para auditoria de estoque no SAP S/4HANA.

## Objetivo
Gerar visibilidade operacional e contábil sobre estoque por material, centro e depósito.

## Stack
- ABAP CDS Views
- Eclipse / ADT
- OData V4
- SAP Fiori Elements
- VS Code
- SAP Launchpad

## Funcionalidades
- Filtros por Material, Centro e Depósito
- Análise de Standard Price vs Moving Average Price
- Visão por valuation class
- Navegação no SAP Fiori Launchpad

## Screenshots

### Visão geral
![Overview](./screenshots/stock-audit-overview.png)

### Colunas e estrutura
![Columns](./screenshots/stock-audit-columns.png)

### Material em destaque
![Material First](./screenshots/stock-audit-material-first.png)

## Estrutura técnica
- `cds/`: views e modelagem
- `odata/`: service definition e binding
- `fiori/`: configurações do app
- `screenshots/`: imagens do projeto
