# FI1105 - Física para Biotecnología

[![deploy](https://github.com/glacy/FI1105/actions/workflows/deploy.yml/badge.svg)](https://github.com/glacy/FI1105/actions/workflows/deploy.yml)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/glacy/FI1105)

🚀 **Sitio web oficial (Versión compilada):** [https://glacy.github.io/FI1105](https://glacy.github.io/FI1105)

---

## Acerca del curso

Este repositorio contiene los materiales oficiales, planeamiento y recursos didácticos para el curso **FI1105 Física para Biotecnología** del **Instituto Tecnológico de Costa Rica**.

El contenido abarca desde fundamentos de unidades y análisis dimensional hasta aplicaciones avanzadas de óptica y electricidad en sistemas biológicos, estructurado para apoyar la formación de estudiantes de Ingeniería en Biotecnología.

### 🛠️ Tecnología

Este proyecto está construido utilizando el motor **[MyST Course Starter](https://github.com/glacy/myst-course-starter)**, una plantilla diseñada para desacoplar el diseño instruccional de la implementación técnica.

Esto permite que el curso se genere automáticamente a partir de un archivo de planeamiento centralizado (`planeamiento.json`), garantizando que el sitio web y los materiales estudiantes estén siempre sincronizados con el sílabo oficial.

## Ejecución y Edición

### ☁️ En la nube (Recomendado)

La forma más sencilla de editar o visualizar el curso en entorno de desarrollo es utilizando **GitHub Codespaces**.

1. Haga clic en el botón "Open in GitHub Codespaces" de arriba.
2. Espere a que el entorno se construya.
3. Una vez listo, tendrá un entorno con todas las dependencias (Python, Node.js, MyST) preinstaladas.

### 💻 Ejecución local

Si prefiere trabajar localmente, asegúrese de tener instalado [Conda](https://docs.conda.io/en/latest/).

1. **Configurar el entorno:**
   ```bash
   conda env create -f environment.yml
   conda activate FI1105
   ```

2. **Iniciar el servidor:**
   ```bash
   myst start
   ```
   El sitio estará disponible en `http://localhost:3000`.

## Estructura del Repositorio

- `planeamiento.json`: Fuente de verdad del sílabo (objetivos, semanas, evaluación).
- `sessions/`: Archivos markdown con el contenido de cada clase.
- `activities/`: Guías de actividades prácticas y laboratorios.
- `assets/`: Imágenes y recursos estáticos.

## Contribuir

Si encuentra un error o desea sugerir una mejora en los materiales del curso, por favor abra un [Issue](https://github.com/glacy/FI1105/issues) o envíe un Pull Request.

---
**Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) para contenidos.
