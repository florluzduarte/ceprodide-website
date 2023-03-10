# CEPRODIDE - Web Institucional

![logo ceprodide](https://res.cloudinary.com/dgixc3e9z/image/upload/v1678804701/website-ceprodide/metatags/metatags-ceprodide_kqoceq.png)

## 馃搶 Introducci贸n y resumen del proyecto

Este proyecto es un sitio web institucional que desarroll茅 para el Centro de Proyecto, Dise帽o y Desarrollo de FADU-UBA.

Adem谩s de proveer informaci贸n relevante sobre el Centro, el sitio contempla un espacio de publicaciones (blog) donde se iran actualizado los art铆culos y documentos desarrollados por los investigadores, as铆 como tambi茅n, una secci贸n dedicada a la difusi贸n de los proyectos de investigaci贸n vigentes dentro del CEPRODIDE.

## 馃殌 Deploy

Pueden acceder al sitio desde: [www.ceprodide.com.ar](https://www.ceprodide.com.ar)

## 馃捈 Mi rol en el proyecto

- Frontend Developer
- UX/UI Designer

## 馃幆 Necesidades del cliente

- Desarrollar un espacio web que pueda servir como consulta y repositorio de los trabajos desarrollados por los investigadores que forman parte de este Centro de Investigaci贸n.
- Difundir las publicaciones y proyectos de investigaci贸n del Centro.
- Proveer informaci贸n de contacto y consulta para habilitar la comunicaci贸n con personas interesadas en el trabajo desarrollado al interior del Centro.

## 馃敤 Tecnolog铆as utilizadas

`Astro` --> Como framework web.  
Se decidi贸 trabajar con esta tecnolog铆a porque:

- Ofrece excelente performance para sitios web con gran cantidad de contenido
- Su estrategia de "Islas de contenido" permite minimizar la cantidad de JavaScript innecesario
- Permite un buen trabajo con componentes reutilizables

`Astro-Icons` --> Para el trabajo con 铆conos y optimizaci贸n de gr谩ficos SVG  
`JavaScript` --> Como lenguaje de programaci贸n  
`TypeScript` --> Para generar interfaces que faciliten el trabajo con datos y props  
`Netlify` --> Como servicio para el deploy del proyecto  
`Cloudinary` --> Como servicio para el almacenamiento y procesamiento de assets (im谩genes)  
`CSS` --> Para los estilos
`HTML` --> Para la estructura
`Figma` --> Para realizar dise帽os y prototipos

## 馃 Comandos

Todos los comandos corren desde el root del proyecto, utilizando la terminal:

| Comando                | Acci贸n realizada                                   |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Instala todas las dependencias                     |
| `npm run dev`          | Inicia un server de desarrollo en `localhost:3000` |
| `npm run build`        | hace el build de producci贸n en `./dist/`           |
| `npm run preview`      | Para previsualizar el build antes de deployar      |
| `npm run astro ...`    | Comandos de CLI como `astro add`, `astro check`    |
| `npm run astro --help` | Ayuda para utilizar el CLI de Astro                |
