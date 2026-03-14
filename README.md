# Dental Uno — Sitio Web del Consultorio

Página web informativa para el consultorio dental Dental Uno, desarrollada para presentar los servicios, doctores y facilitar el agendado de citas.

## 🚀 Stack tecnológico

- **Astro** — Framework de desarrollo web para sitios estáticos
- **Tailwind CSS v4** — Framework de estilos utilitarios
- **OpenStreetMap** — Mapa interactivo sin API key

## 📁 Estructura del proyecto
```
/
├── public/
│   ├── images/         → fotos de doctores y assets
│   └── favicon.ico
└── src/
    ├── components/
    │   ├── Navbar.astro
    │   ├── Hero.astro
    │   ├── Doctores.astro
    │   ├── PorQueNosotros.astro
    │   ├── Tratamientos.astro
    │   ├── Ubicacion.astro
    │   └── Footer.astro
    ├── layouts/
    │   └── Layout.astro
    ├── pages/
    │   ├── index.astro
    │   ├── agendar.astro
    │   ├── privacidad.astro
    │   └── terminos.astro
    └── styles/
        └── global.css
```

## 📄 Páginas

| Ruta | Descripción |
|---|---|
| `/` | Página principal con todas las secciones |
| `/agendar` | Formulario para agendar, reagendar o cancelar citas |
| `/privacidad` | Aviso de privacidad |
| `/terminos` | Términos y condiciones |

## 🛠️ Correr el proyecto localmente
```bash
npm install
npm run dev
```

El servidor corre en `http://localhost:4321`

## 📌 Pendientes futuros

- Conectar formulario a WhatsApp Business API o correo real
- Integrar mapa con Google Maps
- Conectar una base de datos para capturar información de pacientes
