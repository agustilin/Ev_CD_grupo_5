# Ev2_grupo_5
### Sobre el archivo `requirements_encargo2.txt`

**¿Qué es exactamente este archivo?**
Es una "fotografía" (snapshot) estática del entorno de desarrollo de Google Colab en el momento exacto en que se programaron y entrenaron los modelos. Consiste en un listado exhaustivo de todas las librerías de Python utilizadas y sus versiones milimétricamente específicas (por ejemplo, `scikit-learn==1.x.x`, `pandas==2.x.x`).

**¿Por qué es vital para este proyecto?**
Su propósito es garantizar la Reproducibilidad Científica Absoluta.

En la Ciencia de Datos y el Machine Learning, las librerías se actualizan constantemente. Una versión más nueva de una librería podría cambiar ligeramente el cálculo subyacente de un algoritmo, haciendo que el código falle o arroje métricas distintas en otra computadora. Al adjuntar este archivo y "congelar" las dependencias, aseguramos que la comisión evaluadora pueda reconstruir nuestro entorno de forma idéntica. Esto elimina el sesgo tecnológico y garantiza que al ejecutar el código se obtendrán exactamente los mismos resultados, F1-Scores y Matrices de Confusión reportados en el informe técnico.

---

### Instrucciones de Reproducibilidad (Cómo usar este archivo)

Para replicar el entorno exacto del proyecto, selecciona una de las siguientes opciones de ejecución:

**Opción 1: Ejecución en Entorno Local (Recomendado)**
Si deseas clonar el repositorio y ejecutar los scripts de forma local, sigue estos pasos para aislar el entorno:

1. Abre tu terminal en la carpeta raíz del proyecto y crea un entorno virtual:
   - En Windows: `python -m venv venv`
   - En macOS/Linux: `python3 -m venv venv`

2. Activa el entorno virtual:
   - En Windows: `venv\Scripts\activate`
   - En macOS/Linux: `source venv/bin/activate`

3. Instala las dependencias exactas ejecutando:
   - `pip install -r requirements_encargo2.txt`

**Opción 2: Ejecución en Google Colab**
El proyecto fue desarrollado originalmente en Google Colab. Si decides evaluar el proyecto importando los cuadernos (.ipynb) a esta plataforma, debes forzar a Colab a usar nuestras versiones.

Para ello, sube el archivo `requirements_encargo2.txt` al almacenamiento de sesión de Colab y ejecuta la siguiente celda al inicio de tu cuaderno:
   - `!pip install -r requirements_encargo2.txt`

Equipo de Trabajo
Diego Améstica
Agustín Cáceres
Dante Rodríguez
