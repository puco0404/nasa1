# BabyImport - Sitio Web para Importadora de Bebés

## Descripción
Sitio web moderno y responsivo para una importadora de productos para bebés, inspirado en las mejores prácticas de e-commerce del sector infantil.

## Estructura del Proyecto
```
bebe-importadora/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Hoja de estilos
├── js/
│   └── main.js         # JavaScript para interactividad
└── images/             # Carpeta para imágenes (opcional)
```

## Características Principales

### 🎨 Diseño
- **Paleta de colores suave**: Tonos rosados, turquesa y neutros apropiados para el nicho de bebés
- **Tipografía amigable**: Fuente Nunito, redondeada y legible
- **Diseño responsivo**: Se adapta a móviles, tablets y escritorio
- **Iconos intuitivos**: FontAwesome para una navegación visual clara

### 📱 Secciones Incluidas

1. **Header**
   - Información de contacto
   - Carrito de compras
   - Lista de favoritos
   - Menú de navegación sticky

2. **Hero Section**
   - Banner principal con llamada a la acción
   - Mensaje claro de valor

3. **Características**
   - Envío rápido
   - Productos seguros certificados
   - Devolución gratis
   - Soporte 24/7

4. **Categorías**
   - Sillas de Auto
   - Cochecitos
   - Cunas y Moisés
   - Ropa de Bebé
   - Alimentación
   - Juguetes

5. **Productos Destacados**
   - Grid de productos con filtros
   - Sistema de calificaciones
   - Badges (Nuevo, Hot, Sale)
   - Botón de añadir al carrito con animación

6. **Sobre Nosotros**
   - Historia de la empresa
   - Estadísticas clave
   - Ventajas competitivas

7. **Newsletter**
   - Formulario de suscripción
   - Captura de emails para marketing

8. **Contacto**
   - Información de contacto completa
   - Formulario de mensajes
   - Horarios de atención

9. **Footer**
   - Enlaces rápidos
   - Redes sociales
   - Métodos de pago aceptados

### ⚡ Funcionalidades JavaScript

- **Menú móvil hamburguesa**: Navegación optimizada para móviles
- **Filtrado de productos**: Por categoría (Todos, Sillas, Cochecitos, Ropa, Juguetes)
- **Carrito interactivo**: Contador dinámico con animación
- **Scroll suave**: Navegación fluida entre secciones
- **Formularios validados**: Newsletter y contacto con feedback
- **Animaciones al scroll**: Elementos aparecen suavemente
- **Header dinámico**: Sombra al hacer scroll
- **Active nav link**: Resalta la sección actual en el menú

### 🎯 Elementos de E-commerce

- Tarjetas de producto con:
  - Imagen/icono representativo
  - Nombre del producto
  - Calificación con estrellas
  - Precio (con descuento si aplica)
  - Botón de compra
  - Badges promocionales

- Sistema de filtros por categoría
- Carrito de compras funcional (frontend)
- Lista de deseos (wishlist)
- Múltiples métodos de pago visibles

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con variables CSS
- **JavaScript Vanilla**: Sin dependencias externas
- **Font Awesome 6**: Iconografía
- **Google Fonts**: Tipografía Nunito

## Cómo Usar

1. Abre el archivo `index.html` en tu navegador
2. Para producción, sirve los archivos desde un servidor web

```bash
# Opción 1: Usando Python
cd bebe-importadora
python -m http.server 8000

# Opción 2: Usando Node.js (http-server)
npx http-server bebe-importadora

# Opción 3: Usando PHP
cd bebe-importadora
php -S localhost:8000
```

3. Visita `http://localhost:8000` en tu navegador

## Personalización

### Colores
Edita las variables CSS en `css/styles.css`:
```css
:root {
    --primary-color: #FF6B9D;      /* Color principal (rosa) */
    --primary-dark: #E84A7F;       /* Rosa oscuro */
    --secondary-color: #4ECDC4;    /* Turquesa */
    --accent-color: #FFE66D;       /* Amarillo */
}
```

### Productos
Modifica la sección de productos en `index.html`, añadiendo o editando las tarjetas `.product-card`.

### Información de Contacto
Actualiza los datos en las secciones de header y contacto según la información real de la empresa.

## Próximas Mejoras Sugeridas

- [ ] Integrar backend para gestión de pedidos
- [ ] Añadir página de detalle de producto
- [ ] Implementar pasarela de pago real
- [ ] Agregar sistema de usuarios/login
- [ ] Crear panel de administración
- [ ] Optimizar SEO
- [ ] Añadir más productos y categorías
- [ ] Implementar búsqueda de productos
- [ ] Agregar galería de fotos reales
- [ ] Integrar con redes sociales

## Licencia
Libre uso para proyectos comerciales y personales.

---

**BabyImport** 👶 - Tu aliado en el cuidado de los más pequeños
