# GESTIA ERP - Frontend

Frontend del sistema **GESTIA ERP**, un ERP modular orientada a la gestión comercial y administrativa.

Este proyecto está construido con **HTML semántico, CSS responsivo y JavaScript puro**, siguiendo una arquitectura escalable inspirada en frameworks modernos como React, Vue, Next.js y Angular.

---

## Objetivo actual

En esta estapa el enfoque es el **módulo de Autenticación (AUTH)**:

- Login
- Registro de usuarios
- Manejo básico de sesión
- Protección de rutas

No se implementan aún módulos como inventario, ventas o productos.

---

## Arquitectura del Frontend

La estructura del proyecto está pensada para crecer sin necesidad de ser reescrita.

```
└──📁frontend
      └── 📁assets # Recursos estáticos
      └── 📁src
      |   └── 📁app # Configuración global
      |   |   ├── guards.js
      |   |   ├── router.js
      |   |   └──store.js
      |   └── 📁pages # Páginas del sistema
      |   |   └── 📁auth
      |   |         ├── auth.js
      |   |         ├── login.html
      |   |         └── registrer.html
      |   └── 📁services # Comunicación con backend
      |   |   ├── auth.service.js
      |   |
      |   └── 📁styles # Estilos globales
      |      └── 📁base
      |      |      ├── reset.css
      |      |      ├── variables.css
      |      └── main.css
      ├── index.html
      ├── main.js
      └── README.md
```

## Modulo AUTH

### Funciones
- Autenticación de usuarios
- Simulación de sesión con localStorage
- Redirección automática según el estado de sesión

### Archivos clave

```
   📁src
   └──📁pages
   |   └──📁auth
   |      ├── auth.js
   |      ├── login.html
   |      └── registrar.html
   |   
   └──📁services
      ├── auth.service.js

```

---

## Principios del proyecto

- Separación de responsabilidades
- HTML -> estructura
- CSS -> estilos
- JavaScript -> lógica
- Código preparado para migrar a frameworks

---

## Tecnologías usadas

- HTML5 (semántico)
- CSS3 (responsive, modular)
- JavaScript (ES Modules)
- VS Code

---

## Estado del proyecto

En desarrollo – módulo de autenticación

---

## Backend (planificado)

El backend del sistema será desarrollado en **Java con Spring Boot**, exponiendo una API REST consumida por este frontend.

Actualmente el desarrollo se encuentra enfocado únicamente en el frontend.

## Autor

Proyecto desarrollado con fines de aprendizaje y crecimiento profesional en desarrollo web moderno.