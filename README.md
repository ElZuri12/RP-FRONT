# RP-FRONT

El frontend del proyecto RPFrontend es la interfaz de usuario diseñada para facilitar la interacción de estudiantes, profesores y jefes de carrera con la plataforma de gestión de tesis. Esta aplicación fue desarrollada utilizando Next.js, React y TypeScript, lo que garantiza una experiencia de usuario ágil, escalable y segura.

El sistema está optimizado para ofrecer una navegación fluida y un diseño intuitivo, asegurando que los usuarios puedan gestionar, visualizar y consultar las tesis de manera eficiente. Además, el frontend se conecta con una [API RESTful](https://github.com/ElZuri12/RP-BACK) proporcionada por el backend, lo que permite realizar operaciones de creación, actualización y visualización de datos de tesis, manteniendo una comunicación constante y eficaz entre el cliente y el servidor.

Con TailwindCSS, se ha implementado un diseño flexible y moderno que facilita la personalización y mantiene una alta consistencia visual a lo largo de toda la plataforma.


---

## Estructura de Carpetas de RP-FRONT📁

```plaintext
RP-FRONT/ 🏠
├── public/ 🖼️                   # Archivos estáticos (imágenes, fuentes, etc.)
├── src/ 🛠️                       # Código fuente del proyecto
│   ├── app/ 📄                    # Páginas y rutas principales del proyecto
│   │   ├── (auth)/
│   │   ├── repository-intranet/
│   │   ├── page.tsx              # Página principal
│   │   ├── layout.tsx            # Layout global de la aplicación
│   ├── assets/ 🎨                # Estilos globales y fuentes
│   ├── components/ ⚙️            # Componentes reutilizables
│   ├── hooks/ 🔧                 # Hooks personalizados
│   │   ├── useAuth.ts            # Hook para autenticación
│   │   └── ...                   # Otros hooks reutilizables
│   ├── lib/ 🔗                   
│   ├── redux/ 🔥                 # Lógica de estado global con Redux
│   │   ├── store.ts              # Configuración del store de Redux
│   │   ├── features/             
│   │   └── services/                   
├── .eslintrc.json                
├── .gitignore                   
├── next.config.ts               
├── package.json                  
├── postcss.config.mjs           
├── README.md                    
├── tailwind.config.ts           
└── tsconfig.json                 
```

---

### Descripción de Carpetas Principales

- **public/**: Contiene los recursos estáticos como imágenes y archivos SVG.
- **src/app/**: Contiene las páginas principales del proyecto, incluyendo el layout y la estructura de la aplicación.
- **src/assets/**: Contiene fuentes y estilos globales.
- **src/components/**: Componentes reutilizables de la aplicación.
- **src/hooks/**: Hooks personalizados para lógica reutilizable.
- **src/lib/**: Funciones y utilidades compartidas.
- **src/redux/**: Configuración y lógica de estado global utilizando Redux.

---

## Requisitos Previos

- [Node.js](https://nodejs.org/) (versión 16 o superior)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)

---

## Tecnologías Utilizadas 🧰

- **Next.js** 🚀: Framework de React para aplicaciones web.
- **TailwindCSS** 🎨: Framework de utilidades CSS.
- **Redux** 🔥: Manejo de estado global.
- **TypeScript** 🔠: Tipado estático para JavaScript.

