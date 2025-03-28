# AWS Big Data Dashboard Plugin for Grafana

Este es un plugin personalizado para Grafana que proporciona visualizaciones para entornos de Big Data en AWS, incluyendo servicios como AWS Glue, Athena, Step Functions, Lambda, S3 y Lake Formation. El plugin incluye un DAG (Grafo Acíclico Dirigido) para mostrar flujos de trabajo y está diseñado para ser extensible con tus propias fuentes de datos.

## Características

- Visualización de flujos de trabajo como DAGs usando D3.js.
- Datos simulados por defecto para pruebas.
- Fácil integración con APIs de AWS (CloudWatch, CloudTrail, etc.).
- Compatible con Grafana 9.0.0 y superior.

## Requisitos

- Node.js (>= 16.x)
- npm (>= 8.x)
- Grafana (>= 9.0.0)

## Estructura
```
grafana-aws-bigdata-plugin/
├── src/
│   ├── panel.js       # Lógica de visualización
│   ├── module.js      # Punto de entrada y fetchData
│   └── styles.css     # Estilos
├── dist/              # Carpeta generada
├── package.json       # Dependencias y scripts
├── plugin.json        # Metadatos del plugin
├── webpack.config.js  # Configuración de Webpack
└── README.md          # Este archivo
```
