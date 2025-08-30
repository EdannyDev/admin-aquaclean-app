🚀AquaClean Admin - Frontend

📌Descripción
Este es el panel administrativo de AquaClean IoT.
Su objetivo es gestionar los formularios de contacto enviados desde la web informativa.
Está desarrollado como PWA, con notificaciones push y soporte offline.

🛠️Tecnologías utilizadas
-Framework: Next.js
-Estilos: Emotion Styled
-Iconos: FontAwesome
-Llamadas a API: Axios
-Gestor de paquetes: Yarn
-uuid: Generación de identificadores únicos en datos locales.
-web-push: Integración con backend para enviar notificaciones push.
-push.js: Librería que permite mostrar notificaciones nativas del navegador de forma sencilla.

⚙️Instalación y ejecución

1.-Clonar el repositorio:
git clone https://github.com/EdannyDev/admin-aquaclean-app.git

2.-Instalar dependencias:
yarn install

3.-Crear un archivo .env.local con:
NEXT_PUBLIC_VAPID_PUBLIC_KEY=<tu_vapid_public_key>

4.-Ejecutar la aplicación:
yarn dev

5.-Abrir en el navegador:
http://localhost:3000

✨Características principales:
-Gestión de formularios enviados por los usuarios.
-Notificaciones push en tiempo real.
-Soporte offline gracias a Service Worker.
-Interfaz ligera y moderna.

🔗Enlaces útiles
Backend: https://github.com/EdannyDev/backend-aquaclean
Web informativa: https://github.com/EdannyDev/aquaclean-app