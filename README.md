# CoderDocs

**CoderDocs** es una plataforma educativa construida con [Docusaurus](https://docusaurus.io/). Este espacio está diseñado para centralizar contenido de diferentes **rutas de aprendizaje** y  **conceptos técnicos** .

## 🚀 Instalación

Instala las dependencias del proyecto usando el gestor de paquetes de Node:

**Bash**

```
npm install
```

## 💻 Desarrollo Local

Para iniciar el servidor de desarrollo:

**Bash**

```
npm run start
```

El sitio estará disponible en `http://localhost:3000`. Los cambios en los archivos `.md` o `.mdx` se actualizarán automáticamente.

## 🏗️ Construcción (Build)

Para generar los archivos estáticos listos para producción:

**Bash**

```
npm run build
```

## 📁 Estructura de Carpetas de CoderDocs

Para mantener tus rutas de aprendizaje y conceptos organizados, así es como se estructura el proyecto:

**Plaintext**

```
coderdocs/
├── docs/                # Aquí vive el corazón de tu contenido
│   ├── modulo1-python/   # Carpeta para una ruta específica
│   │   ├── conceptos.md
│   │   └── intro.md
│   ├── modulo2-javascript/    # Otra ruta de aprendizaje
│   │   └── nodejs.md
│   └── intro.md         # Página de bienvenida a la documentación
├── blog/                # (Opcional) Para anuncios o tutoriales cortos
├── src/
│   ├── css/             # Estilos personalizados (custom.css)
│   └── components/      # Componentes de React para docs interactivos
├── static/              # Imágenes, PDFs y otros recursos estáticos
├── docusaurus.config.js # Configuración principal (Nombre, logo, Navbar)
├── sidebars.js          # Aquí defines el orden de tus rutas y temas
├── package.json         # Dependencias y scripts de NPM
└── README.md            # Este archivo
```

### Notas clave para tu contenido:

* **`docs/`** : Es donde crearás las subcarpetas para cada "Ruta". Docusaurus generará automáticamente la jerarquía basada en esta estructura.
* **`docusaurus.config.js`** : Asegúrate de cambiar el `title` a **"CoderDocs"** y configurar el `navbar` para que apunte a tus rutas principales.
* **`sidebars.js`** : Si quieres un control total sobre qué temas aparecen primero en el menú lateral, deberás listarlos aquí.
