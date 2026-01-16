# 🚀 El Algoritmo del Marketing Digital: De la Intuición al Dato

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Data Science](https://img.shields.io/badge/Data_Science-F0FFF0?style=for-the-badge&logo=google-analytics&logoColor=forestgreen)
![Marketing Strategy](https://img.shields.io/badge/Strategy-FF69B4?style=for-the-badge&logo=target&logoColor=white)

> *"Los datos no matan la creatividad; la potencian. No tengo que elegir entre el arte y la ciencia, fusiono ambos."*

## 👋 Sobre mí

¡Hola! Soy **María Luisa Ros Bolea**.
Soy Graduada en **Comunicación Digital** y actualmente estoy finalizando mi máster en **Big Data e Inteligencia Artificial** en la Universidad CEU San Pablo (Madrid).

Mi especialidad está en la intersección del análisis de datos y la creación de estrategias digitales efectivas. Traduzco aspectos técnicos (Python, R, SQL) en planes de negocio ejecutables. Actualmente, aplico esta visión como **Marketing & Communications Manager** en **Optisaz** y en el **Instituto de Sexología Élan**.

## 🎯 Objetivo del Proyecto

En el mundo del marketing, escucho demasiadas veces frases como *"creo que esto funcionará"* o *"siento que TikTok va mejor"*. Como analista, eso no me vale.

Este proyecto, **"El Algoritmo del Marketing Digital"**, nace con un objetivo claro: **desterrar la intuición y abrazar la evidencia estadística**.

He desarrollado un análisis estadístico avanzado para responder a preguntas de negocio críticas:
1.  ¿Dónde es más rentable invertir cada euro de nuestro presupuesto?
2.  ¿Existen diferencias estadísticamente significativas entre invertir en **Instagram, TikTok o LinkedIn**?
3.  ¿Podemos predecir las ventas futuras basándonos en la inversión histórica?

## 🛠️ Metodología e Ingeniería de Datos

Para este estudio, tomé una decisión metodológica clave: **no usar datasets públicos sucios o desactualizados**.

En su lugar, diseñé un proceso de **Simulación de Monte Carlo** (`set.seed(2025)`) para generar un dataset sintético (**Marketing_2025**) que replica fielmente las métricas de una agencia real en 2025, garantizando:
* **Limpieza total:** 0 valores nulos.
* **Realismo:** Métricas basadas en KPIs reales del sector (LinkedIn con CTR alto y alcance nicho vs. TikTok con viralidad alta y conversión variable).
* **Volumen:** 1.000 campañas simuladas.

### Stack Tecnológico
* **Lenguaje:** R
* **Librerías:** `tidyverse` (manipulación), `ggplot2` (visualización avanzada), `knitr`.
* **Técnicas:** ANOVA de un factor, Regresión Lineal Simple, Simulación de Monte Carlo.

## 📊 Análisis y Resultados Clave

El estudio se dividió en tres fases estratégicas:

### 1. Análisis Exploratorio (EDA)
Descubrimos que **LinkedIn** actúa como el canal "Premium" con una media de ventas superior, mientras que **TikTok** presenta una volatilidad extrema (muchos outliers): o se viraliza o no convierte.

### 2. Inferencia Estadística (ANOVA)
Planteé la hipótesis nula ($H_0$) de que todas las plataformas rinden igual.
* **Resultado:** p-valor < 2e-16.
* **Conclusión:** Rechazamos $H_0$ rotundamente. Confirmado matemáticamente: **el rendimiento depende de la plataforma elegida.**

### 3. Modelización Predictiva (Regresión)
Creamos un modelo matemático ($R^2 \approx 0.75$) que explica el 75% de la variabilidad de las ventas según el presupuesto.
* **Hallazgo:** La pendiente de la recta de regresión es más inclinada en LinkedIn, lo que indica un **ROI marginal superior**.

## 💡 Conclusiones Estratégicas

Tras el análisis, mis recomendaciones de negocio son:

1.  **LinkedIn es el motor de rentabilidad:** Es el canal más seguro y eficiente para conversión directa.
2.  **TikTok para Branding, no para Ventas:** La relación presupuesto-ventas es casi plana. Invertir más dinero no garantiza más ventas; depende de la viralidad orgánica.
3.  **Predicción:** Ahora podemos estimar el retorno de la inversión con un margen de error mínimo antes de gastar un solo euro.

---

## 📂 Estructura del Repositorio

* `TRABAJOFINAL_ESTADÍSTICA.Rmd`: Código fuente en R con todo el análisis, generación de datos y narrativa.
* `Explicacion_Detallada_Proyecto.pdf`: Documento en profundidad sobre las decisiones metodológicas.
* `README.md`: Este archivo.

## 📫 Conectemos

* 💼 **LinkedIn:** [María Luisa Ros Bolea](https://www.linkedin.com/in/mar%C3%ADa-luisa-ros-bolea-400780160/)
* 🌐 **Portfolio:** [Digital Strategy & Data Portfolio](https://malurosbolea-ux.github.io/digital-strategy-portfolio/)
* 📸 **Instagram:** [@malu_menolu](https://www.instagram.com/malu_menolu/)
* 📧 **Email:** malurosbolea@gmail.com

---
*Este proyecto fue realizado como parte del Máster en Big Data e IA en la Universidad CEU San Pablo (2026).*
