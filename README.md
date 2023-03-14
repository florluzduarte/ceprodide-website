# CEPRODIDE - Web Institucional

![logo ceprodide](https://res.cloudinary.com/dgixc3e9z/image/upload/v1678804701/website-ceprodide/metatags/metatags-ceprodide_kqoceq.png)

## 📌 Introducción y resumen del proyecto

Este proyecto es un sitio web institucional que desarrollé para el Centro de Proyecto, Diseño y Desarrollo de FADU-UBA.

Además de proveer información relevante sobre el Centro, el sitio contempla un espacio de publicaciones (blog) donde se iran actualizado los artículos y documentos desarrollados por los investigadores, así como también, una sección dedicada a la difusión de los proyectos de investigación vigentes dentro del CEPRODIDE.

## 🚀 Deploy

Pueden acceder al sitio desde: [www.ceprodide.com.ar](https://www.ceprodide.com.ar)

## 💼 Mi rol en el proyecto

- Frontend Developer
- UX/UI Designer

## 🎯 Necesidades del cliente

- Desarrollar un espacio web que pueda servir como consulta y repositorio de los trabajos desarrollados por los investigadores que forman parte de este Centro de Investigación.
- Difundir las publicaciones y proyectos de investigación del Centro.
- Proveer información de contacto y consulta para habilitar la comunicación con personas interesadas en el trabajo desarrollado al interior del Centro.

## 🔨 Tecnologías utilizadas

`Astro` --> Como framework web.  
Se decidió trabajar con esta tecnología porque:

- Ofrece excelente performance para sitios web con gran cantidad de contenido
- Su estrategia de "Islas de contenido" permite minimizar la cantidad de JavaScript innecesario
- Permite un buen trabajo con componentes reutilizables

`Astro-Icons` --> Para el trabajo con íconos y optimización de gráficos SVG  
`JavaScript` --> Como lenguaje de programación  
`TypeScript` --> Para generar interfaces que faciliten el trabajo con datos y props  
`Netlify` --> Como servicio para el deploy del proyecto  
`Cloudinary` --> Como servicio para el almacenamiento y procesamiento de assets (imágenes)  
`CSS` --> Para los estilos
`HTML` --> Para la estructura
`Figma` --> Para realizar diseños y prototipos

## 🧞 Comandos

Todos los comandos corren desde el root del proyecto, utilizando la terminal:

| Comando                | Acción realizada                                   |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Instala todas las dependencias                     |
| `npm run dev`          | Inicia un server de desarrollo en `localhost:3000` |
| `npm run build`        | hace el build de producción en `./dist/`           |
| `npm run preview`      | Para previsualizar el build antes de deployar      |
| `npm run astro ...`    | Comandos de CLI como `astro add`, `astro check`    |
| `npm run astro --help` | Ayuda para utilizar el CLI de Astro                |
