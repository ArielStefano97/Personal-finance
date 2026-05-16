# Quantfury + Rotki Workflow

## Objetivo
Organizar operaciones de Quantfury para análisis fiscal y seguimiento de portfolio.

## Flujo recomendado

```text
Quantfury CSV/PDF
↓
Corrección balances
↓
Importación Rotki
↓
Revisión manual
↓
Informe fiscal
```

## Riesgos detectados

- Operaciones short BTC/ETH/MSTR
- Margin trading
- Conversión entre activos
- Muchas operaciones pequeñas

## Recomendaciones

1. Exportar CSV mensualmente.
2. Mantener backups.
3. Revisar balances negativos.
4. Validar FIFO manualmente.
5. No depender solo de Quantfury para Hacienda.

## Herramientas útiles

- Rotki
- Koinly
- Trade Republic exports
- Kraken exports

## Estado actual

El archivo consolidado generado contiene más de 2000 movimientos listos para análisis.
