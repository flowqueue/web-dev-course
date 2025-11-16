# WebDev Course – F1nTrack

<!-- * Carátula -->

# Informe Trabajo Final 📙

<img src="assets/images/Banner-UPC.png" alt="Banner UPC">

### Universidad Peruana de Ciencias Aplicadas ♨️  
**Ingeniería de Software - 2025-02**  

**Sección:** 7357  
**Docente:** Rafael Oswaldo Castro Veramendi
**StartUp:** ProtectX  

---

### Repositorio  
[https://github.com/ProtectX-5377/webdev-course-protectx](https://github.com/ProtectX-5377/webdev-course-protectx.git)

### Prácticas  
Usaremos únicamente **CodePen** ([https://codepen.io](https://codepen.io)) para todas las actividades prácticas del curso.

---

##  Contenido del Curso

### 1 Introducción y Conceptos  
**Tema:** Introducción al desarrollo web (¿qué es un sitio web?)  
**Duración estimada:** 5 minutos  

**Descripción:**  
Descubre qué es el **desarrollo web** y cómo funcionan los sitios web detrás de escena.  
Aprenderás cómo los navegadores y los servidores se comunican, y qué lenguajes hacen posible una página web.  

**Conceptos clave:**  
- Un sitio web es un conjunto de archivos almacenados en un **servidor**.  
- El **navegador** (como Chrome o Firefox) solicita esos archivos y los muestra al usuario.  
- El **desarrollo web** consiste en escribir esos archivos usando **HTML y CSS**.  
- **HTML** define la estructura del contenido.  
- **CSS** da color, estilo y formato visual.  

.


### 2️ Estructura HTML  
**Tema:** Estructura HTML básica (etiquetas, elementos, atributos)  
**Duración estimada:** 10 minutos  

**Descripción:**  
Aprende a construir la estructura base de una página web usando **HTML**.  
Descubre cómo funcionan las **etiquetas**, los **elementos** y los **atributos**, y crea tu primera página desde cero.

**Código de ejemplo:**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi primera página</title>
  </head>
  <body>
    <h1>Bienvenidos</h1>
    <p>Mi nombre es F1nTrak y me encanta aprender HTML.</p>
    <h2>Atributos en HTML</h2>
    <p>Ejemplo de enlace con atributos:</p>
    <a href="https://www.google.com" target="_blank">Ir a Google</a>
    <p>Ejemplo de imagen con atributos:</p>
    <img src="https://via.placeholder.com/150" alt="Imagen de ejemplo" />
    <!-- Este es un comentario: no se verá en la página, solo en el código -->
  </body>
</html>
```

**Conceptos clave:**  
- `<!DOCTYPE html>` → Indica que el documento usa HTML5.  
- `<html>` → Contiene todo el documento web.  
- `<head>` → Guarda la información interna (metadatos, título, CSS).  
- `<body>` → Contiene el contenido visible.  
- `<a>` y `<img>` → Incluyen **atributos** (`href`, `src`, `alt`, etc.).  

**Práctica:**  
En **CodePen**, crea tu página con:  
1️ Un título con tu nombre o proyecto.  
2️ Un párrafo sobre ti.  
3️ Un enlace a tu red social favorita.  
4️ Una imagen con texto alternativo.  

---

### 3️⃣ Contenido HTML  
**Tema:** Elementos HTML comunes (encabezados, párrafos, listas, imágenes, enlaces)  
**Duración estimada:** 8 minutos  

**Descripción:**  
Aprende a estructurar el contenido usando **etiquetas comunes de HTML**.  
Organiza tu texto, crea listas y agrega imágenes y enlaces de manera correcta.  

**Etiquetas principales:**  
- Encabezados: `<h1>` a `<h6>`  
- Párrafos: `<p>`  
- Listas: `<ul>` (no ordenada) y `<ol>` (ordenada)  
- Elementos de lista: `<li>`  
- Enlaces: `<a href="...">Texto</a>`  
- Imágenes: `<img src="..." alt="...">`

**Ejemplo:**

```html
<h1>Sobre mí</h1>
<p>Hola, soy F1nTrak y me gusta el desarrollo web.</p>

<h2>Mis hobbies</h2>
<ul>
  <li>Programar</li>
  <li>Escuchar música</li>
  <li>Jugar fútbol</li>
</ul>

<p>Puedes conocer más en 
<a href="https://www.linkedin.com" target="_blank">mi perfil</a>.</p>
```

**Práctica:**  
Crea una mini biografía con una lista de tus pasatiempos, una imagen y un enlace.  

---

### 4️⃣ Estilos con CSS  
**Tema:** Introducción a CSS (selectores, propiedades, color, fuente, diseño)  
**Duración estimada:** 10 minutos  

**Descripción:**  
Aprende a usar **CSS** para dar estilo a tus páginas.  
Usarás selectores y propiedades para cambiar colores, fuentes y márgenes.

**Ejemplo:**

```css
body {
  background-color: #f4f4f4;
  font-family: 'Poppins', sans-serif;
}

h1 {
  color: #0077ff;
  text-align: center;
}

p {
  color: #333;
  line-height: 1.6;
}

img {
  border-radius: 10px;
}
```

**Conceptos clave:**  
- Los **selectores** indican qué elemento se va a modificar.  
- Las **propiedades** definen el estilo (color, fuente, tamaño).  
- Se puede usar CSS en el `<head>` o en un archivo externo `.css`.  

**Práctica:**  
Aplica color, bordes y fuentes personalizadas a tu página HTML creada en la Lección 2.  

---

### 5️⃣ Proyecto y Cierre  
**Tema:** Creación de una página web básica  
**Duración estimada:** 15 minutos  

**Descripción:**  
Combina todo lo aprendido en un proyecto final:  
una **página personal o de tu startup F1nTrack**.  

**Pasos sugeridos:**  
1️⃣ Diseña un encabezado con tu nombre o logo.  
2️⃣ Agrega una sección de presentación con texto e imagen.  
3️⃣ Incluye enlaces a redes sociales.  
4️⃣ Aplica estilos CSS coherentes y colores agradables.  

**Errores comunes a evitar:**  
- No cerrar etiquetas.  
- No usar texto alternativo en imágenes.  
- Usar demasiados colores o fuentes diferentes.  

**Entrega final:**  
Sube tu proyecto a **CodePen** o **GitHub Pages**, y graba un breve video mostrando tu página funcionando.  


