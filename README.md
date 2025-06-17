# Machine-Learning-Clasificacion-Binaria
Proyecto de Estudio en TripleTen

## 📊 Detección de Clientes Propensos a Cancelar — Clasificación Binaria

### 📌 Descripción del Proyecto

Este proyecto tiene como objetivo evaluar y comparar distintos modelos de clasificación para resolver un problema de detección binaria: identificar clientes con alta probabilidad de cancelar su servicio.  

Se trabajó con un conjunto de datos desbalanceado, aplicando distintas técnicas de ajuste para mejorar la clasificación de la clase minoritaria.

### 🛠️ Modelos Implementados

- Regresión Logística
- Árbol de Decisión
- Bosque Aleatorio

### ⚖️ Estrategias de Balanceo de Clases

- Asignación de pesos a las clases
- Sobremuestreo (upsampling)
- Submuestreo (downsampling)

### 📏 Métricas de Evaluación

- F1-Score (mínimo aceptable: 0.59)
- AUC-ROC (para el mejor modelo)

### 📈 Resultados

El modelo **Árbol de Decisión con clases balanceadas** obtuvo:

- **F1-Score:** 0.60  
- **AUC-ROC:** 0.846  

Se comprobó que ajustar los pesos de las clases fue la técnica más eficaz para este modelo.

