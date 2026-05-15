# 📊 Análisis NovaRetail+ — Sprint 8

## Objetivo
Identificar qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado en NovaRetail+, plataforma de e-commerce en Latinoamérica, mediante un análisis correlacional completo.

## Dataset utilizado
| Archivo | Descripción |
|---|---|
| `novaretail_comportamiento_clientes_2024.csv` | Comportamiento de 15,000 clientes de NovaRetail+ durante 2024 |

## Etapas del análisis
1. Carga y exploración inicial del dataset
2. Preparación de datos y documentación de supuestos
3. Visualización de relaciones (heatmap y scatterplots)
4. Cálculo de coeficientes de correlación (Pearson, Spearman, Punto Biserial, V de Cramér)
5. Interpretación de resultados para el negocio
6. Limitaciones y próximos pasos

## Principales hallazgos
- `compras_mes` es el principal driver del ingreso anual (Pearson r = 0.97)
- `visitas_mes` muestra una relación moderada con el ingreso (r = 0.34)
- Variables como `edad`, `nivel_ingreso` y `satisfaccion` no tienen relevancia práctica

## Cómo ejecutar el notebook
1. Abre [Google Colab](https://colab.research.google.com/)
2. Ve a **Archivo → Abrir notebook → GitHub**
3. Pega la URL de este repositorio
4. Ejecuta las celdas en orden con `Shift + Enter`

## Herramientas
- Python 3.9
- pandas, numpy, seaborn, matplotlib, scipy
