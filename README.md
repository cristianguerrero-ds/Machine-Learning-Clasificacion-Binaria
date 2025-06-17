# Machine-Learning-Clasificacion-Binaria
Proyecto de Estudio en TripleTen

## 📊 Proyecto: Clasificación Binaria de Cancelaciones de Clientes

### 📑 Descripción

Este proyecto tiene como objetivo evaluar y comparar distintos modelos de clasificación para resolver un problema de detección binaria de clientes propensos a cancelar sus servicios.

Se implementaron y compararon los modelos de:

* Regresión Logística
* Árbol de Decisión
* Bosque Aleatorio

Dado que el conjunto de datos está desbalanceado, se aplicaron técnicas de:

* Asignación de pesos a las clases
* Sobremuestreo (upsampling)
* Submuestreo (downsampling)

El rendimiento se midió con la métrica **F1-score**, estableciendo un umbral de aceptación mínimo de **0.59**. Además, se calculó la métrica **AUC-ROC** para el mejor modelo.

### 📈 Resultado Principal

El modelo **Árbol de Decisión con clases balanceadas** obtuvo:

* **F1-score: 0.60**
* **AUC-ROC: 0.846**

Mostrando una adecuada capacidad para discriminar entre las clases.

### 📦 Estructura del Repositorio

```
Machine-Learning-Clasificacion-Binaria/
├── data/                         # Conjuntos de datos (excluidos en .gitignore)
│   └── Churn.csv
├── Sprint_10_Aprobado.ipynb      # Notebook con el desarrollo completo
├── requirements.txt              # Dependencias del proyecto
├── .gitignore                    # Archivos y carpetas ignoradas por Git
└── README.md                     # Documentación general
```

### 📥 Instalación y Ejecución

1. Clonar el repositorio:

```bash
git clone https://github.com/cristianguerrero-ds/Machine-Learning-Clasificacion-Binaria.git
cd Machine-Learning-Clasificacion-Binaria
```

2. Crear y activar entorno virtual:

```bash
python -m venv env
source env/Scripts/activate  # En Git Bash / Windows
```

3. Instalar dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecutar el notebook:

```bash
jupyter notebook
```

Y abrir `Sprint_10_Aprobado.ipynb` para correr las celdas.

### 📌 Notas

* La carpeta `data/` y el entorno virtual `env/` están excluidos mediante `.gitignore`.
* Los archivos de datos deben ubicarse en `data/` para su correcta ejecución.

### 📊 Conclusiones

Se recomienda el uso del Árbol de Decisión balanceado como modelo final, por su buen equilibrio entre precisión, clasificación de ambas clases y capacidad discriminativa según AUC-ROC.

---

🔗 *Desarrollado por Cristian Guerrero, 2025.*
