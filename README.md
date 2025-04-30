# infonext
Información sobre nextjs

## Indice

## 1 Introducción y ventajas de Next.js

## 2 Renderizado: SSR, SSG, ISR y CSR

## 3 Routing y estructura de archivos

## 4 API Routes y capacidades fullstack

## 5 Optimización y despliegue


### 1. **Introducción y ventajas de Next.js**  
Next.js es un framework de React que permite construir aplicaciones web modernas con renderizado del lado del servidor, rutas automáticas y capacidades fullstack, todo en un solo proyecto.



### 2. **Renderizado: SSR, SSG, ISR y CSR**  
Next.js permite elegir cómo se renderiza cada página:  
- **SSR** (Server-Side Rendering): en cada request.  
- **SSG** (Static Site Generation): en build time.  
- **ISR** (Incremental Static Regeneration): mezcla lo mejor de ambos.  
- **CSR** (Client-Side Rendering): tradicional en React.  



### 3. **Routing y estructura de archivos**  
El enrutamiento se basa en la estructura de carpetas (`pages/` o `app/`). Los archivos `.js` o `.tsx` se convierten en rutas automáticamente. Soporta rutas dinámicas, anidadas y layout persistente en `app/`.



### 4. **API Routes y capacidades fullstack**  
Podés crear endpoints backend en la carpeta `/api`, lo que te permite manejar formularios, autenticación o conectarte a bases de datos sin necesidad de otro servidor.


### 5. **Optimización y despliegue**  
Next incluye herramientas como `next/image` para imágenes optimizadas, `next/font` para tipografías eficientes y está pensado para ser desplegado en Vercel con un clic, aunque también funciona en otras plataformas.
