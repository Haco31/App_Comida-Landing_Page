# 🍔 App Comida - Landing Page

Este proyecto es una **landing page para una aplicación de delivery de comida**, desarrollada con **HTML y CSS**, aplicando buenas prácticas modernas de diseño web y un enfoque **responsive (Mobile First)**.

---
PREVIEW: 📷
https://haco31.github.io/App_Comida-Landing_Page/


# 🧠 Objetivo del Proyecto

Crear una interfaz atractiva y funcional que permita:

* Buscar restaurantes y platillos
* Explicar cómo funciona la app
* Mostrar testimonios de usuarios
* Destacar restaurantes populares
* Invitar a repartidores a unirse

---

# 🏗️ Estructura del Proyecto

```
/proyecto
│── index.html
│── styles.css
│── /img
```

---

# 🎨 Secciones de la Página

---

## 🚀 1. Hero (Buscador)

### 📌 Descripción

Sección principal donde el usuario puede buscar:

* Restaurante
* Platillo

Incluye:

* Logo
* Navegación
* Formulario de búsqueda
* Ilustración

### 🧠 Conceptos usados

* Flexbox
* Inputs estilizados
* Botones personalizados

---

## ⚙️ 2. ¿Cómo funciona?

### 📌 Descripción

Explica el proceso en 3 pasos:

1. Selecciona restaurante
2. Elige tu platillo
3. Envío al instante

### 🧠 Conceptos usados

* Grid
* Cards reutilizables
* Diseño centrado

---

## 💬 3. Testimoniales

### 📌 Descripción

Sección con reseñas de usuarios en formato tipo dashboard.

### 🧠 Conceptos usados

* CSS Grid (layout principal)
* Flexbox (alineación interna)
* Responsive design

---

### 🧩 Estructura clave

```html
<article class="card">
    <div class="header">
        <figure class="avatar">
            <img src="..." alt="">
        </figure>

        <div class="info">
            <h3>Nombre</h3>
            <img src="estrellas.png" alt="">
        </div>
    </div>

    <p>Comentario...</p>
</article>
```

---

### 🎨 Layout con Grid

```css
.evaluaciones-list {
    display: grid;
    gap: 20px;
}
```

---

### 📱 Responsive

```css
/* Mobile */
grid-template-columns: 1fr;

/* Tablet */
grid-template-columns: repeat(2, 1fr);

/* Desktop */
grid-template-columns: repeat(5, 1fr);
```

---

### 🔥 Aprendizaje clave

* Grid → estructura
* Flexbox → contenido interno

---

## 🍽️ 4. Restaurantes Favoritos

### 📌 Descripción

Listado de restaurantes destacados en formato de cards.

### 🧠 Conceptos usados

* CSS Grid
* Cards repetibles
* Sombra y bordes redondeados

---

### 🎨 Ejemplo

```css
.restaurantes {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}
```

---

## 💼 5. Gana dinero con AppComida

### 📌 Descripción

Sección promocional para reclutar repartidores.

Incluye:

* Imagen
* Texto descriptivo
* Botón CTA

### 🧠 Conceptos usados

* Flexbox
* Layout en dos columnas
* Responsive

---

## 📩 6. Footer

### 📌 Descripción

Sección final con:

* Información de la empresa
* Navegación
* Contacto

### 🧠 Conceptos usados

* Grid o Flexbox
* Organización en columnas

---

# 📱 Responsive Design

El proyecto sigue un enfoque **Mobile First**:

```css
/* Base (móvil) */
grid-template-columns: 1fr;

/* Tablet */
@media (min-width: 768px) {}

/* Desktop */
@media (min-width: 1024px) {}
```

---

# 🎯 Buenas Prácticas Aplicadas

✅ Mobile First
✅ Código limpio y organizado
✅ Reutilización de clases
✅ Separación de responsabilidades
✅ Uso correcto de Grid y Flexbox
✅ Diseño escalable

---

# ⚠️ Problemas Resueltos

* ❌ Layout roto en pantallas pequeñas
* ❌ Mala alineación de elementos
* ❌ Uso excesivo de clases específicas
* ❌ Estructura poco mantenible

---

# 🧠 Conceptos Clave Aprendidos

* CSS Grid avanzado
* Flexbox
* Responsive Design
* Arquitectura de componentes
* Diseño de UI moderno

---

# 🚀 Mejoras Futuras

* Agregar JavaScript (interactividad)
* Conectar con backend (API)
* Implementar autenticación
* Mejorar accesibilidad (ARIA)
* Optimizar SEO

---

# 👨‍💻 Autor

**Harol Contreras**

Proyecto desarrollado como parte de MI formación en desarrollo web 🚀

---

# ⭐ Conclusión

Este proyecto representa un paso importante hacia convertirMe en un desarrollador **Frontend profesional**, aplicando conceptos modernos y construyendo interfaces reales similares a aplicaciones como Uber Eats o Rappi.

---
