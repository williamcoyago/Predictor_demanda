# Proyecto Predictor de Demanda

## Breve descripción y objetivo

Motor de predicción de demanda basado en modelos de ML (gradient boosting, random forest, ridge) que mediante el análisis histórico de información (1 año) relacionada con los movimientos que implican la salida (venta, merma, bajas, perdidas, etc.,) de inventario genera una proyección para las siguientes **12 semanas** de la demanda que tendrá ese SKU en particular y cuyo objetivo principal es ayudar a las organizaciones a la toma decisiones respecto del abastecimiento de sus productos críticos de operación y reducir de esta forma el riesgo de perdida de credibilidad junto con mantener sus ingresos y relaciones comerciales.

## Parámetros técnicos

El proyecto está desarrollado en formato .ipynb en Google Colab estructurado de la siguiente forma:

1. **Estructura base y definiciones:** Configuración general del entorno, definición de librerias, y definición de reglas de demanda y no demanda para el análisis de movimientos.
2. **Carga y normalización de datos:** limpieza de datos y estructuración de los mismos para el modelo.
3. **Machine learning y evaluación:** entrenamiento, prueba y comparación de algoritmos en busqueda del que mejor puntuación obtenga.
4. **Resultados y proyección:** ejecución del modelo ganador al dia inmediato poserior a la finalización del data set y proyección para las siguientes 12 semanas.

## Contenido del repositorio

1. `predictor_demanda.ipynb`: motor desarrollado en python que ejecuta los pasos previamente explicados.
2. `readme.md`: descripcion del proyecto y especificaciones.
3. `Input.xlsx`: dataset utilizado.

## Links adicionales

1. `Repositorio Google`: **https://drive.google.com/drive/folders/1x7v7ce_tGgyS_ATgGz_sx9fI6dxu91Wa?usp=sharing**
2. `Video explicativo`: **https://youtu.be/UjNx41GtdRg**
