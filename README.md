# 📚 Biblioteca Horizonte

Proyecto **Taller Final: Ecosistema Web** — Interfaz multipágina completamente responsiva desarrollada con **HTML5 + Bootstrap 5**, sin CSS personalizado.

## 🎯 Tema
Sitio web de una biblioteca pública ("Biblioteca Horizonte") con landing page, módulo de autenticación y dashboards de administración y cliente.

## 🛠️ Tecnologías
- HTML5
- [Bootstrap 5.3](https://getbootstrap.com/) (vía CDN)
- [Bootstrap Icons](https://icons.getbootstrap.com/) (vía CDN)
- `bootstrap.bundle.min.js` como único script del proyecto

## 📂 Estructura del proyecto

```
taller4/
├── app/
│   ├── login.html       -> Inicio de sesión
│   ├── registro.html    -> Registro de nuevos usuarios
│   ├── recuperar.html   -> Recuperación de contraseña
│   ├── admin.html       -> Dashboard administrativo
│   └── cliente.html     -> Dashboard de usuario/cliente
├── assets/
│   └── img/             -> Imágenes y logos utilizados
├── index.html            -> Landing Page
└── README.md
```

## 🧩 Páginas y componentes

### Landing Page (`index.html`)
- Navbar fija (`fixed-top`) con menú hamburguesa responsivo.
- Carrusel principal con 3 imágenes, texto superpuesto y botones de acción.
- Sección de tarjetas (`card`) con los servicios de la biblioteca.
- Sección de catálogo destacado.
- Footer oscuro estructurado en columnas.

### Autenticación (`app/`)
- **login.html**: formulario con `form-floating`, checkbox "Recordarme" y botón `w-100`.
- **registro.html**: formulario extendido con grid (`row`, `col-md-6`) agrupando Nombre/Apellidos y Correo/Teléfono.
- **recuperar.html**: formulario con validación visual estática (`is-valid` / `is-invalid`) simulando un error de "Correo no encontrado".

### Dashboards
- **admin.html**: sidebar lateral (oculto en móvil), 4 tarjetas de métricas con `badge`, tabla de usuarios (`table-striped`, `table-hover`, `table-responsive`) con estados por `badge` contextual, botones de acciones y un **modal** para editar registros con datos prellenados.
- **cliente.html**: panel de perfil con foto (`rounded-circle`), sistema de pestañas (`nav-tabs`) para alternar entre préstamos activos e historial, y una alerta descartable (`alert-warning alert-dismissible`) recordando la devolución de un libro.

## 🚀 Despliegue
Este proyecto está desplegado con **GitHub Pages**.

🔗 Enlace de despliegue: `[PEGAR AQUÍ EL ENLACE DE GITHUB PAGES]`

## 👩‍💻 Autor
Taller desarrollado como práctica de HTML + Bootstrap + Git — SENA.
