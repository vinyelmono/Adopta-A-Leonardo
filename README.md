# 🐾 Adopta una Mascota

Sitio web de un refugio de animales sin fines de lucro dedicado a rescatar, cuidar y encontrar hogar para perros y gatos abandonados. Proyecto escolar desarrollado con HTML, CSS y JavaScript.

## 📋 Descripción

La página presenta el refugio, muestra a las mascotas disponibles para adopción y permite a los visitantes conocer la ubicación, el horario y ponerse en contacto con el equipo.

## ✨ Características

- **Encabezado fijo** con menú de navegación que se mantiene visible al hacer scroll.
- **Menú con sección activa**: el enlace de la sección que se está viendo se subraya automáticamente (JavaScript con `IntersectionObserver`).
- **Hero** con mensaje principal y botón de llamada a la acción.
- **Sobre nosotros**: misión del refugio y valores (Responsabilidad, Cuidado, Amor).
- **Adóptame**: tarjetas de mascotas con efecto al pasar el mouse.
- **Visítanos**: ubicación, horario, actividades y botón "Cómo llegar" hacia Google Maps.
- **Contáctanos**: formulario con nombre, correo y mensaje.
- **Diseño responsivo** para pantallas pequeñas.

## 🗂️ Estructura del proyecto

```
.
├── index.html    # Estructura y contenido de la página
├── styles.css    # Estilos y diseño responsivo
└── README.md
```

## 🚀 Cómo ejecutarlo

No requiere instalación ni dependencias.

1. Clona el repositorio:
   ```bash
   git clone <URL-DEL-REPOSITORIO>
   ```
2. Entra a la carpeta del proyecto:
   ```bash
   cd <nombre-de-la-carpeta>
   ```
3. Abre `index.html` en tu navegador (doble clic o con la extensión *Live Server* de VS Code).

## 🌿 Ramas

| Rama | Descripción | Pull request |
| --- | --- | --- |
| `main` | Rama principal (por defecto) con la versión estable del proyecto. | — |
| `feature/hero` | Desarrollo de la sección principal (hero) de la página. | — |
| `nosotros` | Desarrollo de la sección "Sobre nosotros". | — |
| `nosotrosytarjetas` | Sección "Sobre nosotros" y tarjetas de mascotas ("Adóptame"). | #2 |
| `contacto` | Sección de contacto con su formulario. | #1 |

### Flujo de trabajo

1. Cada sección o funcionalidad se desarrolla en su propia rama a partir de `main`.
2. Al terminar, se abre un *Pull Request* hacia `main`.
3. Se revisan los cambios y se fusionan (*merge*) a `main`.

## 💻 Comandos de Git

### 1. Primera configuración (una sola vez por persona)

| Comando | ¿Qué hace? |
| --- | --- |
| `git config --global user.name "Tu Nombre"` | Define cómo aparecerá tu nombre en los commits |
| `git config --global user.email "tu@correo.com"` | Define el correo asociado a tus commits |

### 2. Crear o copiar el repositorio

| Comando | ¿Qué hace? |
| --- | --- |
| `git init` | Convierte la carpeta actual en un repositorio de Git |
| `git clone <URL-del-repositorio>` | Copia un repositorio remoto a tu computadora |
| `git remote add origin <URL>` | Conecta tu repositorio local a uno remoto |
| `git remote -v` | Muestra a qué repositorios remotos está conectado |

### 3. Trabajo diario (guardar mis cambios)

| Comando | ¿Qué hace? |
| --- | --- |
| `git status` | Muestra el estado actual: archivos modificados, nuevos, en conflicto |
| `git add <archivo>` | Prepara un archivo (o varios) para el commit |
| `git add .` | Prepara todos los archivos modificados |
| `git commit -m "mensaje"` | Guarda una versión («foto») de los cambios con un mensaje |
| `git log --oneline` | Muestra el historial de commits (uno por línea) |
| `git diff` | Muestra los cambios que aún no se han preparado |

### 4. Ramas

| Comando | ¿Qué hace? |
| --- | --- |
| `git branch` | Lista las ramas y marca en cuál estás |
| `git branch <nombre>` | Crea una rama nueva (sin moverse a ella) |
| `git checkout -b <nombre>` (o `git switch -c <nombre>`) | Crea una rama nueva y se cambia a ella |
| `git checkout <rama>` (o `git switch <rama>`) | Se cambia a otra rama ya existente |
| `git branch -d <rama>` | Elimina una rama ya integrada |

### 5. Subir y bajar cambios (remoto)

| Comando | ¿Qué hace? |
| --- | --- |
| `git push -u origin <rama>` | Sube la rama por primera vez y la conecta al remoto |
| `git push` | Sube los commits siguientes de esa rama |
| `git pull` | Baja los cambios de la rama remota y los integra a tu copia |

### 6. Integrar ramas (merge)

| Comando | ¿Qué hace? |
| --- | --- |
| `git checkout main` | Se cambia a la rama principal |
| `git pull` | Asegura que `main` esté actualizada |
| `git merge <rama>` | Integra los cambios de la rama en `main` |
| `git log --graph --oneline` | Muestra el historial con las ramas como un gráfico |
| `git log --graph --oneline --all` | Muestra el gráfico con todas las ramas (evidencia de la integración final) |

### 7. Resolver conflictos

| Comando | ¿Qué hace? |
| --- | --- |
| `git status` | Muestra qué archivos están en conflicto |
| _(editar el archivo)_ | Se decide qué texto conservar |
| `git add <archivo>` | Se confirma que el conflicto está resuelto |
| `git commit -m "conflicto resuelto"` | Se guarda la solución |

## 🛠️ Tecnologías

- HTML5
- CSS3 (Flexbox, Grid, degradados, `clamp()`, *media queries*)
- JavaScript (vanilla)
- Git y GitHub

## 👥 Autores

De la torre Bermudez Karol Steven (KaroolTheMonoo),
Fuentes Lopez Pablo (pablof007289),
Martinez De la cruz Leonardo (leonardo-cruz12),
Rodriguez Ventura Roberto (roberto3T),
## 📄 Licencia

Proyecto con fines educativos.