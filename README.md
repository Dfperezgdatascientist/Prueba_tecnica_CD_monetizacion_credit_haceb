![haceb](haceb.png)
# **Prueba Técnica - Científico de Datos monetización de Crédito**
## Prueba Analítica: Modelo score de crédito
### Científico de Datos:

* Daniel Felipe Pérez Grajales . dfperezg@unal.edu.co<br>

<br><br>


---
<br>

**Objetivo:**

Esta prueba analítica tiene como objetivo diseñar y desarrollar un modelo de pronóstico scorecard.


**Los entregables son los siguientes:**

Notebook *Prueba_Tecnica_HACEB_DsC_DFPG.ipynb* con lo siguiente: <br>

1. Análisis Exploratorio: 
* Distribuciones de variables 
* Correlaciones con default 
* Patrones por segmentos (clientes nuevos vs existentes) 
2. Modelo Predictivo: 
* Usar variables como: edad, ingresos, score_bureau_externo, días de mora, 
compras_promedio_mensual, etc. 
* NO usar directamente un score crediticio interno (porque eso es lo que van a crear) 
3. Scorecard Interno: <br>
 Convertir el modelo en un scorecard con puntos Ejemplo:<br>
  
* Score bureau 700-850: +50 puntos 
* Ingresos >3M: +30 puntos 
* Cliente existente >24 meses: +20 puntos 
* Sin mora: +40 puntos 
4. Puntos de Corte: 
* Score total mínimo para aprobación 
* Diferentes cortes por segmento/monto 
* Variables Clave que SÍ Deben Usar: 
* score_bureau_externo (DataCrédito/TransUnion) 
* dias_mora_actual, max_dias_mora_12m 
* ingreso_mensual 
* meses_como_cliente, compras_promedio_mensual 
* tipo_empleo, antiguedad_laboral_años 