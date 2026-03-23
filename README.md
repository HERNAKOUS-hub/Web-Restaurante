# Diseño Web Restaurante: La Tintorería

Proyecto final de desarrollo web integral para un restaurante exclusivo situado en unos sótanos históricos del siglo XVII en Madrid. Este proyecto demuestra la aplicación práctica de diseño responsive, accesibilidad, usabilidad web y animaciones interactivas.

## Características Principales

* **Diseño 100% Adaptativo:** Arquitectura fluida y responsive (Grid/Flexbox) que adapta la visualización de 3 columnas en escritorio a 1 columna en dispositivos móviles.
* **Experiencia de Usuario (UX):** Navegación intuitiva con una cabecera global fijada en la parte superior para orientación constante. 
* **Bilingüismo:** Experiencia inmersiva y sin fricciones adaptada a múltiples idiomas.
* **Formularios Optimizados:** Implementación del patrón de diseño "Floating Labels" para reducir la carga cognitiva y optimizar el espacio.

---

## Decisiones de Diseño (Guía de Estilos)

El diseño busca un equilibrio armónico entre la tradición de la alta gastronomía y una interfaz de usuario (UI) moderna, limpia y funcional.

### Sistema Cromático
* **Contraste y Limpieza:** Se utiliza el blanco puro (#ffffff) como fondo base para maximizar la legibilidad y potenciar la limpieza visual. 
* **Colores de Marca:** El "Vino Tinto" (#781f33) es el protagonista y se usa para jerarquizar títulos y llamadas a la acción (CTAs). El "Vino Oscuro" (#5a1726) se reserva para aportar profundidad en las microinteracciones.
* **Salud Visual:** El texto principal emplea un gris antracita (#333333) en lugar de negro puro para mitigar la fatiga visual del usuario.

### Tipografía
La selección tipográfica responde a un esquema dual estratégico:
* **Tradición y Elegancia:** Tipografías Serif (Georgia, Times New Roman) para los títulos (h1, h2, h3) y el cuerpo del texto, evocando el carácter premium del local.
* **Funcionalidad Técnica:** Tipografía Sans-Serif (Arial) para elementos compactos de interfaz, formularios y navegación, asegurando la máxima legibilidad en dispositivos móviles.

### Motion UI (Diseño de Movimiento)
Se ha implementado un sistema de animaciones para aportar una fluidez análoga a la de un servicio de sala de alta categoría:
* **Preloader:** Pantalla de carga introductoria que se desvanece de forma inmersiva tras 0.5 segundos.
* **Scroll Reveal:** Los bloques de contenido emergen progresivamente desde la parte inferior de la pantalla (translación en el eje Y) e interpolan su opacidad en 0.8 segundos coincidiendo con el scroll del usuario, apoyado en un motor de Intersection Observer.
* **Microinteracciones Fotográficas:** La galería gastronómica responde al cursor con un sutil escalado y un ligero descenso de la exposición para invitar a la interacción.

---

## Tecnologías Utilizadas
* HTML5 (Semántico y Accesible)
* CSS3 (Variables, Grid, Flexbox, Transiciones y Animaciones)
* JavaScript (Intersection Observer, manipulación del DOM)
