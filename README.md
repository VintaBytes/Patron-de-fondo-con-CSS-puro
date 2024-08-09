# Patron de fondo con CSS puro

El proyecto consiste en una página HTML sencilla que aplica un fondo estilizado utilizando propiedades avanzadas de CSS. El fondo está compuesto por una serie de patrones radiales (círculos) que se repiten, creando un efecto visual similar a una textura o patrón.

<span><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/></span>
<span><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/></span>
<span><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></span>

### Captura de pantalla
<img src="https://github.com/VintaBytes/Campo-password-interactivo-en-formularios-HTML/blob/main/captura.png?raw=true">

---

## Descripción del Proyecto

Este proyecto utiliza HTML y CSS para crear un fondo dinámico con patrones radiales. El objetivo es mostrar cómo se puede utilizar CSS avanzado para crear efectos visuales interesantes, incluso sin un conocimiento profundo de la tecnología.

### Archivos del Proyecto

- **index.html**: Contiene la estructura básica de la página web.
- **style.css**: Contiene el código CSS que genera el fondo dinámico.

## ¿Qué hace este código CSS?

El código CSS de este proyecto crea un fondo texturizado mediante la superposición de varios patrones radiales. Cada patrón es un círculo que se repite en toda la página. Además, se establece un color de fondo oscuro que complementa los patrones radiales.

### Desglose del Código CSS

```css
html {
    /* Fondo con patrones radiales */
    background:
        /* Primer patrón: círculos negros con transparencia en el borde */
        radial-gradient(black 35%, transparent 16%) 0 0,

        /* Segundo patrón: círculos negros desplazados 8px */
        radial-gradient(black 35%, transparent 16%) 8px 8px,

        /* Tercer patrón: círculos con transparencia y un ligero color blanco */
        radial-gradient(rgba(255,255,255,.1) 35%, transparent 20%) 0 1px,
        
        /* Cuarto patrón: círculos similares al tercero, pero desplazados 8px en ambas direcciones */
        radial-gradient(rgba(255,255,255,.1) 35%, transparent 20%) 8px 9px;

    /* Color de fondo principal */
    background-color:#282828;

    /* Tamaño del patrón de fondo */
    background-size:16px 16px;
}
```

### Explicación

- **Radial Gradients**: Se utilizan cuatro `radial-gradient` para crear diferentes patrones de círculos que se superponen. Los colores van desde negro hasta un blanco muy transparente, y los patrones están ligeramente desplazados entre sí para crear una textura compleja.

- **Background Color**: Se establece un color de fondo oscuro (`#282828`) que sirve como base para los patrones radiales. Este color asegura que los círculos más claros resalten.

- **Background Size**: El tamaño de cada unidad del patrón es de 16x16 píxeles, lo que hace que el patrón se repita de manera uniforme en toda la página.

## Cómo Utilizar Este Proyecto

1. Descarga los archivos `index.html` y `style.css`.
2. Abre `index.html` en tu navegador web.
3. Observa cómo el fondo dinámico aparece en la página.

Este proyecto es un buen punto de partida para experimentar con fondos dinámicos en CSS y entender cómo se pueden combinar diferentes propiedades para crear efectos visuales complejos.

## Contribuciones

Si tienes ideas para mejorar este proyecto o quieres agregar nuevas funcionalidades, no dudes en hacer un fork y enviar un pull request.

