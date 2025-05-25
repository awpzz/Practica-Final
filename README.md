# Proyecto Web HTML5 - Valorant Spain

## Descripción del proyecto
He creado una página web sobre Valorant, el shooter táctico de Riot Games. Es mi primer proyecto grande de HTML y CSS para la clase de SMX. La web tiene información sobre el juego y sus agentes principales.

## Tema escogido
Elegí Valorant porque es un juego que me gusta mucho y tiene personajes muy variados. Me pareció interesante hacer algo sobre videojuegos en lugar de una empresa normal.

## Layout y estructura
La web tiene 3 páginas:
- **index.html**: Página principal con bienvenida
- **agentes.html**: Información detallada de 4 agentes
- **contacto.html**: Formulario de contacto y redes sociales

### Estructura de cada página:
- Header fijo con logo y navegación
- Main con el contenido principal
- Footer con copyright

He usado etiquetas semánticas como `header`, `nav`, `main`, `section`, `article` y `footer` para que esté bien estructurado.

## Estilo CSS y efectos visuales

### Colores principales:
- Fondo oscuro: #0f1419
- Color principal: #ff4655 (rojo de Valorant)
- Texto: #ffffff
- Secundario: #1e2328

### Efectos que he puesto:
- **Animación de brillo** en el título principal con `@keyframes`
- **Efectos hover** en botones y tarjetas con `transform`
- **Transiciones suaves** con `transition` en todos los enlaces
- **Tarjetas que se mueven** cuando pasas el ratón por encima

### Propiedades CSS importantes:
- `display: grid` para organizar las tarjetas de información
- `display: flex` para el header y navegación
- `position: fixed` para que el menú quede arriba siempre
- `border-radius` para esquinas redondeadas
- `box-shadow` para sombras bonitas

## Decisiones de diseño
Quería que se pareciera un poco a la web oficial de Valorant pero más simple. Por eso elegí:
- Colores oscuros como el juego
- Rojo como color principal (es el color de Valorant)
- Fotos circulares para los agentes
- Botones con efectos para que sea más interactivo

## Responsive Design
He usado media queries para que funcione en móvil:
- En pantallas pequeñas (menos de 768px) el menú pasa a vertical
- Las tarjetas se ponen en una sola columna
- Los textos se hacen más pequeños
- El formulario de contacto se reorganiza

## Imágenes necesarias
Para que funcione todo hay que tener estas imágenes en la carpeta `images/`:
- `logo.png` - Logo de Valorant
- `jett.png` - Foto de Jett
- `sage.png` - Foto de Sage  
- `reyna.png` - Foto de Reyna
- `omen.png` - Foto de Omen

## Cómo verlo
1. Descarga todos los archivos
2. Pon las imágenes en la carpeta `images/`
3. Abre `index.html` en el navegador

## Tecnologías usadas
- HTML5
- CSS3
- Responsive design con media queries

---
