# Portafolio de Proyectos — Jose M. Gil

¡Bienvenido a mi portafolio público! Aquí encontrarás una colección de proyectos personales y de experimentación en ciencia de datos, automatización, heurísticas y otras áreas de la ingeniería de software.

## 📂 Estructura del repositorio

```text
Portfolio/
├── FirstProject/          # Proyecto 1 — comparativa de rendimiento
│   ├── .venv/            # Entorno virtual — **no se sube** al repo
│   ├── Code/             # Scripts y módulos de Python
│   ├── Data/             # Datos brutos / procesados
│   ├── requirements.txt  # Dependencias del proyecto
│   └── README.md         # Descripción detallada del proyecto
├── <OtroProyecto>/       # Sigue la misma convención
└── README.md             # (este archivo)
```

* Cada carpeta de proyecto es **autosuficiente** y contiene su propio entorno virtual, código y datos.
* El archivo `.gitignore` global ignora todos los `.venv`, `__pycache__` y checkpoints de Jupyter.

## 🚀 Proyectos incluidos

| Proyecto         | Descripción breve                                                                                     | Tecnologías clave             |
| ---------------- | ----------------------------------------------------------------------------------------------------- | ----------------------------- |
| **FirstProject** | Comparación de rendimiento entre diferentes modelos de ML utilizando notebooks y scripts optimizados. | Python, Jupyter, Scikit‑learn |
| *(Próximamente)* | …                                                                                                     | …                             |

> **Nota:** Cada proyecto incluye su propio `README.md` con instrucciones de instalación, datos y explicación del enfoque.

## 🔧 Prerrequisitos generales

* **Python 3.10+** (se recomienda instalar mediante [pyenv](https://github.com/pyenv/pyenv) o [conda](https://docs.conda.io/en/latest/))
* **Git**
* Opcional: [VS Code](https://code.visualstudio.com/) + extensiones Python

## 🏃‍♀️ Cómo clonar y ejecutar un proyecto

```bash
# Clona el portafolio completo
git clone https://github.com/jmgilv/Portfolio.git
cd Portfolio/FirstProject

# Crea y activa el entorno virtual (ejemplo en macOS/Linux)
python3 -m venv .venv
source .venv/bin/activate

# Instala dependencias específicas del proyecto
pip install -r requirements.txt

# ¡A ejecutar!
python Code/mi_script_principal.py
```

## 🤝 Contribuciones

Las contribuciones, ideas y *pull requests* son bienvenidos.

1. Abre un *issue* con tu propuesta.
2. Haz *fork* del repositorio y crea tu rama: `git checkout -b feature/mi‑mejora`.
3. Envía tu *pull request*.

## 📜 Licencia

Distribuido bajo la licencia MIT — consulta el archivo `LICENSE` para más información.

## 👤 Autor

**Jose M. Gil V.**
Operations Administrator · RPA Developer · Data Science Enthusiast
[https://www.linkedin.com/in/jmgilv](https://www.linkedin.com/in/jmgilv)

---

> “El mejor código es aquel que se comparte, se aprende y se mejora en comunidad.”
