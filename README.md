# Odin Form Project

Este proyecto forma parte del [currículum de The Odin Project](https://www.theodinproject.com/).  
El objetivo fue **replicar un formulario de registro** siguiendo un diseño dado, practicando:

- Estructura HTML semántica.
- Estilos con CSS.
- Validaciones básicas con HTML5.
- Uso de imágenes, tipografías externas y estados de inputs.

---

## 📂 Estructura

- `index.html` → Página principal con el formulario.
- `style.css` → Estilos de la página.
- `images/` → Contiene el logo y el fondo.
- `font/` → Fuente Norse-Bold usada para el logo.

---

## 🎨 Características

- **Sidebar con imagen de fondo** (proveniente de Unsplash).
- **Logo personalizado** con la fuente Norse-Bold.
- **Formulario dividido en filas** con campos para nombre, correo, teléfono y contraseñas.
- **Botón de submit estilizado** fuera del cuadro blanco, con colores basados en la paleta de la imagen de fondo.
- **Validación HTML5:**
  - Todos los campos son requeridos.
  - Emails usan validación nativa de tipo.
  - Contraseñas con mínimo 8 caracteres.
  - Inputs muestran borde rojo en estado inválido.
  - Inputs resaltan en azul al estar enfocados.
- **Enlaces accesibles** con estados `hover`, `focus`, `active` y `visited`.
- **Créditos de la foto y la tipografía** incluidos en la interfaz.

---

## 📸 Créditos

- **Foto de fondo:**  
  [Halie West en Unsplash](https://unsplash.com/photos/planta-de-hoja-verde-en-fotografia-de-primer-plano-25xggax4bSA)

- **Logo (fuente):**  
  [Norse Bold](https://www.dafont.com/norse.font)

---

## 🚀 Próximos pasos

- Añadir validación con JavaScript para confirmar que las dos contraseñas coincidan.
- Mejorar accesibilidad con mensajes de error textuales además del borde rojo.
- Ajustar estilos con unidades más flexibles (`clamp`, `%`, `em`) para preparar la versión responsive.
- Revisar contraste de colores para cumplir con WCAG.

---

## 🛠️ Cómo usar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/odin-form.git
   ```
2. Abre index.html en tu navegador.
3. ¡Listo! 🎉
