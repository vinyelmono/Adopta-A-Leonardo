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

## 🛠️ Tecnologías

- HTML5
- CSS3 (Flexbox, Grid, degradados, `clamp()`, *media queries*)
- JavaScript (vanilla)
- Git y GitHub

## 👥 Autores
KaroolTheMonoo
leonardo-cruz12
roberto3T
pablof007289


## 📄 Licencia

MIT License.