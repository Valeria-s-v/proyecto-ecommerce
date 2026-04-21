# ✨ JOLIE - Tienda Online de Moda

> Una tienda online elegante y moderna donde la moda se encuentra con el diseño web responsivo.

![Status](https://img.shields.io/badge/Status-En%20Desarrollo-brightgreen)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple)

---

## 🎯 Descripción del Proyecto

**JOLIE** es mi primer proyecto de página web desarrollado como trabajo práctico académico. Se trata de una tienda online de moda que combina diseño elegante, interfaz intuitiva y responsividad moderna.

El proyecto utiliza **HTML5**, **CSS3** y **Bootstrap 5** como tecnologías base, enfocándose en la maquetación y estilos sin depender de JavaScript para funcionalidades complejas.

---

## ✨ Características Principales

### 🏠 **Página de Inicio**
- Carrusel automático con transiciones suaves
- Sección de acceso rápido con efecto hover
- Tendencias 2026 con grid responsivo
- Destellos dorados decorativos

### 🛍️ **Catálogo de Productos**
- Grid dinámico de 3 columnas (adaptable a móvil)
- Tarjetas con efecto hover (escala y sombra)
- Información clara de producto y precio

### 📦 **Página de Productos**
- Buscador de productos
- Filtros por categoría
- Ordenamiento por precio
- Grid responsive

### 📝 **Formulario de Registro**
- Campos: Nombre, Apellido, Email, Teléfono, Contraseña
- Iconos de visibilidad de contraseña
- Botones Registrarse y Limpiar Formulario
- Validación visual con bordes inferiores

### 🎨 **Diseño Visual**
- Paleta de colores de lujo: Dorado (#c5a36c), Púrpura (#8b4789), Negro (#1a1a1a)
- Gradientes cálidos y destellos dorados
- Animaciones CSS suaves y elegantes
- Tipografía moderna con Playfair Display

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Versión | Uso |
|-----------|---------|-----|
| **HTML** | 5 | Estructura |
| **CSS** | 3 | Estilos y animaciones |
| **Bootstrap** | 5.3.8 | Grid y componentes |
| **Font Awesome** | 6.0.0 | Iconos |
| **Google Fonts** | - | Tipografías |

---

## 📁 Estructura del Proyecto

```
jolie/
├── index.html              # Página de inicio
├── productos.html          # Listado de productos
├── catalogo.html          # Catálogo general
├── registro.html          # Formulario de registro
├── css/
│   ├── style.css          
│   └── registro.css       # Estilos del registro
│   └── catalogo.css       # Estilos del catalogo
│   └── index.css           # Estilos principales
│   └── productos.css       # Estilos del producto
├── img/
│   ├── logo-oficial.png
│   ├── banner2.png
│   ├── 30_off_summer.png
│   └── ... (más imágenes)
└── README.md              # Este archivo
```

---

## 🚀 Características Destacadas

### ✅ Carrusel Automático
```html
<div id="carouselExampleCaptions" class="carousel slide" 
     data-bs-ride="carousel" data-bs-interval="5000">
```
Cambia automáticamente cada 5 segundos con controles manuales.

### ✅ Efecto Hover en Tarjetas
```css
.product-card:hover {
    transform: translateY(-10px) scale(1.02);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
}
```
Las tarjetas se elevan y agrandan suavemente al pasar el mouse.

### ✅ Texto sobre Imágenes
```css
.image-text {
    position: absolute;
    opacity: 0;
    transition: opacity 0.3s ease;
}
.image-container:hover .image-text {
    opacity: 1;
}
```
Los textos aparecen al pasar el mouse sobre las imágenes.

### ✅ Fondo Degradado con Destellos
```css
background: linear-gradient(135deg, #faf8f5 0%, #f0ebe5 50%, #dfd7c8 100%);
```
Gradientes cálidos con efectos de luz dorada.

### ✅ Formulario Elegante
- Inputs con bordes inferiores solo
- Iconos de visibilidad de contraseña
- Validación visual clara
- Botones con efectos hover

---

## 📱 Responsividad

El proyecto es **100% responsivo** con breakpoints en:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Móvil**: Menos de 768px

```css
@media (max-width: 768px) {
    .product-grid {
        grid-template-columns: 1fr;
    }
}
```

---

## 🎓 Aprendizajes Clave

Durante el desarrollo de este proyecto aprendí:

✨ **Maquetación moderna con CSS Grid y Flexbox**
- Distribución eficiente de elementos
- Espaciado y alineación precisos

✨ **Animaciones CSS puras**
- Transiciones suaves
- Transformaciones 2D
- Animaciones keyframe

✨ **Diseño responsivo**
- Mobile-first approach
- Media queries efectivas
- Flexible layouts

✨ **Bootstrap 5**
- Componentes reutilizables
- Sistema de grid
- Carrusel automático

✨ **Buenas prácticas**
- Código HTML semántico
- CSS modular y organizado
- Nombres de clases descriptivos

---

## 🎨 Paleta de Colores

```
Primario:     #1a1a1a (Negro)
Secundario:   #c5a36c (Dorado)
Acento:       #8b4789 (Púrpura)
Fondo:        #f5f3f0 (Beige)
Error:        #dc3545 (Rojo)
```

---

## 📸 Capturas de Pantalla

### Página de Inicio
- Carrusel con textos dorados
- Sección de acceso rápido con 3 imágenes
- Tendencias 2026 con grid de productos

### Página de Productos
- Buscador y filtros funcionales
- Grid de 3 columnas
- Efecto hover en tarjetas

### Formulario de Registro
- Diseño elegante y limpio
- Campos bien organizados
- Botones distintivos

---

## 🔄 Cómo Usar

### 1. Clonar el repositorio
```bash
git clone https://github.com/tuusuario/jolie.git
cd jolie
```

### 2. Abrir en el navegador
```bash
# Opción 1: Doble clic en index.html
# Opción 2: Usar Live Server en VS Code
```

### 3. Navegar por las páginas
- **Inicio**: Carrusel y tendencias
- **Productos**: Listado con filtros
- **Catálogo**: Galería completa
- **Registro**: Formulario de usuario

---

## 💡 Ideas Futuras

- [ ] Agregar JavaScript para validación de formularios
- [ ] Implementar filtrado dinámico de productos
- [ ] Agregar funcionalidad de búsqueda
- [ ] Crear página de carrito de compras
- [ ] Integrar backend con base de datos
- [ ] Agregar sistema de comentarios
- [ ] Implementar dark mode

---

## 📚 Recursos Utilizados

- [MDN Web Docs](https://developer.mozilla.org/) - Documentación CSS y HTML
- [Bootstrap Docs](https://getbootstrap.com/docs/5.3/) - Componentes y grid
- [Font Awesome](https://fontawesome.com/) - Librería de iconos
- [Google Fonts](https://fonts.google.com/) - Tipografías gratuitas
- [CSS Tricks](https://css-tricks.com/) - Guías y tutoriales

---

## 🎓 Créditos Académicos

Este proyecto fue desarrollado como **trabajo práctico académico** con las siguientes exigencias:

✅ Maquetación con HTML5 y CSS3  
✅ Uso de Bootstrap 5  
✅ Sin JavaScript (solo CSS para interactividad)  
✅ Diseño responsivo  
✅ Navegación clara y intuitiva  
✅ Buenas prácticas de código  

---

## 📝 Notas del Desarrollador

> *"JOLIE fue mi primer proyecto web profesional. A través de este proyecto descubrí la belleza de combinar diseño elegante con código limpio. Cada línea de CSS cuenta una historia de aprendizaje."*

Este proyecto me permitió:
- Dominar CSS avanzado (Flexbox, Grid, Animaciones)
- Entender la importancia del diseño responsivo
- Aplicar buenas prácticas de desarrollo web
- Crear una experiencia de usuario cohesiva

---

## 📄 Licencia

Este proyecto es de código abierto bajo la licencia MIT.

---

## 📧 Contacto

**Desarrollador**: Valeria Villegas  
**Email**: valeria.s.villegas@gmail.com 
**LinkedIn**: https://www.linkedin.com/in/valeria-s-villegas/
**GitHub**: [github.com/tuusuario  ](https://github.com/Valeria-s-v)

---

<div align="center">

### Hecho con ❤️ y CSS ✨

⭐ Si te gusta el proyecto, ¡no olvides darle una estrella! ⭐

</div>
