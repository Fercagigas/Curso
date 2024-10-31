Este repositorio contiene una serie de notebooks de Jupyter enfocados en temas avanzados relacionados con inteligencia artificial, biología computacional y redes neuronales lógicas. A continuación, se presenta una descripción de cada uno de los notebooks, así como las instrucciones necesarias para configurar el entorno y ejecutar los análisis.

## Contenido

### 1. `Documentacion_DeepXDE.ipynb`

Este notebook proporciona una introducción a **Physics Informed Neural Networks (PINNs)** y hace uso de la biblioteca **DeepXDE** para la creación de modelos informados por ecuaciones diferenciales parciales. PINNs son redes neuronales diseñadas para resolver problemas de física e ingeniería donde se dispone de información teórica en forma de ecuaciones diferenciales. 

- **Contenido**:
  - Introducción a Physics Informed Neural Networks.
  - Configuración de DeepXDE para resolver problemas de física.
  - Ejemplos prácticos de resolución de ecuaciones diferenciales con DeepXDE.
  
- **Objetivos**:
  - Proporcionar una comprensión de cómo implementar PINNs utilizando DeepXDE.
  - Ejemplificar el uso de DeepXDE en problemas prácticos y mostrar su versatilidad en aplicaciones de física y matemáticas.

### 2. `EEG_Epileptor.ipynb`

Este notebook explora modelos biológicos para el estudio de la epilepsia, incluyendo el **modelo Epileptor** y el análisis del **potencial de membrana** y las **descargas eléctricas** que se observan en pacientes epilépticos.

- **Contenido**:
  - Fundamentos biológicos del potencial de membrana y su relación con descargas epilépticas.
  - Implementación del modelo Epileptor, que simula la dinámica de las crisis epilépticas.
  - Análisis de los patrones EEG (electroencefalograma) asociados con la epilepsia.

- **Objetivos**:
  - Brindar una herramienta de simulación que permita el estudio de las descargas epilépticas.
  - Comprender los mecanismos de disparo neuronal en el contexto de la epilepsia.
  
### 3. `LNNs.ipynb`

Este notebook ofrece un tutorial detallado sobre **Logical Neural Networks (LNNs)**, un enfoque que integra lógica simbólica y redes neuronales para crear modelos interpretables y lógicos.

- **Contenido**:
  - Introducción a los conceptos de redes neuronales lógicas.
  - Ejemplos de implementación de LNNs para tareas de razonamiento lógico.
  - Comparación entre LNNs y modelos neuronales tradicionales en cuanto a interpretabilidad y rendimiento.

- **Objetivos**:
  - Proveer una base sólida en la implementación y uso de LNNs.
  - Mostrar cómo LNNs pueden aplicarse a problemas de razonamiento lógico con interpretabilidad aumentada.

## Configuración del entorno

Para ejecutar estos notebooks, es necesario instalar las dependencias requeridas. A continuación, se listan los pasos para configurar el entorno.

### Requisitos previos

- Python 3.7 o superior
- Jupyter Notebook o JupyterLab

### Instalación de dependencias

1. Clona este repositorio:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
   ```

2. Crea un entorno virtual (opcional, pero recomendado):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. Instala las dependencias necesarias utilizando el archivo `requirements.txt` incluido en el repositorio:

   ```bash
   pip install -r requirements.txt
   ```

## Uso

Para iniciar Jupyter y explorar los notebooks:

```bash
jupyter notebook
```
