# Better Upload Skills

Bienvenido a mi repositorio de skills personalizados diseñados para trabajar con **Better Upload** — una librería para subir archivos directamente a almacenamiento compatible con S3 en aplicaciones React/Next.js.

## Instalación

Este repositorio usa [skills.sh](https://skills.sh). Para instalar estos skills, ejecuta el siguiente comando en tu terminal:

```bash
npx skills add https://github.com/juanbarmo05/better-upload-skills
```

## Skills Disponibles

### Better Upload (`better-upload`)

Usa este skill cuando trabajes con Better Upload, agregando subida de archivos a tu app React o Next.js usando URLs pre-firmadas de S3, configurando rutas de subida o callbacks (onBeforeUpload, onAfterSignedUrl, RejectUpload), configurando clientes S3 (AWS S3, Cloudflare R2, MinIO, Backblaze, DigitalOcean Spaces, Tigris, Wasabi), usando los hooks useUploadFiles o useUploadFile, implementando multiparts uploads, manejando progreso o cancelación de subida, usando uploadFile/uploadFiles imperativamente, integrando con TanStack Query o React Hook Form, trabajando con helpers de S3 (deleteObject, presignGetObject, moveObject), o usando los componentes UploadDropzone/UploadButton.

**Características Principales:**

- **Arquitectura**: Subidas directas del navegador a S3 usando URLs pre-firmadas (sin proxy del servidor).
- **Clientes S3**: Soporta AWS S3, Cloudflare R2, MinIO, Backblaze, DigitalOcean Spaces, Tigris y Wasabi.
- **React Hooks**: `useUploadFiles`, `useUploadFile`, y funciones imperativas `uploadFile`/`uploadFiles`.
- **Integraciones**: TanStack Query, React Hook Form, componentes shadcn pre-construidos.
- **Helpers del Servidor**: `deleteObject`, `presignGetObject`, `moveObject`, `copyObject` y más.

Puedes encontrar la definición completa del skill en [skills/better-upload/SKILL.md](./skills/better-upload/SKILL.md).