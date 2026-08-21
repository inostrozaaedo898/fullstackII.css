```markdown
# 🛒 Lo Quieres, Te Lo Vendo - Maquetación y Frameworks CSS

Este repositorio contiene el desarrollo del proyecto **"Lo quieres, te lo vendo"**,
 un sitio web para una PYME comercializadora ubicada en Santiago de Chile.

 El proyecto abarca desde la maquetación semántica en HTML5 puro hasta la implementación de diseño responsivo con CSS3 tradicional, Bootstrap 5 y Materialize CSS.

---

## 📂 Estructura del Repositorio

fullstackII.css/
├── index.html               # Paso 1: Inicio en HTML5 puro
├── contacto.html            # Paso 1: Formulario de contacto en HTML5
├── assets/
│   ├── css/
│   │   └── style.css        # Paso 2: Estilos externos y Media Queries manuales
│   └── images/
│       └── Tienda.jpg    # Recursos de imágenes
├── bootstrap/               # Paso 3: Refactorización con Bootstrap 5
│   ├── index.html
│   └── contacto.html
└── materialize/             # Paso 4: Refactorización con Materialize CSS
    ├── index.html
    └── contacto.html

```

---

## Fases de Desarrollo

### Paso 1: Maquetación HTML5 Base

* Estructuración mediante etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
* Menú de navegación inicial utilizando enlaces separados por el carácter `|`.
* Aplicación de estilos inline en etiquetas específicas según la pauta técnica (`<h1>` y `<p>`).
* Construcción del formulario de contacto base en `contacto.html`.

### Paso 2: CSS Externo y Responsividad Manual

* Creación y vinculación de la hoja de estilos externa `assets/css/style.css`.
* Estilización personalizada para el menú (fondo azul con enlaces blancos) y pie de página (fondo negro).
* Implementación de diseño responsivo manual con `@media` queries para 3 pantallas:
* **Móvil:** hasta 576px (menú vertical apilado).
* **Tablet:** entre 577px y 992px (contenido al 80% de ancho).
* **Escritorio:** superior a 992px (contenido al 60% de ancho).



### Paso 3: Refactorización con Bootstrap 5

* Importación del framework Bootstrap mediante CDN.
* Reemplazo del menú manual por el componente **Navbar** con menú desplegable para móviles.
* Estilización de formularios con las clases nativas `form-control` y `btn`.
* Ajuste de imágenes fluidas con la clase `.img-fluid`.
* Eliminación de las `@media` queries manuales, delegando la adaptabilidad al sistema de grillas de Bootstrap.

### Paso 4: Refactorización con Materialize CSS

* Importación de Materialize CSS mediante CDN.
* Adaptación de la interfaz bajo los lineamientos visuales de Material Design.
* Elaboración de un análisis comparativo sobre facilidad de uso, documentación y diseño entre ambos frameworks.

---

##  Tecnologías Utilizadas

| Tecnología | Rol en el Proyecto |
| --- | --- |
| **HTML5** | Estructuración semántica y formularios |
| **CSS3** | Estilos personalizados y reglas `@media` para responsividad |
| **Bootstrap 5** | Framework UI para maquetación rápida y grillas adaptables |
| **Materialize CSS** | Framework UI basado en la filosofía Material Design |
| **Git / GitHub** | Control de versiones y trabajo colaborativo |

---

## Autores

* **Equipo:** Los Pulentos
* **Asignatura:** Desarrollo Full Stack II (DSY1104)
* **Año:** 2026

```
