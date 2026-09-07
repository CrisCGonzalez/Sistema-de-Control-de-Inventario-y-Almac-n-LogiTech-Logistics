Sistema de Control de Inventario y Almacén — LogiTech Logistics
Panel de control administrativo diseñado para la gestión en tiempo real de entradas, salidas, alertas de stock y métricas operativas de inventario informático y componentes de hardware.

Descripción del Proyecto

El objetivo de este proyecto es proveer una interfaz limpia, intuitiva y altamente funcional para los supervisores de almacén. Permite visualizar de forma rápida los niveles de existencias, productos con bajo stock, despachos diarios y el historial reciente de movimientos por código SKU.

Componentes Principales Seleccionados

Barra Lateral de Navegación (Sidebar): Permite el acceso rápido a las distintas secciones del almacén (Resumen, Catálogo, Proveedores y Movimientos), adaptándose de forma responsiva según el dispositivo.

Tarjetas de Resumen (Stat Cards): Ubicadas en la parte superior del área principal para mostrar indicadores clave (KPIs) como el stock total disponible, envíos del día y alertas de reabastecimiento crítico.

Tabla de Datos Operativa: Diseñada para mostrar información detallada de productos (código SKU, descripción, categoría, estado y existencias) con etiquetas de estado codificadas por color.

Tecnologías Utilizadas

HTML5 Semántico: Uso de etiquetas estructurales (header, aside, main, article, section, footer) y tablas accesibles.

CSS3 Avanzado:

CSS Grid: Implementación de grid-template-areas para maquetar la estructura global de la aplicación de forma sólida e independiente del orden de flujo.

Flexbox: Distribución y alineación interna de componentes dentro del header, las tarjetas informativas y los ítems del menú lateral.

Custom Properties (Variables CSS): Centralización de la paleta de colores (incluyendo fondo vinotinto para la barra lateral) y velocidades de transición.

Media Queries: Adaptación fluida del layout para resoluciones de escritorio, tablet y dispositivos móviles.

SVG Vectorial: Íconos incrustados de manera nativa para evitar dependencias externas de librerías y optimizar la carga.

Decisión de Diseño y Accesibilidad

Decisiones de Diseño:

Estructura Dinámica: Se optó por CSS Grid en la estructura principal para separar claramente el menú navegacional del área de contenido. En pantallas móviles, la barra lateral cambia su disposición a una barra de navegación horizontal simplificada para aprovechar el espacio vertical.

Interacciones Visuales: Transiciones suaves en enlaces del menú y un ligero desplazamiento vertical al interactuar con las tarjetas informativas.

Criterios de Accesibilidad (WCAG):

Atributos ARIA: Inclusión explícita de role="banner", role="navigation", role="main" y role="contentinfo".

Navegación por Teclado: Estilos claros de focus en entradas de texto, botones y enlaces navegables para asegurar una experiencia utilizable sin ratón.

Semántica y Contraste: Uso de un contraste adecuado entre el texto y los fondos, asegurando que los estados de las etiquetas tengan alta legibilidad. Todos los gráficos e íconos SVG incluyen aria-hidden="true" para evitar lecturas redundantes en lectores de pantalla.