# IE-0629 Sistemas de Comunicaciones (II-2026)

Este repositorio contiene los notebooks de Jupyter utilizados a lo largo del curso de licenciatura **IE-0629 Sistemas de Comunicaciones**, impartido en la **Escuela de Ingeniería Eléctrica** de la **Universidad de Costa Rica (UCR)** durante el **segundo semestre de 2026 (II-2026)**.

El objetivo de este espacio es recopilar las guías, análisis interactivos y demostraciones prácticas desarrolladas en clase o como parte de los proyectos del curso.

---

## 📂 Contenido del Repositorio

A continuación se detallan los notebooks disponibles actualmente en el repositorio. Esta sección se mantendrá en constante actualización conforme avance el semestre y se incorporen nuevos temas de estudio:

| Notebook | Descripción |
| :--- | :--- |
| 📘 [Decodificación de Viterbi y Diagrama de Trellis](./Decodificación_de_Viterbi_y_Diagrama_de_Trellis.ipynb) | Estudio e implementación del algoritmo de decodificación de Viterbi y la representación mediante diagramas de trellis para códigos convolucionales. |
| 📘 [Gradient Descent](./gradient_descent.ipynb) | Introducción y desarrollo práctico del algoritmo de optimización por descenso de gradiente. |
| 📘 [Funciones de Activación y Neuronas Muertas](./Funciones_de_Activación_y_Neuronas_Muertas.ipynb) | Para comprender por qué ocurre el fenómeno del *Dying ReLU* y cómo lo solucionan otras alternativas. |

---

## 🛠️ Requisitos de Ejecución

Para poder ejecutar estos entornos interactivos de manera local, es necesario contar con un entorno de Python y soporte para Jupyter Notebooks.

### 1. Clonar el repositorio
```bash
git clone https://github.com/roalchaq/IE0629-Sistemas_de_Comunicaciones.git
cd IE0629-Sistemas_de_Comunicaciones
```

### 2. Configurar el entorno (Recomendado)
Se sugiere el uso de un entorno virtual para instalar las dependencias requeridas (como `numpy`, `matplotlib`, `scipy` u otras bibliotecas estándar de procesamiento de señales y matemáticas):

```bash
# Crear entorno virtual
python -bin/python -m venv env

# Activar entorno (Linux/macOS)
source env/bin/activate

# Activar entorno (Windows)
.\env\Scripts\activate
```

### 3. Iniciar Jupyter
Una vez instaladas las herramientas, puede iniciar la interfaz local:
```bash
jupyter notebook
```

---

## 👥 Contribuciones y Avance

Este repositorio se encuentra bajo el desarrollo de [roalchaq](https://github.com/roalchaq) como parte del material formativo de la carrera. Se irán subiendo nuevos notebooks periódicamente alineados con el cronograma de lecturas del curso de Sistemas de Comunicaciones.
