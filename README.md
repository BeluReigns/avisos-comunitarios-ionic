
# Avisos comunitarios | Angular + Ionic

Aplicación híbrida desarrollada como proyecto académico de Programación Híbrida (IPLACEX). Permite gestionar avisos de una comunidad desde una interfaz adaptable a navegador y Android.

## Funcionalidades

- Crear avisos con título, descripción, fecha e imagen.
- Consultar los avisos y visualizar sus detalles en un modal.
- Eliminar avisos desde la pantalla principal.
- Conservar los datos localmente mediante Capacitor Preferences, sin requerir un servidor ni una base de datos externa.

## Tecnologías

- **Angular 19 y TypeScript:** aplicación y componentes.
- **Ionic 8:** interfaz híbrida.
- **HTML y SCSS:** presentación y estilos.
- **Capacitor 7:** almacenamiento local e integración con Android.

## Cómo ejecutar la versión web

### Requisitos

- Node.js compatible con las dependencias del proyecto.
- npm.
- Ionic CLI (opcional).

### Instalación

```bash
git clone https://github.com/BeluReigns/examen_ph_bi5.git
cd examen_ph_bi5
npm install
npx ionic serve
```

## Cómo abrir la versión Android

Con Android Studio y el entorno Android configurados:

```bash
npx ionic build
npx cap sync android
npx cap open android
```

Abre el proyecto generado en Android Studio y ejecútalo en un emulador o dispositivo configurado.

## Alcance del proyecto

Proyecto académico orientado al desarrollo de interfaces híbridas, componentes Angular/Ionic, formularios y persistencia local.

No incluye backend ni almacenamiento en una base de datos externa.

**Autora:** Belén Ulloa.

