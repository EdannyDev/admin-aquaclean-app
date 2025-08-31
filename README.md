# 🚀AquaClean Admin - Frontend  

## 📌Descripción  
**AquaClean Admin** es el **panel administrativo** del sistema **IoT AquaClean**.  

Su objetivo principal es:  
- Gestionar los formularios de contacto enviados desde la web informativa.  
- Enviar y recibir **notificaciones push en tiempo real**.  
- Funcionar como una **PWA**, con soporte **offline** y una interfaz ligera.  

## 🛠️Tecnologías utilizadas  

- **Framework:** Next.js  
- **Estilos:** Emotion Styled  
- **Iconos:** FontAwesome  
- **Llamadas a API:** Axios  
- **Gestor de paquetes:** Yarn  
- **uuid:** Generación de identificadores únicos en datos locales.  
- **web-push:** Integración con backend para notificaciones push.  
- **push.js:** Notificaciones nativas del navegador.  

## ⚙️Instalación y ejecución  

```bash
# 1. Clonar el repositorio
git clone https://github.com/EdannyDev/admin-aquaclean-app.git

# 2. Instalar dependencias
yarn install

# 3. Crear archivo de entorno
En la raíz del proyecto, crea un archivo .env.local con:
NEXT_PUBLIC_VAPID_PUBLIC_KEY=tu_vapid_public_key

# 4. Ejecutar la aplicación
yarn dev

# 5. Abrir en el navegador
http://localhost:3000

```

## ✨Características principales
- Gestión de formularios enviados por los usuarios.
- Notificaciones push en tiempo real.
- Soporte offline gracias a Service Worker.
- Interfaz ligera y moderna.

## 🔗Enlaces útiles
Backend: https://github.com/EdannyDev/backend-aquaclean

Web informativa: https://github.com/EdannyDev/aquaclean-app
