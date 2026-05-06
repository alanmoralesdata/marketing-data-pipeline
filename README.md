# Marketing Data Pipeline

Pipeline de análisis de marketing que conecta campañas,
leads y ventas para tomar decisiones con datos reales.

## Empresa
Agencia de activaciones y tecnología experiencial —
$130K MXN/mes en Meta Ads y Google Ads.

## Stack tecnológico
- **Fuentes:** Meta Ads API · Google Ads · HubSpot CRM · Ventas
- **Warehouse:** Google BigQuery (gratuito hasta 10GB)
- **Transformaciones:** dbt Core
- **Dashboard:** Looker Studio

## Pipeline
Meta Ads ──┐
Google Ads ─┼──→ BigQuery RAW ──→ BigQuery STAGING ──→ Looker Studio
HubSpot ───┤
Ventas ────┘

## Métricas calculadas
- ROAS · CPL · CPA · Tasa de cierre · Ticket promedio

## Estado
🚧 En construcción — Mayo 2026
