# 🎵 MúsicaPro - Página Web de Servicios Musicales

Una página web moderna y profesional para vender servicios musicales y partituras personalizadas.

## 📋 Características

- **Diseño Responsivo**: Se adapta perfectamente a dispositivos móviles, tablets y computadoras
- **Navegación Suave**: Scroll automático entre secciones
- **Filtros Interactivos**: Para categorizar partituras por instrumento
- **Formulario de Contacto**: Con validación de campos
- **Animaciones Modernas**: Efectos visuales atractivos
- **Sistema de Notificaciones**: Feedback visual para el usuario
- **Optimizado para SEO**: Estructura semántica correcta

## 🎯 Secciones Incluidas

### 1. **Header/Navegación**
- Logo y menú de navegación
- Menú hamburguesa para móviles
- Enlaces a todas las secciones

### 2. **Hero Section**
- Título principal atractivo
- Descripción de servicios
- Botones de llamada a la acción
- Efectos visuales animados

### 3. **Servicios**
- Partituras Personalizadas
- Composiciones Originales
- Arreglos Musicales
- Cada servicio con iconos y descripción detallada

### 4. **Catálogo de Partituras**
- Filtros por categoría (Piano, Guitarra, Violín, Orquesta)
- Precios claros
- Botones de compra
- Diseño de tarjetas atractivo

### 5. **Testimonios**
- Opiniones de clientes satisfechos
- Diseño de tarjetas elegante

### 6. **Formulario de Contacto**
- Campos para nombre, email, servicio y mensaje
- Validación en tiempo real
- Notificaciones de éxito/error

### 7. **Footer**
- Información de contacto
- Enlaces a servicios
- Copyright

## 🚀 Cómo Usar

### 1. **Abrir la Página**
```bash
# Simplemente abre el archivo index.html en tu navegador
# O usa un servidor local:
python -m http.server 8000
# Luego ve a http://localhost:8000
```

### 2. **Personalizar Contenido**

#### **Cambiar Información Personal**
Edita el archivo `index.html`:
- Cambia "MúsicaPro" por tu nombre o marca
- Actualiza la información de contacto
- Modifica los precios de las partituras
- Añade tus propias partituras al catálogo

#### **Modificar Servicios**
En la sección de servicios, puedes:
- Cambiar los títulos y descripciones
- Añadir más servicios
- Modificar los iconos (usando Font Awesome)

#### **Actualizar Partituras**
En la sección de partituras:
- Cambia los títulos y descripciones
- Actualiza los precios
- Añade más categorías de filtros
- Incluye imágenes reales de tus partituras

### 3. **Personalizar Estilos**

Edita el archivo `styles.css`:
- Cambia los colores principales (busca `#6366f1`)
- Modifica las fuentes
- Ajusta espaciados y tamaños
- Personaliza animaciones

### 4. **Añadir Funcionalidad**

Edita el archivo `script.js`:
- Conecta el formulario a un backend real
- Añade un sistema de pagos
- Implementa un carrito de compras
- Conecta con una base de datos

## 🎨 Personalización Avanzada

### **Cambiar Colores**
```css
/* Color principal */
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #f59e0b;
}
```

### **Añadir Más Partituras**
```html
<div class="sheet-item" data-category="tu-categoria">
    <div class="sheet-image">
        <img src="ruta-a-tu-imagen.jpg" alt="Nombre de la partitura">
    </div>
    <div class="sheet-info">
        <h3>Nombre de la Partitura</h3>
        <p>Descripción</p>
        <span class="price">€XX</span>
        <button class="btn btn-primary">Comprar</button>
    </div>
</div>
```

### **Conectar Formulario a Email**
```javascript
// En script.js, reemplaza la simulación por envío real
contactForm.addEventListener('submit', async function(e) {
    e.preventDefault();
    
    // Enviar a tu servidor o servicio de email
    const response = await fetch('/api/contact', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(formData)
    });
});
```

## 📱 Responsive Design

La página está optimizada para:
- **Móviles**: 320px - 768px
- **Tablets**: 768px - 1024px
- **Desktop**: 1024px+

## 🔧 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con Flexbox y Grid
- **JavaScript ES6+**: Interactividad y animaciones
- **Font Awesome**: Iconos profesionales
- **Google Fonts**: Tipografía Inter

## 📈 Optimizaciones Incluidas

- **Performance**: Código optimizado y ligero
- **SEO**: Meta tags y estructura semántica
- **Accesibilidad**: Navegación por teclado y lectores de pantalla
- **Cross-browser**: Compatible con todos los navegadores modernos

## 🎵 Próximas Mejoras Sugeridas

1. **Sistema de Pagos**: Integrar PayPal, Stripe o similar
2. **Galería de Partituras**: Vista previa de las partituras
3. **Blog Musical**: Artículos sobre música y composición
4. **Sistema de Usuarios**: Registro y login de clientes
5. **Carrito de Compras**: Para compras múltiples
6. **Chat en Vivo**: Soporte al cliente en tiempo real
7. **Portfolio**: Galería de trabajos realizados

## 📞 Soporte

Para personalizar o mejorar la página:
1. Revisa los comentarios en el código
2. Modifica los archivos según tus necesidades
3. Prueba en diferentes dispositivos
4. Optimiza las imágenes antes de subirlas

## 📄 Licencia

Este proyecto es de uso libre. Puedes modificarlo y usarlo para tu negocio musical.

---

**¡Que la música nunca pare! 🎼** 