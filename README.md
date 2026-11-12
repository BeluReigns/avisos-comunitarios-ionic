Avisos comunitarios | Angular + Ionic
Aplicación híbrida desarrollada como proyecto académico de Programación Híbrida (IPLACEX). Permite gestionar avisos de una comunidad desde una interfaz adaptable a navegador y Android.
Funcionalidades
- Crear avisos con título, descripción, fecha e imagen.
- Consultar los avisos y visualizar sus detalles en un modal.
- Eliminar avisos desde la pantalla principal.
- Conservar los datos localmente mediante Capacitor Preferences, sin requerir un servidor ni una base de datos externa.
Tecnologías
- Angular 19 y TypeScript para la aplicación y sus componentes.
- Ionic 8 para la interfaz híbrida.
- HTML y SCSS para presentación y estilos.
- Capacitor 7, incluida la API de Preferences, para almacenamiento local e integración con Android.
Cómo ejecutar la versión web
Requisitos: Node.js compatible con las dependencias del proyecto y npm. Se puede instalar Ionic CLI para usar ionic serve.
git clone https://github.com/BeluReigns/examen_ph_bi5.git
cd examen_ph_bi5
npm install
npx ionic serve
Si renombras el repositorio, actualiza la URL y el nombre de carpeta de los comandos anteriores.

Cómo abrir la versión Android
Con Android Studio y el entorno Android configurados:
npx ionic build
npx cap sync android
npx cap open android
Abre el proyecto generado desde Android Studio y ejecútalo en un emulador o dispositivo configurado.
Capturas de pantalla
Las capturas se incorporarán una vez verificadas en ejecución real. Se recomiendan tres: lista de avisos, formulario de creación y detalle de un aviso. No se incluyen imágenes de demostración ficticias.
Alcance del proyecto
Proyecto académico para practicar interfaces híbridas, componentes Angular/Ionic, interacción con formularios y persistencia local. No incluye backend ni almacenamiento en una base de datos externa.

Autora: Belén Ulloa.
