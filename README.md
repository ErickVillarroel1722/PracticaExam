# PracticaExamen

**Autor:** Erick Villarroel  
**Descripción:**  
Aplicación desarrollada con **Vue.js** y **Firebase** que permite mostrar la ubicación actual del usuario y ofrece una funcionalidad de chat en tiempo real.

---

## Funcionalidades

- **Visualización de la ubicación:**  
  Utiliza la API de geolocalización para obtener y mostrar la ubicación actual del usuario en tiempo real.

- **Chat interactivo:**  
  Implementación de mensajería en tiempo real mediante Firebase para una experiencia fluida.

---

## Capturas de pantalla

### Inicio de la aplicación
<img src="https://github.com/user-attachments/assets/e90b6ad0-26a3-4c87-b4f8-9044ccd4a0c2" alt="Inicio de la aplicación" width="400">

### Ubicación en tiempo real
<img src="https://github.com/user-attachments/assets/6f302226-33fc-47b9-b04f-831516c12243" alt="Ubicación en tiempo real" width="400">

### Chat funcional
<img src="https://github.com/user-attachments/assets/ac35580b-7528-4f07-bcf4-7e1dcb654274" alt="Chat funcional" width="400">

---

## Instalación

Sigue estos pasos para clonar y ejecutar el proyecto localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/PracticaExamen.git
   cd PracticaExamen

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Configura las variables de entorno en un archivo `.env`:
   ```plaintext
   VITE_API_KEY=tu-api-key
   VITE_AUTH_DOMAIN=tu-auth-domain
   VITE_PROJECT_ID=tu-project-id
   VITE_STORAGE_BUCKET=tu-storage-bucket
   VITE_MESSAGING_SENDER_ID=tu-messaging-sender-id
   VITE_APP_ID=tu-app-id
   ```

4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

---

## Construcción de la APK

1. Asegúrate de tener configurado **Capacitor**.
2. Ejecuta el siguiente comando para construir la APK:
   ```bash
   ionic capacitor build android
   ```
3. Abre el proyecto en Android Studio y genera la APK desde allí.

---

## Tecnologías utilizadas

- **Frontend:** Vue.js, Capacitor
- **Backend:** Firebase (Auth, Firestore, Storage)
- **Otros:** Geolocalización, API de Google Maps (opcional)

---

¡Siéntete libre de usarlo y mejorarlo!
```
