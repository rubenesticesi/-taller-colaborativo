# **Estructura de Repositorio para Entregas**
A medida que avancemos en el curso, la organización será tan importante como el código que escriban. Para garantizar que todos los proyectos sean fáciles de revisar, entender y replicar, usaremos una estructura de repositorio estandarizada para cada entrega.

### La Regla de Oro: Claridad y Reproducibilidad
Cada una de sus entregas estará contenida en su propia carpeta principal (entrega 1, entrega 2, etc.), pero dentro de ellas, siempre deben incluir la siguiente organización.

Al seguir esta estructura sugerida, nos aseguramos de que cualquier persona (incluyéndote a ti mismo en el futuro) pueda:

- Entender el Proyecto rápidamente leyendo el README.md.

- Ejecutar el Código sin problemas gracias a requirements.txt.

- Localizar el código fuente principal dentro de la carpeta src/.

### Estructura Detallada por Entrega
**IMPORTANTE**: a continuación se presenta una sugerencia detallada, no es necesario que su estructura tenga exactamente los detalles que se presentan a continuación. El objetivo es mostrar la estructura que típicamente encontraran en un proyecto.
Para cada entrega, tu carpeta debe replicar la siguiente jerarquía (hasta donde les sea posible), adaptando los archivos internos según sea necesario (esta es la estructura, pero simplificada para el contexto de una entrega y de acuerdo a sus necesidades):
```
📦 nombre-del-proyecto/
│
├── 📂 docs/                     # Documentación del proyecto
│   ├── 📜 README.md             # Documentación extendida
│   ├── 📜 arquitectura.md       # Detalles del modelo y diseño
│   ├── 📜 api.md               # Documentación de la API (si aplica)
│   └── 📜 instalacion.md       # Guía de instalación y dependencias
│
├── 📂 src/                      # Código fuente principal
│   ├── 📂 data/                 # Scripts para cargar/preprocesar datos
│   │   └── preprocess.py
│   ├── 📂 models/               # Definición de arquitecturas de modelos
│   │   └── my_model.py
│   ├── 📂 training/             # Scripts de entrenamiento
│   │   └── train.py
│   ├── 📂 evaluation/           # Scripts de validación y pruebas
│   │   └── evaluate.py
│   ├── 📂 utils/                # Funciones auxiliares
│   │   └── helpers.py
│   └── main.py                  # Punto de entrada principal
│
├── 📂 notebooks/                # Jupyter Notebooks para experimentación
│   └── experiment_1.ipynb
│
├── 📂 experiments/              # Resultados de experimentos
│   ├── 📂 logs/                 # Logs de entrenamiento
│   ├── 📂 checkpoints/          # Modelos guardados
│   └── 📂 results/              # Métricas, gráficas, outputs
│
├── 📂 tests/                    # Pruebas unitarias y de integración
│   └── test_models.py
│
├── 📜 requirements.txt          # Dependencias del proyecto (Python)
├── 📜 environment.yml           # Alternativa (conda env)
├── 📜 .gitignore                # Archivos a ignorar en git
├── 📜 LICENSE                   # Licencia del proyecto
└── 📜 README.md                 # Descripción principal del proyecto
```

```
```
