# Misión: PPT del Terror 💀

Un juego de supervivencia académica creado con React, Vite y Tailwind CSS. Tu objetivo es esquivar los obstáculos académicos y subir tu tarea antes de que el profesor te repruebe.

## ⚠️ Aclaración Importante
**NO NECESITAS NINGUNA API KEY.**
Este juego es 100% estático y corre localmente en tu navegador. Si leíste instrucciones sobre claves de Google anteriormente, eran parte de una plantilla genérica y puedes ignorarlas.

## 🚀 Cómo ejecutar el juego

Tienes dos formas de correrlo:

### Opción A: Usando Docker (Lo más fácil para desplegar)
Si ya tienes el `Dockerfile` configurado:

1. **Construir la imagen:**
   ```bash
   docker build -t ppt-attack .
   ```

2. **Correr el contenedor:**
   ```bash
   docker run -p 8080:80 ppt-attack
   ```

3. Abre tu navegador en: `http://localhost:8080`

### Opción B: Ejecución Local (Node.js)
Si prefieres instalar las librerías en tu sistema (Debian/Windows/Mac):

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Iniciar modo desarrollo:**
   ```bash
   npm run dev
   ```

## 🎮 Controles
- **Flechas del teclado:** Mover al estudiante.
- **Objetivo:** Recolectar los disquetes (💾) para subir el PPT.
- **Evita:** Los proyectiles del profesor (❌) y las tareas extra (📝).

## 🛠 Tecnologías
- React 18
- TypeScript
- Tailwind CSS
- Canvas API (para la lógica del juego)
- Docker + Nginx (para producción)
