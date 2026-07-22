# 📅 Daily Standup Workflow

Workflow de GitHub Actions para automatizar los daily standups.

## 🚀 Cómo usar

### Opción 1: Workflow Manual
1. Ve a **Actions** → **Daily Standup → GitHub**
2. Haz clic en **Run workflow**
3. Rellena los campos
4. Haz clic en **Run workflow**

### Campos del workflow manual
Al ejecutar **Run workflow**, se te pedirán estos campos:
- **Nombre:** tu nombre o alias para identificar el daily.
- **Qué hice ayer:** resume las tareas que completaste el día anterior.
- **Qué haré hoy:** indica las tareas que planeas realizar hoy.
- **Bloqueadores:** menciona impedimentos, dependencias o problemas que te estén frenando.

### Opción 2: Crear Issue
1. Ve a **Issues** → **New Issue**
2. Selecciona **📅 Daily Standup**
3. Rellena el formulario
4. Añade la etiqueta **daily**

### Opción 3: Automático
El workflow se ejecuta automáticamente de Lunes a Viernes a las 8:00 AM.

## 📁 Estructura
- **.github/workflows/daily-capture.yml**: define el workflow de GitHub Actions que captura los daily y genera los archivos.
- **.github/ISSUE_TEMPLATE/daily.yml**: plantilla del formulario para crear un daily desde una issue.
- **.daily/**: carpeta donde se guardan los archivos Markdown diarios generados.
- **DAILY_LOG.md**: registro consolidado con los daily realizados.
- **README.md**: documentación del proyecto y uso del workflow.