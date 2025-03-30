# Sitio Web de RV Cargo

🚚 **Sitio web profesional para RV Cargo**, empresa salvadoreña de transporte y logística.

---

## 🌐 Descripción del Proyecto

Este sitio web fue diseñado para ofrecer una experiencia moderna, funcional y visualmente atractiva. Incluye:

- Página de Inicio con mensaje poderoso
- Secciones: Sobre Nosotros, Cómo Funciona, Galería, Contacto
- Diseño responsivo (móvil/tablet/desktop)
- Formularios funcionales (via Formspree)
- Chatbot integrado (via Tawk.to)
- Navegación clara y animaciones suaves

---

## 🚀 Cómo desplegar en GitHub Pages

1. Crear un repositorio en [GitHub](https://github.com)
2. Subir los archivos contenidos en la carpeta ZIP
3. Ir a `Settings` > `Pages`
4. Seleccionar la rama `main` y carpeta `/root`
5. Acceder al enlace generado (`https://usuario.github.io/repositorio`)

---

## 🚀 Cómo desplegar en Netlify

1. Ir a [https://www.netlify.com](https://www.netlify.com)
2. Crear una cuenta y seleccionar "Deploy manually"
3. Subir el archivo `.zip` del sitio
4. ¡Listo! Netlify genera una URL pública

---

## 🧩 Configurar el Formulario (Formspree)

1. Crear cuenta gratuita en [Formspree.io](https://formspree.io)
2. Crear un nuevo formulario y copiar tu `Form ID`
3. En el archivo `contacto.html`, reemplazar:

```html
<form action="https://formspree.io/f/yourFormID" method="POST">
```

⬇️ por

```html
<form action="https://formspree.io/f/TU_ID_REAL" method="POST">
```

---

## 💬 Activar Chatbot (Tawk.to)

1. Ir a [Tawk.to](https://www.tawk.to/)
2. Crear cuenta y registrar tu sitio web
3. Copiar el script que te genera (ej. contiene `/PROPERTY_ID/WIDGET_ID`)
4. En cualquier archivo HTML, busca este bloque al final:

```html
<!-- Start of Tawk.to Script -->
<script type="text/javascript">
var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
(function(){
var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
s1.async=true;
s1.src='https://embed.tawk.to/PROPERTY_ID/WIDGET_ID';
s1.charset='UTF-8';
s1.setAttribute('crossorigin','*');
s0.parentNode.insertBefore(s1,s0);
})();
</script>
<!-- End of Tawk.to Script -->
```

⬇️ y reemplazá el `PROPERTY_ID/WIDGET_ID` con el que te da Tawk.

---

## ✍️ Créditos

Desarrollado por Rafa (vonbolan) con enfoque profesional y visión estratégica para la industria logística.

