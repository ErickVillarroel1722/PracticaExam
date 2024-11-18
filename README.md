```
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
![Inicio de la aplicación](https://github.com/user-attachments/assets/68d21561-965f-40f9-9167-46062a992bdf)

### Ubicación en tiempo real
![Ubicación en tiempo real](https://github.com/user-attachments/assets/f74c664d-179d-4ea8-ae8a-82083d96b17d)

### Chat funcional
![Chat funcional](https://github.com/user-attachments/assets/4d684600-af74-451f-8e17-382c2f8bad06)

---

## Instalación

Sigue estos pasos para clonar y ejecutar el proyecto localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/PracticaExamen.git
   cd PracticaExamen
   ```

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

## Licencia

Este proyecto está bajo la licencia [MIT](https://opensource.org/licenses/MIT). ¡Siéntete libre de usarlo y mejorarlo!
```
