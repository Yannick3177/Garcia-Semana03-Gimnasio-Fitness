# PowerGym OTI | Elite Fitness Center & Training Performance

## 👥 Integrantes
GARCIA YUPANQUI FERDINAND PIERO

## 🎯 Tema Elegido
* Diseño y desarrollo de una **Interfaz Web para un Gimnasio/Fitness - Planes, rutinas, membresías**

## 🛠️ ¿Cómo combinamos Bootstrap y Tailwind CSS?
Para aprovechar lo mejor de ambos mundos sin generar conflictos de estilos, la integración se estructuró de la siguiente manera:

1. **Bootstrap 5.3.3 como Estructura Base:**
   * Se utilizó el sistema de grillas de 12 columnas (`container`, `row`, `col-md-4`, etc.) para garantizar una distribución simétrica y perfectamente responsiva en dispositivos móviles, tablets y escritorios.
   * Se implementaron componentes nativos optimizados, tales como el sistema de navegación (`navbar`, `navbar-toggler`, `dropdown`) y las clases de validación de formularios (`needs-validation`, `invalid-feedback`, `valid-feedback`).

2. **Tailwind CSS (Play CDN) para Estilizado Avanzado (UI/UX):**
   * Se configuró Tailwind mediante su script de configuración en el `<head>` para definir una paleta de colores corporativa personalizada (`brand-dark`, `brand-card`, acentos ambarinos).
   * Se aplicaron utilidades avanzadas de Tailwind como efectos de iluminación ambiental (*glows* con `blur-[160px]`), fondos translúcidos mediante *Glassmorphism* (`backdrop-blur-xl`), microinteracciones en las tarjetas (`hover:-translate-y-2`, transiciones de color en iconos) y tipografía fluida (`text-balance`).

3. **Compatibilidad y Rendimiento:**
   * Ambas librerías se importaron exclusivamente mediante CDNs oficiales estables, evitando el uso de reglas `@import` bloqueantes para asegurar una carga rápida y puntajes óptimos en las auditorías de rendimiento y accesibilidad.