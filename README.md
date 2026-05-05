MMVL
Aplicación web desarrollada con Python + Flask y base de datos SQLite, orientada a la gestión de registros y sorteos. Incluye panel de administración, dashboard de estadísticas y sistema de registro de participantes.

Tecnologías utilizadas
TecnologíaUsoPython 3Lógica del servidorFlaskFramework web (backend)SQLiteBase de datos localHTML5 / CSS3Estructura y estilosJavaScriptInteractividad en el clienteVS CodeEntorno de desarrollo

📁 Estructura del proyecto
MMVL/
├── app.py                  # Aplicación principal Flask (rutas y lógica)
├── database.db             # Base de datos SQLite
├── templates/
│   ├── base.html           # Plantilla base (layout compartido)
│   ├── index.html          # Página de inicio
│   ├── registro.html       # Formulario de registro de participantes
│   ├── dashboard.html      # Panel de estadísticas
│   ├── admin.html          # Panel de administración
│   └── sorteo.html         # Página del sorteo
├── static/
│   ├── css/
│   │   └── style.css       # Estilos globales
│   └── js/
│       ├── dashboard.js    # Lógica del dashboard
│       └── registro.js     # Lógica del formulario de registro

⚙️ Instalación y ejecución
Requisitos previos

Python 3.8 o superior
pip

Pasos
bash# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/MMVL.git
cd MMVL

# 2. Crear y activar un entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate       # Linux/Mac
venv\Scripts\activate          # Windows

# 3. Instalar dependencias
pip install flask

# 4. Ejecutar la aplicación
python app.py
La aplicación estará disponible en: http://127.0.0.1:5000

Funcionalidades principales

 Registro de participantes mediante formulario web
 Sorteo aleatorio entre los participantes registrados
 Dashboard con visualización de datos
 Panel de administración para gestionar registros
 Persistencia de datos con SQLite (sin necesidad de servidor externo)


 Capturas de pantalla

(Añade aquí imágenes de tu aplicación)


 Desarrollo
Proyecto desarrollado con Visual Studio Code como entorno de desarrollo principal.

 Licencia
Este proyecto es de uso personal/educativo. Siéntete libre de usarlo como referencia.
